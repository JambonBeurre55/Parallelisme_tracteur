Version 1

# Parallelisme_tracteur
Réglage facile et rapide du parallélisme des tracteurs 




Solution rapide de réglage de parallélisme pour les roues de tracteurs. 
L'imu est un bno055 mais un autre modèle peut être utilisé  nécessitant une modification du code. 
Les adresses i2c seront peut être différentes pour votre écran et votre IMU.

Procédure de réglage : 

- Remplacement des rotules une par une

- Tracteur sur une surface plane avec les deux cotés gonflés à la même pression 

- Une fois la rotule remplacée (coté gauche pour notre exemple) procédez a la Calibration du boitier en le plaçant sur la roue arrière droite

- Déplacez délicatement le boitier sur le réducteur avant droite puis tournez le volant jusqu'a atteindre 0 degrés puis ne touchez plus au volant

- Répétez la Calibration coté gauche puis placez le boitier sur le réducteur gauche

- Réglez la rotule jusqu'a zéro degrés

- Répétez l'opération de calibrage en fin d'opération afin de vérifier et être sûr que l'IMU n'ai pas dévié


Le bouton de Calibration est sur la pin 2
Le buzzer optionnel est sur la pin 3
L'écran et l'IMU en liaison i2C 

Biliothèques nécessaires : 

Adafruit_Sensor.h

Adafruit_BNO055.h

Adafruit_GFX.h

Adafruit_SSD1306.h
