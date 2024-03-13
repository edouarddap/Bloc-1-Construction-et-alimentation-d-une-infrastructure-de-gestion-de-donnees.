# Jedha_Kayak_Project-


Construction d'une infrastructure Cloud accueillant des données Big Data (collecte de données web, intégration des données dans un Data Lake, nettoyage et chargement des données dans une base de données type AWS Redshift par traitement parallélisé si nécessaire via la construction d'un processus ETL).

Hôtels et informations météorologiques récupérés pour une liste de villes donnée
Données nettoyées stockées dans un compartiment S3 et transférées vers l'instance de base de données AWS RDS
Base de données SQL interrogée pour la sélection des meilleures villes en fonction de la météo
Fourniture de cartes de certains emplacements de villes et d'hôtels illustrant les températures quotidiennes et les fourchettes de prix des hôtels

_Bibliothèques: APIs, BeautifulSoup, Boto3, AWS S3, AWS RDS, SQL, SQLAlchemy, Plotly_

# Kayak_Project - Plan your trip with Kayak
Company's description 📇

Kayak is a travel search engine that helps user plan their next trip at the best price.

The company was founded in 2004 by Steve Hafner & Paul M. English. After a few rounds of fundraising, Kayak was acquired by Booking Holdings which now holds:

    Booking.com
    Kayak
    Priceline
    Agoda
    RentalCars
    OpenTable

With over $300 million revenue a year, Kayak operates in almost all countries and all languages to help their users book travels accros the globe.

# Project 🚧

The marketing team needs help on a new project. After doing some user research, the team discovered that 70% of their users who are planning a trip would like to have more information about the destination they are going to.

In addition, user research shows that people tend to be defiant about the information they are reading if they don't know the brand which produced the content.

Therefore, Kayak Marketing Team would like to create an application that will recommend where people should plan their next holidays. The application should be based on real data about:

    Weather
    Hotels in the area

The application should then be able to recommend the best destinations and hotels based on the above variables at any given time.

# Goals 🎯

As the project has just started, your team doesn't have any data that can be used to create this application. Therefore, your job will be to:

    Scrape data from destinations
    Get weather data from each destination
    Get hotels' info about each destination
    Store all the information above in a data lake
    Extract, transform and load cleaned data from your datalake to a data warehouse

# Scope of this project 🖼️

Marketing team wants to focus first on the best cities to travel to in France. According One Week In.com here are the top-35 cities to visit in France:

["Mont Saint Michel", "St Malo", "Bayeux", "Le Havre", "Rouen", "Paris", "Amiens", "Lille", "Strasbourg", "Chateau du Haut Koenigsbourg", "Colmar", "Eguisheim", "Besancon", "Dijon", "Annecy", "Grenoble", "Lyon", "Gorges du Verdon", "Bormes les Mimosas", "Cassis", "Marseille", "Aix en Provence", "Avignon", "Uzes", "Nimes", "Aigues Mortes", "Saintes Maries de la mer", "Collioure", "Carcassonne", "Ariege", "Toulouse", "Montauban", "Biarritz", "Bayonne", "La Rochelle"]

Your team should focus only on the above cities for your project.

# Deliverable 📬

To complete this project, your team should deliver:

    A .csv file in an S3 bucket containing enriched information about weather and hotels for each french city

    A SQL Database where we should be able to get the same cleaned data from S3

    Two maps where you should have a Top-5 destinations and a Top-20 hotels in the area. You can use plotly or any other library to do so.
