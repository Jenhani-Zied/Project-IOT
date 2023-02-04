# Project-RL Project IOT
La présentation de notre projet :
-Acquisition et visualisation des données sur
une plateforme Cloud
-Affichage des mesures de différents capteurs
de température, pression, gyroscope, humidité
par le protocole MQTT sur le Node Red
-Stockage des données affichées sur la base de
données FireBase
-Définition d’un seuil pour chaque mesure, si la
valeur affichée atteint la valeur maximal, un
message s’envoie à l’utilisateur via Telegram

Installez:
-arduino IDE avec les libraries utulisé dans ce projet
-Mosquitto
-Node-Red
Etapes:
1-Connectez la carte STM32L475 IoT Node avec votre PC. 
2-Partagez le point d'accès avec votre téléphone portable pour créer un réseau local.
3-Comprenez le code et vous pouvez l'utiliser 
4-Ouvrez CMD et essayez d'afficher différentes valeurs des capteurs de la carte embarquée à travers les commandes du mosquitto
5-Ouvrez CMD et lancez Node-Red pour créer une interface graphique (nous ajoutons la partie Firebase et Telegram)(Telegram:
    https://www.youtube.com/watch?v=4NVHvA1kXG0&ab_channel=IFTTT
    Firebase: https://www.youtube.com/watch?v=IItfEkeh9cA&ab_channel=TheDefeatedEngineer)
  
