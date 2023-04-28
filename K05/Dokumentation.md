# K04 Dokumentation K05

***
## A.)

Für diesen Teil der Abgabe, musste ich meine Instanzen und die dazu gehörige Dinge löschen.

<img src="./images/keine-instanze-leere-liste.png">

***

## B.)

**Subnetz**

Als erstes musste ich ein Subnetz erstellen. Dazu habe ich folgende Einstellungen ausgewählt.

<img src="./images/web-subnetz-k05.png">

Nach dem ich das Subnetz erfolgreich erstellt hatte sah meine Liste so aus.

<img src="./images/web-subnetz-liste.png">

***

**Elastic IPs**

Als nächstes habe ich eine Elastic IP-Adresse erstellt. Diese habe ich für den Rest des Auftrags verwendet.

<img src="./images/k05-ip-adresse-1.png">

***

**Security Groups**

Für den weiteren Teil des Auftrags, habe ich zwei Sicherheitsgruppen erstellt. Die eine sollte für die Datenbank und die andere für die Web-Instanz dienen. 

Für die DB-Instanz habe ich folgende Einstellungen gewählt.

<img src="./images/k05-db-sicherhietsgruppe.png">

Für die Web-Instanz habe ich folgende Regeln defniert.

<img src="./images/k05-sivherheitsgruppe-web-server.png">

Nachdem ich die beiden Sicherheitsgruppen erstellt hatte, sah meine Liste so aus.

<img src="./images/k05-erstellte-sicherhietsgruppe-liste.png">

Wie man sieht, habe ich zwei default Sicherheitsgruppen, welche ich schon im voraus hatte und nicht löschen konnte und meine beiden kürzlich erstellten Sicherheritsgruppen.

Ich habe ebenfalls noch je einen Screenshot gemacht, worauf man sieht was mir nach dem erstellen einer Sicherheitsgruppe angezeigt wurde. 

Screenshot für die DB-Sicherheitsgruppe:

<img src="./images/erstellt-sicherheitsgruppe-k05.png">

Screenshot für die Web-Sicherheitsgruppe:

<img src="./images/erstellte-web-sicherheitsgruppe.png">


***

**Netzwerk-Interfaces**

Hier habe ich ebenfalls zwei Netzwerk-Interfaces erstellt, wieder eine für das Web und eine für die Datenbank. 

*Leider habe ich später beim erstellen der Web-Instanz einen Fehler gemacht und diesen erst bemerkt, als ich mich mit adminer einloggen wollte. Daher stimmen die Ip-Adressen hier bei dem Web-Netzwerk-Interface nicht mit der von den Screenshots der Datein (Index.html, info.php etc) überein. Falls Sie zweifel haben an der Echtheit meiner Screenshots haben, können Sie diese gern selbst auf AWS überprüfen.*

Einstellungen des Web-Netzwerk-Interface:

<img src="./images/k05-web-s3.png">

<img src="./images/k05-web-s4.png">

Einstellungen des DB-Netzwerk-Interfaces:

<img src="./images/k05-web-s1.png">

<img src="./images/k05-web-s2.png">

Ebenfalls habe ich Screenshots davon gemacht, wie die Netzwerk-Interfaces in der Liste aussehen.

<img src="./images/real-interfaces.png">

<img src="./images/real-interfaces-2.png">

***

**Instanzen**

Zuerst habe ich logischerweise die Datenbank-Instanz erstellt. Alle Wichtigen Einstellungen, welche ich machen musste, damit alles Funktioniert, habe ich dokumentiert. 

<img src="./images/k05-instanz-db1.png">

<img src="./images/k05-instanz-db-netzwerkeinstellungen.png">

<img src="./imges/../images/k05-instanz-db-cloudinit.png">

Nachdem ich die Instanz erstellt hatte, konnte ich folgende Infos über die Instanz sehen.

<img src="./images/k05-created-instanz.png">



Das gleiche habe ich Natürlich auch für die Web-Instanz gemacht. Jedoch habe ich logischerweise andere Einstellungen genommen.

<img src="./images/k05-instanz-web-1.png">

<img src="./images/k05-web-instanze-netzwerkeinstellungen.png">

<img src="./images/k05-web-instanze-cloud-init.png">

Auch hier habe ich wieder folgende Infos nach dem erstellen der Instanz erhalten.

<img src="./images/kn05-web-instnz-erstellt.png">

Anschliessend habe ich die Seiten über den Web-Server aufgerufen.

Index.html:
<img src="./images/k05-index-html.png">

Info.php:
<img src="./images/k05-info-php.png">

Adminer:
<img src="./images/k05-adminer-funktioniert.png">