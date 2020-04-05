# Kunden

Die Agenturverwaltung verwendet für die Abbildung der Auftraggeber-Seite drei hierarchische Ebenen: **Kunde** &gt; Etat &gt; Projekt. 

![](../../.gitbook/assets/1.png)

Zu einem Kunden können ein oder mehrere **Etats** verwaltet werden.   
Innerhalb eines **Etats** kann es ein oder mehrere Projekte geben.  
Diese Seite behandelt die mittlere Ebene: **den Etat**.

## Kunden in der Projektverwaltung

Ein Kunde ist die oberste Hierarchie-Ebene in der Projektverwaltung. An einem Kunden werden die Stammdaten eines Kunden hinterlegt, welche es dann beim Anlegen eines neuen Etats verwendet werden.

Jeder Kunde hat ein einzigartiges Kürzel, welches für Projekt- und Rechnungsnummern verwendet wird und in den Kundenstammdaten angezeigt wird.

Da an einem Kunden-Datensatz alle Etat- und Projekte-Informationen zusammenkommen, lassen sich hier Kunden-weite Reportings und Berichte anzeigen und auswerten.

## Der Kunden-Status

Ein Kunde kann über den Status von `aktiv` auf `ruhend` gestellt werden. Alle Etats sowie Projekte dieses Kunden gelten dann unabhängig von deren Status auch als geschlossen. D.h. es können keine weiteren Arbeitszeiten oder Fremdleistungen darauf gebucht werden, neue Finanzdokumente wie Kostenvoranschläge, Gutschriften oder Rechnungen können auch nicht mehr für diese Projekte erstellt werden.

Der Status kann jederzeit zurück auf `aktiv` gestellt werden.

{% hint style="info" %}
**Statuswechsel nur mit bestimmten Berechtigungen ermöglichen**  
Es kann auch definiert werden, dass ein Nutzer nur unter bestimmten Bedingungen - z.B. nur mit Administrator-Rechten -  den Status ändern kann.   
Ein Anwendungsszeario wäre z.B. das erneute Öffnen eines ruhenden Kunden nur durch Administratoren zu erlauben.  
Sprecht unseren Kundenservice an wenn ihr solche Regeln in euren Abläufen habt:  
info@dieagenturverwaltung.de
{% endhint %}



