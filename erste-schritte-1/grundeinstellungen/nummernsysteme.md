# Nummernsysteme

Die Agenturverwaltung erlaubt die Verwendung komplexer Nummernsysteme.

Uns sind im Verlauf der letzten Jahre schon etliche \(mehr und oft auch weniger nützliche\) Nummersysteme begegnet. Wenn es keinen Grund dafür gibt - z.B. externe Systeme, die mit den gleichen Nummern arbeiten - sollte das Nummernsystem so einfach wie möglich gehalten werden.

Die Agentursoftware verwendet ein standardmässig Nummernsysteme, welche sich in den vergangenen Jahren bei einer Vielzahl von Kunden bewährt haben. 

{% hint style="info" %}
Solltet ihr aufgrund von Abhängigkeiten zu Drittsystemen aber einen anderes Nummernsystem benötigen, können wir dieses fast immer übernehmen und unterstützen wir euch bei der Konfiguration.   
  
Kontaktiert uns gern über unseren Kundenservice: [info@dieagenturverwaltung.de](mailto:info@dieagenturverwaltung.de)
{% endhint %}

## Informationen zu den Nummernsystemen in der Agenturverwaltung

Im Nachfolgenden erfahrt ihr, welche Best Practice Nummernsysteme sich herausgebildet haben. Wir besprechen nacheinander:

* Kostenvoranschlagsnummern
* Projektnummern
* Rechnungsnummern

Allen Nummernsystem ist gemein, dass die Agenturverwaltung sicherstellt, dass 

* keine Nummern doppelt erzeugt werden können 
* keine Nummern fehlen 

### **Best Practice bei Kostenvoranschlägen**

Die Nummern setzen sich zusammen aus &lt;KV-Präfix&gt;-&lt;vierstelliges Jahr&gt;-&lt;dreistellige durchlaufende Zahl&gt;

> KV-2018-015   
> KV-2019-001

Die dreistellige durchlaufende Zahl der Kostenvoranschlag beginnt zum Jahreswechsel erneut mit der 001. Sollte es in einem Jahr tatsächlich mal mehr als eintausend Kostenvoranschläge an einen Kunden geben, wird die Zahl automatisch vierstellig.

#### Die Kostenvoranschlagsnummer enthält kein Kundenkürzel

Wenn wir einem Neugeschäftskunden ein Angebot erstellen, möchten wir evtl. nicht zunächst einen Kunden, Etat und ein Projekt in der Agentursoftware anlegen. Wir wissen ja noch nicht, ob aus der Anbahnung überhaupt etwas wird.  
  
Gibt der Kunde den Kostenvoranschlag später frei und wir legen den Kunden und das Projekt im System an, verschieben wir den bestehenden Kostenvoranschlag einfach ins neu angelegte Projekt. Da Kostenvoranschläge generell keine Kundenkürzel führen, entsteht dadurch auch kein Nummernkonflikt beim Erstellen von weiteren Angeboten für diesen Kunden.

#### Vorteile dieses Musters

* Die Nummer ist als Dateiname - sogar auf einem Webserver - geeignet
* Das Präfix unterscheidet zwischen Kostenvoranschlag und Rechnung
* In einem Dateisystem sortieren sich nach Kostenvoranschlagsnummer benannte Dateien automatisch nach Jahr und durchlaufender Nummer

#### Kostenvoranschlagsnummer ist nicht gleich Projektnummer

* Ein Kostenvoranschlag sollte auch ohne Projekt erstellt werden können
* Ein Projekt kann mehrere Kostenvoranschläge enthalten
* Ein Projekt kann mehrere \(nicht realisierte\) Versionen eines KVs enthalten, die bereits beim Kunden waren. Diese Versionen sollten durch unterschiedliche Nummern eindeutig voneinander unterscheidbar sein.

#### Nummernkreise bei Kostenvorschlagsnummern sind möglich

Kostenvoranschläge können optional in so genannten Nummernkreisen gepflegt werden. Das heißt, ihr könnt für jeden Kunden einen eigenen Kostenvoranschlagsnummernkreis öffnen.   
Dadurch wird für einen Kunden nicht aus der Kostenvoranschlagsnummer erkennbar, ob und wieviele Kostenvoranschläge ihr anderen Kunden stellt.

### **Best Practice bei Projektnummern**

#### Warum überhaupt Projektnummern?

* Projektnummern können in Kostenvoranschlägen, Rechnungen und der Korrespondenz mit dem Kunden hilfreiche Referenznummern sein.
* Sie können bei der Beauftragung an Lieferanten weitergegeben werden, die die Projektnummer dann auf ihren Rechnungen führen. Das vereinfacht die Zuordnung von Fremdleistungen auf Projekte erheblich.

Sprecht uns an, wenn ihr weitergehende Fragen zu diesem Thema haben.

