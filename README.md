# CG scale

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=R69PMKTCXQBUU&source=url)


Balance basée sur Arduino pour peser les modèles d'avion. Relativement peu de composants sont requis et devraient être faciles à reproduire même pour les débutants. Les fonctions principales:

 - supporte des balances avec 2 ou 3 capteurs
 - prend en charge ESP8266 et Arduino avec ATmega328, ATmega32u4
 - calibration automatique basée sur un objet de référence, donc pas de détermination fastidieuse des valeurs de calibration
 - Affichage par sur écran OLED
 - La tension de la batterie peut être mesurée
 - Les réglages se font via un menu via une interface série
 - Avec l'ESP8266, les réglages peuvent également être effectués facilement via la page Web
 - Les paramètres sont enregistrés en permanence dans l'EEprom et ne doivent plus être paramétrés après une mise à jour logicielle
 - seuls quelques composants sont nécessaires, ce qui permet une installation rapide et facile

Plus d'informations sur la construction peuvent être trouvées dans [Wiki](https://github.com/nightflyer88/CG_scale/wiki)

![init](https://github.com/nightflyer88/CG_scale/blob/master/Doc/img/cgScale_init.jpeg)
![run](https://github.com/nightflyer88/CG_scale/blob/master/Doc/img/cgScale.jpeg)
![cgscale_home](https://github.com/nightflyer88/CG_scale/blob/master/Doc/img/cgscale_home.png)
![cgscale_models](https://github.com/nightflyer88/CG_scale/blob/master/Doc/img/cgscale_models.png)
![cgscale_settings](https://github.com/nightflyer88/CG_scale/blob/master/Doc/img/cgscale_settings.png)
