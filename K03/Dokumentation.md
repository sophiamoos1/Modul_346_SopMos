# Dokumentation K03
***

## A.) AWS Kurs


### Lab 4.1 - EC2
<br>

**HTML-Page inklusive URL:**

Auf dem folgendem Bild sieht man, wie man über die IP-Adresse meiner Instanz eine eingefügte HTML-Seite aufrufen kann.

<img src="images/bucket-html-page.png">

***

**Liste der EC2-Instanzen**

Auf diesem Bild, sieht man meine existierenden Instanzen.

<img src="images/instanze-list1.png">

***

**Details der Web Server-Instanz (öffentliche IP sichtbar)**

Hier sieht man die öffentliche IP-Adresse meiner Instanz, über welche auch die HTML-Page aufgerufen wurde.

<img src="images/ip-öffentlich.png">

***

**Security-Group: Liste der Inbound-Regeln**

Auf diesem Bild kann man die Security-Group meiner Instanz sehen genau wie die Liste von den Regeln.

<img src="images/security-group.png">

***

### Lab 4.2 - S3
<br>

**Liste der Buckets**

Auf diesem Bild sind meine Buckets aufgelistet.

<img src="images/bucket-list-1.png">

***

**HTML-Seite, inkl. URL**

Hier sieht man die HTML Seite, welche in sich in meinem Bucket befindet und über den URL aufgerufen werden kann.

<img src="images/bucket-html-page.png">

***

**Liste der Dateien im Bucket**

Dieses Bild zeigt alle Datein welche sich in meinem Bucket befinden.

<img src="images/objects-in-bucket.png">

***

**Eigenschaften von "Static website hosting"**

Hier kann man die Eigenschaften von Static website hosting von meinem Bucket sehen.

<img src="images/properties-static-web-hosting.png">

***

## B) Zugriff mit Passwort

**Ubuntu 22.04**
Es wurde Ubuntu 22.04 als System ausgewählt.

<img src="./images/ubuntu-settings.png">

***

**Vockey-Key**
Bei "Key pair" wurde "Vockey gewählt".

<img src="./images/vockey-key.png">

***

**Cloud-init-true-false**
Could-Init Settings sind auf true und false gesetzt.

<img src="./images/true-false.png">

Ergebnis im CMD:

<img src="./images/cmd-2-first-instnze.png">

***

**Could-init-false-false**
Could-Init Settings sind auf false und false gesetzt.

<img src="./images/false-false.png">

Ergebnis im CMD: 

<img src="./images/false-login.png">

***

## C) Zugriff mit SSH-Key

**Zwei Key-Pairs**
Zwei Key-Pairs wurden neu erstellt und lokal abgespeichert.

<img src="./images/creating-keys.png">
<img src="./images/saved-ley-pairs.png">

*** 

**Key1 ausgewählt**
Der Key1 wurde ausgewählt.

<img src="./images/selected-key-pair.png">

*** 

**Login CMD**
Nicht funktionierendes Login mit KeyPair2:

<img src="./images/key2-login-failed.png">

Funktionierendes Login mit KeyPair1:

<img src="./images/ssh-key-login.png">

*** 

## D) SSH-Key und Cloud-init

**Key-Pair Einstellung**
KeyPair2 wird ausgewählt.

<img src="./images/key-pair2-use.png">

*** 

**Cloud-Init**

Oberer ausgewählter "KeyPair2" wird mit Could-Init Konfig überschrieben.

<img src="./images/cloud-init-key1.png">

*** 

**Testing CMD**
Jedes login failed, ausser das mit dem richtigen User und dem richtigen Key (KeyPair1).

<img src="./images/only-one-key-works.png">