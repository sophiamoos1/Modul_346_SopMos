# JaSch_Modul346

##Aufsetzen von zwei VM's
###confident-group & square-scoter
![](./Images/1.png)

<hr>

##Starten und Stoppen Sie die Instanz via Command Line (Konsole)
###Beweis, dass die Vm's momentan auf "Running" stehen

![](./Images/3.png)
###Stoppen von square-scoter

![](./Images/2.png)
###Starten von Square-Scoter

![](./Images/6.png)
<hr>

##Ändern Sie die Anzahl CPU der Instanz
###Vor der Anpassung CPU=1
![](./Images/5.png)
###Nach der Anpassung CPU=2
![](./Images/4.png)

<hr>

##Rufen Sie die Shell der Instanz auf (Linux Bash)
###Shell für square-scoter gestartet
![](./Images/8.png)

<hr>

##Löschen Sie eine Instanz (permanent!).
###Ordner vor dem Löschen
![](./Images/7.png)
###Löschvorgang
![](./Images/9.png)
###Nach dem Löschen
![](./Images/10.png)

<hr>

##Ausführen der folgende Befehle
###sudo apt update
![](./Images/11.png)
###sudo apt install apache2
![](./Images/14.png)
###sudo apt install php
![](./Images/16.png)
###sudo apt install libapache2-mod-php
![](./Images/15.png)
###sudo apt install mariadb-server
![](./Images/18.png)
###sudo apt install php-mysqli
![](./Images/17.png)
###sudo mysql -sfu root -e "GRANT ALL ON *.* TO 'admin'@'%' IDENTIFIED BY'password' WITH GRANT OPTION;"
![](./Images/19.png)
###cd ~
![](./Images/20.png)
###git clone https://gitlab.com/ch-tbz-it/Stud/m346/m346scripts.git
![](./Images/21.png)
###sudo cp ./m346scripts/KN01/*.php /var/www/html/
###IP
![](./Images/22.png)
###Windows 10
![](./Images/curl.localhost.png)
![](./Images/curl.png)
![](./Images/curl3.png)