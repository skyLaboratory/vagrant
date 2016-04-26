# vagrant setup guide
1. Entsprechende Version von https://www.vagrantup.com/downloads.html downloaden und installieren
2. Entsprechende Version von https://git-scm.com/downloads downloaden.
    * bei Installation können alle Optionen standardmäßig gelassen werden, außer die Wahl des Terminals : ![](http://i.imgur.com/junfh2Z.png)
3. Order erstellen, in dem die Virtual Box installiert werden soll ( Hier bezeichnet als `<dir>` )
4. `cmd.exe`öffnen und folgende Schritte durchführen
  1. `git clone https://github.com/swp-unikat/vagrant.git <dir>`
  2. `cd <dir>`, `cd \d <dir>` falls `<dir>` nicht auf C:\\ liegt
  3. `vagrant up`, Anweisungen auf dem Bildschirm folgen ( **dauert** )
  4. VagrantBox läuft jetzt (Im Browser 127.0.0.1:8080 als Test öffnen)
5. https://the.earth.li/~sgtatham/putty/latest/x86/putty-0.67-installer.msi installieren 
  1. `puttygen` ausführen 
  2. Conversions -> Import Key auswählen 
  ![](http://i.imgur.com/1Lo8Zkf.png)
  3. zu `<dir>\.vagrant\machines\default\virtualbox' wechseln 
  4. Datei `private_key` wählen 
  ![](http://i.imgur.com/LIrEhXi.png)
  5. in PuTTYGen `Generate` wählen und danach `Save Private Key`. Irgendeinen Dateinamen wählen und in `<dir>` speichern
  6. PuTTY öffnen
  7. zu `Connection -> Data` navigieren und bei `Auto-login username` `vagrant` eintragen 
  ![](http://i.imgur.com/bbAl0S4.png)
  8. zu `Connection -> SSH -> Auth` navigieren und bei zuvor erstellte Datei wählen 
  ![](http://i.imgur.com/gUtXKJT.png)
  9. zu `Session` navigieren und IP-Adresse & Port eingeben und Einstellungen speichern 
  ![](http://i.imgur.com/wqhzENc.png)
  10. Open klicken, jetzt ist man zur VagrantBox verbunden. Das Fenster sollte in etwa so aussehen 
  ![](http://i.imgur.com/Jsbkoxe.png) 
  
