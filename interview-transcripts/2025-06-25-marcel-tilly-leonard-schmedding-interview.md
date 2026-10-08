# Marcel Tilly × Leonard Schmedding Interview

Prof. Dr. Marcel Tilly · Professor für Künstliche Intelligenz und Cloud Computing an der [Hochschule Rosenheim](https://www.th-rosenheim.de/) · [@everlastai](https://www.youtube.com/@everlastai) · 2025-06-25 · 43 Min · Deutsch · [YouTube](https://www.youtube.com/watch?v=b848PMMfgk8)

[Marcel Tilly](https://www.th-rosenheim.de/) ist Professor für [Künstliche Intelligenz](https://de.wikipedia.org/wiki/K%C3%BCnstliche_Intelligenz) und [Cloud Computing](https://en.wikipedia.org/wiki/Cloud_computing) an der Hochschule Rosenheim und blickt auf über zwölf Jahre [Microsoft](https://www.microsoft.com/) zurück, mit Fokus auf [Internet of Things](https://en.wikipedia.org/wiki/Internet_of_things), [Big Data](https://en.wikipedia.org/wiki/Big_data) und [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning). Im Gespräch geht es um die Geburtsstunde der KI rund um den [Dartmouth-Antrag von John McCarthy und Marvin Minsky](https://en.wikipedia.org/wiki/Dartmouth_workshop) im Jahr 1955, wie [neuronale Netze](https://en.wikipedia.org/wiki/Artificial_neural_network), [Convolutional Neural Networks](https://en.wikipedia.org/wiki/Convolutional_neural_network) und die [Transformer-Architektur](https://en.wikipedia.org/wiki/Transformer_(deep_learning_architecture)) hinter [ChatGPT](https://chat.openai.com/) wirklich funktionieren, warum [Halluzinationen](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)) systembedingt sind und wie [Mixture of Experts](https://en.wikipedia.org/wiki/Mixture_of_experts) und kleinere domänenspezifische Modelle den Energiehunger der grossen [Large Language Models](https://en.wikipedia.org/wiki/Large_language_model) drosseln sollen. Marcel Tilly ordnet ausserdem den Hype um [KI-Agenten](https://en.wikipedia.org/wiki/Intelligent_agent), die Debatte um [AGI](https://en.wikipedia.org/wiki/Artificial_general_intelligence) und [ASI](https://en.wikipedia.org/wiki/Superintelligence) im Sinne von [Ray Kurzweil](https://en.wikipedia.org/wiki/Ray_Kurzweil), den Vormarsch von [Voice AI](https://en.wikipedia.org/wiki/Speech_recognition) und kulturelle Unterschiede bei der KI-Adoption ein und schliesst mit einem Plädoyer für ein [Informatik](https://de.wikipedia.org/wiki/Informatik)- bzw. KI-Studium, etwa im Studiengang [Angewandte Künstliche Intelligenz](https://www.th-rosenheim.de/) in Rosenheim.

## Timestamps

- [00:00](https://www.youtube.com/watch?v=b848PMMfgk8&t=0s) – Intro
- [01:16](https://www.youtube.com/watch?v=b848PMMfgk8&t=76s) – Geburtsstunde der KI
- [04:50](https://www.youtube.com/watch?v=b848PMMfgk8&t=290s) – Was bringt Tiefenverständnis über KI?
- [08:02](https://www.youtube.com/watch?v=b848PMMfgk8&t=482s) – So funktioniert ChatGPT
- [15:50](https://www.youtube.com/watch?v=b848PMMfgk8&t=950s) – Das Trainingsdaten-Problem
- [20:10](https://www.youtube.com/watch?v=b848PMMfgk8&t=1210s) – Kosten und Effizienz
- [21:41](https://www.youtube.com/watch?v=b848PMMfgk8&t=1301s) – Der Aufstieg der KI-Agenten
- [27:30](https://www.youtube.com/watch?v=b848PMMfgk8&t=1650s) – Der Weg zur AGI und ASI
- [31:26](https://www.youtube.com/watch?v=b848PMMfgk8&t=1886s) – Wie wichtig wird Voice AI?
- [34:28](https://www.youtube.com/watch?v=b848PMMfgk8&t=2068s) – Kulturelle Unterschiede bei der KI-Adoption
- [37:54](https://www.youtube.com/watch?v=b848PMMfgk8&t=2274s) – Karriere und Weiterbildung

## Transcript

### 00:00 – Intro

**Leonard Schmedding**

Du nutzt [ChatGPT](https://chat.openai.com/) vielleicht täglich, aber weisst du eigentlich, wie diese KI wirklich funktioniert? Lass mich ehrlich zu dir sein: die meisten Menschen, die KI nur oberflächlich nutzen, werden ihr wahres Potenzial niemals verstehen und am Ende keinen einzigen Cent damit verdienen. Genau aus diesem Grund spreche ich heute mit Prof. Dr. Marcel Tilly. Er ist Professor für Künstliche Intelligenz und Cloud Computing mit über zwölf Jahren Erfahrung bei [Microsoft](https://www.microsoft.com/), unter anderem in den Bereichen [Internet of Things](https://en.wikipedia.org/wiki/Internet_of_things), [Big Data](https://en.wikipedia.org/wiki/Big_data) und [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning), und gehört zu den führenden Köpfen in Deutschland, wenn es um KI im Geschäftskontext geht. In diesem Gespräch klären wir, warum echte KI-Champions ein tieferes Verständnis brauchen, anstatt blind mit ChatGPT herumzuspielen, und worauf Gewinner jetzt setzen, wenn KI bald Millionen von Jobs verändert.

### 01:16 – Geburtsstunde der KI

**Leonard Schmedding**

Mit November 2022 ist [generative KI](https://de.wikipedia.org/wiki/Generative_k%C3%BCnstliche_Intelligenz) so richtig in den Mainstream gekommen, in den öffentlichen Diskurs und in die Arbeitswelt der meisten Menschen. KI wird mittlerweile fast synonym mit ChatGPT verwendet. Sie sind aber super tief im Thema. Was ist eigentlich die Geburtsstunde der KI, und wie lange gibt es dieses Feld wirklich?

**Prof. Dr. Marcel Tilly**

Eine sehr interessante Frage. Es gibt diesen einen Zeitpunkt, den man als Geburtsstunde definiert, aber wenn man historisch ganz an die Anfänge geht, muss man weit zurück. Die Motivation des Menschen war immer, etwas Mechanisches zu bauen, das menschenähnlich agieren kann. Historisch ist dem einen oder anderen vielleicht der [Schachtürke](https://de.wikipedia.org/wiki/Schacht%C3%BCrke) begegnet, dieser angebliche Schachroboter, mit dem ein Erfinder im 18. Jahrhundert durch die Adelshäuser zog und behauptete, er sei super smart. In Wirklichkeit sass ein Mensch im Schrank darunter und machte die smarten Züge. Aber man sah schon das Bedürfnis, menschenähnliche Maschinen zu bauen, die intelligent wirken.

Darüber hinaus gab es die Motivation der Informatik, Maschinen zu bauen, die rechnen können. Erste einfache Additions- und Subtraktionsmechanismen, [Leibniz](https://de.wikipedia.org/wiki/Gottfried_Wilhelm_Leibniz) hat zum Beispiel eine Rechenmaschine gebaut. Eigentlich gilt aber das Jahr 1955 als Geburtsstunde. Eine kleine Gruppe um [John McCarthy](https://en.wikipedia.org/wiki/John_McCarthy_(computer_scientist)) hat damals einen Antrag für ein Förderprojekt geschrieben, eine Art Summer Camp, in dem sie sich Probleme anschauen wollten, die zu der Zeit nur Menschen lösen konnten. In diesem Antrag wurde zum ersten Mal der Begriff [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence) erwähnt. Davor gab es natürlich schon Vorarbeiten, [Alan Turing](https://en.wikipedia.org/wiki/Alan_Turing) hat mit dem [Imitation Game Paper](https://en.wikipedia.org/wiki/Computing_Machinery_and_Intelligence) bereits viel Vorarbeit geleistet. Aber als Geburtsstunde gilt dieser Antrag von John McCarthy, [Marvin Minsky](https://en.wikipedia.org/wiki/Marvin_Minsky) und Kollegen.

**Leonard Schmedding**

1955, das wären rund 70 Jahre. Ein durchaus älteres Feld, nichts, was es erst seit zwei Jahren gibt.

### 04:50 – Was bringt Tiefenverständnis über KI?

**Leonard Schmedding**

Sie sind Professor für Künstliche Intelligenz, wir haben in unserem Unternehmen auch Mitarbeiter, die KI studiert haben. Warum ist das überhaupt wichtig? Wieso kann ich nicht einfach mit ChatGPT drauflosbauen, als Unternehmer oder als Interessierter? Was bringt es ganz konkret, sich tiefer mit der Materie auseinanderzusetzen?

**Prof. Dr. Marcel Tilly**

Klar kann man mit ChatGPT einfach losexperimentieren. Mein Beispiel aus einer Kinderuni war: erzähl mir das Märchen von Schneewittchen. Dann bekommt man zwei Bildschirmseiten Geschichte und kann sagen, mach es kürzer. Das ist Showcase. Als Unternehmer bietet es sich aber an, die Hintergründe zu verstehen. Eine KI ist ein Modell, das eine Aussage vorhersagt, "predicts" auf Englisch. Nicht wie eine Wettervorhersage, sondern auf Basis von Eingabedaten sagt sie eine Aussage oder eine Klassifizierung vorher. Eine KI bewegt sich nur in dem Datenraum, in dem sie trainiert wurde. Wenn ein Bildklassifizierer nur Katzen und Hunde kennt und du gibst ihm ein Bild, das weder Katze noch Hund zeigt, versucht er das trotzdem in diese Klassen einzuordnen.

Eine generative KI halluziniert auch sehr gerne. Sie weiss es vielleicht nicht besser und erfindet eine Antwort, weil es eine Antwort geben muss. Das sollte man verstehen, dem kann man entgegenwirken. Es gibt noch andere Themen, etwa der [Bias](https://en.wikipedia.org/wiki/Algorithmic_bias) im Trainingsdatensatz, eine Tendenz in eine bestimmte Richtung. Wenn der Datensatz einen Bias hat, hat das Ergebnis der KI ebenfalls eine Tendenz. Wenn man über den Tellerrand hinausblickt, kann man besser einschätzen, wie man mit Antworten von ChatGPT umgehen muss.

**Leonard Schmedding**

In erster Linie geht es also um Hintergrundverständnis, um Halluzinationen auf dem Radar zu haben. Vor allem im unternehmerischen Umfeld ist das hochrelevant, wenn es um geschäftskritische Abläufe geht. Vielleicht auch ein kurzer Abriss, wie das eigentlich technisch funktioniert. Für viele wirkt das ja magisch, ob ChatGPT oder ein Telefonagent. Wie funktioniert ein [künstliches neuronales Netzwerk](https://de.wikipedia.org/wiki/K%C3%BCnstliches_neuronales_Netz)?

### 08:02 – So funktioniert ChatGPT

**Prof. Dr. Marcel Tilly**

Ich fange mit dem Stichwort neuronales Netz an. Das ist tatsächlich erst einmal Mathematik, in eine Richtung sehr einfache Mathematik. Wir Informatiker adaptieren oft die Natur. Wenn wir uns vorstellen, wie das [Gehirn](https://en.wikipedia.org/wiki/Brain) funktioniert: es gibt [Neuronen](https://en.wikipedia.org/wiki/Neuron) und [Synapsen](https://en.wikipedia.org/wiki/Synapse), die Neuronen sind über Synapsen verschaltet. Wir machen davon eine Abstraktion. Ein Neuron ist eine Rechenvorschrift, da kommen Eingabeimpulse rein, werden verrechnet, und es entsteht ein Ausgabeimpuls, der an ein folgendes Neuron weitergeht. Unser Gehirn ist eine Verkettung von ganz vielen Neuronen, das bilden wir nach. Das ist ein neuronales Netz.

Eingangssignale kommen rein, sie sind unterschiedlich wichtig. Diese Signale werden gewichtet summiert, das ist nichts anderes als Gewichtung mal Eingangssignal plus Gewichtung mal nächstes Eingangssignal und so weiter. Wenn die Summe eine Schwelle übersteigt, schickt das Neuron ein Signal weiter. Daraus baue ich ein komplettes Netz mit Eingangs- und Ausgangsschicht. Klassisches Beispiel: Hund oder Katze. Ein Hundebild geht rein, das Ausgangs-Neuron sagt Hund. Diese Berechnung vorwärts ist relativ einfach: Multiplikation, Addition, eine [Aktivierungsfunktion](https://en.wikipedia.org/wiki/Activation_function), und am Ende leuchtet ein Neuron in der Ausgangsschicht auf. Das ist ein neuronales Netz. Trainiert werden die Gewichtungen der Verbindungen.

Auf dieser Grundlage gibt es viele Netztopologien. Für die Bildverarbeitung [Convolutional Neural Networks](https://en.wikipedia.org/wiki/Convolutional_neural_network), die mit Filtern und Faltungen, also Konvolutionen, Eigenschaften aus Bildern extrahieren, etwa Anzahl der Beine, Schnabel ja oder nein, kurzer oder langer Hals. Daraus folgt: zwei Beine plus Schnabel ergibt Vogel, vier Beine plus langer Hals ergibt Giraffe. Ich simplifiziere. Für Sequenzen wie Zeitreihendaten gibt es andere Netze, etwa [rekurrente Netze](https://en.wikipedia.org/wiki/Recurrent_neural_network).

Und jetzt haben wir die [Transformer-Netze](https://en.wikipedia.org/wiki/Transformer_(deep_learning_architecture)). Sie funktionieren in Kombination mit neuronalen Netzen, machen vorher aber eine andere Art Eigenschaftsextraktion, weil sie Eigenschaften von Texten erfassen sollen. Bei generativer KI wie ChatGPT, einem grossen Sprachmodell, will ich Eigenschaften eines Texts hernehmen, um vorherzusagen, was das nächste Wort ist. Die zentrale Eigenschaft dabei: wie wichtig ist ein Wort im Kontext eines Satzes im Bezug auf alle anderen Worte. Das nennt man [Attention](https://en.wikipedia.org/wiki/Attention_(machine_learning)). Im Deutschen kann ich am Ende des Satzes die gesamte Aussage noch verneinen, das ist für das Verständnis wichtig. Jedes Wort wird mit Zahlen im Kontext eines anderen Wortes bewertet, KI ist alles sehr zahlenbasiert.

Diese Eigenschaften gehen in das neuronale Netz, das vorhersagt: bei diesen vier Worten, was ist das fünfte Wort, das am meisten Sinn ergibt. Trainiert wurde das mit unfassbar vielen Texten aus dem Internet. Damit habe ich ein grosses Sprachmodell, gross wegen der Datenmenge und der Anzahl Parameter. Es kann das erste Folgewort auf Basis des Prompts vorhersagen, dann das zweite, dritte, vierte. Das ist ein Transformermodell, die Grundlage all dieser Sprachmodelle.

**Leonard Schmedding**

Sehr abstrakt, viele Begrifflichkeiten, aber das hilft, das Ganze zu entzaubern.

### 15:50 – Das Trainingsdaten-Problem

**Leonard Schmedding**

Sie haben das Thema Trainingsdaten angesprochen. Im Kontext von [GPT-4.5](https://openai.com/) und einem kommenden GPT-5 wird heiss diskutiert, dass irgendwann das gesamte Internet als Datenquelle aufgebraucht ist. [Elon Musk](https://en.wikipedia.org/wiki/Elon_Musk) hat [X](https://x.com/) erworben und damit Social-Media-Daten erschlossen. Wie sehen Sie diese Entwicklung? Es gibt Ansätze mit synthetischen Daten, wie geht es weiter?

**Prof. Dr. Marcel Tilly**

Eine spannende Frage. Erst einmal: wo wollen wir überhaupt hin? Reicht es uns als Endanwender, ein Sprachmodell zu haben, dem wir Fragen stellen und Antworten bekommen? Da haben wir schon eine sehr hohe Qualität. Müssen wir wirklich immer grössere, kompliziertere Sprachmodelle trainieren? Eine Tendenz, die ich sehe: man reduziert wieder, geht problemspezifischer vor, mit kleineren Modellen, die sehr spezifische Fragestellungen lösen, statt eines globalen Modells, das alles kann. Etwa für mathematische Probleme oder Programmieraufgaben.

Eine weitere wichtige Sache ist die Qualität und [Verifizierbarkeit](https://en.wikipedia.org/wiki/Formal_verification) der Ausgabe. Sprachmodelle erzeugen syntaktisch und grammatikalisch hochwertige, eloquent formulierte Antworten. Aber sie haben oft logische Fehler, weil in der Sprache die Logik als solche nicht so präsent ist beziehungsweise im Trainingsdatensatz nicht reflektiert wurde. Man könnte diese Modelle mit [Logik-Systemen](https://en.wikipedia.org/wiki/Symbolic_artificial_intelligence) anreichern, die die logische Korrektheit überprüfen. Da geht generative KI eine Heirat mit klassischer, regelbasierter "alter" KI ein, mit der man [reasoning](https://en.wikipedia.org/wiki/Automated_reasoning) machen kann. Das ist der spannende Trend, weniger das eine Modell, das alles regiert.

### 20:10 – Kosten und Effizienz

**Prof. Dr. Marcel Tilly**

Diese Fragen führen mich zu meinem persönlichen Forschungsinteresse: was kostet KI eigentlich, und wie kann man das Ganze günstiger gestalten? Wie kann das ökologisch noch Sinn machen? Diese Modelle laufen in grossen [Rechenzentren](https://en.wikipedia.org/wiki/Data_center), die Unmengen Energie brauchen. Das wird kaum diskutiert. Wie kann ich energiesparend arbeiten, kann ich Modelle auf kleinere Geräte auslagern, oder muss ich immer hochkapazitive Serversysteme mit [GPUs](https://en.wikipedia.org/wiki/Graphics_processing_unit) bauen, die wahnsinnig viel Energie ziehen? Das sind spannende Themen.

**Leonard Schmedding**

Ich habe gelesen, ein Trainingsdurchlauf für GPT-5 soll rund 500 Millionen Dollar kosten. Deshalb geht man jetzt zunehmend in Richtung [Mixture of Experts](https://en.wikipedia.org/wiki/Mixture_of_experts). Damit sind wir auch bei den KI-Agenten.

### 21:41 – Der Aufstieg der KI-Agenten

**Leonard Schmedding**

Wie sehen Sie die Entwicklung der KI-Agenten? Ein kurzer Abriss für die Zuschauer: was sind KI-Agenten überhaupt, und wie werden sie unser Leben prägen?

**Prof. Dr. Marcel Tilly**

KI-Agenten sind ein sehr spannender Ansatz, mit Sprachmodellen zu arbeiten. Viele haben sich schon damit auseinandergesetzt, wie man einen [Prompt](https://en.wikipedia.org/wiki/Prompt_engineering) schreibt, ihn beeinflusst, das Resultat in eine bestimmte Form bringt, etwa eine Tabelle oder gefilterte Informationen. Mit Agenten kann ich komplexe Themen kleiner machen. Anstatt einen Prompt zu formulieren, der mir eine eierlegende Wollmilchsau liefern soll, zerlege ich das Problem. Ein Agent liefert ein Teilergebnis, dieses wird Input für den nächsten. So bekommt man Multi-Agent-Systeme, die kombiniert werden, bis ein Gesamtergebnis entsteht.

Für Firmen ist das ein wahnsinnig gutes Element. Programmatisch betrachtet kann ein Agent aus einer Datenstruktur Code in Python erzeugen, ein anderer in [Java](https://en.wikipedia.org/wiki/Java_(programming_language)), ein dritter die zugehörige Webpage, ein vierter die Datenbankstruktur. Man könnte Agenten haben, die ein dreischichtiges Softwaresystem bauen: Web-, Business-, Datenbank-Layer. Web ist immer noch challenging genug. Auch [Requirements Engineering](https://en.wikipedia.org/wiki/Requirements_engineering) lässt sich abstrahieren: ein Agent nimmt Anforderungen auf, ein zweiter macht aus Anforderungen Features, daraus User Stories, daraus Tasks. Wenn jeder Agent diese eine Aufgabe gut beherrscht, kann ich ihn auch in anderen Projekten wiederverwenden. Das ist extrem flexibel.

**Leonard Schmedding**

Für Endverbraucher denke ich an Shopping-Use-Cases oder Sprach-KI mit Tool-Anbindung, die im Hintergrund Bestellungen ausführt. Im Unternehmenskontext ist es deutlich komplexer.

**Prof. Dr. Marcel Tilly**

Ich erinnere mich an meine Zeit bei Microsoft, vor der Hochschule, etwa 2015 und 2016. Wir hatten damals genau diese Use Cases im Kopf. Bestellung machen, ich brauche ein Taxi zum Flughafen, auf dem Weg möchte ich eine Flasche Wein für den Geburtstag meines Bruders kaufen, finde mir den besten Shop. Damals waren diese Szenarien sehr artificial, heute sind sie machbar. Aber ob das der ultracoole Use Case für den Endverbraucher ist, weiss ich nicht.

**Leonard Schmedding**

Sehe ich auch so, ich bin im Zweifel selbst schneller, als wenn ein Agent das ausführt. In Demos sieht es schön aus, es gibt aber sinnvollere Anwendungsfälle.

### 27:30 – Der Weg zur AGI und ASI

**Leonard Schmedding**

Das grosse Ziel von [OpenAI](https://openai.com/) und Stimmen wie [Ray Kurzweil](https://en.wikipedia.org/wiki/Ray_Kurzweil) ist [Artificial General Intelligence](https://en.wikipedia.org/wiki/Artificial_general_intelligence) und [Artificial Superintelligence](https://en.wikipedia.org/wiki/Superintelligence). Kurzweil sagt, 2045 erreichen wir ASI, bis 2027 sehen einige bereits AGI. Wie ist Ihr Blick darauf, vor allem auf die Zeitspanne?

**Prof. Dr. Marcel Tilly**

Das ist Crystal-Ball-Reading. Ich kann mich nur in die Nesseln setzen, wenn ich ein Datum nenne. Ich weiss auch nicht, ob ich eine AGI brauche. Wir fangen an zu philosophieren. Ich finde KI cool, wenn sie mir bei meinen täglichen Aufgaben hilft. Eine [Google-Suche](https://www.google.com/) war früher hilfreich, weil ich Informationen fand. Die Rechtschreibprüfung in [Word](https://www.microsoft.com/microsoft-365/word) hat mir geholfen, fehlerfreie Dokumente zu schreiben. Sprachmodelle nutze ich gerne als Ideengeber, wenn ich blockiert bin. Brauche ich eine allgemeine künstliche Intelligenz? Persönlich fühle ich mich ganz gut ohne.

Wie definieren wir AGI überhaupt? Es wäre eine starke Intelligenz, die mit wenig Trainingsdaten auskommt und mit wenigen neuen Inputs auf neue Situationen reagieren kann. Das macht uns Menschen aus, wir können uns sehr schnell adaptieren. Dazu kommt das Empathische, etwa wie [C-3PO](https://en.wikipedia.org/wiki/C-3PO) aus [Star Wars](https://en.wikipedia.org/wiki/Star_Wars), dieser goldene Computer mit Empathie, der Angst kennt und wegläuft. Das ist fast eine Art AGI. Ich tue mich schwer, eine Zahl zu benennen, ob wir das in zwei oder zwanzig Jahren haben.

**Leonard Schmedding**

Fair, es gibt auch keine ganz klare Definition. Aber die Bestrebungen sind gross, an der Abschaffung des klassischen Wissensarbeiters zu arbeiten, und dafür braucht man AGI.

### 31:26 – Wie wichtig wird Voice AI?

**Leonard Schmedding**

Eine These von meiner Seite: ich glaube, wir werden eine klare Entwicklung Richtung Sprach-KI sehen. 2015 hat man noch sofort gehört, dass es eine Maschine ist, das ändert sich gerade massiv. Manche merken nicht mehr, dass sie mit einer KI sprechen. Können Sie sich vorstellen, dass in wenigen Jahren niemand mehr tippt, sondern nur noch mit Geräten spricht?

**Prof. Dr. Marcel Tilly**

Zwei Aspekte. Nehmen wir [Alexa](https://en.wikipedia.org/wiki/Amazon_Alexa) als Beispiel, das Gerät, mit dem man zu Hause sprachlich kommuniziert. Das funktioniert lala. Interessant ist die Art und Weise, wie wir mit dem Ding kommunizieren. Wir sprechen im Kommandoton, weil wir das Gefühl haben, sonst klappt es nicht. Wenn man heute beobachtet, wie man mit ChatGPT kommuniziert, ist das viel freundlicher. Ich erwische mich häufig dabei, viel höflicher zu formulieren als mit einer Person auf Augenhöhe.

Beim Reden mit Geräten kommt eine kulturelle Komponente dazu. Die Beobachtung damals war, dass Menschen in China offener sind, mit dem Handy zu sprechen, als Menschen in Deutschland. Vielleicht weil Chinesisch schwer zu schreiben ist, oder wegen anderer Privatsphäre-Empfindungen. Diese Privatsphäre bleibt uns erhalten, aber definitiv geht der Trend dahin, mehr mit Geräten zu reden. Auch das Programmieren wird sich dramatisch ändern. 150 Zeilen Python von Hand wird der Vergangenheit angehören. Stattdessen formuliert man eine Problembeschreibung, und ein Modell übersetzt sie in Ausführbares. Ob noch Python dazwischen liegt, sei dahingestellt.

Meine Vision ist, mit Gesten an solchen Dingen zu arbeiten, in einem Interaktionsraum zu sein, statt Maus zu schubsen, Text zu markieren, zu kopieren. Wie bei [Iron Man](https://en.wikipedia.org/wiki/Iron_Man) mit seinem [J.A.R.V.I.S.](https://en.wikipedia.org/wiki/J.A.R.V.I.S.) als Personal Assistant. Das ist gar nicht so weit weg, die Sprache verstehen unsere Modelle, die Interaktion ist heute schon möglich.

### 34:28 – Kulturelle Unterschiede bei der KI-Adoption

**Leonard Schmedding**

Genau, und Menschen vermenschlichen Maschinen zunehmend. Es gibt das Konzept des [Anthropomorphisierens](https://en.wikipedia.org/wiki/Anthropomorphism), Menschen sprechen mit KI-Agenten wie mit Haustieren. Ich gehe stark davon aus, dass wir einen riesigen Trend Richtung Sprach-KI sehen, und dass wir noch am Anfang stehen. In ein, zwei Jahren wird es nicht mehr unterscheidbar sein, ob ein Mensch oder eine Maschine spricht.

**Prof. Dr. Marcel Tilly**

Ich hatte zur Zeit bei Microsoft auch beobachtet, wie sehr kulturelle Unterschiede die Akzeptanz prägen. Menschen in China sprechen offener mit ihren Geräten, in Deutschland sind wir zurückhaltender, sensibler in Sachen Privatsphäre. Das wirkt sich direkt auf die Adoption aus.

### 37:54 – Karriere und Weiterbildung

**Leonard Schmedding**

Abschliessend: viele Zuschauer fragen sich, wie sie sich weiterbilden können. Tiefer in KI eintauchen, vielleicht karrieretechnisch Fuss fassen. Welche Studiengänge, sollte man überhaupt studieren, sich einen Job suchen oder programmieren lernen? Was würden Sie raten?

**Prof. Dr. Marcel Tilly**

Eine sehr subjektive Antwort. Grundsätzlich finde ich schon, dass man das studieren sollte. Irgendjemand muss diese Systeme im Überblick haben und wissen, was passiert. Wir können nicht eine ganze Generation nur Prompts schreiben lassen. Am Ende müssen die Bits und Bytes immer noch von Datacentern auf den Computer kommen. Das muss man verstehen, im Zweifel erweitern, verbessern, oder einfach reparieren können, wenn etwas kaputt ist.

Es macht Sinn, Informatik zu studieren. Eine Möglichkeit wäre, zu uns nach [Rosenheim](https://en.wikipedia.org/wiki/Rosenheim) zu kommen und [Angewandte Künstliche Intelligenz](https://www.th-rosenheim.de/) zu studieren. Dort lernt man nicht nur generative KI, sondern auch [deklarative](https://en.wikipedia.org/wiki/Declarative_programming) und [diskriminative KI](https://en.wikipedia.org/wiki/Discriminative_model), wie man die Systeme baut, die das einsetzen. Das ist auch jenseits generativer KI relevant, etwa für Produktionsüberwachung, [Qualitätssicherung](https://en.wikipedia.org/wiki/Quality_control), [Bilderkennung](https://en.wikipedia.org/wiki/Computer_vision), oder die Frage: wer baut das System für den Rechtsanwalt, der Verträge formulieren will, möglicherweise lokal gehostet, weil die Daten nicht auf einem Server in Amerika landen sollen? Das muss jemand aufsetzen.

Es gibt unzählige offene Fragen: wie machen wir KI kostengünstiger, ressourcenschonender, verfügbar, auch wenn wir nicht connected sind, mit kleineren, trotzdem guten Modellen. Wer mathematisch affin ist und Interesse hat, sollte das studieren. Und warum nicht in Rosenheim? Hier im Süden Deutschlands lässt es sich gut studieren, da, wo andere gerne Urlaub machen.

**Leonard Schmedding**

Wir sehen eine stark steigende Nachfrage. Bei unseren Kunden werden laufend Entwickler eingestellt, wir haben selbst offene Stellen in dem Bereich. Man bringt aus so einem Studiengang viele Fähigkeiten des logischen Denkens und Problemlösens mit, die sich auch auf der Anwenderseite bezahlt machen. Für alle anderen ist dieser Kanal hier perfekt, um sich in Eigeninitiative weiterzubilden. Prof. Tilly, vielen Dank, dass Sie heute mit dabei waren.

**Prof. Dr. Marcel Tilly**

Sehr gerne, vielen, vielen Dank.

---

Quelle: https://www.youtube.com/watch?v=b848PMMfgk8
