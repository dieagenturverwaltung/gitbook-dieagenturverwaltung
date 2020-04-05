# Projekte

Die Agenturverwaltung verwendet für die Abbildung der Auftraggeber-Seite drei hierarchische Ebenen: Kunde &gt; Etat &gt; **Projekt**. 

![](../../.gitbook/assets/1.png)

Zu einem Kunden können ein oder mehrere Etats verwaltet werden.   
Innerhalb eines Etats kann es ein oder mehrere Projekte geben.  
Diese Seite behandelt die unterste Ebene: **das Projekt**.

Das Projekt ist die Ebene, auf welcher die operative Arbeit einer Agentur abgebildet wird. Hier werden unter anderem:

* Vorgänge verwaltet
* Projekt-Reportings bereitgestellt
* Finanzdokumente mit Projektbezug gesammelt
* Agentur- und Fremdleistungen sowie Projektbudgets überwacht
* Projektdokumente und -notizen gepflegt
* Zugriffsrechte verwaltet
* Projektbezogene Wiedervorlagen erstellt und eingesehen

Ein Projekt ist darüber hinaus die Grundlage für viele operative Prozesse in der Agenturverwaltung:

* Projektmitarbeiter buchen Zeit auf Projekte
* Fremdleistungen werden Projekten zugeordnet 
* Vorgänge, also Teilaufgaben, können in Projekten verwaltet werden
* Kostenvoranschläge werden im Rahmen von Projekten erstellt
* Aufwände aus Projekten werden in Rechnungen überführt
* In manchen Fällen werden sogar Gutschriften in Projekten erstellt

Wie ihr Projekte anlegt, konfiguriert, überwacht und abrechnet erfahrt ihr auf den Unterseiten.

## Die Projektnummer

Die Projektnummer ist die eindeutige Kennung, die beim Erstellen eines Projekts nach dem von euch vorgegebenen Muster erzeugt wird. Diese Nummer kann z.B. an Lieferanten herausgegeben werden damit diese bei der Rechnungsstellung später auf das Projekt verweisen können. So wird bei der Belegerfassung viel Zeit gespart.

Nach welchem Muster eine Projektnummer aufgebaut sein kann, erfährst du hier:

{% page-ref page="../../erste-schritte-1/grundeinstellungen/nummernsysteme.md" %}

## Projektstatus

Ein Projekt kann über den Status von `aktiv` auf `geschlossen` gestellt werden wenn es abgeschlossen ist. Es können dann keine weiteren Arbeitszeiten oder Fremdleistungen darauf gebucht werden. Neue Finanzdokumente wie Kostenvoranschläge, Gutschriften oder Rechnungen können auch nicht mehr für diese Projekte erstellt werden.

Ein Projekt im Status `abzurechnen` signalisiert, dass die Arbeiten abgeschlossen sind und das Projekt darauf wartet von der zuständigen Person abgerechnet zu werden.

Der Status `ruhend` dokumentiert, dass ein Projekt zur Zeit zwar nicht geschlossen ist, sich jedoch wie ein geschlossenes Projekt verhält, d.h. es können z.B. keine Zeiten darauf gebucht werden.

{% hint style="info" %}
**Statuswechsel nur mit bestimmten Berechtigungen ermöglichen**  
Es kann auch definiert werden, dass ein Nutzer nur unter bestimmten Bedingungen - z.B. nur mit Administrator-Rechten -  einen Status ändern kann.   
Ein Anwendungsszeario wäre z.B. das erneute Öffnen eines bereits geschlossenen Projekts nur durch Administratoren zu erlauben.  
Sprecht unseren Kundenservice an wenn ihr solche Regeln in euren Abläufen habt:  
info@dieagenturverwaltung.de
{% endhint %}

## Wann sollte ein Projekt unterteilt werden?

Projekte in Teilschritte zu zerlegen macht aus unterschiedlichsten Gründen Sinn, beispielsweise weil sich Teilabschnitte leichter kalkulieren, beim Einkauf freigeben und abrechnen lassen.

Weitere Hinweise dazu in unserem Blog:  
[https://www.dieagenturverwaltung.de/blog/projekte-richtig-unterteilen/](https://www.dieagenturverwaltung.de/blog/projekte-richtig-unterteilen/)

## Auswertung mehrerer Projekte

Um Gruppen von Projekten auszuwerten bieten sich entweder Etats an oder falls die Projekte aus bestimmten Gründen nicht zusammen in einem Etat liegen können Benutzerdefinierte Filter. Mit diesen Filtern ist es zum Beispiel möglich alle Projekte einer bestimmten Branche oder alle Media-Projekte auszuwerten.

Wie Benutzerdefinierte Filter verwendet werden steht hier:

{% page-ref page="../../einstellungen-1/berichte/benutzerdefinierte-filter.md" %}



