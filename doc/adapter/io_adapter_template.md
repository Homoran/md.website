<img src="media/Adaptericon.png" width=150 hight=150 />

# Common Adapter Name

## Vorbemerkung
In diesem Abschnitt wird etwas Hintergrundinformaton zu der dem Adapter zugrundeliegenden
Technik gegeben.

Dies kann im Rahmen eines Geräteadapters etwas Information zu dem Gerät sein, oder bei 
einem Adapter für ein Kommunikationsprotokoll ein wenig Grundlagen zu dem Protokoll.

Trotzdem sollte dieser Text allgemeinverständlich auch für Einsteiger sein.


## Der Adapter

In diesem Abschnitt wird ein wenig grundlegendes zum Adapter gesagt.


> Hier netter Screenshot zur Motivation, z.B. aus VIS oder oder oder


### Ich bin ein Inhaltsverzeichnis oder so etwas ähnliches
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


## Steckbrief
|  |  |
| --- | :---: |
| aktuelle Version stable| link und logo npm |
| aktuelle Version latest | link und logo npm      |
| OS| Lunterstützte OS |
| node-Version | unterstützte node-Versionen |
| Entwickler | Name/Alias des Entwicklers |
| Lizenz | Bezeichnung der Lizenz |
| Github | LINK |
| Keywords | Suchworte |
| Kategorie | gemäß Adapterliste |
| Stand der Doku | letzte Bearbeitung (inhaltlich) |


## Installation

Eine Instanz des Adapters wird über den Admin installiert.

Dazu wird unter der Rubrik "Adapter" die Kachel für den Adaptername Adapter gesucht.

Auf dieser Kachel wird auf das Icon für die erweiterten Einstellungen geklickt.

<img src="media/adapter_AdapterName_install_01.png">

und in diesen Einstellungen auf das (+) zum Erstellen einer Instanz.

<img src="media/adapter_AdapterName_install_02.png">

Es öffnet sich ein Installationsfenster in dem der Fortschritt der Installation
durch die Anzeige der ablaufenden Befehlsfolgen angezeigt wird.

<img src="media/adapter_AdapterName_install_03.png">

Nach vollendeter Installation schließt sich das Fenster standardmäßig von selbst.

<img src="media/adapter_AdapterName_install_04.png">


Danach öffnet sich das Konfigurationsfenster der Instanz.

##  Konfiguration

Der Adapter findet automatisch die harmony Hubs im lokalen Netzwerk

<img src="media/adapter_AdapterName_config_01.png">

Die angezeigten Felder müssen nur ausgefüllt werden, wenn der Hub mit Usernamen und
Passwort gesichert ist.

Jetzt kann man das Konfigurationsfenster schließen.




## Angelegte Objekte und ihre Bedeutung

in der Rubrik wurde eine neue Gruppe für die Instanz (üblicherweise harmony.0) angelegt.

<img src="media/adapter_AdapterName_objects_01.png">

Die Struktur der angelegten Objekte und ihre Funktionen sind wie folgt:

**Instanz**

mehrere Instanzen sind bei diesem Adapter nicht erlaubt


   **Hub Name**
   
   Name des Hubs
   
   
      **Gerät**
      
      Hier erscheinen alle am Harmony-Hub angelernten Geräte
      
         
         **Funktion**
         
         Die zur Verfügung stehenden Funktionen hängen von dem entsprechenden Gerät ab
         
      
      **Aktivität**
      
      Hier erscheinen alle am Harmony Hub programmierten Aktivitäten
      
      
         **Funktion**
         
         Instance.Hub_Name.activity zeigt die aktuell gewählte Aktivität an - Nur Lesen
         
         Instance.Hub_Name.connected zeigt an, ob der Hub mit ioBroker verbunden ist - Nur Lesen





#### Bedeutung der States
(in die Struktur oben einbinden!)

Beschreibung der Objekte

Beschreibung der States
 Beschreibung der möglichen Zustände



## Deinstallation
sollte die Instanz wieder entfernt werden sollen wird diese über das zugeordnete Mülleimer-Icon 
in der Rubrik Instanzen entfernt

<img src="media/adapter_AdapterName_delete_01.png">

Es erscheint eine Sicherheitsabfrage, die mit ***OK*** bestätigt werden muss

<img src="media/adapter_AdapterName_delete_02.png">

Anschließend erscheint wieder ein Fenster, dass die Abarbeitung der Deinstallationsbefehle zeigt

<img src="media/adapter_AdapterName_delete_03.png">

Bei dieser Deinstallation werden alle zu der Instanz gehörenden Objekte vollständig entfernt.

Sollten die Installationsdateien vollständig von dem Host gelöscht werden, muss dies über das Mülleimer-Icon 
in der Kachel des AdapterName-Adapters in der Rubrik Adapter geschehen.





## Beispiele/Demo
Lorem ipsum


## Besonderheiten
Backup
Multihost
History
Performance


## Bekannte Probleme

* was auch immer
  Lösung:

* und noch ein ganz böser
  Lösung:

* weiß der Teufel
  Lösung:



## Einbinden der States

### Blockly
Lorem ipsum

### Node-Red
Lorem ipsum

### vis
Lorem ipsum

### History
Lorem ipsum


## Links
Irgendwo kommen auch noch Links zu GitHub (Entwicklerbereich?) und
externen Ressourcen? Aber bitte nicht gleich am Doku-Anfang, eher am Ende.
Zuerst die leichte Kost.



## Entwicklerbereich


----------


