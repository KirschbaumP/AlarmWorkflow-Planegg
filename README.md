# AlarmWorkflow-Planegg
Ein vorangestelltes $ bedeutet dass der nachfolgende befehl in konsole eingefügt werden muss(natürlich ohne $).

1. aktuelles Raspberry Pi Image auf SD Karte installieren.
2. RaspberryPi starten
3. $ sudoraspi-config 
3.1 Expand Filesystem ausführen
3.2 Internationalisation Options -> Change Locale -> "de_DE.UTF-8 UTF-8"
3.3 Internationalisation Options -> Change Keyboard Layout ->  Classmate PC -> Other -> German -> German -> The default for the keyboard layout -> No compose key -> No
3.4 Advanced Options -> SSH -> Enable
4. $ sudo reboot
5. $ wget https://raw.githubusercontent.com/KirschbaumP/AlarmWorkflow-Planegg/master/install
6. die Installparameter anpassen -> $ sudo nano install
7. $ sudo chmod 755 install
8. $ sudo ./install
