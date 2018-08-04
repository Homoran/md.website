# Idee von ioBroker
Die Grundidee von ioBroker ist es, eine Plattform anzubieten, auf der verschiedene IoT-Systeme zusammengefasst werden k�nnen um diese �ber ***eine*** Oberfl�che zu steuern oder zu visualisieren.

![Broker](img/marketing-buzz.png)

Dazu bietet ioBroker verschiedene so genannte Adapter an, die sich z.B. mit dem Gateway des jeweiligen Systems verbinden. Die Zust�nde der in dem jeweiligen System angeschlossenen Ger�te werden von diesen Adaptern bidirektional ausgewertet und in einer gemeinsamen Datenbank verwaltet, so dass mit einfachen Mitteln nur noch die Zust�nde dieser Datenbank bearbeitet werden m�ssen.

Mit weiteren Adaptern aus der Gruppe der Logik kann dann auf �nderungen dieser Zust�nde reagiert und ebenso Zust�nde, die auch von einem anderen Adapter kommen ge�ndert werden.

Es k�nnen nicht nur komplette IoT-Systeme eingebunden werden, sondern auch andere Datenquellen. Dabei ist es ebenfalls m�glich Daten nicht nur aus bereitgestellten Adaptern, z.B. Benzinpreise von dem Tankerk�nig-Adapter zu verwerten, es ist auch m�glich per Javascript oder mit dem Parseradapter eigene Datenpunkte zu erzeugen und mit Daten zu f�llen.