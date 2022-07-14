# WatchDrip + XDrip für das MiBand 5/6


In diesem Dokument möchte ich euch zeigen, wie Ihr
XDrip mit WatchDrip für das MiBand 5/6 einrichten könnt.


Hinweise:



Was benötigt wird ?

- XDrip
- WatchDrip
- aktiver Follower in der Libre3 App
- Handy
- MiBand 5/6
- aktive Internetverbindung


Downloads:
Bitte ladet die angegeben APKs im Vorfeld herrunter!

Für die Installation muss in den Android Einstellungen
die Option: Installation aus Unbekannten Quellen aktivieren.
Bitte sucht in den Android Einstellungen danach, da es je
nach Hersteller Unterschiede geben kann, müsst ihr selbst suchen.
Erst wenn diese Option aktiviert ist können die folgenden Apps
installiert werden.

- Link XDrip
- Link WatchDrip
- Link freemayband.com
- Libre LinkUp App


Schritt 1:
Im ersten Schritt richten wir uns einen neuen Follower
inkl. Konto ein. Solltet Ihr schon einen aktiven Follower
haben, könnt Ihr gleich zum nächsten Schritt springen. Schritt 1
dient lediglich der Überprüfung ob die Follower Verbindung klappt.

- Öffnet den Playstore sucht und ladet bzw Installiert euch
die LibreLinkUp App (https://play.google.com/store/apps/details?id=org.nativescript.LibreLinkUp)

- Nach der Installation der LibreLinkUp App diese
öffnen und im unteren Bereich ein neues Konto erstellen.

- Merkt euch die Emailadresse welche Ihr für das neue Konto
benutzt habt !

- Wechselt in die Libre3 App im linken Menü auf: Verbundene Apps
klicken danach auf LibreLinkUp Verwalten klicken 

- Als nächstes auf Verbindung hinzufügen dort trägt Ihr den Namen und
die Emailadresse des zuvor erstellten Kontos ein.

- Wechselt wieder in die LibreLinkUp App, akzeptiert die
erhaltene Einladung

- Nach einigen Sekunden evtl. auch Minuten solltet Ihr Werte
in der LibreLinkUp App sehen

Wenn Ihr keine Werte seht, ist irgendwo etwas schiefgelaufen, und Ihr
solltet die Schritte nochmals durchgehen ! Es ist zwingend erforderlich
das Ihr Daten empfängt.


Schritt 2:
Vorbereitung des MiBandes, dies ist zugleich der schwierigste
Schritt, hier nach hast du das gröbste geschafft. :)

Hinweis:
Wir gehen von einem bereits gekoppelten MiBand aus, solltest du es
Neu haben, so richte es bitte nach der Herstelleranleitung ein. Danach
kannst du hier weiter machen!

Es gehen keine Daten aus der MiFit/Zepp Life App verloren. Die Daten sind
in der Cloud gespeichert und werden bei Anmeldung mit eurem 
Account wiederhergestellt. Ihr benötigt für diesen Schritt auch die 
Zugangsdaten eures Accounts welcher in der MiFit/Zepp Life App 
benutzt wird.

- Öffnet die MiFit/Zepp Life App und geht in die Einstellungen des Bandes.
Im Einstellungsmenü ganz unten auf Entkoppeln gehen. Und das Band entkoppeln.

- Deinstalliert nun die MiFit/Zepp Life App von eurem Handy

- Nachdem die App deinstalliert wurde, installieren wir die gepatchte
Version von freemayband.com (Link oben) welche wir zuvor herruntergeladen haben.

- Wenn die Installation der gepatchten App abgeschlossen ist, diese öffnen
und wie gewohnt das Band hinzufügen. Wenn das Band erfolgreich hinzugefügt
wurde stellt die Sichtbarkeit des Bandes auf aktiv.

- Jetzt öffnet Ihr einen Dateimanager (ist regulär onBoard bei jedem Android Phone,
solltest du dennoch keinen haben lade dir einfach irgendeinen aus dem Playstore.

- Wechselt auf Euren Speicher oder SD Karte, und schaut ob Ihr einen
Ordner mit dem Namen: freemyband findet. In diesem Ordner sollte sich
eine Textdatei enthalten sein. In dieser Textdatei befinden sich die MAC Adresse
und der AuthCode beides benötigen wir für Watchdrip. Merkt euch den
Ordner, wir werden diesen evtl. später nochmal brauchen.

- Schaut bitte genau nach ob ihr diesen Ordner: freemyband findet. Er ist da !
Wenn nicht musst Ihr die Schritte wiederholen. Die Daten in der Textdatei werden
zwingend im weiteren Verlauf benötigt. Ohne diese kannst du nicht weitermachen !

Schritt 3:
Jetzt richten wir noch Watchdrip und XDrip ein. Danach hast du 
es geschafft. :)

