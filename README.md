
# Projet_Robot_C

##  Description
Ce projet implémente un robot autonome basé sur STM32 (NUCLEO-L476RG).  
Il détecte les obstacles via un capteur sonar et adapte sa trajectoire en conséquence. Il peut être contrôlé par bluetooth. 
Le contrôle est assuré par PWM (moteurs + servomoteur), encodeurs pour la vitesse, et surveillance batterie via ADC.
Si vous avez la bonne carte (NUCLEO-L476RG) il vous suffit de copier le main.c et l'IOC pour que le robot fonctionne

##  Fonctionnalités
- Détection d'obstacles par sonar
- Contrôle des moteurs par PWM
- Servomoteur pour orientation
- Encodeurs pour mesure de vitesse
- Watchdog pour sécurité
- Surveillance batterie par ADC

##  Technologies
- Langage C
- STM32CubeIDE
- STM32 HAL
- Carte NUCLEO-L476RG

##  Structure
- `main.c` : Code pour le robot principale du robot
- `robot_watchdog.ioc` : configuration de l'ioc Timers ADC Watchdog ect...
- `algorigramme` : algorigramme pour l'implémentation en c de ce projet

## 👨‍💻 Auteur
Fares Osman – Étudiant ISMIN, Mines de Saint-Étienne
