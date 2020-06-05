# carcazone
Tes sorties entre amis sur Carcassonne, gratuit et sans pubs !

https://carcazone.org

CarcaZone est un projet à but non lucratif, il s'agit de proposer, sur Carcassonne et aux alentours, un site web/app mobile permettant de se rencontrer pour faire des sorties amicales.

Le projet sera porté par une association 1901 afin de prendre les décisions et orientations sur le futur du projet et sur les nouveautés de la manière la plus collectivement possible, le projet doit appartenir à toutes et tous :)

Une fois que le projet sera assez solide, il sera possible d'étendre le projet à d'autres villes !

La partie technique du projet se compose en 2 parties :

frontend : une application React (pwa) avec un certain nombre de modules, notamment pour l'UI/UX basé principalement sur Material
la partie frontend est hebergée sur S3/CloudFront (AWS)

backend : une Api sur Amazon Web Services (AWS) qui utilise:
  - cognito pour la partie authentification
  - lambda pour le code
  - dynamoDB pour la base de données NOSQL
  - ses pour les notifications email
