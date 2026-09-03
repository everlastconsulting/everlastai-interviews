# Martin Riedmiller × Leonard Schmedding Interview

Prof. Dr. Martin Riedmiller · Research Director [Google DeepMind](https://deepmind.google/) · [@everlastai](https://www.youtube.com/@everlastai) · 2026-01-15 · 67 Min · Deutsch · [YouTube](https://www.youtube.com/watch?v=_N5_qstuFQU)

[Martin Riedmiller](https://en.wikipedia.org/wiki/Martin_Riedmiller) ist einer der einflussreichsten deutschen KI-Forscher und seit 2013 bei [Google DeepMind](https://deepmind.google/), wo er heute das Control Team leitet. Bereits 1992 entwickelte er an der [TH Karlsruhe](https://www.kit.edu/) mit dem [Rprop-Algorithmus](https://en.wikipedia.org/wiki/Rprop) ein Trainingsverfahren, das neuronale Netze deutlich schneller trainierbar machte, später folgte mit [Neural Fitted Q Iteration](https://link.springer.com/chapter/10.1007/11564096_32) ein Vorläufer moderner [Deep-Reinforcement-Learning-Methoden](https://en.wikipedia.org/wiki/Deep_reinforcement_learning). Mit seinem Team [Brainstormers](https://en.wikipedia.org/wiki/RoboCup) gewann er fünf [RoboCup](https://www.robocup.org/)-Weltmeistertitel, war Co-Autor der berühmten [Nature-Publikation zu Deep Reinforcement Learning](https://www.nature.com/articles/nature14236) und erlebte den [AlphaGo](https://deepmind.google/research/breakthroughs/alphago/)-Moment 2016 als einer von wenigen deutschen Forschern hautnah mit. Im Gespräch geht es um seine frühen Jahre, [AlphaGo](https://deepmind.google/research/breakthroughs/alphago/) gegen Lee Sedol, [AlphaFold](https://deepmind.google/technologies/alphafold/) und das Proteinfaltungsproblem, den [Kernfusions-Durchbruch mit dem EPFL-Tokamak](https://www.nature.com/articles/s41586-021-04301-9), seine Sicht auf [AGI](https://en.wikipedia.org/wiki/Artificial_general_intelligence), das Verhältnis von Skalierung zu neuen Forschungsansätzen und seine Hoffnung für Deutschland als Innovationsstandort. Auch [Demis Hassabis](https://en.wikipedia.org/wiki/Demis_Hassabis), [Shane Legg](https://en.wikipedia.org/wiki/Shane_Legg), [Jürgen Schmidhuber](https://en.wikipedia.org/wiki/J%C3%BCrgen_Schmidhuber), [Sebastian Thrun](https://en.wikipedia.org/wiki/Sebastian_Thrun) und [ChatGPT](https://chat.openai.com/) kommen zur Sprache.

## Timestamps

- [00:00](https://www.youtube.com/watch?v=_N5_qstuFQU&t=0s) – Beschleunigung der KI-Welt
- [01:29](https://www.youtube.com/watch?v=_N5_qstuFQU&t=89s) – Vorstellung Martin Riedmiller
- [04:44](https://www.youtube.com/watch?v=_N5_qstuFQU&t=284s) – Beginn Interview
- [04:50](https://www.youtube.com/watch?v=_N5_qstuFQU&t=290s) – Rprop Algorithmus
- [06:30](https://www.youtube.com/watch?v=_N5_qstuFQU&t=390s) – Wie funktioniert Rprop?
- [08:56](https://www.youtube.com/watch?v=_N5_qstuFQU&t=536s) – Durchbrüche der 90er
- [11:38](https://www.youtube.com/watch?v=_N5_qstuFQU&t=698s) – RoboCup & Brainstormers
- [16:34](https://www.youtube.com/watch?v=_N5_qstuFQU&t=994s) – Humanoide Roboter
- [19:28](https://www.youtube.com/watch?v=_N5_qstuFQU&t=1168s) – Von Professor zu DeepMind
- [23:37](https://www.youtube.com/watch?v=_N5_qstuFQU&t=1417s) – Der AlphaGo Moment
- [28:06](https://www.youtube.com/watch?v=_N5_qstuFQU&t=1686s) – Proteinfaltung: 50-Jahre-Problem gelöst
- [31:29](https://www.youtube.com/watch?v=_N5_qstuFQU&t=1889s) – Wie lernen neuronale Netze?
- [36:44](https://www.youtube.com/watch?v=_N5_qstuFQU&t=2204s) – Was bedeutet AGI für DeepMind?
- [39:46](https://www.youtube.com/watch?v=_N5_qstuFQU&t=2386s) – Aktuelle Forschung: Robotik & Steuerung
- [41:39](https://www.youtube.com/watch?v=_N5_qstuFQU&t=2499s) – Kernfusion Durchbruch
- [48:56](https://www.youtube.com/watch?v=_N5_qstuFQU&t=2936s) – Kommerzialisierung der Kernfusion
- [49:20](https://www.youtube.com/watch?v=_N5_qstuFQU&t=2960s) – Wahrnehmung der Beschleunigung
- [53:54](https://www.youtube.com/watch?v=_N5_qstuFQU&t=3234s) – Grenzen neuronaler Netze
- [56:26](https://www.youtube.com/watch?v=_N5_qstuFQU&t=3386s) – Scaling vs. neue Ansätze zur AGI
- [59:03](https://www.youtube.com/watch?v=_N5_qstuFQU&t=3543s) – Leben in Deutschland, Arbeit in London
- [1:02:06](https://www.youtube.com/watch?v=_N5_qstuFQU&t=3726s) – Deutschlands Stärken & Chancen
- [1:06:17](https://www.youtube.com/watch?v=_N5_qstuFQU&t=3977s) – Schlussworte

## Transcript

### 04:44 – Beginn Interview

**Leonard Schmedding**

Hallo Martin, schön, dass du heute mit dabei bist. Ich freue mich sehr, mit dir zu sprechen. Du bist ja ein wahrer KI-Pionier, hast Informatik studiert und 1992 in deiner Diplomarbeit an der [TH Karlsruhe](https://www.kit.edu/) den sogenannten [Rprop-Algorithmus](https://en.wikipedia.org/wiki/Rprop) entwickelt, um neuronale Netzwerke deutlich schneller und trainierbar zu machen. Mich interessiert zunächst: was war damals für dich der Auslöser, dich in dieser noch sehr frühen Phase mit [neuronalen Netzen](https://en.wikipedia.org/wiki/Artificial_neural_network) zu beschäftigen? Und vielleicht erklärst du auch noch, was es mit dem Rprop-Algorithmus auf sich hat.

**Prof. Dr. Martin Riedmiller**

Das war eine Zeit, in der neuronale Netze gerade wieder ein bisschen an Bedeutung gewonnen haben. Es gab zwei ganz dicke Bücher, [Parallel Distributed Processing 1 und 2](https://en.wikipedia.org/wiki/Connectionism), die voll von verschiedenen neuronalen Netztypen waren und davon, was man alles damit machen kann. Da gab es ein Paper, in dem ein neuronales Netz angefangen hat zu brabbeln wie ein Baby, und ich fand das damals unheimlich spannend. Dazu kam ein Lehrstuhl bei uns, der eine Vorlesung über neuronale Netze hielt, eher theoretisch angehaucht, sehr systematisch aufgebaut. Ich war auf der Suche nach einer Diplomarbeit, habe Heinrich Braun, den Betreuer dort, gefragt, ob er etwas Interessantes hätte, und er hat mir einen Stapel Papers in die Hand gedrückt: das Training von neuronalen Netzen, das kann man noch verbessern. So hat das angefangen.

### 06:30 – Wie funktioniert Rprop?

**Leonard Schmedding**

Kannst du für die Zuschauer etwas ausholen? Es gibt ja viele Arten, ein neuronales Netz zu trainieren. Was genau hat es mit dem Rprop-Algorithmus auf sich, was war damals dein Ansatz?

**Prof. Dr. Martin Riedmiller**

Das Standardverfahren für tiefe neuronale Netze ist [Gradientenabstieg](https://en.wikipedia.org/wiki/Gradient_descent). Dabei berechnet man die Ableitung jedes einzelnen Gewichts nach der Ausgabe und ändert das Gewicht so, dass der Fehler am Ausgang kleiner wird. Klassisches überwachtes Lernen. Das Problem: der Gradient sagt nicht immer genau vorher, wie weit man springen muss, um das Minimum zu erreichen. Es gab dann verschiedene Verfahren, die für jedes Gewicht eine eigene Lernrate mitlernten und mit dem Gradienten multiplizierten. Ich habe verschiedene Sachen ausprobiert, manche funktionierten besser, manche schlechter. Irgendwann fiel mir ein: wenn der Gradient keine richtige Bedeutung für die Gewichtsanpassung hat, warum passen wir die Anpassung dann nicht direkt selbst an, ohne über den Gradienten zu gehen? Wir schauen praktisch nur, ob wir das Gewicht größer oder kleiner machen müssen. Wenn ich ein paar Mal denselben Wert addiere, mache ich offenbar zu kleine Schritte, also vergrößere ich die Schrittweite. Ändert sich das Vorzeichen, bin ich über ein Minimum gesprungen, dann halbiere ich die Schrittweite. Witzigerweise hat das Verfahren super funktioniert, viel schneller als alles, was bis dahin in der Literatur bekannt war, und der zusätzliche Vorteil war, dass man kaum Parameter einstellen musste. Out of the box gute Ergebnisse für ganz viele Probleme.

### 08:56 – Durchbrüche der 90er

**Leonard Schmedding**

Für mich war in der Recherche besonders interessant, dass 1992, auch 1991, viele Durchbrüche stattfanden. Ich hatte zuletzt mit [Jürgen Schmidhuber](https://en.wikipedia.org/wiki/J%C3%BCrgen_Schmidhuber) gesprochen, der genau in diesen Jahren auch viele Durchbrüche im Deep Learning gemacht hat. Für die meisten ist [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning) und [Generative AI](https://en.wikipedia.org/wiki/Generative_artificial_intelligence) erst seit drei Jahren so richtig relevant, seit dem [ChatGPT](https://chat.openai.com/)-Hype, durch deutlich höhere Rechenleistung, aber im Kern beruht vieles auf Algorithmen aus den 90ern. War für dich damals absehbar, dass das mit mehr Rechenleistung so explodiert, oder kam dich der ChatGPT-Moment auch überraschend?

**Prof. Dr. Martin Riedmiller**

Dass man mit neuronalen Netzen tolle Sachen machen kann, war für mich von Anfang an klar. Wir konnten sehr gute Vorhersagen machen, die [Generalisierungsfähigkeit](https://en.wikipedia.org/wiki/Generalization_(learning)) auf unbekannte Eingaben war immer schon ziemlich gut. Wir hatten damals schon Prognosen auf Wechselkurse und Aktienkurse gemacht, das funktionierte erstaunlich gut. Insofern habe ich immer geglaubt, dass man damit etwas Gutes machen kann. Dass es zu meinen Lebzeiten in aller Munde sein würde und jeder von KI sprechen würde, das war überhaupt nicht zu erwarten. Als ich 2013 bei DeepMind anfing, war zwar unsere Story, KI zum Durchbruch zu verhelfen, aber ob in 5, 10 oder 50 Jahren, das war nicht klar. Die Heftigkeit, mit der ChatGPT eingeschlagen ist, hat mich auch selbst überrascht. Dass man Texte produzieren kann, die über mehrere Sätze, sogar über Seiten hinweg, Sinn ergeben, hätte ich wie viele andere im Feld zwei Jahre zuvor nicht vermutet.

### 11:38 – RoboCup & Brainstormers

**Leonard Schmedding**

Du hast dich aber nicht nur mit Generative AI beschäftigt, sondern vor allem mit [Reinforcement Learning](https://en.wikipedia.org/wiki/Reinforcement_learning). Mit den [Brainstormers](https://en.wikipedia.org/wiki/RoboCup) hast du zwischen 1998 und 2008 fünf Weltmeistertitel bei den [RoboCup](https://www.robocup.org/)-Weltmeisterschaften gewonnen, ihr wart eines der ersten Teams weltweit, das Reinforcement Learning im Roboterfußball eingesetzt hat. 2007 übernahm sogar [Angela Merkel](https://de.wikipedia.org/wiki/Angela_Merkel) symbolisch die Roboterpartnerschaft für einen eurer Roboter. Wie kam es zu diesem RoboCup-Projekt, was war dein Ziel?

**Prof. Dr. Martin Riedmiller**

1996 hatte ich meine Dissertation zum Thema selbstlernende Systeme abgelegt und reingeschaut, wie man Reinforcement Learning praktisch anwenden kann. Damals gab es erste Beispiele mit Labyrinthen. Mich hat fasziniert, wie Maschinen lernen können, sich selbständig fortzubewegen, Sachen zu greifen, sich auszubalancieren, ohne dass man ihnen vorher zeigt, wie das geht. Also nicht überwachtes Lernen, sondern man sagt der Maschine nur: das ist gut, wenn du ein bestimmtes Ziel erreichst, aber wie du dorthinkommst, musst du selbst lernen. Damals gab es den Rat: wenn du in der akademischen Welt bleiben willst, geh in die USA oder wechsle das Thema, um Breite zu zeigen. Das hat mir nicht gefallen, weil ich in das Thema verliebt war. Ich habe mir gedacht, vielleicht wird es interessanter, wenn ich von einzelnen Agenten zu [Multi-Agenten-Systemen](https://en.wikipedia.org/wiki/Multi-agent_system) gehe. Bin auf Roboterfußball gestoßen, fand es toll, weil ich selbst gerne Fußball spiele und Sport mache, und der Wettbewerbsgedanke war attraktiv. Ich bin dann ganz naiv nach Berlin gefahren zu [Hans-Dieter Burkhard](https://de.wikipedia.org/wiki/Hans-Dieter_Burkhard), die waren damals Vizeweltmeister, und habe gefragt, wie man da einsteigt. Wir haben uns auf der ersten Weltmeisterschaft in Paris eine blutige Nase geholt, sogar meine Kollegen in Karlsruhe haben sich darüber lustig gemacht. Aber das war der Beginn, zu sagen: das kann es nicht gewesen sein. Wir können das besser, vor allem wollten wir, dass die Roboter selbst Fußball spielen lernen. Wir haben eine Steuerungsarchitektur aufgebaut, in der einzelne Verhalten trainierbar waren, etwa ein stärkerer Kick, später Tacklings. Die Simulation war realitätsnah, klassisch auszuprogrammieren war schwierig. Mit Reinforcement Learning konnten wir sagen: spiele den Ball so fest wie möglich in eine Richtung, und der Roboter hat eine Sequenz von Kicks gelernt. Wir hatten den stärksten Kick der Liga, sind auf Anhieb Vize-Europameister und Vizeweltmeister geworden, haben die Architektur über die Jahre weiterentwickelt und sind dann auf reale Roboter übergegangen. Da wurde es schwerer, denn am realen Roboter entspricht eine Million Wiederholungen ein paar Jahren. Daraus ist mein heutiges Forschungsgebiet entstanden: dateneffiziente Lernalgorithmen. Wir waren dann die Ersten mit einer gelernten Dribbelroutine für die Mid-Size-Roboter, die viel besser war als alles, was Studenten in Jahren davor ausprogrammiert hatten.

### 16:34 – Humanoide Roboter

**Leonard Schmedding**

Inwieweit ist das übertragbar auf die Entwicklung, die wir heute mit [humanoiden Robotern](https://en.wikipedia.org/wiki/Humanoid_robot) sehen? Viele sagen, ab 2026 geht es richtig los, China hat die Massenproduktion von humanoiden Robotern als Staatsziel ausgerufen. Sind das im Wesentlichen die gleichen Konzepte und Prinzipien?

**Prof. Dr. Martin Riedmiller**

Der finale Ansatz, wie man humanoide Roboter steuert, ist noch nicht draußen. Die große Problematik beim Reinforcement Learning ist: wenn ich nicht nur einen Freiheitsgrad habe, sondern 20 oder 30, wie es bei humanoiden Robotern der Fall ist, funktionieren diese Techniken nicht mehr so einfach. Da gibt es noch Forschung zu tun. Deshalb hat sich in der Robotik in letzter Zeit [Imitation Learning](https://en.wikipedia.org/wiki/Imitation_learning) durchgesetzt, also wieder überwachtes Lernen, bei dem ein Mensch den Roboterarm steuert, Trainingsdaten gesammelt werden und das Ganze in einem großen [Transformer](https://en.wikipedia.org/wiki/Transformer_(deep_learning_architecture)) gespeichert wird, in der Hoffnung auf Generalisierung. Es ist im Prinzip die Story aus der Sprache, ganz viele Trainingsdaten, ganz große Netze, einfaches Lernziel: das nächste Wort vorhersagen. Das jetzt auf Robotik zu übertragen, ist eine Wette, weil im Vergleich zur Sprache, wo das ganze Internet, Wikipedia, viele Bücher zur Verfügung stehen, für die Ansteuerung von Robotern viel weniger Daten existieren. Die muss man sammeln, das dauert. Ob die Wette aufgeht, wird sich mit der Zeit zeigen.

### 19:28 – Von Professor zu DeepMind

**Leonard Schmedding**

Du warst dann gut 13 Jahre Professor an der [TU Dortmund](https://www.tu-dortmund.de/), der [Universität Osnabrück](https://www.uni-osnabrueck.de/) und der [Universität Freiburg](https://www.uni-freiburg.de/). Dann hast du den Weg aus der sicheren Professur in die Privatwirtschaft zu DeepMind gemacht, 2013, und das war damals deutlich ungewöhnlicher und vor der [Akquisition durch Google](https://en.wikipedia.org/wiki/DeepMind#History). Was war der Grund?

**Prof. Dr. Martin Riedmiller**

Ich war immer gerne Uniprofessor, mit jungen Leuten zu arbeiten macht Spaß, Talente kennenzulernen ist eine sehr belohnende Arbeit. Was mir aber gefehlt hat, war selbst forschen zu können, sich selbst hinzusetzen und etwas auszuprogrammieren. Reinforcement Learning hat mich von Anfang an gepackt: nachts einen Trainingslauf anstoßen, am nächsten Morgen kommen und sehen, ah, der hat etwas gelernt, das hätte ich gar nicht gedacht. Dafür ist immer weniger Zeit geblieben. 2010 habe ich mit Roland Hafner, einem ehemaligen Doktoranden, eine Firma gegründet (Cognit GmbH), wir wollten diese Sachen in die Welt bringen. Das funktionierte ganz gut, dann wurde ich 2012 von [Shane Legg](https://en.wikipedia.org/wiki/Shane_Legg), einem der Gründer von DeepMind, auf einer Konferenz angesprochen. Sie hätten etwas ganz Großes vor, sie wollten KI lösen, und das, was ich vorgestellt hatte, passe perfekt. Wie ich nachher erfahren habe, war ich einer der wenigen etablierten Professoren, die die Idee gut fanden, viele dachten, es sei zu früh. Als ich dann [Demis Hassabis](https://en.wikipedia.org/wiki/Demis_Hassabis) kennengelernt habe, war für mich klar: wenn das jemand hinkriegt, dann diese Leute, so ambitioniert und groß zu denken von Anfang an. Ich musste mein kleines Unternehmen aufgeben und wollte Teil dieser DeepMind-Geschichte werden.

### 23:37 – Der AlphaGo Moment

**Leonard Schmedding**

DeepMind wurde 2016 dann erst richtig öffentlich bekannt, durch den [AlphaGo](https://deepmind.google/research/breakthroughs/alphago/)-Moment, den [Move 37](https://en.wikipedia.org/wiki/AlphaGo_versus_Lee_Sedol) im März 2016. Du warst da schon drei Jahre dabei. Wie hast du das erlebt?

**Prof. Dr. Martin Riedmiller**

Das war ganz besonders. Unser erstes Projekt, mit dem auch Google auf uns aufmerksam wurde, war [Atari](https://en.wikipedia.org/wiki/Atari) zu lösen. Wir hatten einen Agenten entwickelt, der einfach vom Zuschauen lernt, Atari-Spiele zu spielen, ohne die Regeln zu kennen, viel besser als ein Mensch. Das war der Benchmark, den wir innerhalb von neun Monaten von ersten Anfängen auf 45 von 50 Spielen auf menschlichem Niveau gebracht haben. Die Art und Weise, das anzugehen, mit der Professionalität, einem menschlichen Atari-Spieler, der den ganzen Tag spielt, um Baselines zu liefern, das war komplett anders, als ich es von der Uni gewohnt war. Direkt auf eine [Nature-Publikation](https://www.nature.com/articles/nature14236) abgezielt. Bei Go war es so: ein guter Kollege und Freund von mir, [David Silver](https://en.wikipedia.org/wiki/David_Silver_(computer_scientist)), ist selbst Go-Spieler und hat an Go gearbeitet. Irgendwann war klar, dass man vom reinen Bild des Go-Bretts eine [Wertfunktion](https://en.wikipedia.org/wiki/Reinforcement_learning#Value_function) lernen kann, indem man die Situation direkt in ein tiefes Netz füttert, ohne komplizierte Features zu bauen. Das war das erste Zeichen: oh, das könnte mit Deep Learning direkt klappen. Wir hatten dann einen eingeladen, der zu der Zeit der Beste im maschinellen Go war, auf Neun-mal-Neun-Brettern. Der hat erzählt, wie mühsam es ist, welche Features sie nutzen, und ich dachte: das ist ein schwieriges Problem. Ein paar Wochen später sagte David, sie machen ganz gute Fortschritte. Es gab dann ein erstes geheimes Match gegen den europäischen Go-Champion, das positiv für den gelernten Spieler ausging. Bei der Weltmeisterschaft in Seoul war ein Teil der Delegation vor Ort, die anderen sind morgens um 4 Uhr in einen Konferenzraum gekrochen und haben zugeschaut. Ich verstehe nicht so viel von Go, dass ich es vom Brett her beurteilen könnte, aber gerade beim Move 37 sagten die Kommentatoren: das ist komisch, was soll das jetzt, hat sich der Agent verzockt? Und dann dieses 4 zu 1 zu sehen, wie die Welt darauf reagiert: das war ein Moment, in dem ich dachte, ich bin bei einem ganz besonderen Verein gelandet.

### 28:06 – Proteinfaltung: 50-Jahre-Problem gelöst

**Leonard Schmedding**

Es gibt eine tolle Doku, [The Thinking Game](https://www.thinkinggamefilm.com/), die ich jedem Zuschauer empfehlen kann. Da wird auch klar, dass nach AlphaGo dann [AlphaZero](https://deepmind.google/discover/blog/alphazero-shedding-new-light-on-chess-shogi-and-go/) kam, dann das [Proteinfaltungsproblem](https://en.wikipedia.org/wiki/Protein_folding), eines der größten Probleme der Biochemie, das über 50 Jahre existierte. Warum war das so wichtig?

**Prof. Dr. Martin Riedmiller**

Ich bin selbst kein Experte in Proteinfaltung, kann es nur so erzählen, wie ich es aufgenommen habe. Es war lange die Frage, wie sich aus reiner DNA-Information ein Protein in eine dreidimensionale Struktur entfaltet. Eigentlich könnte man denken, das ist ein Coding-Problem, aber die Sache ist viel komplizierter. State of the Art war, dass Menschen die DNA genommen, Vermutungen angestellt und mühevolle Messungen gemacht haben. Eine ganze Doktorarbeit, um von einem DNA-String auf das Protein zu schließen. Es gab den [CASP-Wettbewerb](https://en.wikipedia.org/wiki/CASP), in dem man für bekannte DNA-Sequenzen Vorhersagen treffen sollte. 20 Jahre lang lag das Niveau bei 10 bis 15 Prozent. Eine Gruppe bei DeepMind hat sich dem angenommen, im ersten Jahr gewonnen mit 30 Prozent, zwei Jahre später über 80 oder 90 Prozent, sodass man sagen konnte: das Problem ist gelöst. Und zwar über ein lernendes System, das aus den bekannten Entfaltungen vorhersagen kann, wie sich Proteine für unbekannte DNA-Sequenzen entfalten. [AlphaFold](https://deepmind.google/technologies/alphafold/) wurde [open-sourced](https://github.com/google-deepmind/alphafold) und wird weltweit als Tool eingesetzt, um Forschung zu beschleunigen. Demis hat von Anfang an gesagt: wenn wir KI lösen und einzelne Bausteine verstehen, beschleunigen wir die Wissenschaft in vielen Bereichen, bis hin zu dem Punkt, an dem eine KI selbst Wissenschaft betreiben kann. Im Nachhinein ist es für mich erstaunlich, wie jemand so groß denken und solche Vorhersagen machen kann zu einem Zeitpunkt, an dem das für viele Menschen nicht absehbar war.

### 31:29 – Wie lernen neuronale Netze?

**Leonard Schmedding**

Demis hat dafür 2024 sogar den [Nobelpreis](https://www.nobelprize.org/prizes/chemistry/2024/summary/) bekommen, eine ganz wichtige Arbeit mit AlphaFold. Lass uns kurz darauf eingehen, was Lernen bei [Alpha Go](https://deepmind.google/research/breakthroughs/alphago/) eigentlich heißt. Für viele ist es eine Blackbox: wie kann ein Computer einen Zug entwickeln, den vielleicht einer von 10.000 Spielern getroffen hätte? Und wo ist der Kontrast zu ChatGPT?

**Prof. Dr. Martin Riedmiller**

Es gibt mindestens zwei Arten, neuronale Netze zu trainieren. Das eine ist [überwachtes Lernen](https://en.wikipedia.org/wiki/Supervised_learning): für jede Eingangssituation weiß man genau, was rauskommen soll. Bei Go: ich habe eine Brettsituation, früher hat ein Großmeister diesen Zug gespielt, also sage mir bitte den Zug voraus. Das war ein großer Teil unseres ersten Ansatzes bei Go, aus vergangenen Beispielen zu lernen. Es war aber klar, dass man so nur auf ein bestimmtes Level kommt. Der heilige Gral ist: ich stecke gar nicht rein, wie du das Spiel spielen sollst, ich habe nur ein Trainingssignal. Wenn du gegen dich selbst spielst, gewinnt eine Hälfte und die andere verliert. Aus beiden Signalen kann man lernen. Das ist [Reinforcement Learning](https://en.wikipedia.org/wiki/Reinforcement_learning). Die große Überraschung war, dass es selbst für Go möglich ist, aus diesem Trainingssignal Strategien zu entwickeln. Wenn ich nur überwacht lerne, lerne ich von den Großmeistern, die in der asiatischen Kultur teilweise mit sechs Jahren in spezielle Schulen geschickt wurden, wo man sagte: bestimmte Muster darfst du nicht spielen. Eine Maschine kümmert das nicht, sie sucht einfach einen Weg, ihre Belohnung zu maximieren, und kann das millionenfach wiederholen. So entstehen Züge wie Move 37, über den kein Mensch vorher nachgedacht hat, weil es einfach so viele Möglichkeiten gibt und eine Maschine Zeit, Rechenpower und Geduld hat, viele Wege zu explorieren.

**Leonard Schmedding**

Das hört sich super sinnvoll an. In der Praxis ist es ja eine riesige Anzahl an Zahlen, die so ein neuronales Netz bildet. Was bedeutet eigentlich Lernen in dem Moment, das Anpassen der Gewichte und Biases auf Basis der Belohnungsfunktion?

**Prof. Dr. Martin Riedmiller**

Zurück zum einfachen Weltbild, einem Labyrinth. Wenn ich rechts laufe, komme ich vielleicht in eine Sackgasse, links komme ich irgendwann zum Ziel. In unserem Reinforcement Learning lernt das neuronale Netz vorherzusagen, wie viele Schritte ich noch brauche, wenn ich rechts gehe (unendlich viele) oder wenn ich nach oben gehe (zehn). Dann hat es die Wahl. Das Lernen der sogenannten [Wertfunktion](https://en.wikipedia.org/wiki/Bellman_equation) kann ich komplett unüberwacht aus Erfahrung machen, über [dynamische Programmierung](https://en.wikipedia.org/wiki/Dynamic_programming), ein Optimierungsprinzip, das schon in den 50er Jahren von [Richard Bellman](https://en.wikipedia.org/wiki/Richard_E._Bellman) entwickelt wurde. Vom Ende her aufbauen: am Ziel brauche ich null Schritte, von dort aus lerne ich rückwärts. Genau das passiert bei AlphaGo: wenn du diesen Zug machst, geht es voraussichtlich noch 20 Züge bis zum Sieg, bei jenem Zug 50 Züge oder du verlierst. Diese Vorhersage wird im neuronalen Netz aus Erfahrung dynamisch generiert.

### 36:44 – Was bedeutet AGI für DeepMind?

**Leonard Schmedding**

Du hast vorhin von deinem ersten Treffen mit Shane Legg und Demis erzählt: ihr Ziel war, KI zu lösen. Inzwischen ist [AGI](https://en.wikipedia.org/wiki/Artificial_general_intelligence) immer mehr in aller Munde. Was ist das übergeordnete Ziel, was bedeutet das für euch?

**Prof. Dr. Martin Riedmiller**

Wir haben den Begriff bei uns wohltuend undefiniert gelassen, weil er schwer zu greifen ist. Warum hat Demis irgendwann gesagt, wir machen nicht nur KI, sondern allgemeine KI? Aus Erfahrung: es gab Schachprogramme, die gut waren, aber nur Schach spielen konnten. Was man eigentlich anstrebt, ist etwas Geniales wie ein Gehirn zu bauen, das Schach spielt, aber gleichzeitig auch Fußball spielen oder ein schönes Gedicht formulieren kann. Mit der Idee, dass die Grundmechanismen, die man fürs Schachspielen braucht, vielleicht auch nützlich sind, um ein Gedicht zu schreiben oder Bilder zu erkennen. Was mir gut gefällt, ist eine alte Definition vom ersten KI-Workshop 1956 in [Dartmouth](https://en.wikipedia.org/wiki/Dartmouth_workshop): jeden Aspekt menschlicher Intelligenz so präzise zu formulieren, dass eine Maschine ihn ausführen kann. Das ist keine Superintelligenz, das ist einfach KI. Wenn man so anschaut, sind wir ein gutes Stück davon entfernt, künstliche Intelligenz mit all ihren Aspekten zu verstehen. Mal abgesehen davon, mit welcher Energieeffizienz unser Gehirn arbeitet im Vergleich zu den Maschinen, die wir heute brauchen.

### 39:46 – Aktuelle Forschung: Robotik & Steuerung

**Leonard Schmedding**

Du hast schon angedeutet, dass du nicht so groß bei AlphaFold dabei warst. Womit beschäftigst du dich gerade bei DeepMind?

**Prof. Dr. Martin Riedmiller**

Ich habe das Glück, dass ich an ähnlichen Themen arbeiten kann wie zu meiner Doktorarbeit: selbständiges Lernen für regelungstechnische Anwendungen. Etwas zu balancieren, jetzt komplexer mit Roboterarmen Dinge greifen, zusammenführen, stapeln, mit zweibeinigen Robotern sich fortzubewegen, und zwar so, dass wir nur das Ziel vorgeben, etwa nach vorne zu bewegen, und die Ansteuerung der Motoren autonom gelernt wird. Geändert hat sich die Komplexität der Systeme: wir können heute Roboterarme mit sieben Freiheitsgraden von Null lernen lassen, Objekte zu greifen und zu bewegen, das Ganze auch von rohen Kamerabildern, ähnlich wie beim Menschen. Mein Twist ist, das besonders dateneffizient hinzukriegen, mit so wenig Experimenten wie möglich.

### 41:39 – Kernfusion Durchbruch

**Leonard Schmedding**

Dein Team hat 2022 einen [Durchbruch im Bereich der Kernfusion](https://www.nature.com/articles/s41586-021-04301-9) erzielt, mit Deep Reinforcement Learning ein [Tokamak](https://en.wikipedia.org/wiki/Tokamak)-Plasma stabil gehalten. Erzähl uns davon.

**Prof. Dr. Martin Riedmiller**

Wir haben Reinforcement Learning nie nur auf Robotik eingeschränkt, [Regelungstechnik](https://en.wikipedia.org/wiki/Control_theory) ist ein allgemeines Gebiet, von der Heizung bis zum Motor. Reinforcement Learning erlaubt uns, das System nicht in allen Details zu verstehen, sondern idealerweise nur das Ziel anzugeben: hol so viel Energie aus diesem Tokamak wie möglich. Wir hatten die Möglichkeit, mit der [EPFL](https://www.epfl.ch/) in Lausanne zusammenzuarbeiten, die einen Versuchstokamak haben und bereit waren, unsere Lernagenten an ihren teuren Reaktor heranzulassen. Eines der klassischen Regelungsprobleme ist das Plasma, ein sehr heisses Gas, eine wabernde Masse, die nicht an den Rand des Gefäßes kommen darf, weil sonst alles kaputtgeht und keine Fusion mehr stattfinden kann. Das Plasma hält man durch Magnetfelder, erzeugt von 19 Magneten, die um das Gefäß angeordnet sind. Es ist ein komplexes Regelungsproblem, das Plasma stabil zu halten und ihm bestimmte Umrisse, etwa ein Dreieck, zu geben. Wir konnten zeigen, dass ein lernendes System ohne Kenntnis der Physik das Plasma stabil halten kann, zunächst in Simulation, dann am realen Reaktor. Wir haben gefragt, ob man da etwas kaputt machen kann, weil lernende Regler kreativ sind. Beim ersten geklappten Versuch hat der Agent Magnete eingesetzt, die für einen anderen Zweck gedacht waren, und an der mechanischen Struktur gezerrt. Die Designer sagten: bitte mach das nicht wieder. Sehr interessant, dass es überhaupt funktioniert hat. Im Anschluss hat er eine Lösung gefunden, die freundlicher zum Aufbau war.

### 48:56 – Kommerzialisierung der Kernfusion

**Leonard Schmedding**

Das ist bemerkenswert, im Wesentlichen das Gleiche wie bei AlphaGo, für eines der größten Probleme der Menschheit eingesetzt. ChatGPT verbraucht in etwa so viel Strom wie eine Großstadt. [Sam Altman](https://en.wikipedia.org/wiki/Sam_Altman) hat 375 Millionen Dollar in das Fusions-Startup [Helion](https://www.helionenergy.com/) investiert, mit dem Versprechen, bis 2028 Strom aus Kernfusion zu liefern. Welche Rolle spielt euer Durchbruch in der Kommerzialisierung, wo sind die größten Bottlenecks?

**Prof. Dr. Martin Riedmiller**

Was wir gezeigt haben, ist auf jeden Fall ein Weg, wie man einfache Regler lernen kann, statt sie zu entwickeln. Statt von vorne anzufangen, kann ich dem System einen Umriss vorgeben, und es lernt einfach. Das spart Zeit, und vielleicht können wir Wege finden, an die ein Mensch nicht gedacht hat. Dazu muss das Wohnsystem (Fusionsenergie aus einem Reaktor) erstmal funktionieren. Aus dem Projekt habe ich gelernt, dass große Schritte gemacht wurden, vor allem beim Erzeugen starker Magnetfelder mit wenig Strom. Das macht optimistisch für die nächsten Jahre. Es gibt aber offene physikalische Probleme: dass die Fusion mehr Energie produziert als reingesteckt wird, und dann, wie ich die Energie aus dem Prozess herausbekomme. Ich bin kein Fusionsexperte, aber ich denke, in den nächsten zwei, drei Jahren werden wir noch große Durchbrüche sehen, allein dadurch, dass jetzt Milliarden in Fusionsreaktoren fließen.

### 49:20 – Wahrnehmung der Beschleunigung

**Leonard Schmedding**

Es gibt jetzt auch die [Genesis Mission](https://www.whitehouse.gov/) der US-Regierung, die genau das als Staatsziel erklärt. Mich interessiert deine Wahrnehmung dieser Beschleunigung. Ist das nur gefühlt, weil die Öffentlichkeit erst seit drei Jahren konfrontiert ist, oder gibt es einen Unterschied zwischen dem, was Öffentlichkeit sieht, und dem, was ihr intern habt? Bei Google ist auffällig: wenn ChatGPT vorne ist, kommt der große Paukenschlag, dann ist Ruhe, dann kommt ihr wieder.

**Prof. Dr. Martin Riedmiller**

Sogar für mich, der schon lange auf dem Gebiet tätig ist, ist das, was gerade passiert, total verrückt. Ich selbst habe Schwierigkeiten Schritt zu halten: jetzt funktioniert wieder [Gemini 3](https://deepmind.google/technologies/gemini/), Gemini 3 ist viel besser als ChatGPT, jetzt müssen die wieder aufholen, dann wird ein Test bestanden. Wahnsinnig viel Rauschen im System. Auf der anderen Seite werden immense Fortschritte gemacht, weil so viel Forschungsleistung darauf konzentriert ist. Die Rechenleistung ist irrsinnig gestiegen. Wenn ich vergleiche, was im Studium ein Rechner konnte und was Rechner heute machen, ist das unvorstellbar viel schneller. Da kommen zwei Techniken zusammen: schnellere Rechner und bessere Algorithmen, plus der Mut, mehr Daten in größere Netze reinzuschmeissen. Und plötzlich passiert etwas, das durch Forschung allein nicht hinzubekommen war. Es war nicht klar, dass man ein Sprachmodell einfach durch mehr Daten und größere Netze so gut machen kann. Es hätte auch sein können, man muss bessere Sachen verstehen, bessere Merkmale oder ganz andere Algorithmen. Nein, da kamen zwei Technologien zusammen und dann passiert etwas Großes. Selbst für Leute im Gebiet ist es unvorstellbar, was da auf uns einprasselt, getrieben auch davon, dass alle Geld machen wollen. Zur Frage der Wissenschaftsbeschleunigung: AlphaFold ist ein Beispiel, wo ein anderer Zweig (Biologie, Medikamentenentwicklung) plötzlich beschleunigt wird, gleiches in der Kernfusion oder in der Gravitationswellenerkennung, wozu wir neulich ein Paper rausgebracht haben. Wenn das mal angefangen hat, kann der Fortschritt nicht linear, sondern multiplikativ sein, plötzlich exponentielles Wachstum. Es ist also nicht nur eine verzerrte Wahrnehmung, es ist tatsächlich eine objektive Beschleunigung des Feldes.

### 53:54 – Grenzen neuronaler Netze

**Leonard Schmedding**

Mich beeindruckt immer, wenn führende KI-Forscher sagen, sie könnten nicht bis ins letzte Detail erklären, wie ein neuronales Netz seine Entscheidung fällt. Ist das tatsächlich so?

**Prof. Dr. Martin Riedmiller**

Wir wissen, wie ein neuronales Netz grundsätzlich funktioniert, mathematische Funktionen zusammengesteckt. Was wir nicht wissen, ist, welche Daten ich reinstecken muss, um ein bestimmtes Ergebnis zu erzielen. Viele Daten helfen, Generalisierung entsteht. Für mich ist immer noch erstaunlich, dass ein Netz Text reproduzieren kann, weil es viele Texte gesehen hat. Das kann ich nachvollziehen. Was ich erstaunlich finde: wenn man dem sagt, erzähl es aus der Sicht eines Kindergartenkindes oder eines Gymnasiasten, findet es andere Erklärungen. Da ist offensichtlich etwas in den Texten drin, was ich von außen nicht vermuten würde. Da hört das Erklären ganz schnell auf. Wir wissen grundsätzlich, wie es funktioniert, aber die Effekte können wir nicht im Einzelnen nachvollziehen, die Systeme sind dafür zu komplex.

**Leonard Schmedding**

Da höre ich auch raus, dass du nicht der Verfechter dieser [stochastische-Papagei-Analogie](https://en.wikipedia.org/wiki/Stochastic_parrot) bist, dass es im Zweifel nur Stochastik und eine riesige Datenbank ist.

**Prof. Dr. Martin Riedmiller**

Bei mir ist es wie bei einer optischen Täuschung. Einmal denke ich, ja, das sagt das nächste Wort voraus, was solls, das andere Mal sehe ich eine Anwendung oder eine Antwort und denke: was passiert hier gerade? Das macht es spannend. Aber man darf nicht vergessen, egal wie viele Daten wir reinstecken: eine Idee von Wahrheit oder ein tiefes Gegründetsein in der Realität ist bei diesen einfachen Sprachmodellen, wie wir sie gerade trainieren (Text rein, nächstes Wort vorhersagen), nicht gegeben. Man muss das wissen, damit man mit den Systemen, egal wie nützlich sie sind, mit einer gewissen Vorsicht umgeht.

### 56:26 – Scaling vs. neue Ansätze zur AGI

**Leonard Schmedding**

Die große Wette gerade, durch den Ausbau von Infrastruktur und Energie, ist: wir müssen nur weiter [Pretraining](https://en.wikipedia.org/wiki/Foundation_model), mehr Daten, mehr Rechenleistung, dann kommen wir zur AGI. Andere sagen, wir brauchen einen fundamental anderen Ansatz, weil uns die Daten ausgehen oder der Hebel kleiner wird. Was ist deine Meinung?

**Prof. Dr. Martin Riedmiller**

Die Geschichte "wir wissen wie es geht, brauchen einfach mehr von demselben, dann passieren Wunder" verfängt natürlich super, weil sie attraktiv ist. Wir haben in der Richtung viel gesehen, bessere Daten, mehr Daten, größere Netze, plötzlich kommen Antworten, mit denen wir nicht gerechnet haben. Ich bin trotzdem der Meinung, dass das nicht reichen wird. Wir sollten die Erfahrung mitnehmen, dass Skalierung und Generalisierung sehr nützlich sind. Wir sollten aber auch weiter forschen, wie man aus eigener Erfahrung, durch Interaktion mit der Welt, Erfahrung bauen kann, und in der Robotik nicht nur Menschen imitieren, sondern erforschen, wie Maschinen sich Handlungsabläufe selbst beibringen. Nur dann kommen wir dem Ziel näher, das Gehirn oder Intelligenz zu verstehen. Sprachmodelle sind gekommen, um zu bleiben, sie werden ein wichtiges Modul sein, aber es fehlen noch ganz viele einzelne Prinzipien, um in die Nähe der Mächtigkeit des Gehirns zu kommen, wenn man das überhaupt schafft.

### 59:03 – Leben in Deutschland, Arbeit in London

**Leonard Schmedding**

Du arbeitest für DeepMind in London, wohnst in einem Ort mit etwa 1300 Einwohnern, bist etwa einmal pro Woche vor Ort. Wie kam es zu dieser ungewöhnlichen Konstellation?

**Prof. Dr. Martin Riedmiller**

Ich wurde von Shane angesprochen und dann von Demis. Die Arbeiten, die wir damals gemacht haben (mit tiefen Netzen direkt von Bildern selbständig zu lernen), passten wie die Faust aufs Auge zu DeepMind. Damals waren ungefähr 40 Leute dort. Demis wollte mich unbedingt an Bord holen. Ich habe es mit meiner Familie besprochen, wir waren erst drei Jahre vorher zurück in unsere ursprüngliche Heimat gezogen. Die Kinder wollten nicht weg, uns hat es auch sehr gut gefallen. Ich habe Demis gesagt: DeepMind wäre der Traum meines Lebens, ich will da unbedingt mitarbeiten, aber ich kann nicht umziehen. Er hat sich darauf eingelassen, ich sollte ein Team in London aufbauen und so oft wie möglich vor Ort sein, den Rest aus Deutschland arbeiten. Diese Vereinbarung gilt bis heute. Ich hatte das Glück, in London Leute anzustellen, mit denen ich seit deren Bachelorarbeit zusammengearbeitet hatte und die mir nach London gefolgt sind. Durch die Pendelei und Videokonferenzen funktioniert es ganz gut.

**Leonard Schmedding**

Ist es noch aktuell, einmal im Monat für eine Woche?

**Prof. Dr. Martin Riedmiller**

Je nachdem was ansteht, manchmal auch öfter. Die Kinder sind jetzt aus dem Haus, ich bin flexibler. Wenn etwas ansteht, bin ich gerne in London und sehe meine Leute.

### 1:02:06 – Deutschlands Stärken & Chancen

**Leonard Schmedding**

Du hast Einblicke in beide Welten, führende KI-Entwicklung in London und im Silicon Valley, und in Deutschland als Professor und Einwohner. Welche Unterschiede siehst du? Wie ist dein Blick auf Deutschland gerade? Viele sagen, wir sind abgeschlagen, hinken bei Rechenzentren hinterher, und selbst wenn wir sie bauen würden, wo kommt die Energie her?

**Prof. Dr. Martin Riedmiller**

Ich sehe das überhaupt nicht schwarz. In Deutschland dürfen wir das sehr gute Bildungssystem nicht unterschätzen, das allen kostenlosen Zugang zur Bildung ermöglicht. Ich war an großen Unis wie [Karlsruhe](https://www.kit.edu/) und an kleineren wie Osnabrück und habe überall sehr gute Leute getroffen, mit denen man alles Mögliche reißen kann. In den USA konzentriert sich das auf wenige Universitäten, die Leute dort sind auch richtig gut, aber wir können in Deutschland stolz sein. An Talenten mangelt es nicht. Was ich bei Google faszinierend fand: sie hatten Geld und haben es nicht in mehr vom Selben gesteckt, sondern in Wetten, die möglich erscheinen, aber vielleicht nicht in einem halben Jahr Geld bringen. Zum Beispiel autonomes Fahren, 2008 mit [Sebastian Thrun](https://en.wikipedia.org/wiki/Sebastian_Thrun) angefangen, 16 Jahre, bis Autos heute in San Francisco rumfahren. Ich war neulich in San Francisco und bin in einem [Waymo](https://waymo.com/)-Taxi gefahren, eine total tolle Erfahrung. Google sagte: wenn wir Talent kriegen können, Leute, die etwas können, dann lass sie zu uns kommen, bezahl sie ordentlich und lass sie machen. Das habe ich im akademischen System manchmal vermisst: das Erkennen, dass es Leute gibt, die nicht nur 40 Stunden in der Woche arbeiten, sondern Sachen erreichen, die niemand sonst auf der Welt hinkriegt, und denen muss man ein gutes Umfeld bieten. Der Geist, etwas zu riskieren, hat in Deutschland gefehlt, ich glaube, das ändert sich gerade. Wir sollten nicht aus der Lehre schließen "wir haben KI verpasst, jetzt müssen wir nachholen", sondern grundsätzlich innovationsfreundlicher sein. Dann darf man auch mal scheitern. Bei erneuerbaren Energien, wenn es länger dauert oder die Batterien für Elektroautos noch nicht so weit sind, sollte man nicht gleich sagen, das wird sowieso nichts. Man sollte sich mehr trauen, und wenn es nicht klappt, sollte man nicht hämisch sein. Die großen amerikanischen Firmen haben das Kapital, die Möglichkeiten, Rechenzentren zu bauen, das wird eine Weile dauern. Auf der anderen Seite werden Modelle auch kleiner und gut sein. Man kann zu jedem Zeitpunkt einsteigen, weil die Technologie nicht unerreichbar ist für die Leute, die wir in Deutschland haben.

### 1:06:17 – Schlussworte

**Leonard Schmedding**

Das kann ich genauso unterschreiben. Es ist bemerkenswert, wie viel der heutigen Durchbrüche auf deutscher Forschung basiert. Sei es ChatGPT, sei es das autonome Fahren, du hast Sebastian Thrun angesprochen, den hatten wir auch zu Gast. Martin, das war ein super Schlusswort. Danke dir für die aufschlussreichen Erkenntnisse. Wenn ihr Fragen an Martin habt, schreibt sie gerne in die Kommentare. Wie wir gehört haben, überschlagen sich die Entwicklungen, da können wir sicher in Zukunft einen zweiten Teil ansetzen.

**Prof. Dr. Martin Riedmiller**

Danke, Leo, dass ich hier sein durfte, und danke für die sehr coolen Fragen und die tiefe Recherche.

---

Quelle: https://www.youtube.com/watch?v=_N5_qstuFQU
