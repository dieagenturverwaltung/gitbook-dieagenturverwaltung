---
description: >-
  Eingangsrechnungen sind Rechnungsdokumente und Belege der Lieferanten unseres
  Unternehmens. Sie sind oft projektbezogen und gehen auf digitalem oder
  analogem Weg ein.
---

# Eingangsrechnungen

![](../../.gitbook/assets/bildschirmfoto-2020-03-08-um-16.56.42.png)

## Filter in der Eingangsrechnungsliste

Die Liste der Eingangrechnungen lässt sich über Filter oberhalb der Liste einschränken.

### Suche mit Wildcards \*

Die Suche erlaubt das Suchen nach Dokumentennummer, Projektnummer,Lieferant oder Betreff des Dokuments.\
Mit dem Asterisk (\*) können auch Wildcard-Suchen durchgeführt werden im abgebildeten Beispiel kann ich z.B. durch die Eingab des Suchbegriffs `12*2020`  Alle Dokumente finden in denen "12" gefolgt von "2020" vorkommt. Wir hätten hier z.B. einen Suchtreffer beim zweiten Dokument der Liste.

### Suche nach Verantwortlichem

Über diesen Filter kann ein Nutzer ausgewählt werden und die Liste zeigt dann nur die Dokumente dieses Nutzers. Der Filter beinhaltet auch den Eintrag "Meine Eingangsrechnungen".

### **Suche nach Status**

Dieser Filter schränkt die Liste nach Dokumenten ein, die sich in einen bestimmten Status befinden.

{% hint style="info" %}
FIltereinstellungen werden bis zur nächsten Anmeldung am System gespeichert.
{% endhint %}

## Status von Eingangsrechnungen

Eingangsrechnungen laufen von der Erfassung des Belegs bis zur Übergabe in die Buchhaltung durch folgende Prozessschritte:

#### wartet auf Erfassung

Ein Beleg wurde z.B. bereits als Anhang hochgeladen, jedoch noch nicht weiter erfasst.

#### wartet auf Projektzuordnung

Dieser Beleg wurde erfasst und wartet darauf dass ein Projektmanager ihn als Fremdleistung auf ein oder mehrere Projekte bucht.\
Unter Umständen wurde der Projektmanager bereits per Wiedervorlage benachrichtigt.

#### wartet auf Zahlungsfreigabe (optional)

Dieser Beleg wartet darauf, dass eine zur Zahlungsfreigabe berechtigte Person, den Beleg zur Zahlung freigibt.

#### wartet auf Buchung  (optional)

Die Zuordnung des Belegs zu einem oder mehreren Projekten ist erfolgt. Je nach Konfiguration ist auch eine Zahlungsfreigabe erteilt worden. Der Beleg kann nun ggf. bezahlt werden und an ein Buchhaltungs-Drittsystem z.B. DATEV übergeben werden.

#### gebucht

Dieser Beleg wurde an die Buchhaltung übergeben.

{% hint style="info" %}
**In deinem Unternehmen sind eventuell nicht alle Prozessschritte aktiviert?**

Du kannst als Administrator die optionalen Schritte unter Einstellungen > Prozessdefinitionen > Prozess-Konfigurator für Eingangsrechnungen aktivieren.

[Mehr erfahren](../../einstellungen-1/prozessdefinitionen/prozess-konfigurator-fuer-eingangsrechnungen.md)
{% endhint %}

In der Liste der Eingangsrechnungen kann auf einen Blick erkannt werden, in welchem Status sich ein Dokument befindet:



![](../../.gitbook/assets/bildschirmfoto-2020-03-08-um-16.56.58.png)
