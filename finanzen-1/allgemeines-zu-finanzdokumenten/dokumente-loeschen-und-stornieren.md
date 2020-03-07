# Dokumente löschen und stornieren

![Beispielansicht der L&#xF6;sch- und Storno-Funktion einer Ausgangsrechnung](../../.gitbook/assets/bildschirmfoto-2020-03-07-um-15.46.30%20%281%29.png)

## Dokument löschen

Im Reiter "Optionen" kann ein Finanzdokument gelöscht werden.

Bei Ausgangsrechnungen und Gutschriften hängt die Möglichkeit einer Löschung davon ab, ob die Inkrementelle Nummer des Rechnungsnummernkreises die höchste ihres Kreises ist.

{% hint style="info" %}
**Beispiel**

AKA-2020-003 kann gelöscht werden  
AKA-2020-002 kann nur storniert werden  
AKA-2020-001 kann nur storniert werden  
AKA-2019-087 kann storniert oder gelöscht werden  
AKA-2019-086 kann nur storniert werden  
AKA-2019-085 kann nur storniert werden  
...
{% endhint %}

## Dokument stornieren

Beim Stornieren einer Ausgangsrechnung oder Gutschrift wird eine Kopie des Dokuments mit einer neuen Nummer erzeugt, deren Beträge mit -1 multipliziert werden. D.h. beide Dokumente zusammen verhalten sich buchhalterisch neutral.

In der Druckversion verweist ein Kasten im Fuß beider Dokumente auf das stornierte Dokumente bzw. das Quelldokument der Stornorechnung.

![](../../.gitbook/assets/bildschirmfoto-2020-03-07-um-16.18.09.png)

Der Zahlungsstatus dieser beiden Dokumente wird auf "storniert" gestellt.

