# Ernergiewende_FD8407
Meine kleine Enwegiewende mit Kühlschrank

# Motivation

Da hat man einen Carport und Platz für Solarzellen. Nun gut, prima für die Elektrokarre. Aber halt, die steht ja wenn die Sonne scheint auf dem Parkplatz auf Arbeit... Also hat sich die Industrie ausgedacht, dass man ja einen teuren Batteriespeicher kaufen kann. Die Kosten kriegt man nur seeehr selten wieder rein. Momentan ist das eher noch eine ideologisch motivierte Kaufentscheidung.

Aber halt, wir haben ja einen Speicher im Haus... einen Kältespeicher. Nein, sogar zwei. Kühlschrank und Kühltruhe. Jetzt müsste man den nur einschalten, wenn ein Überschuss da ist und ausschalten, wenn beispielsweise die Lebensmittel zu doll gefrieren oder die Karre wieder da ist und geladen werden will.

Damit wird gekühlt, wenn ein Leistungsüberschuss da ist. Und dann wird wenn die Sonne weg ist wieder in den Normalbetrieb gewechselt. Es wird dann langsam wieder wärmer (in Richtung der üblichen eingestellten Temperatur). Klar, dass durch eine größere Temperaturdifferenz zwischen Innenraum des Kühlschranks und Außen auch größere Verluste gibt. Aber so schlecht ist die Isolation nun auch wieder nicht und bevor ich den Strom quasi der Allgemeinheit schenke (sieben Cent Einspeisevergütung pro kWh) oder fürs Speichern draufzahle....

Doof nur, dass der Kühlschrank absolut nicht intelligent ist. Das Ding ist nun einmal knapp zwanzig Jahre alt, tut aber noch prima seinen Dienst. Zum Wegschmeißen zu schade und abgeschrieben ist er auch. Solange er läuft gehts nicht billiger... Also muss das Ding irgendwie aufgeschlaut werden. 

# Das Gerät

Die beschrieben ist die Kiste schon etwas älter. Und ohne viel drumherum ist hier ein Bild der Steuereinheit, die oben am Kühlschrank sitzt:  
![Bild Bedieneinheit](platine_in_gehaeuse.jpg)

Zu erkennen sind verschiedene Bedientaster, eine Siebensegmentanzeige, LEDs und der Hauptschalter.

# Lösungsmöglichkeiten

## Kompressor manuell schalten

Mit einem Schütz kann man beispielsweise die Netzspannung, die normalerweise von der Elektronik geschaltet wird, trennen und mit einem zweiten Schütz stumpf Netzspannung dauerhaft aufschalten solange man Leistungsüberschuss hat.

Diese Lösung hat aber eigentlich nur Nachteile... Leistungsschütze-/Schalter sind nicht gerade günstig und man setzt damit auch die Überwachung des Kompressors durch die Elektronik außer Kraft. Einen Controller zum Steuern braucht man auch noch.

## Elektronik einspannen

Der Kühlschrank hat ein Bedienpanel, das üblicherweise nicht zugänglich ist, weil die Tür geschlossen ist. An die Elektronik kommt man aber dann doch recht leicht ran, weil diese nicht von der Dichtung eingeschlossen ist, d.h. sie ist nicht im Kühlraum. Also keine Undichtigkeiten durch Kabel, die nach draußen geführt werden müssen (WLAN Empfang im Kühlschrank ist eher schlecht...).

Einen Controller zum Steuern (z.B. über WLAN) braucht man eh (s.o.), es liegt also nahe, diesem auch Bedienaufgaben zu übertragen. Also muss eine Lösung gefunden werden, wie der Controller die Knöpfe bedienen kann und die aktuellen Einstellungen lesen kann.

# Lösung durch Elektronik einspannen

