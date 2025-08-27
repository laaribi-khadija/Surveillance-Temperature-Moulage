# Surveillance de Température dans une Machine de Moulage

Ce projet a été réalisé dans le cadre de mon stage chez **STANDARD PROFIL**.  
Il consiste à développer un système embarqué basé sur une carte **ESP32** pour la **surveillance de la température** dans une machine de moulage des joints automobiles.

## Matériel utilisé
- ESP32  
- Capteur de température **DS18B20**  
- Module GSM **SIM800L** (envoi de SMS d’alerte)  
- LED rouge (signalisation d’alarme)  

## Fonctionnalités
Dans le processus de fabrication des joints d’étanchéité, la température des machines de moulage joue un rôle déterminant dans la qualité des pièces produites.  
Une surchauffe peut entraîner non seulement des défauts visibles sur les produits finis, mais également un endommagement du moule ou de certains composants internes de la machine, provoquant ainsi des arrêts de production coûteux.  

Face à ces enjeux, ce système permet :  
- La **mesure en temps réel** de la température grâce au capteur DS18B20.  
- La **détection d’anomalies thermiques** (dépassement de seuil critique).  
- L’activation d’une **LED rouge** en cas de surchauffe.  
- L’envoi immédiat d’un **SMS d’alerte via le module SIM800L** pour prévenir l’opérateur.  

---
