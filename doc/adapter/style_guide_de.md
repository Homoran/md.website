# Style-Guide zur Adapter-Dokumentation

* Die Dokumentation wird mit Hilfe der Sprache "Markdown" erstellt.
* Die Dateiablage für die Adapterdokumentation ist wie folgt geregelt:
  * In jedem Adapter-Projekt gibt es einen Ordner
    `doc/adapter/{github-projektname}`.
  * In diesem Ordner liegt die Datei `io-info.json`.
    Mit dieser Datei werden Metadaten sowie die Dateistruktur der
    Dokumentation beschrieben. Zum Aufbau dieser Datei siehe ...
  * Wenn die Dokumentation in deutsch vorliegt, wird sie im Unterordner
    `de` gespeichert. Erlaubte Sprachen und damit Ordnernamen sind:
    `en, de, ru, pt, nl, fr, it, es, pl`.
  * Die eigentliche Adapterdokumentation steht der Datei `info.md`,
    die direkt im jeweilgen Sprachenordner liegt.
  * Medien werden im Unterordner `media` abgelegt, der sich ebenfalls im
    Sprachenordner befindet.
  * Datei- und Ordnernamen werden mit Kleinbuchstaben geschrieben.
    Erlaubt sind die Zeichen `a-z`, `0-9`, der Unterstrich `_` sowie der
    Dezimalpunkt `.`
* Dokumente sollen einen Zeilenumbruch bei 80 Zeichen haben.
* Vorzugsweise erfolgt die Textformatierung wie in der Datei `.editorconfig`
  beschrieben.
  * Ein [Plugin][] zur automatischen Anwendung dieser Regeln ist für
    verschiedene Editoren erhältlich.
* Für deutsche Texte wird die Einhaltung der neuen deutschen Rechtschreibung
  bevorzugt.
* In Referenzdokumentationen ist die Verwendung von Personalpronomen (z.B.
  "ich", "du", "wir") zu vermeiden.
  * Verwende geschlechtsneutrale Pronomen und mehrzahlige Hauptwörter.
    * In Ordnung: "sie (mehrere)", "ihr (Besitz)", "Personen",
      "Leute", "Entwickler"
    * Nicht in Ordnung: "seine", "ihre", "er", "sie (Frau)", "Jungs", "Mädels"
* Werden Klammerelemente verwendet (alle Klammerformen und
  Anführungszeichen), werden Satzzeichen wie folgt gesetzt:
  * Innerhalb der Klammer, wenn das Klammerelement einen kompletten
    Satz enthält (Subjekt, Verb, Objekt).
  * Außerhalb der Klammer, wenn das Klammerelement nur einen Teilsatz
    enthält.
* Dokumente beginnen immer mit einer Überschrift in der Ebene H1.
* Links werden nicht inline platziert (z.B. mit `[a link](http://example.com)`),
  sondern mit Hilfe von inline `[a link][]` und
  `[a link]: https://a.link/to/know` an das Dokumentenende gestellt.
* Wenn Gedankenstriche verwendet werden, benutzt man die kurze Schreibweise
  mit dem Minuszeichen und nicht "—" oder `Option+Shift+"-"` in OSX.
* Zusätzliche Inhalte:
  * Dokumente wie Binärdateien, Bilder, Video- oder Audio-Aufnahmen werden
    im Ordner `media` abgelegt.
  * Die Einbindung der Medien in den Text erfolgt für allgemeine Dateien
    mittels `[Medienbegriff](media/{dateiname})` und für Bilder mittels
    `![Medienbegriff](media/{dateiname})`.
  * Abbildungen weden vorzugsweise im Format SVG abgelegt. Wenn SVG
    nicht möglich ist, dann als jpg oder png-Datei. Bitte ein Auge auf die
    Dateigröße haben.
* Für Quelltextabschnitte gilt folgendes:
  * Je nach Quellcodesprache ist ein entsprechende Markup zu wählen. Zum
    Beispiel ` ```js`  für JavaScript.
  * Ein Quelltext kann, muss aber nicht vollständig sein. Quelltextblöcke
    stellen Beispiele zur Verdeutlichung des jeweis gerade beschriebenen
    Standpunkts dar. Es müssen also keine vollständig lauffähigen Programme
    geliefert werden. Wenn dennoch ein vollständig lauffähiges Programm
    bereitgestellt werden soll, erfolgt das als Mediendatei im Ordner
    `media/{code_beispieldatei}` mit einer entsprechender Verknüpfung in
    der Dokumentation.
* Falls Unterstriche, Hochkommas, Sternchen oder Backslashes verwendet
  werden, sind die richtigen Escape-Zeichen zu setzten:
  `\_`, `\*`, `\\` und ``\` `` anstelle von `_`, `*`, `\` und `` ` ``.
* Um einen Hinweis besonders hervorzuheben, sind die folgenden Richtlinien
  zu beachten:
  * Setze den "Hinweis:"-Bezeichner in italic, also als `*Hinweis*:`.
  * Fahre mit einem Großbuchstaben nach dem "Hinweis:"-Bezeichner fort.
  * Setze den Hinweis an den Anfang eines neuen Absatzes, damit er besser
    sichtbar ist.
* Für Adapter-Dokumentionen gibt es eine [Vorlage][]. Die relevanten
  Vorlagenabschnitte sind in der hinterlegten Reihenfolge und Form zu nutzen.

[Plugin]: http://editorconfig.org/#download
[Vorlage]: /doc/adapter/io_adapter_tempate.md
