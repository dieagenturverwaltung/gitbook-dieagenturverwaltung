# Kostenvoranschlagsnummern

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