- Installiert XDrip (Link oben) und öffnet die App

- Im linken Menü einmal auf Sensor starten klicken. Dieser Schritt ist
notwendig da es noch einen kleinen Bug gibt. Wir umgehen diesen Bug einfach mit 
dem manuellen Starten des Sensors (Ihr startet diesen virtuell XDrip stellt keine direkte Verbindung
zu dem Libre3 Sensor her). Als Startzeitpunkt könnt ihr jetzt auswählen.

- Als nächstes wieder über das Menü in den Punkt Einstellungen Wechseln.
Im oberen Bereich den Punkt Datenquelle (Source) anklicken.

- Aus der Liste wählt Ihr den WebFollower aus. Geht zurück
und ihr seht das ein weiteres Feld unter dem Webfollower aufgetaucht ist.
Antippen

- Im folgenden die Zugangsdaten und Passwort für den im Schritt 1 eingerichteten
Follower eintragen. Das oberste Feld mit dem Scriptnamen NICHT verändern.

- Nachdem Ihr die Zugangsdaten eingetragen habt, sollten schon erste Werte in der XDrip
App zu sehen sein. 

- Geht noch mal über das linke Menü in die Einstellungen, und scrollt
ein wenig nach unten, dort findet Ihr den Punkt: InterApp Einstellungen, öffnen

- Aktiviert dort den Service und schaut das Senden von Glucosedaten
aktiviert ist, genauso wie ganz unten Broadcast Service API (wenn dieser Punkt nicht aktiviert ist
kann Watchdrip keine Werte empfangen)

- Das wars in der App XDrip

- Installiert und öffnet nun die App WatchDrip (Link oben)

Es gibt jetzt zwei Szenarien:

Szenario 1:
Ihr aktiviert den Schieberegler bei Enable Service in Watchdrip.
Wenn Ihr Glück habt übernimmt Watchdrip den AuthCode und MAC Adresse
aus der Textdatei aus dem freemyband Ordner. Herzlichen Glückwunsch du hast es geschafft !
Du solltest nun Werte auf deinem MiBand 5/6 sehen.

Szenario 2:
Ihr aktiviert den Schieberegler bei Enable Service in WatchDrip.
Aber das Band wird nicht automatisch erkannt. Dann schaltet den Schieberegler
bei Enable Service wieder auf aus.

Wechselt in den freemyband Ordner und öffnet die darin enthaltene Textdatei.
In der Textdatei findet Ihr zwei Werte, der erste ist die MAC
Adresse der zweite der AuthCode. Beide Werte sind mit einem Semikolon (;) getrennt.

Kopiert den ersten Teil bis zum Semikolon. Es sollte ähnlich wie:
0A:6F:FF:8G:S1 aussehen. Das Semikolon nicht mit kopieren. Achtet auch darauf daß ihr 
ausversehen ein Leerzeichen mit kopiert.

- Wechselt jetzt wieder zu Watchdrip und tippt auf MAC Adresse. Dort den
kopierten Wert einfügen. (lange gedrückt halten)

- wechselt wieder in die Textdatei und kopiert euch den AuthCode. Dieser beginnt
rechts vom Semikolon. (Semikolon nicht mit kopieren, keine Leerzeichen mit kopieren.

- wechselt wieder zu WatchDrip und tippe auf AuthCode, füge dort den eben kopierten Wert
ein. (lange gedrückt halten, einfügen auswählen)

- Aktiviert nun wieder den Schalter bei: Enable Service

Herzlichen Glückwunsch, wenn du alles richtig gemacht hast siehst auch du nun Werte auf dem
MiBand 5/6

Hinweis: Sobald das erfolgreich gekoppelt würde, wird das Watchface
automatisch auf das Band geladen, du brauchst nix zu machen.

Du kannst keine anderen Watchfaces benutzen ! Nur auf XDrip
optimierte Watchfaces gehen und können hinzugefügt werden.

WatchDrip zeigt erst einen Wert an wenn dieser durch XDrip aktualisiert wurde 
Ein manuelles Update kannst du über den oberen rechten Button anstoßen.
