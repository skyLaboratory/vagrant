# vagrant setup guide
1. Entsprechende Version von https://www.vagrantup.com/downloads.html downloaden und installieren
2. Entsprechende Version von https://git-scm.com/downloads downloaden.
    * bei Installation können alle Optionen standardmäßig gelassen werden.
3. Order erstellen, in dem die Virtual Box installiert werden soll ( Hier bezeichnet als `<dir>`, beispielsweise : `C:\\MeineVagrantBox` )
4. `cmd.exe`öffnen und folgende Schritte durchführen
  1. `git clone https://github.com/swp-unikat/vagrant.git <dir>`
  2. `cd <dir>`, `cd \d <dir>` falls `<dir>` nicht auf C:\\ liegt
  3. `vagrant up`, Anweisungen auf dem Bildschirm folgen ( **dauert** )
  4. VagrantBox läuft jetzt (Im Browser 127.0.0.1:8080 als Test öffnen)

#mit VirtualBox über SSH verbinden
1. `cmd.exe` öffnen und `"C:\Program Files\Git\bin\sh.exe"` ausführen ![](http://i.imgur.com/OHcTuap.png) 
2. Ins Verzeichnis der VirutalBox wechselen `cd <dir>`
3. vagrant ssh ausführen
