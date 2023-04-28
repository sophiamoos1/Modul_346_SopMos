# Dokumentation K05

***
## A.) Kostenberechnung

#### 1.) Rehosting

**AWS Kosten**

<img src="./images/k07-aws-kosten1.png">

Bei AWS konnte die RAM und andere Werte nicht exakt ausgewählt werden. Der Webserver hat 2 GB statt 1 GB.
Die Speichermenge konnte genau bestimmt werden.
Beide Instanzen laufen auf einem Linux. Für den Loadbalancer wurde eine Standardauswahl getroffen.
Das Backup Angebot war dafür einfach einzustellen.

**Azure Kosten**

<img src="./images/k07-azure-kosten.png">

Im Vergleich zu AWS ist Azure in seiner Struktur einfacher aufgebaut, was es Nutzern erleichtert, sich zurechtzufinden. Allerdings können RAM- und CPU-Konfigurationen nicht so dynamisch angepasst werden wie bei AWS, da diese Einstellungen bereits vorgenommen wurden. Das Gleiche gilt für die Speichermengen, die auf herkömmliche Größen wie 64GB, 128GB usw. begrenzt sind. Der Loadbalancer ist jedoch einfach zu bedienen und das Backup kann sehr einfach und präzise konfiguriert werden.

Trotz dieser Vorteile habe ich nach meinen Berechnungen definitiv AWS gewählt. Die AWS-Website ermöglicht es mir, genauere Einstellungen vorzunehmen und eine genaue Kostenübersicht zu erhalten, sodass ich genau weiß, wofür ich bezahle.

***

#### 2.) Replattforming

<img src="./images/k07-heroku-kosten1.png">

Bei Heroku wusste ich nicht genau wo das Angebot anfängt und wo es aufhört. Ich habe mich besten Wissens an die Angaben gehalten, jedoch bin ich mir nicht sicher
, ob ich nur die standart L, M oder sonst eine spezifische Version erhalten habe.

Heroku ist monatlich teurer als z.B. Azure oder AWS kombiniert.

***

#### 3.) Repurchasing

Ich habe mich für das Professional-Paket entschieden, da Essentials nur bis zu 10 Mitglieder unterstützt. Allerdings empfand ich die Gestaltung der Webseite als nicht benutzerfreundlich. Um einfache Informationen zu bekommen, musste ich zuerst viele Daten angeben. Das macht es schwierig, wenn man sich nur mal erkundigen will. Das Angebot von Salesforce ist auch nicht so transparent wie das anderer Anbieter. Beim Austausch mit meinen Mitschüler, habe ich gemerkt, dass diese das ganze als ähnlich empfunden haben. Deshalb vermute ich, dass es nicht an mir als Benutzer sondern an Salesforce liegt.

Nach dieser Erfahrung würde ich Salesforce nicht weiterempfehlen und stattdessen nach einem anderen Anbieter suchen.


<img src="./images/k07-salesforce-liste.png">


*Mein Fazit ist, dass: Aus der ganzen Auswahl würde ich zu AWS greifen. Die Monatlichen kosten können mittels langjährigen Plänen klein gehalten werden und wie bereits erwähnt, weiss man wofür man bezahlt.*