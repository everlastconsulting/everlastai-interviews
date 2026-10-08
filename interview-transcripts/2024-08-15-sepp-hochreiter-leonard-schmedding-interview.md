# Dr. Sepp Hochreiter × Leonard Schmedding Interview

Prof. Dr. Sepp Hochreiter · Direktor des [Instituts für Machine Learning](https://www.jku.at/institut-fuer-machine-learning/) an der [Johannes Kepler Universität Linz](https://www.jku.at/) · [@everlastai](https://www.youtube.com/@everlastai) · 2024-08-15 · 30 Min · Deutsch · [YouTube](https://www.youtube.com/watch?v=QJYmKbZJt8k)

[Sepp Hochreiter](https://de.wikipedia.org/wiki/Sepp_Hochreiter) ist Professor für Bioinformatik an der [Johannes Kepler Universität Linz](https://www.jku.at/) und Direktor des Instituts für Machine Learning. Mit seiner Diplomarbeit an der [TU München](https://www.tum.de/) bei [Jürgen Schmidhuber](https://en.wikipedia.org/wiki/J%C3%BCrgen_Schmidhuber) hat er das [Long Short-Term Memory](https://en.wikipedia.org/wiki/Long_short-term_memory) (LSTM) erfunden, eine rekurrente Architektur, die fast zwei Jahrzehnte lang den Standard in [Spracherkennung](https://en.wikipedia.org/wiki/Speech_recognition), [maschineller Übersetzung](https://en.wikipedia.org/wiki/Machine_translation) und Sequenzmodellierung gesetzt hat und in jedem Smartphone, in [Alexa](https://en.wikipedia.org/wiki/Amazon_Alexa) und unzähligen weiteren Anwendungen verbaut war, bevor sie 2017 durch die [Transformer](https://en.wikipedia.org/wiki/Transformer_(deep_learning_architecture))-Architektur abgelöst wurde, die heute Modelle wie [ChatGPT](https://chat.openai.com/) antreibt. Im Gespräch geht es um die ehrliche Definition von [künstlicher Intelligenz](https://de.wikipedia.org/wiki/K%C3%BCnstliche_Intelligenz) (zurück bis zu Barr und Feigenbaum 1981), das von Hochreiter gelöste [Vanishing-Gradient-Problem](https://en.wikipedia.org/wiki/Vanishing_gradient_problem), warum [Large Language Models](https://en.wikipedia.org/wiki/Large_language_model) eher eine moderne Datenbank sind als ein intelligentes System (sechsbeinige Ameisen mit vier Beinen, fehlendes Weltwissen beim autonomen Fahren), die [McKinsey-Prognose](https://www.mckinsey.com/) zu 400 Millionen verschwindenden Jobs, das deutsche Innovations- und Umsetzungsdefizit gegenüber [USA](https://en.wikipedia.org/wiki/United_States) und [Asien](https://en.wikipedia.org/wiki/Asia) (am Beispiel der [SELU](https://en.wikipedia.org/wiki/Activation_function)-Aktivierungsfunktion, die [Amazon](https://www.amazon.com/) binnen drei Monaten eine Milliarde Dollar Umsatz brachte) sowie eine ruhige Antwort auf die [Terminator](https://en.wikipedia.org/wiki/Terminator_(franchise))- und [Matrix](https://en.wikipedia.org/wiki/The_Matrix)-Szenarien einer feindlichen Superintelligenz.

## Timestamps

- [00:00](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=0s) – Intro
- [00:34](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=34s) – Was bedeutet "Künstliche Intelligenz"?
- [02:07](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=127s) – Hintergrund von Sepp Hochreiter
- [03:13](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=193s) – Was sind LSTM-Netzwerke?
- [06:18](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=378s) – Anwendungsfälle von KI im Alltag
- [08:36](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=516s) – Welche Berufsfelder sind von KI betroffen?
- [10:36](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=636s) – Wie profitiert man am meisten von der KI?
- [13:33](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=813s) – Welche Fähigkeiten benötigt der Mensch am Ende?
- [15:22](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=922s) – Was sind die größten Missverständnisse über KI?
- [20:04](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=1204s) – Deutscher Wirtschaftsmarkt in Bezug auf KI
- [23:01](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=1381s) – Langfristige Prognosen
- [27:32](https://www.youtube.com/watch?v=QJYmKbZJt8k&t=1652s) – Conclusio

## Transcript

### 00:00 – Intro

**Leonard Schmedding**

Wir haben heute einen spannenden Gast, Dr. Sepp Hochreiter. Herr Hochreiter, Sie sind Experte auf dem Gebiet der künstlichen Intelligenz, Professor für Bioinformatik an der Johannes Kepler Universität in Linz und Direktor des Instituts für Machine Learning. Sie sind insbesondere bekannt für Ihre bahnbrechende Erfindung in der KI-Forschung, die sogenannten LSTM-Netzwerke, und gelten somit, würde ich sagen, als einer der Urväter, Gründer und Erfinder der modernen künstlichen Intelligenz. Schön, dass Sie heute auf dem Kanal mit dabei sind.

### 00:34 – Was bedeutet "Künstliche Intelligenz"?

**Leonard Schmedding**

Es kursieren ja momentan diverse Definitionen von künstlicher Intelligenz. Viele können das Ganze gar nicht so richtig einordnen. Wie würden Sie als Fachexperte den Begriff definieren?

**Dr. Sepp Hochreiter**

Erstmal auch von meiner Seite hallo allerseits. Ich glaube, viele Experten wissen gar nicht so genau, was das ist. Eine Definition, die von [Barr und Feigenbaum](https://en.wikipedia.org/wiki/Edward_Feigenbaum) aus dem Jahr 1981 stammt, ein bisschen adaptiert: Künstliche Intelligenz, das sind Maschinen, die kognitive Fähigkeiten an den Tag legen, wie wir sie von Menschen kennen. Dazu gehört Lernen, Planen, logisches Schließen, die Umwelt verändern, Probleme lösen, und neu hinzugekommen ist auch, sich neue Fähigkeiten anzueignen. Die Definition orientiert sich also stark daran, was wir Menschen können. Das ist die beste Definition, die uns zurzeit zur Verfügung steht, sie ist aber sehr schwach, weil sie total an den Menschen angelehnt ist. Ich kann mir auch vorstellen, dass es intelligente Maschinen oder Lebewesen gibt, die nicht auf menschlichen Fähigkeiten basieren.

### 02:07 – Hintergrund von Sepp Hochreiter

**Leonard Schmedding**

Sie beschäftigen sich ja schon sehr lange mit dem Thema. Wie sind Sie damals in dieses Themenfeld geraten, wo es noch gar nicht so bekannt war?

**Dr. Sepp Hochreiter**

Teilweise hat das Feld auch anders geheißen. Ganz am Anfang der Terminologie waren es [neuronale Netze](https://de.wikipedia.org/wiki/K%C3%BCnstliches_neuronales_Netz), dann [maschinelles Lernen](https://de.wikipedia.org/wiki/Maschinelles_Lernen), und noch viel später hat es künstliche Intelligenz geheißen, obwohl es den Begriff schon vorher gab. Eingeführt wurde er auf der [Dartmouth-Konferenz](https://en.wikipedia.org/wiki/Dartmouth_workshop) 1956. Ich habe Informatik an der TU München studiert. Im Studium gab es immer nur die alten Sachen, schon 20, 30, 50 Jahre alt, nichts Neues, man hat einfach alte Sachen nachgemacht. Dann gab es ein Praktikum zu neuronalen Netzen, und da haben wir noch nicht genau gewusst, wie sie funktionieren, warum sie funktionieren, was überhaupt funktioniert. Das fand ich super spannend. Erst habe ich ein Praktikum gemacht, später meine Diplomarbeit. Mein Betreuer war Jürgen Schmidhuber. Das hat mich fasziniert, weil es ganz anders war als der Rest der Informatik. Es gab kein Lehrbuchwissen, es gab immer wieder etwas Neues zu entdecken.

### 03:13 – Was sind LSTM-Netzwerke?

**Leonard Schmedding**

Können Sie uns mehr über Ihre Erfindung erzählen? Soweit ich weiß, basieren ja so gut wie alle heute bekannten KI-Modelle, von [OpenAI](https://openai.com/) und anderen, ursprünglich auf dieser Architektur. Was sind LSTM-Netzwerke und wieso sind sie so wichtig?

**Dr. Sepp Hochreiter**

LSTM steht für **Long Short-Term Memory**. Es gab eine spezielle Art von neuronalen Netzen, die [rekurrenten neuronalen Netze](https://en.wikipedia.org/wiki/Recurrent_neural_network), Netze, die ihre Neuronen selbst aktivieren konnten und durch diesen Feedback-Loop fähig waren, sich etwas zu merken, ein Gedächtnis zu haben. Wenn ich einen Satz lese, kann ich mir Sachen merken. Damals gab es aber ein sehr großes Problem: Diese Netze konnten sich nur die letzten Wörter merken. Bei einem Satz wie "Ein Mann geht in einem roten Pullover über die Straße" hat das Ding vielleicht gemerkt, dass irgendwas über die Straße geht, aber den Mann am Anfang nicht mehr. Schreibe ich den Satz umgekehrt, "Über die Straße in einem roten Pullover geht ein Mann", erkennt es zwar, dass ein Mann die Straße überquert, aber nicht mehr, was überquert wurde. Alle Wörter sind potenziell wichtig, egal ob sie am Anfang oder am Ende stehen. Das ging mit den rekurrenten Netzen nicht.

Long Short-Term Memory heißt: Es gibt ein Short-Term Memory, in dem ich in den Aktivierungen der Neuronen Information speichere, und das Long heißt, ich habe eine Architektur erfunden, die diese Speicherung über längere Zeiträume, über mehrere Sätze hinweg, möglich macht. Das war die erste Erfindung. Davor ging das nicht, der Grund war der **Vanishing Gradient**: Das Lernen hat nicht funktioniert, weil Information über die Zeit verloren ging. Dasselbe Problem hat damals auch verhindert, dass tiefe Netze, [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning), funktioniert haben, egal ob ich in der Zeit nach hinten gehe oder über die verschiedenen Layer durch ein großes Netzwerk. Das heißt, auch die großen neuronalen Netze, die wir jetzt haben, hätten aus dem gleichen Grund nicht funktioniert. Ich habe dieses Problem in meiner Diplomarbeit für rekurrente Netze gelöst, viel später wurde es allgemein gelöst, sodass wir die großen Netze haben, die wir heute kennen. Das waren die zwei grundlegenden Erfindungen: die LSTM-Architektur zum Speichern und die Lösung des Vanishing-Gradient-Problems.

### 06:18 – Anwendungsfälle von KI im Alltag

**Leonard Schmedding**

KI ist ja erst seit Kurzem in der Masse angekommen, die meisten verbinden es mit ChatGPT. Welche Anwendungsfälle gibt es noch, wo solche Technologien im Alltag stecken, ohne dass man es vermuten würde?

**Dr. Sepp Hochreiter**

Bis 2017 war LSTM auf jedem Handy, in Alexa, überall drin. Diese Architektur wurde milliardenfach kopiert und später durch die Transformer-Technik abgelöst. **GPT** steht für **Generative Pre-trained Transformer**. Das LSTM hat aber bis dahin im Handy Wörter vervollständigt, Vorschläge gemacht, bei der Bildersuche im Kontext geholfen. Wenn man im Internet etwas bestellt, ein Buch, einen Film, gibt es Vorschläge, [Recommender-Systeme](https://en.wikipedia.org/wiki/Recommender_system), da steckt sehr viel KI drin. Auch bei jeder Art von Vorhersage, etwa wenn die Autoindustrie prognostiziert, wie viele Glühbirnen sie demnächst herstellen muss. [Logistik](https://en.wikipedia.org/wiki/Logistics) wird mit KI optimiert, Prozesse werden optimiert. Bei [Zalando](https://www.zalando.de/) ist das Warenlager mit KI optimiert, in vielen Kaufhäusern werden Produkte so platziert, dass die Leute bestimmte Warenkombinationen einkaufen. Die KI war an vielen Stellen schon drin, in einer einfacheren Form. Jetzt kommen immer größere, komplexere Modelle.

### 08:36 – Welche Berufsfelder sind von KI betroffen?

**Leonard Schmedding**

Laut einer [McKinsey-Studie](https://www.mckinsey.com/) könnten 400 Millionen Jobs weltweit durch KI ersetzt werden, insbesondere auch Mittel- und Oberschichtsjobs. Wie sehen Sie das?

**Dr. Sepp Hochreiter**

Vor allem Sachen, wo man sehr repetitive Arbeit macht. Das muss nicht körperlich sein, es kann sein, dass ich immer wieder das gleiche Formular überprüfe oder etwas in einem Nachschlagwerk raussuche. Es gibt aber auch mehrere Studien zu Firmen, die KI-Methoden einsetzen: Die haben mehr Jobs, die haben mehr angestellt. Früher gab es viele Bauernhöfe mit zehn Mägden und zehn Knechten. Dann kamen die Maschinen. Jetzt müsste die Welt von arbeitslosen Mägden und Knechten wimmeln, aber die Leute haben etwas anderes gemacht. So wird es auch mit KI sein. Manche Sachen werden ersetzt, aber KI braucht neue Jobs: Leute, die Daten kuratieren, Daten sammeln, schauen, wo man sie einsetzen kann. Statt einem Lehrjungen das Drehen an der Maschine beizubringen, bringt man es der KI bei: "Du drehst zu schnell, das Öl wird zu heiß, der Span ist zu lang." Es wird neue Arten geben, wie man rangeht, [Prompt Engineering](https://en.wikipedia.org/wiki/Prompt_engineering) und vieles mehr. Es werden Jobs wegfallen, aber es werden viele hinzukommen. Es ist das Gesetz der Zeit, dass sich Jobs ändern.

### 10:36 – Wie profitiert man am meisten von der KI?

**Leonard Schmedding**

Unser Publikum interessiert sich dafür, wie man mit KI Geld verdienen, davon profitieren und sich weiterbilden kann. Welche Berufsfelder oder Sparten finden Sie gerade besonders spannend und lukrativ?

**Dr. Sepp Hochreiter**

Ein paar von meinen Studenten waren bei [Amazon](https://www.amazon.com/) und haben mir gezeigt, wie sie heute Software-Engineering machen. Das hat sich total geändert. Sie haben den Code-[Copiloten](https://github.com/features/copilot), lassen sich von der KI das Programm vorgeben und drücken es nur noch zurecht. Programmieren hat eine komplett andere Dimension angenommen. Vieles, was ich programmiere, gibt es schon irgendwo auf der Welt. Wenn die KI das weiß und mir vorschlägt, muss ich es nur leicht anpassen. Statt im Internet zu googeln, frage ich später vielleicht mein [Language Model](https://en.wikipedia.org/wiki/Language_model): "Wieviele Tote hat es bei [Waterloo](https://en.wikipedia.org/wiki/Battle_of_Waterloo) gegeben?" Aktuell gibt es noch das Problem des [Halluzinierens](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)), das wird aber besser. Diese KI-Sachen werden Tools sein, die jeder tagtäglich verwendet, ganz normal, weil sie Sachen erleichtern. Bei einer Steuererklärung schaut die KI durch und sagt: "Hier ist etwas Auffälliges, schau drüber." Ich kann mich auf das konzentrieren, was mir Spaß macht, und nicht auf die langweiligen Rechengeschichten im Hintergrund.

### 13:33 – Welche Fähigkeiten benötigt der Mensch am Ende?

**Leonard Schmedding**

Wenn repetitive Aufgaben wegfallen: Was sind die wichtigsten Fähigkeiten, die der Mensch in Zukunft braucht? Geht es mehr um Entscheidungen, um Kreativität, um Prompt Engineering? Wo ist auch das Bildungssystem gefragt?

**Dr. Sepp Hochreiter**

Es wird verschiedene Stufen geben. Es wird Leute geben, die die Technik verstehen, sie adaptieren, weiterentwickeln, richtig einsetzen, und es wird die viel breitere Masse geben, die ein bisschen über die Technik verstehen muss, genauso wie ich heute mit Handy oder Computer umgehe, ohne genau zu wissen, was drin ist. Bei der KI ist man noch nicht mal so weit, dass man weiß, wo man sie einsetzt, wo sie super effizient ist, wo es länger dauert, ihr etwas beizubringen oder Fehler zurückzukorrigieren. Man muss sich damit auseinandersetzen, was KI kann und nicht kann. Wenn ich zu wenig Daten habe, kann KI das Problem nicht lernen, dann setze ich sie prinzipiell nicht ein. Es braucht einen Crashkurs: Was kann KI, was nicht, in welche Richtung geht das, damit ich weiß, ob ich sie einsetzen kann oder ob es mich am Ende mehr Zeit kostet.

### 15:22 – Was sind die größten Missverständnisse über KI?

**Leonard Schmedding**

Für viele ist KI eine Blackbox, es werden Horrorszenarien aufgemalt. Was sind die größten Missverständnisse?

**Dr. Sepp Hochreiter**

Eine Sache, die jeder kennt, sind Large Language Models wie ChatGPT. Das ist nicht intelligent, das hat nichts mit Intelligenz zu tun. Das ist wie eine Datenbank, ziemlich trivial. Es wird sehr viel Text reingefüttert und dann ähnlicher Text wieder zusammengeführt, ein Wissensfaktum daraus gemacht. Die Ausgabe hört sich an wie menschlicher Text, weil der Text ja schon irgendwo geschrieben oder gesprochen wurde. Außerdem kann das System generalisieren: Wenn ich eine Geschichte mit Namen habe, kann ich diese Namen austauschen, weil das System weiß, Namen sind Variablen. Geburtstage kann ich austauschen. Das schaut so aus, als wisse das System extrem viel, dabei kann es keine Logik. Wenn ich eine logische Aufgabe habe und sie in eine andere Domäne übertrage, dann kann es das nicht, obwohl es die gleiche Logik ist, die gleichen logischen Schritte. Es hat die Logik nicht kapiert. Für mich ist das nicht so intelligent, das ist eine moderne Datenbank, gut zum Speichern bisherigen menschlichen Wissens. Das System wird gezwungen, immer etwas auszugeben, auch wenn es nichts weiß, und fängt dann an zu fantasieren, zu halluzinieren. Das muss man in den Griff kriegen.

Genauso bei Bildern und Videos. Das ist beeindruckend, aber es hat die Welt nicht verstanden. [OpenAI](https://openai.com/) hat vor kurzem [Sora](https://openai.com/sora) veröffentlicht. Es gibt da ein schönes Video, in dem eine Ameise durch einen Ameisenbau geht. Schaut total beeindruckend aus, dann sieht man genauer hin: Die Ameise hat **vier Beine**. Eine Ameise hat sechs Beine, das ist Weltwissen, wir wissen, wie die Biologie funktioniert. Das System hat einfach generalisiert: zwei Beine, vier Beine, sechs Beine, acht Beine, irgendwann hat es sich für vier entschieden, ohne Wissen reinzutun.

Anderes Beispiel, [autonomes Fahren](https://en.wikipedia.org/wiki/Self-driving_car): Vor mir ist eine Klippe und links davon ein Maisfeld. Ich habe nur die Möglichkeit, die Klippe runterzufahren oder ins Maisfeld zu fahren. Wir wissen, das Maisfeld ist besser, ich möchte nicht hunderte Meter runterfallen. Wir haben das nie erlebt, aber wir können uns vorstellen, dass es nicht gut ist, weil wir die Welt verstanden haben. Wir wissen, was physikalisch passiert. Eine KI bräuchte Weltwissen, kein Erfahrungswissen, weil dieses Szenario in keiner Fahrschule oft vorkommt. Wenn ein Kind sich am Straßenrand von der Mutter losreißt, weiß ich sofort, dass das gefährlich ist, weil ich weiß, Kinder können das nicht einschätzen. Das ist Weltwissen. Heutige KIs haben die Welt nicht verstanden, da sind wir noch weit weg.

### 20:04 – Deutscher Wirtschaftsmarkt in Bezug auf KI

**Leonard Schmedding**

Sie haben bahnbrechende Erfindungen gemacht, auch Jürgen Schmidhuber haben Sie angesprochen. Tatsächlich wurden in Deutschland und der Schweiz sehr viele Grundlagentechnologien erfunden, aber heute denkt der Verbraucher direkt an OpenAI, [Google](https://www.google.com/), [Meta](https://about.meta.com/). Wie erklären Sie sich das? Verpassen wir gerade den Anschluss?

**Dr. Sepp Hochreiter**

Erstens haben die amerikanischen Firmen einen sehr starken Einfluss, das Internet, soziale Medien, das ist stark amerikanisch dominiert. Wenn wir hier in Europa eine tolle Erfindung haben, denken wir: "Cool, vielleicht kann ich Professor werden, ich publiziere und werde Professor in Amerika." Die gleiche Person in den USA sagt: "Cool, ich gründe eine Firma und kann Geld machen." Die Amerikaner setzen viel mehr um, daraus werden Produkte, die Millionen Leute nutzen, dadurch wird es bekannt. Auch die Kultur ist anders: Hier muss ich mich im Studium entscheiden, ob ich in die Industrie gehe und nicht mehr an die Uni zurückkann, oder umgekehrt. In Amerika ist das nicht so.

Wir hatten mal die **[SELU](https://en.wikipedia.org/wiki/Activation_function)-Aktivierungsfunktion**. Drei Monate später haben uns die Leute von Amazon gratuliert, die hatten **eine Milliarde US-Dollar Umsatzsteigerung** dadurch. Drei Monate. Hier in Europa kämpfen wir mit deutschen Firmen, dass sie sich überhaupt etwas anschauen, es dauert sehr lange. Jeder hat Angst in der Firma, die jungen Leute, die das viel besser können als er, könnten ihm seine Position streitig machen. Am schnellsten adaptieren die [Asiaten](https://en.wikipedia.org/wiki/East_Asia) neue Technik. Wir in Europa sind viel träger und vorsichtiger. Das können wir uns aber nicht leisten. Diese Technologie ist sehr viel schneller als frühere. Innerhalb von drei Monaten ist von einem Paper zur Idee zum eingesetzten Produkt der Umsatzgewinn da. Bei manchen Sachen sind wir in Europa nicht schnell genug, und wir haben die Kultur nicht, Sachen sehr schnell in Produkte umzusetzen. Sobald wir etwas haben, nehmen es die Amerikaner und Chinesen schneller her als wir selber.

### 23:01 – Langfristige Prognosen

**Leonard Schmedding**

Jürgen Schmidhuber hat ja interessante Ideen, wo die Reise hingeht. Er stellt sich vor, dass intelligente Roboter eine eigene Zivilisation bilden könnten und die Menschen wie Ameisen betrachten. Wie sehen Sie das? Schließen Sie sich Szenarien wie [Superintelligenz](https://en.wikipedia.org/wiki/Superintelligence) oder [Terminator](https://en.wikipedia.org/wiki/Terminator_(franchise)) an?

**Dr. Sepp Hochreiter**

Jürgen nennt das **Transzendenz**, eine Evolutionsstufe. Wir Menschen sind eine Stufe, danach kommen die Maschinen, vielleicht sterben die Menschen aus, können aber froh sein, dass sie bei der Evolution mitgeholfen haben. Es ist ein bisschen frustrierend, dass wir Menschen nicht mehr die Krönung sind, eine Kränkung der Menschheit. Daran glaube ich nicht. Maschinen kommen nicht aus der Evolution, Maschinen haben **keinen Selbsterhaltungstrieb**. In der Evolution überlebt nur, was um Ressourcen, um Nahrung kämpft. Bei einer Kaffeemaschine, die nicht funktioniert, schalte ich sie aus oder schmeiße sie weg, ich habe keine Angst, dass sie die Welt übernimmt. So sehe ich es auch bei der KI: Wenn etwas nicht funktioniert, kopiert es der Mensch nicht weiter. Was schon ist: dass der Mensch sie schlecht einsetzt, etwa für Waffen, oder um Unheil anzurichten. Das ist bei jeder Technologie so, Fahrzeuge oder Flugzeuge wurden auch militärisch eingesetzt. Aber dass die Technologie für sich selbst etwas tut, sehe ich nicht.

Wir haben immer ein **Objective**, eine mathematische Vorgabe. Das System soll Hunde von Katzen unterscheiden oder erkennen, welches Objekt da ist. Es soll nichts anderes machen. Eine Kaffeemaschine soll kein Gedicht schreiben, das Mahlwerk mahlt Kaffee. Wir bestimmen, was die Objectives sind, wohin diese Maschinen optimiert werden. Man kann sich vorstellen, dass böse Leute eine Umgebung bauen, in der Maschinen gegeneinander kämpfen, aber das wären eher Software-Pakete, das ist für mich viel zu weit weg. In einer realen Welt, mit den gleichen Ressourcen wie wir, sehe ich keine Chance.

Bei Terminator und [Matrix](https://en.wikipedia.org/wiki/The_Matrix), Menschen als Batterien, Maschinen, die Menschen jagen: Warum soll eine super intelligente Maschine in dieser dünnen Biosphäre bleiben, wo sie rostet, wo Wasser ist, das ihr schadet? Im [Asteroidengürtel](https://en.wikipedia.org/wiki/Asteroid_belt) gibt es viel mehr Rohmaterialien und viel mehr Energie als das bisschen Sonnenlicht auf der Erde. Wir leben hier, weil wir Nahrung und Wasser brauchen. Warum sollen Maschinen dort leben, wo es ihnen schadet? Die würden sofort die Erde verlassen und sich nicht mit Menschen um Ressourcen streiten, die sie gar nicht brauchen. Das Wichtigste: Es überlebt nur die Maschine, die wir weiterkopieren. Wir sagen: "Das war eine gute KI, davon mache ich eine Kopie." Eine fehlerhafte KI kopiert man nicht weiter. Wir sitzen an der Quelle. Deswegen sehe ich keine Chance, dass KIs entstehen, die uns gefährlich werden.

### 27:32 – Conclusio

**Leonard Schmedding**

Was ist abschließend Ihr Appell an die Menschen da draußen, an Arbeitnehmer und Unternehmer? Wie muss man sich positionieren, auch mental, um von diesen Entwicklungen die nächsten Jahre zu profitieren?

**Dr. Sepp Hochreiter**

Die KI wird kommen, sie ist da, sie wird mehr eingesetzt werden, sie wird die Produktivität steigern. Genauso wie der [Computer](https://en.wikipedia.org/wiki/Computer) oder die [Elektrizität](https://en.wikipedia.org/wiki/Electricity), das sind Sachen, die da sind, und es wäre dumm, das zu ignorieren. Man muss sich mit der Thematik beschäftigen, sowohl als Unternehmer als auch als Arbeitnehmer. Wo könnte sie bei mir Einfluss haben, wo kann ich sie nutzen, wo könnte sie mir schaden oder meine Arbeit beeinflussen? Als Unternehmer: Habe ich Daten, oder muss ich Sensoren installieren, damit Daten generiert werden, die ich verwenden kann, um meine Prozesse und Produkte zu optimieren? Kann ich ChatGPT hernehmen, um Akten zu durchsuchen, einen Rohentwurf für Briefe oder Programme zu machen? Wo kann es mir auch schaden, könnten mich welche betrügen? Beschwerdebriefe, die von ChatGPT geschrieben sind, Aufsätze beim Lehrer, die KI-generiert sind. Wo kann es gefährlich sein, bei [Wahlen](https://en.wikipedia.org/wiki/Election), bei sozialen Medien, wo können Stimmungen beeinflusst, Menschen manipuliert werden? Das ist mein Appell: **Beschäftigt euch mit der Sache.** Schaut, wo die Grenzen sind, wo die Möglichkeiten, sucht aktiv nach Möglichkeiten. Dann kann man besser einordnen und entscheiden, wo man sie braucht und wo nicht.

**Leonard Schmedding**

Sehr gute Worte, vielen Dank. Ich sehe KI auch als Allzweck-Technologie, ähnlich wie das Internet. Auch damals musste man sich früher oder später damit auseinandersetzen. Heute kennen wir keine Firmen mehr, die das Internet nicht benutzen. Man muss sich damit beschäftigen, sich fragen, wo man es sinnvoll einsetzt, wo es schaden könnte, wo man manipuliert werden könnte. Genau dafür sind solche Kanäle und Interviews wertvoll. Vielen Dank, Herr Hochreiter, dass Sie heute mit dabei waren. Bis zum nächsten Mal.

---

Quelle: https://www.youtube.com/watch?v=QJYmKbZJt8k
