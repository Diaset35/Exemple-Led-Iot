# Exemple Led Iot
![arduino](https://sdz-upload.s3.amazonaws.com/prod/upload/arduinoBouton.png)
Ce projet permet d'allumer une Led à distance depuis internet.
## Bibliothéque utilisée

+ Wifi
+ Adafruit-MQTT
+ NodeRED
# Matériel

+ **ESP32**
+ Serveur MQTT
+ Led
+ Fils de connexion
+ Alimentation microUSB +5v

## Installation


    int pinBouton;
    void setup()
    {
       Serial.begin(9600);
       pinBouton=10;
       pinMode(pinBouton,INPUT);
    }
       void loop()
    {
       boolean etatBouton=digitalRead(pinBouton);
       Serial.println(etatBouton);
    }
    
   ## Brochage ![brochage](https://wiki.mchobby.be/images/thumb/0/09/OrdBot-Ramps-RampDetailled.jpg/800px-OrdBot-Ramps-RampDetailled.jpg)
    
   ## Acheter les composants
    
[esp32](https://openclassrooms.com/fr/courses/2778161-programmez-vos-premiers-montages-avec-arduino/3285224-le-bouton-poussoir)

[led](https://openclassrooms.com/fr/courses/2778161-programmez-vos-premiers-montages-avec-arduino/3285224-le-bouton-poussoir)
    
