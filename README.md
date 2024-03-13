# Jedha - Bloc 1


Construction d'une infrastructure Cloud accueillant des données Big Data (collecte de données web, intégration des données dans un Data Lake, nettoyage et chargement des données dans une base de données type AWS Redshift).

Les données sur les hôtels et les informations météorologiques ont été collectées pour une liste spécifique de villes. Après avoir été nettoyées, ces données ont été stockées dans un compartiment S3 avant d'être transférées vers une instance de base de données AWS RDS. La base de données SQL est ensuite interrogée pour identifier les meilleures villes en fonction des conditions météorologiques. Enfin, des cartes sont générées pour certains emplacements de villes et d'hôtels, mettant en évidence les températures quotidiennes et les fourchettes de prix des hébergements.

_Bibliothèques: APIs, BeautifulSoup, Boto3, AWS S3, AWS RDS, SQL, SQLAlchemy, Plotly_