#### **Wir empfehl**en dieses Projektnummernmuster

Die Nummern setzen sich zusammen aus ‌  
&lt;Kundenkürzel&gt;-&lt;vierstellige durchlaufende Zahl&gt;

> TUI-0029‌  
> ‌BAB-0002

Die vierstellige durchlaufende Zahl zählt also innerhalb eines Kunden alle Projekte.

{% hint style="info" %}
Es ist bewusst keine Jahreszahl in die Nummer integriert, da es häufig vorkommt, dass Projekte über Jahresgrenzen hinweg fortlaufen.  
  
Eine Jahreszahl wäre dann lediglich ein Indikator dafür, in welchem Jahr das Projekt angelegt wurde, diese Information ist über eine Agentursoftware jedoch ohnehin zugänglich.
{% endhint %}

#### **Weitere Vorteile dieses Musters** <a id="weitere-vorteile-dieses-musters"></a>

* Die Nummer ist als Dateiname - sogar auf einem Webserver - geeignet
* In einem Dateisystem sortieren sich Projektnummern automatisch nach Kunde und durchlaufender Nummer
* Das Kundenkürzel definiert für den Kunden einen eigenen Nummernkreis 
* Rückschlüsse des Kunden auf andere Projekte der Agentur sind nicht möglich
* Wenn Kundenkürzel in der Agentur etabliert sind, lässt sich leicht danach suchen

### **Best Practice bei Rechnungen**

Die Nummern setzen sich zusammen aus  
&lt;RG-Präfix&gt;-&lt;Kundenkürzel&gt;-&lt;vierstelliges Jahr&gt;-&lt;dreistellige durchlaufende Zahl&gt;

> RG-TUI-2018-012  
> RG-BAB-2019-001

Die dreistellige durchlaufende Zahl der Rechnung beginnt zum Jahreswechsel erneut mit der 001. Sollte es in einem Jahr tatsächlich mal mehr als 999 Rechnungen an einen Kunden geben, wird die Zahl automatisch vierstellig.

#### Vorteile dieses Musters <a id="vorteile-dieses-musters"></a>

* Die Nummer ist als Dateiname - sogar auf einem Webserver - geeignet
* Das Präfix unterscheidet zwischen Rechnung und Kostenvoranschlag
* In einem Dateisystem sortieren sich nach Rechnungsnummer benannte Dateien automatisch nach Kunde, Jahr und durchaufender Nummer
* Das Kundenkürzel definiert für den Kunden einen eigenen Nummernkreis 
* Rückschlüsse des Kunden auf den Agenturumsatz sind nicht möglich
* Wenn Kundenkürzel in der Agentur etabliert sind, lässt sich leicht danach suchen

#### Nummernkreise bei **Rechnungsnummern** sind möglich

Ausserdem erlaubt die Agentursoftware das Führen von Rechnungsnummern in sogenannten Rechnungsnummernkreisen.  
Ihr könnt beispielsweise für jeden Kunden einen eigenen Rechnungsnummernkreis öffnen. So wird für den Kunden nicht aus der Rechnungsnummer erkennbar, ob und wieviele Rechnungen ihr anderen Kunden stellt. Das deutsche Steuerrecht erlaubt das führen solcher Rechnungsnummernkreise.

Sprecht uns an, wenn ihr weitergehende Fragen zu diesem Thema haben.

### **Best Practice bei** Paginiernummern für Fremd- bzw. Eingangsrechnungen

Die Agenturverwaltung vergibt für jede erfasste Eingangsrechnung eine Paginiernummer. Viele Agenturen vermerken diese Nummer beim Rechnungseingang auch auf dem Papierbeleg \(sofern es einen gibt\).

Somit gibt auch der Papierbeleg Auskunft darüber, dass er bereits im System erfasst wurde.

Das Muster bei Paginiernummer ist wie folgt: &lt;vierstellige durchlaufende Zahl&gt;-&lt;vierstelliges Jahr&gt;

> 0009/2019

Die Kennzeichnung digitaler Belege ist in der Agentursoftware nicht notwendig, da sie direkt in Die Agenturverwaltung hochgeladen werden und jederzeit abrufbar sind.

Diese Belege können auch in Form von Links digital an den Steuerberater weitergegeben werden.

## Nummerkreise können ganz schön kompliziert werden...

... vor allem wenn Abhängigkeiten zu Drittsystemen ins Spiel kommen.

{% hint style="info" %}
Solltet ihr allgemeine Fragen haben oder aufgrund von Abhängigkeiten zu Drittsystemen einen anderes Nummernsystem benötigen, kontaktiert uns gern über unseren Kundenservice: [info@dieagenturverwaltung.de](mailto:info@dieagenturverwaltung.de)
{% endhint %}







