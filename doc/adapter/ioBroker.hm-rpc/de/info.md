---
date: "{Änderungsdatum des Artikels}"
title: "{Seitentitel}"
adapter: "{npm Paketname}"
---


# <img src="media/{Adaptericon}" width=150 hight=150/>&emsp;{Adaptername}-Adapter
Der hm-rpc Adapter bietet die Anbindung an die Kommunikationsmodule einer Homematic-Zentrale. Es werden die Module rfd (Funk), rfd-IP (HM-IP Funk), hs485d (wired), cuxd (Zusatzsoftware zur Anbindung externer Komponenten wie EnOcean, FS20 usw.) und homegear (CCU Ersatz) unterstützt. Eine Instanz des Adapters ist für genau EINES dieser Module zuständig. Sollen mehrere Module parallel unterstützt werden, muss für jedes Modul eine eigene Instanz installiert werden. 


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
In diesem Abschnitt wird Grundlegendes zu einem eventuell angebundenen System
oder Verfahren gesagt. Wofür ist es gut? Was kann man damit machen? Wie erfolgt
die Kommunikation? Wie ist der Systemaufbau? Welche Rahmenbedingungen gibt es? 

### {Adaptername}-Adapter
Hier werden Hintergrundinformationen zum Adapter gegeben. Dies kann im Rahmen 
eines Geräteadapters Information zu dem Gerät sein, oder bei einem Adapter für 
ein Kommunikationsprotokoll Grundlagen zu dem Protokoll.
Trotzdem sollte dieser Text allgemeinverständlich auch für Einsteiger sein.



<a name="voraussetzungen"/>

## Voraussetzungen vor der Installation
Der Anwender erhält hier Informationen, welche Schritte ggf. vor der Installation 
des Adapters u.a. auf externen Systemen auszuführen sind. Dazu gehören z.B. die
Registrierung von API-Keys oder die Konfiguration von angebundenen System 
nach Herstellerdokumentation. 



<a name="installation"/>

## Installation
Hier werden Besonderheiten zur Installation beschrieben, die den Umfang der
**hier** dokumentierten Standardinstallation überschreiten. Das kann z.B.
die manuelle Installation von Software vor der eigentlichen Adapterinstallation
oder die Freischaltung von Ports auf dem Server sein.

> Eine Instanz des Adapters wird über die ioBroker Admin-Oberfläche installiert. 
  Die ausführliche Anleitung für die dazu notwendigen Installatonschritte findet 
  man **hier**.



<a name="konfiguration"/>

##  Konfiguration


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


# Snippets


# Adapter - Homematic RPC

Der hm-rpc Adapter bietet die Anbindung an die Kommunikationsmodule einer Homematic-Zentrale CCU2 / CCU1\. Es werden die Module rfd (funk), hs485d (wired), cuxd (Zusatzsoftware zur Anbindung externer Komponenten wie EnOcean, FS20 usw.) und homegear (CCU Ersatz) unterstützt. Eine Instanz des Adapters ist für genau EINES dieser Module zuständig. Sollen mehrere Module parallel unterstützt werden, muss für jedes Modul eine eigene Instanz installiert werden. Der Adapter kommuniziert entweder über BIN-RPC oder XML-RPC mit dem entsprechenden Modul.  Der Adapter arbeitet über eine Ereignisschnittstelle. Daher ist es wichtig, die Adapter Adresse korrekt anzugeben. Die CCU sendet dann automatisch Ereignisse an den Adapter, d.h. ein zyklisches Pollen wie z.B. bei hm-rega ist nicht notwendig. Zustätzlich verfügt der Adapter über die Funktionalität, die Verbindung zur CCU zyklisch zu überwachen. Werden neue Geräte an der CCU angelernt ist es notwendig, den Adapter neu zu starten mit der Konfigration “Initiere Geräte neu (einmalig)”. Dadurch werden die Informationen über die neuen Homematic-Geräte an den Adapter übertragen.


## Konfiguration

  [![](img/ioBroker_HM-rpc_Konfig01.jpg)](img/ioBroker_HM-rpc_Konfig01.jpg)  

### HomeMatic Adresse

Hier wird die IP-Adresse der CCU eingegeben, deren Daten in ioBroker übernommen werden sollen. Es können über mehrere Instanzen des Adapters auch mehrere CCU eingebunden werden. Das Format dieser Adresse muss `192.168.xxx.yyy` sein.

* * *

### Adapter Adresse

Hier wird die IP-Adresse des Servers, auf dem ioBroker läuft eingegeben. Es stehen verschiedene Möglichkeiten mit ipv4 und ipv6 über das pulldown-Menü zur Verfügung. [![](img/ioBroker_HM-rpc_Konfig_Adresses.jpg)](img/ioBroker_HM-rpc_Konfig_Adresses.jpg) Standard ist ipv4 `0.0.0.0`; allerdings muss hier eine von außen (von der anzusprechenden CCU aus) erreichbare Adresse wie `192.168.xxx.yyy` eingegeben werden, da die CCU bei der Kommunikation die Ereignisse an diese Adresse sendet.

* * *

### Daemon

Der zu überwachende Daemon (derzeit _rfd_, _hs485d_, _cuxd, Homematic IP_ oder _homegear_) 
![](img/homematic-rpc-2_ioBroker_HM-rpc_Konfig_daemons.jpg)


* * *

### Homematic Port

Der Port in der CCU über den die Daten abgerufen werden können. Für jedes Modul ist hier bereits der passende Standardport eingetragen, er muss daher nur angepasst werden, wenn er auf der CCU selbst verändert wurde.

* * *

### Protokoll

Das Protokoll über das die Daten aus der CCU abgefragt werden sollen. Es stehen _XML-RPC_ und _BIN-RPC_ zur Verfügung. Das empfohlene Protokoll ist _BIN-RPC_.

* * *

### Adapter Port

Der Port auf dem ioBroker-Server. Ist der eingegebene Wert 0 wird hier der gleiche Port verwendet, wie er auch auf der Homematic-Zentrale verwendet wird. Ansonsten kann man hier einen Port frei wählen. z.B.: 3000

* * *

### Verbindungs-Check Intervall (sek)

Die Zeitabstände in denen die Verbindung geprüft werden soll (_default 180_)

* * *

### Synchronisiere Geräte neu (einmalig)

Wenn in der CCU neue Geräte konfiguriert oder Änderungen an bestehenden Geräten durchgeführt wurden, werden die neuen Daten anschließend in ioBroker geladen.

* * *

## <span id="Bedienung">Bedienung</span>

Eine manuelle Bedienung des Adapters findet nicht statt. Beim Start wird dem entsprechenden CCU Modul mitgeteilt, Änderungen automatisch an den Adapter zu senden. Diese Ereignisse werden dann in die Datenpunkte von ioBroker übernommen.
