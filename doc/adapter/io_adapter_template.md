---
date: "{Änderungsdatum des Artikels}"
title: "{Seitentitel}"
adapter: "{npm Paketname}"
---


# <img src="media/{Adaptericon}" width=150 hight=150/>&emsp;{Adaptername}-Adapter
In diesem Abschnitt wird eine endanwenderfreundliche Zusammenfassung des Anwendungszwecks des Adapters gegeben. Diese Zusammenfassung soll kurz gehalten sein (maximal 1-3 kleine Absätze). Sie soll gerade so viele Informationen enthalten, dass das Interesse des Anwenders geweckt wird und er entscheiden kann, ob der Adapter für ihn relevant ist. 

Technische Hintergrundinformationen zum Adapter und ggf. Geräten stehen im Abschnitt "Überblick". 


<!-- Einführungsbild-->
![{alt BildName}](media/{Bild} "{Bildbeschreibung") <span style="color:grey">  
*{Bildbeschreibung}*</span>



<details open><summary>Inhaltsverzeichnis</summary><p>

| Navigation                          |
|-------------------------------------|
| 1  [Steckbrief](#steckbrief)        |  
| 2  [Überblick](#überblick)          |
| 3  [Installation](#installation)    |
| 4  [Konfiguration](#konfiguration)  |
| 5  [Instanz](#instanz)              |
| 6  [Objekte](#objekte)              |
| 7  [Besonderheiten](#besonderheiten)|
| 8  [FAQ](#faq)                      |
| 9  [Beispiele](#beispiele)          |
| 10 [Deinstallation](#deinstallation)|
| 11 [Links](#links)                  |
| 12 [Historie](#historie)            |
</p></details>



<a name="steckbrief"/>

## Steckbrief
> Achtung! Die folgende Tabelle dient nur als Beispiel. Sie wird vom 
  Dokumentengenerator dynamisch erzeugt und an dieser Stelle eingefügt.
  Je nach den ausgewählten Feldern sind die Datenquellen z.B. `frontmatter`,
  `io-package.json` und `package.json` des jeweilgen Adapters.

|                         |                              |
|-------------------------|:----------------------------:|
| Stand der Doku          | {date:}                      | 
| aktuelle Version stable | ![stable][logo]              |
| aktuelle Version latest | ![latest][logo]              | 
| OS                      | unterstützte OS              |
| node-Version            | unterstützte node-Versionen  |
| Entwickler              | Name/Alias des Entwicklers   |
| Github                  | LINK                         |
| Lizenz                  | MIT                          |
| Kategorie               | gemäß Adapterliste           |
| Keywords                | `Suchworte`                  |
| Abhängigkeiten          | `dependencies`               |      



<a name="überblick"/>

## Überblick

### {Angebundenes System}
In diesem Abschnitt wird grundlegendes zum einem eventuell angebundenen System
gesagt. Wofür ist es gut? Was kann man damit machen? Wie erfolgt die 
Kommunikation? Wie ist der Systemaufbau? Welche Rahmenbedingungen gibt es? 

### {Adaptername}-Adapter
Hier werden Hintergrundinformaton zum Adapter gegeben. Dies kann im Rahmen eines
Geräteadapters Information zu dem Gerät sein, oder bei einem Adapter für ein 
Kommunikationsprotokoll Grundlagen zu dem Protokoll.
Trotzdem sollte dieser Text allgemeinverständlich auch für Einsteiger sein.



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


