# Etats

Die Agenturverwaltung verwendet für die Abbildung der Auftraggeber-Seite drei hierarchische Ebenen: Kunde &gt; **Etat** &gt; Projekt. 

![](../../.gitbook/assets/1.png)

Zu einem Kunden können ein oder mehrere **Etats** verwaltet werden.   
Innerhalb eines **Etats** kann es ein oder mehrere Projekte geben.  
Diese Seite behandelt die mittlere Ebene: **den Etat**.

## Warum Etats? 

Etats benötigen wir, um Gruppen von Projekten auswerten zu können. Außerdem sind im Etat die Stundensätze hinterlegt, die wir mit dem Kunden für verschiedene Arbeiten vereinbart haben. Damit ist es möglich, innerhalb eines Kunden auch **verschiedene Preislisten für Stundensätze** zu führen. 

> Ein Beispiel: Für einen Kunden legen wir einen Etat für die Social-Media-Betreuung im laufenden Jahr an, in dem die mit dem Kunden vereinbarte Stundensätze hinterlegt sind. Wir legen für die Plattformen Facebook und Twitter jeweils ein Projekt in diesem Etat an. Später im Jahr erstellen wir einen zweiten Etat "Webseite" mit verschiedenen Projekten, für die wir mit dem Kunden _andere Stundensätze_ vereinbart haben**,** da diese Arbeiten nicht in den Rahmen des vereinbarten Servicevertrags fallen.
>
> Ein weiteres Beispiel wäre die Neuverhandlung von Preisen bei der Verlängerung der Zusammenarbeit mit dem Kunden. Hier macht es Sinn, einen neuen Etat anzulegen und den Alten Etat zu schliessen sobald alle Projekte darin zu Ende geführt wurden.

### **In den meisten Fällen benötigen wir die Etat-Ebene nicht** 

Das heißt, wenn wir ein Projekt zu einem Kunden anlegen, landet das einfach in einem Standard-Etat "Projekte". Hier gilt für jedes Projekt dieses Kunden dann die gleiche Preisliste.

## Der Etat-Status

Ein Etat kann über den Status von `aktiv` auf `geschlossen` gestellt werden. Die im Etat definierten Projekte gelten dann unabhängig von deren Status auch als geschlossen. D.h. es können keine weiteren Arbeitszeiten oder Fremdleistungen darauf gebucht werden, neue Finanzdokumente wie Kostenvoranschläge, Gutschriften oder Rechnungen können auch nicht mehr für diese Projekte erstellt werden.

Der Status `ruhend` dokumentiert, dass ein Etat zur Zeit zwar nicht geschlossen ist, sich jedoch wie ein geschlossener Etat verhält, d.h. es können z.B. auf die Projekte des Etats keine Zeiten darauf gebucht werden.

{% hint style="info" %}
**Statuswechsel nur mit bestimmten Berechtigungen ermöglichen**  
Es kann auch definiert werden, dass ein Nutzer nur unter bestimmten Bedingungen - z.B. nur mit Administrator-Rechten -  einen Status ändern kann.   
Ein Anwendungsszeario wäre z.B. das erneute Öffnen eines bereits geschlossenen Etats nur durch Administratoren zu erlauben.  
Sprecht unseren Kundenservice an wenn ihr solche Regeln in euren Abläufen habt:  
info@dieagenturverwaltung.de
{% endhint %}

