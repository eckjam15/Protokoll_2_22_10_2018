# Protokoll 2 
# 22.10.2018

## * raspberry pi
   * kleiner Computer
   * Gleicher Prozessor wie in smartphones
      * Multicore 32 bis 64 bit
   * Schnittstellen
      * 4 USB
      * Ethernet
      * chip
      * HDMI
      * Audio
      * micro USB
         * Stromversorgung
   * Festplatte
      * micro SD-Karte
   * IDEC
      * zum aufrüsten mit Sensoren, micro Controller, ...
   * Betriebssystem
      * raspbian [(zum Download)](https://www.raspberrypi.org/downloads/)
         * ableger von Debian (Linux)
   * Kosten ca 35€
   
## * Konsolenbefehle (Zugriff / Steuerung des raspberry's)
   * 'ssh' + 'ip' (in Benutzer einloggen)
      * 'yes'
         * passwort eingeben
   * 'passwd' (ändern des Passworts)
      * aktuelles Passwort eingeben
      * neues Passwort eingeben
   * 'ip' + 'a' (Information)
   * 'sudo' + 'raspi-config' (Tastaturlayout ändern)
   * 'ls' (list files)
   * 'ls/' (root Verzeichnis)
   * 'ls--all' (alles wird angezeigt)
   * '.' (aktuelles Verzeichnis)
   * '..' (übergeordnetes Verzeichnis)
   * 'cd' + ... (Verzeichnis wechseln)
   * 'cd' (Homeverzeichnis)
   * 'pwd' (Verzeichnis in dem man gerade Arbeitet)
   * 'exit' (Benutzer Verlassen)
   * 'whoami' (Benutzer abfragen)
   * 'history' (zeigt den Verlauf der Befehle an)
   * 'sudo' + 'nano' + 'etc/hostname' (Benutzername ändern)
   * 'sudo-i'
      * 'add' + 'user' (Benutzer hinzufügen)
   * 'etc/sudoers' (info: wer darf was)
   
## * Verzeichnis
   * root
   * home
      *pi
   *etc
      * hostname
      * hosts
## * Benutzerinformationen
   * /etc
      * passwd
      * group
      * shadow
   mit dem Befehl 'man passwd' bekommt man informationen ausgegeben
