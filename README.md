</> Markdown
![Screen Poc](SCREEN_POC.JPG)
le but du jeu dans un 1er temps creer un DockerFile s'appuyant sur le framework springboot son Ui est disponible via le port 80  qui attaque la base mysql despui sont port 3306
dans un 2eme temps creer un docker-compose regroupant mon UI backend_springboot:V1 afin d'attaquer la base en mysql depuisle port 3306 
nota: les variables permettant de se connecter à votre base mysql afin de creer les objets et structure , user + password sont à votre convenance sont à renseigner dans un fichier .env qui n'est pas envoyé dans le projet mais vous permmetant de creer votre propre .env avec vos password, user en local afin de lancer votre application depuis votre docker-compose ( commande de lancement docker compose up -d )

