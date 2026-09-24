# Konrad Körding × Leonard Schmedding Interview

Prof. Dr. Konrad Körding · [Penn Integrates Knowledge Professor](https://en.wikipedia.org/wiki/Penn_Integrates_Knowledge) an der [University of Pennsylvania](https://www.upenn.edu/) · [@everlastai](https://www.youtube.com/@everlastai) · 2026-07-07 · 63 Min · Deutsch · [YouTube](https://www.youtube.com/watch?v=lqwJza-EBiY)

[Konrad Körding](https://en.wikipedia.org/wiki/Konrad_Kording) ist einer der einflussreichsten [Computational Neuroscientists](https://en.wikipedia.org/wiki/Computational_neuroscience) der Welt, Penn Integrates Knowledge Professor an der [University of Pennsylvania](https://www.upenn.edu/) und Codirektor des [CIFAR](https://cifar.ca/)-Programms „Learning in Machines and Brains", des Forschungsnetzwerks an der Schnittstelle von [künstlicher Intelligenz](https://de.wikipedia.org/wiki/K%C3%BCnstliche_Intelligenz) und [Neurowissenschaft](https://de.wikipedia.org/wiki/Neurowissenschaften), zu dessen Programm unter anderem auch [Geoffrey Hinton](https://en.wikipedia.org/wiki/Geoffrey_Hinton) gehört. Im Gespräch erklärt Körding, warum er seit November 2025 persönlich gegen die [KI-Blase](https://en.wikipedia.org/wiki/AI_boom) wettet, was hinter seinem Konzept der Intelligenz-Sättigung steckt (der Nutzen von Intelligenz sättigt, weil die physische Welt zum Bottleneck wird), warum [Roboter](https://en.wikipedia.org/wiki/Robot) sich wie Autos und nicht wie [LLMs](https://en.wikipedia.org/wiki/Large_language_model) verbilligen, und warum exponentielles Wachstum nichts Neues ist. Er erläutert sein berühmtes [Mikroprozessor-Paper](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005268) von 2017, das [Bayesian Brain](https://en.wikipedia.org/wiki/Bayesian_approaches_to_brain_function) aus seiner meistzitierten Arbeit mit [Daniel Wolpert](https://en.wikipedia.org/wiki/Daniel_Wolpert) (2004), die Idee, dass jede Zelle so etwas wie [Gradient Descent](https://en.wikipedia.org/wiki/Gradient_descent) betreibt, und seine skeptische Einordnung der digitalen [Fruchtfliege](https://en.wikipedia.org/wiki/Drosophila_melanogaster) von Eon Systems, an der er als Berater beteiligt war.

## Timestamps

- [00:00](https://www.youtube.com/watch?v=lqwJza-EBiY&t=0s) – Intro
- [02:59](https://www.youtube.com/watch?v=lqwJza-EBiY&t=179s) – Singularität oder Überschätzung?
- [03:23](https://www.youtube.com/watch?v=lqwJza-EBiY&t=203s) – Physische Welt vs. Intelligenz
- [06:52](https://www.youtube.com/watch?v=lqwJza-EBiY&t=412s) – Auswirkungen auf den Arbeitsmarkt
- [10:54](https://www.youtube.com/watch?v=lqwJza-EBiY&t=654s) – Können Roboter den Engpass lösen?
- [13:48](https://www.youtube.com/watch?v=lqwJza-EBiY&t=828s) – Exponentielles Wachstum – wirklich anders?
- [18:07](https://www.youtube.com/watch?v=lqwJza-EBiY&t=1087s) – Der Endpunkt der Optimierung
- [22:13](https://www.youtube.com/watch?v=lqwJza-EBiY&t=1333s) – Was bleibt dem Menschen?
- [24:55](https://www.youtube.com/watch?v=lqwJza-EBiY&t=1495s) – Das Mikroprozessor-Experiment
- [29:56](https://www.youtube.com/watch?v=lqwJza-EBiY&t=1796s) – Wie viel wissen wir über das Gehirn?
- [31:42](https://www.youtube.com/watch?v=lqwJza-EBiY&t=1902s) – Das Bayesian Brain
- [36:39](https://www.youtube.com/watch?v=lqwJza-EBiY&t=2199s) – Gradient Descent in jeder Zelle
- [41:56](https://www.youtube.com/watch?v=lqwJza-EBiY&t=2516s) – Sind LLMs wirklich intelligent?
- [51:15](https://www.youtube.com/watch?v=lqwJza-EBiY&t=3075s) – Die Fruchtfliege hochladen
- [58:17](https://www.youtube.com/watch?v=lqwJza-EBiY&t=3497s) – Die nächsten großen Durchbrüche

## Transcript

### 00:00 – Intro

**Leonard Schmedding**

Verbrennen [OpenAI](https://openai.com/), [Anthropic](https://www.anthropic.com/) und [Google](https://about.google/) gerade Hunderte Milliarden Dollar für eine massive ökonomische Überschätzung? Können wir ein Gehirn tatsächlich Neuron für Neuron nachbauen und am Ende hochladen? Und was ist eigentlich noch der Mensch, wenn auch jede einzelne Zelle im Körper so etwas wie Gradient Descent macht? Genau diesen Fragen stellt sich Professor Dr. Konrad Körding.

Professor Körding ist Penn Integrates Knowledge Professor an der [University of Pennsylvania](https://www.upenn.edu/), eine der prestigeträchtigsten Berufungen in den USA, die von der Universitätspräsidentin persönlich vergeben wird und nur an Wissenschaftler geht, deren Arbeit über mehrere Fakultäten hinweg integriert. Er ist gleichzeitig Codirektor des [CIFAR](https://cifar.ca/)-Programms „Learning in Machines and Brains", dem internationalen Forschungsnetzwerk, das die Brücke zwischen künstlicher Intelligenz und Neurowissenschaft wie kein zweites schlägt und zu dessen Programm in den vergangenen Jahren unter anderem auch [Geoffrey Hinton](https://en.wikipedia.org/wiki/Geoffrey_Hinton) gehört. Mit über 23.500 wissenschaftlichen Zitationen ist Körding einer der einflussreichsten Computational Neuroscientists der Welt. Gleichzeitig ist er Berater bei Eon Systems, der Firma, die die erste [Brain Emulation](https://en.wikipedia.org/wiki/Mind_uploading) einer [Fruchtfliege](https://en.wikipedia.org/wiki/Drosophila_melanogaster) veröffentlicht hat. Genau darüber und über vieles weitere werden wir gleich sprechen.

Falls du mich noch nicht kennst: mein Name ist Leonard Schmedding, und als Inhaber der führenden KI-Beratungs- und Implementierungsagentur [Everlast AI](https://www.youtube.com/@everlastai) habe ich in den letzten Jahren nicht nur über 2.100 mittelständische Unternehmen und Hidden Champions erfolgreich in Sachen KI beraten, sondern betreibe auch mehrere KI-Softwareunternehmen. Hier bei Everlast AI spreche ich regelmäßig mit den führenden Köpfen, Experten, Professoren und KI-Unternehmern aus meinem Netzwerk zu der wichtigsten technologischen Revolution dieses Jahrhunderts, mit dem Ziel, dass alle Zuschauer von Everlast AI der breiten Masse immer mindestens zwei, drei Schritte voraus sind. Wenn diese Gespräche für dich hilfreich sind und dich weiterbringen, dann ist die größte Unterstützung, wenn du dieses Video likest und deine Meinung in den Kommentaren teilst. Und nun springen wir rein in das Gespräch mit Konrad Körding.

### 02:59 – Singularität oder Überschätzung?

**Leonard Schmedding**

Konrad, wenn man die KI-Entwicklung der letzten Jahre verfolgt, dann hat man ja den Eindruck, die [Singularität](https://de.wikipedia.org/wiki/Technologische_Singularit%C3%A4t) steht kurz bevor oder wir stecken schon längst mittendrin. Du selbst bist Forscher, Neurowissenschaftler, beschäftigst dich seit jeher aber auch mit künstlicher Intelligenz. Doch du wettest seit November 2025 persönlich gegen den Markt. Warum sind wir noch nicht in der Singularität, und was übersieht der Markt aus deiner Perspektive?

### 03:23 – Physische Welt vs. Intelligenz

**Prof. Dr. Konrad Körding**

Aus meiner Sicht besteht die Welt aus zwei Teilen. Die Welt besteht aus physikalischen Sachen, aus echten Dingen. Stell dir vor, du hast eine Schaufel, ein Auto, einen Zug, eine Straße. Das sind die physikalischen Sachen. Und dann besteht sie aus Intelligenz. Das sind wir, die Leute, die dasitzen und Sachen machen, und eben auch die Computer, die laufen und Sachen kontrollieren.

Ursprünglich bin ich ein Bewegungsforscher, das heißt, ich habe mich ganz viel gefragt, wie wir unseren Körper benutzen, wie wir Sachen in der Welt machen, indem wir unseren Körper benutzen. Und da gibt es immer eine Beschränkung: unser Körper ist halt unser Körper. Ich kann dich nicht fragen, kannst du mal eine Tonne von hier nach dort tragen? Dann sagt dein Körper: nein, das kann ich nicht, weil du vielleicht nicht stark genug dafür bist. Mein Startpunkt ist also: wenn ich über Körper nachdenke, gibt es eine Limitierung, die kommt daher, dass wir nicht unendlich stark sind, und eine andere Limitierung, dass wir nicht unendlich intelligent sind. Und diese beiden Typen, wie stark wir in unseren Effektoren sind, also was unsere physische Fähigkeit ist, mit der Welt zu interagieren, ist eine unabhängige Achse davon, was unsere Intelligenz ist.

**Leonard Schmedding**

Genau. Dazu hast du dann im November ein Paper veröffentlicht, gemeinsam mit deiner Frau, und ihr habt den Begriff Intelligenz-Saturierung, also Sättigung, eingeführt. Also dass der Nutzen von Intelligenz sättigt, wie du es gerade schon angedeutet hast, weil die physische Welt das größte Bottleneck wird. Kannst du das noch näher erläutern? Wieso sättigt der Nutzen von Intelligenz in der physischen Welt?

**Prof. Dr. Konrad Körding**

Stell dir vor, ich gebe dir die Aufgabe, die Erde aus deinem Garten in ein Auto zu bringen. Du gräbst sie auf, bringst sie ins Auto. Ich gebe dir jetzt deinen Körper und ganz wenig Intelligenz. Dann bist du nicht gut darin, das zu planen. Du buddelst ein bisschen, bewegst dich häufig in die falsche Richtung, und die Erde braucht ewig, bis sie im Auto ist. Jetzt mache ich dich ein bisschen intelligenter. Dann trägst du die Erde zu deinem Auto und wirfst sie hinein, Schaufel um Schaufel, und machst es ungefähr richtig. Jetzt mache ich dich unendlich intelligent. Dann findest du den perfekten Weg, die Erde zu transportieren, und den perfekten Weg, deine Hand zu bewegen. Aber du bist immer noch nicht unendlich schnell. Du musst immer noch deinen Körper bewegen, und es gibt physikalische Gesetze: du kannst dich nicht schneller als die [Lichtgeschwindigkeit](https://de.wikipedia.org/wiki/Lichtgeschwindigkeit) bewegen, und dein Körper hat eine gewisse Maximalstärke.

Intelligenz-Saturierung ist eben das: egal welche Aufgabe du dir denkst, die von Menschen oder von Maschinen gelöst wird, mit mehr Intelligenz wirst du besser, aber mit unendlicher Intelligenz wirst du nicht besser als irgendein Grenzwert. Das ist das, was wir den Sättigungswert nennen. Und je intelligenter du bist, umso näher kommst du an deinen Sättigungswert heran.

### 06:52 – Auswirkungen auf den Arbeitsmarkt

**Leonard Schmedding**

Die große Frage ist ja, was die Implikationen daraus konkret für den Arbeitsmarkt sind, auch von künstlicher Intelligenz. Du beschreibst einen hump-shaped, also buckelförmigen Lohnverlauf: erst steigen die Löhne durch die gestiegene Produktivität, dann fallen sie wieder, weil Menschen aus kognitiver Arbeit immer mehr in die physischen Sektoren gedrängt werden und dort die Aufnahmekapazität letztlich begrenzt ist. Was ist hier der konkrete Kipppunkt? Was muss passieren, damit KI kein reines Produktivitätswerkzeug mehr ist, sondern der Mensch vom Computer immer weiter in die physische Arbeitswelt gedrängt wird?

**Prof. Dr. Konrad Körding**

In dem Paper, über das du redest, denken wir darüber nach, wie Menschen und Kapital sich in einem System bewegen. Es gibt jetzt mehr und mehr künstliche Intelligenz. Und was tut die? Das erste ist: wenn du ein bisschen künstliche Intelligenz zu einem Menschen gibst, hilft sie ihm. Nimm [Google Search](https://www.google.com/): wenn ich dir Google Search gebe, bist du besser darin, Forschung zu machen, als ohne. Das heißt, erst einmal macht es dich effizienter, und da gibt es eine Synergie. Wenn du ein bisschen künstliche Intelligenz zu einem Menschen gibst, wird der Mensch effizienter.

Das Gleiche gilt in der physischen Dimension. Stell dir vor, mein Job ist, im Garten zu arbeiten. Und dann gibt es eine Webseite, die mir lauter Tricks sagt, wie ich den Garten effizienter bearbeiten kann. Mein Job ist ein physischer Job, ich löse ein Problem im Garten, und wenn du mir mehr Intelligenz gibst, bin ich besser darin. Das heißt, ich als physischer Arbeiter werde erst einmal effizienter, und jemand wird mir mehr zahlen wollen.

Und dann kannst du fragen, was innerhalb der Intelligenz-Jobs passiert. Es gibt Leute, die machen Podcasts, das ist im Prinzip ein Intelligenz-Job. Erst einmal, wenn mehr Intelligenz kommt, werden die effizienter. Aber dann kannst du sagen: wenn die KI gut genug wird, dann braucht sie dich vielleicht nicht mehr für einen Intelligenz-Job. Vielleicht kann sie eines Tages meinen Artikel genauso gut schreiben wie ich. Dann verdrängt sie mich gewissermaßen aus meinem Intelligenz-Job. Aber ich habe als Professor auch einen physischen Job. Ich stehe vor den Studenten, bewege mich, und mein Vortrag ist viel interessanter, weil ich ein Mensch bin, der vor ihnen steht. Du kannst mich nicht einfach ersetzen. Auch im Professor-Sein gibt es die physische Dimension, meinen Körper vor den Studenten, und die Intelligenz-Dimension, was ich denn sage. Die Idee von unserem Paper ist: selbst wenn Intelligenz über Nacht unendlich gut werden würde, alle Intelligenzprobleme sofort gelöst wären, sind wir immer noch dadurch limitiert, dass wir physische Mittel brauchen, um aus der Intelligenz etwas Wertvolles zu machen.

**Leonard Schmedding**

Das ist ja genau die konkrete Schlussfolgerung: dass KI einen abnehmenden Grenznutzen in Bezug auf konkrete Aufgaben hat, genau wie du es erklärt hast, weil sie durch die physische Welt immer limitiert ist.

### 10:54 – Können Roboter den Engpass lösen?

**Leonard Schmedding**

Die naive Gegenfrage, die man sich jetzt stellen könnte, wäre: was ist denn, wenn KI durch Roboter die physische Welt selbst betritt? Würde das diesen Engpass dann nicht lösen, oder verschiebt sich der Engpass dann nur?

**Prof. Dr. Konrad Körding**

Das ist immer die Frage, die die Leute stellen. Ein Roboter ist zwei Sachen. Das ist das Roboterhirn, das vielleicht unendlich gut wird, was weiß ich. Es ist aber eben auch der Roboterkörper, und der Roboterkörper hat, wenn man darüber nachdenkt, Gelenke und Stahlstreben und Getriebe und so weiter. Wenn du dir anschaust, wie die künstliche Intelligenz besser wird: wenn du Tokens kaufst, wenn du LLMs benutzt, dann werden die billiger. Jedes Jahr werden die Faktor vier billiger oder so, unglaublich schnell, wie sich die künstliche Intelligenz fortbewegt. Aber wenn du dir die Roboter anschaust, ist das überhaupt nicht so. Die Industrieroboter kosteten vielleicht mal 100.000 Dollar, jetzt kosten sie vielleicht 30.000 Dollar. Aber das braucht eine lange Zeit, und Roboter werden eben billiger, so wie alle Sachen in der physischen Welt billiger werden.

Wenn du ein Minenfahrzeug haben willst, das in der Mine arbeitet, das wird billiger, aber nur ein ganz kleines bisschen. Und wenn du dir die Autos anguckst: klar sind die billiger geworden seit der Zeit von [Ford](https://www.ford.com/), aber in Wirklichkeit sind sie teurer geworden, weil wir jetzt viel mehr in Autos einbauen. Selbst wenn wir ein Auto bauen wollten, das so einfach ist wie das von Ford, wäre das nicht kostenlos. Wenn Autos sich entwickeln würden wie künstliche Intelligenz, könntest du jetzt ein Auto für 50 Cent oder 5 Cent kaufen. Aber in Wirklichkeit kannst du eben kein Auto für 5 Cent kaufen, sondern das billige Auto kostet immer noch 5.000, 10.000. Das heißt: die Roboter sind so wie die Autos, die Roboter sind nicht so wie die künstliche Intelligenz.

Für einen Roboter brauchen wir unsere langen Supply Chains. Wir brauchen eine Straße, wir brauchen eine Mine, wir brauchen eine Fabrik, wo aus dem Eisen dann Stahl gemacht wird, und so weiter und so fort. Auf diese Weise limitieren die physikalischen Gesetze die physische Welt auf eine Art, wie nichts die künstliche Intelligenz limitiert.

### 13:48 – Exponentielles Wachstum – wirklich anders?

**Leonard Schmedding**

Das macht absolut Sinn, dass es am Ende immer limitierende Faktoren gibt, aktuell wahrscheinlich vor allem Energie. Mir stellt sich hier noch die Frage nach deinem Zeithorizont, weil zum Beispiel [Solar](https://de.wikipedia.org/wiki/Photovoltaik) sich heute schon exponentiell entwickelt, [Kernfusion](https://de.wikipedia.org/wiki/Kernfusion) bevorsteht, und manch einer sagt, dass durch die KI auch die Durchbrüche in der physischen Welt exponentiell beschleunigt werden. Deswegen frage ich mich: was ist der Zeithorizont, den du hier siehst? Könnte es irgendwann einen Punkt geben, ab dem die physische Welt diese Intelligenz-Explosion nicht mehr limitiert, oder wird es immer wieder so einen limitierenden Faktor geben?

**Prof. Dr. Konrad Körding**

Ich glaube, es wird immer Faktoren geben, aber lass uns erst einmal über exponentiell reden. Wir haben das Gefühl, dass, wenn Sachen exponentiell sind, es irgendwie eine Singularität gibt, weil es immer schneller wird. Das erste, was wichtig ist zu wissen: exponentielles Wachstum gibt es schon immer. In den Zeiten der Römer gab es exponentielles Wachstum. Wo kommt das her, das exponentielle Wachstum zur Zeit der Römer? Die haben angefangen, Straßen zu bauen. Wenn du in einer Welt bist, wo es keine Straßen gibt, kannst du nicht viel Reichtum aufbauen, weil du ihn nicht transportieren kannst. Die Römer haben das geändert. Exponentiell ist also nichts Problematisches. Exponentiell ist schon immer gewesen, exponentiell wird immer sein. Die Frage ist eher, wie schnell es exponentiell ist.

Der Aktienmarkt zum Beispiel ist exponentiell. Seit 70 Jahren werden Aktien exponentiell mehr wert, und der Zeitraum ist vielleicht so, dass es sich alle 7 Jahre verdoppelt. Die Frage ist jetzt: wenn es von einer Verdopplung alle 7 Jahre zu einer Verdopplung von heute bis morgen wird, dann fühlt es sich an wie eine Singularität. Wenn es von 7 Jahren zu 6 Jahren wird, toll, die Welt wird besser, und sie wird schneller besser, besseres Essen, bessere Häuser, mehr Skifahren. Wenn es von 7 Jahren Verdopplungszeit auf ein Jahr geht, dann ändert sich die Welt so schnell, dass es für uns schwierig wird, darin zu leben. Ich denke, das Argument, das wir machen wollen, ist: es geht nicht von 7 Jahren auf 6 Monate. Wenn es von 7 Jahren auf 6 oder 5 Jahre geht, das wäre revolutionär, die Welt wäre viel schneller als vorher, aber nicht revolutionär schneller, es ist bloß schneller.

Und jetzt schau dir die Sachen an, die die Leute bauen. Was tun wir denn in unserer Ökonomie? Wir bauen Häuser. Kannst du ein Haus viel schneller bauen mit mehr Intelligenz? Eher nicht. Solarzellen, ja, die sind schnell exponentiell, aber Solarzellen verdoppeln sich alle paar Jahre, und das ist das Schnellste. Sobald wir viele Solarzellen gebaut haben, ist das nicht mehr der Rate-Limiting-Faktor. Es gibt immer irgendetwas, was das Schwierigste ist. Irgendwann, wenn wir viel Solarstrom haben, wollen wir Plastik machen, und dann wird das das Schwierige, wir müssen es aus der Luft herausziehen und Plastik daraus machen. Egal welches Problem wir lösen, es gibt immer das nächste Problem, und das limitiert die Geschwindigkeit, mit der wir etwas machen können.

### 18:07 – Der Endpunkt der Optimierung

**Leonard Schmedding**

Es wird ja auf ein Ideal hin optimiert, in dem Fall ein makroökonomisches Ideal. Ich hatte beispielsweise mit Professor [Marcus Hutter](https://en.wikipedia.org/wiki/Marcus_Hutter) gesprochen, der mit seinem [AIXI](https://en.wikipedia.org/wiki/AIXI)-Modell zeigt, wie das theoretische Superintelligenz-Ideal immer besser approximiert werden kann. Die meisten Menschen stellen sich aber eher eine relativ binäre Frage: ab wann ist KI in meinem wirtschaftlich relevanten Bereich besser als ich? Sobald sie das ist, ist alles, was danach kommt, erst einmal abstrakt. Das ist für die meisten der Endpunkt der Durchbrüche. Was ist es für dich? Woraufhin wird eigentlich noch optimiert oder skaliert, oder gibt es da gar kein Ende?

**Prof. Dr. Konrad Körding**

Für mich gibt es da kein Ende, und der Grund ist folgender. Nimm deinen Job. Du kannst sagen, im Prinzip ist dein Job so online und so digital, wie es nur sein kann. Es ist quasi ein Video, das von dir auf meinen Bildschirm geht, ich schaue es mir an, alles digital auf meiner Seite. Aber in Wirklichkeit gibt es dich als Person, als physikalischen Körper, und ohne den funktioniert es nicht. Ich will mir keinen roboter-generierten Agenten angucken. Du kannst als Person zu jemandem gehen, mit jemandem reden, der kann mit dir in dein Studio gehen, der nimmt dich ernst, weil du ein Mensch bist. Das ist nicht etwas, was KI uns wegnehmen kann.

Ich weiß nicht, wie das in Deutschland war, aber in Amerika gab es mehr als ein Jahr lang keine Schule während der [Pandemie](https://de.wikipedia.org/wiki/COVID-19-Pandemie). Und ich muss sagen: meine Kinder, ich habe drei davon, haben in dem Jahr nicht viel gelernt. Warum ist das so? Du brauchst die physische Dimension, du musst in einem Zimmer sein. Ich gehe nicht mit der KI ein Bier trinken, aber mit meinen Freunden tue ich das. Ein KI-System kann nicht mit dir konkurrieren, weil du Freunde hast, die mit dir vor dein Mikrofon gehen, auch wenn niemand anders das machen möchte. Und wir geben anderen Menschen ein Standing. Wir sagen quasi, eine andere Person hat ein Recht zu reden, weil sie eine Person ist. Das Recht, das ich einer Person gebe, gebe ich nicht der KI. Und wenn du eine KI wärst, hätte ich nicht Ja gesagt, mich jetzt hier mit dir zu unterhalten.

### 22:13 – Was bleibt dem Menschen?

**Leonard Schmedding**

Um das noch einmal festzuhalten: das ist im Kern die Conclusion aus der Untersuchung, dass die Arbeit hinterm Bildschirm immer mehr in die physische Welt drängen wird. Also dass wir wieder mehr persönliche Beziehung suchen werden oder Leute eher wieder physischer Arbeit nachgehen werden. Aber du stellst schon fest, dass es bei der Arbeit hinterm Bildschirm, bei der Büroarbeit, diesen Kipppunkt gibt, und dadurch das Angebot an Arbeit immer mehr in die physische Arbeit drängen würde. Das wäre so die konkrete Konklusion?

**Prof. Dr. Konrad Körding**

Ein bisschen, aber es gibt Sachen, die quasi so sind wie ein Körper, aber nicht wirklich ein Körper sind. Du kannst zum Beispiel sagen, ein Mensch ist verantwortlich für etwas. Wenn ich Sicherheit haben möchte und ich habe jemanden, der für mich arbeitet, kann ich dem in gewissem Sinne vertrauen, in einer Weise, wie ich der KI nicht vertrauen kann. Denn die KI kann nicht ins Gefängnis geworfen werden, wenn sie etwas falsch macht, ein Mensch kann das. In der Hinsicht gibt es Sachen, die sind nicht wirklich physisch, aber ähnlich: es geht um Menschen und Attention und Responsibility, jemand ist verantwortlich. Auch das ist eine von den Sachen, die wir den Menschen nicht wegnehmen können. Am Ende ist ein Mensch jemand, den du anzeigen und mit dem du vor Gericht gehen kannst. Das kannst du nicht mit einer Maschine machen.

**Leonard Schmedding**

Das wäre natürlich auch noch einmal eine Diskussion für dich. Das wird ja zum Teil diskutiert, ob es so etwas wie eine elektronische Person irgendwann geben sollte oder dürfte. Aber ich würde gerne zunächst auf deine zentrale Aufgabe zu sprechen kommen. Du bist Computational Neuroscientist. Kannst du das zunächst erklären? Was genau ist die Aufgabe eines Computational Neuroscientist, mit welchen Fragestellungen beschäftigst du dich am meisten?

**Prof. Dr. Konrad Körding**

Ich würde jetzt sagen, ich bin ein Gehirnforscher, das ist mein Ziel. Ich würde gerne verstehen, wie das menschliche Gehirn funktioniert, ich würde gerne in der Lage sein, Teile davon nachzubauen, und ich würde gerne verstehen, was Intelligenz ist. Als Computational Neuroscientist heißt das bloß, dass ich dafür Computer und Mathematik benutze. Ich möchte zum Verstehen des Gehirns Ideen benutzen, die sagen, wie dein Gehirn funktioniert, ist ein bisschen so, wie sich ein Computer verhält. Ich benutze Ideen aus der Computerwissenschaft, der Mathematik, der Physik, ich bin ursprünglich Physiker, um zu verstehen, wie wir denken.

### 24:55 – Das Mikroprozessor-Experiment

**Leonard Schmedding**

Du hast 2017 ein berühmtes Paper unter anderem dazu veröffentlicht, also ob ein reiner Neurowissenschaftler einen [Mikroprozessor](https://en.wikipedia.org/wiki/Microprocessor) verstehen könnte. Ihr habt dabei einen alten Prozessor genommen, den Chip aus dem [Apple II](https://en.wikipedia.org/wiki/Apple_II) und [Commodore 64](https://en.wikipedia.org/wiki/Commodore_64), und die Standardmethoden der Neurowissenschaft darauf geworfen. Kannst du das näher erläutern? Was habt ihr da gemacht, und was war die zentrale Erkenntnis daraus?

**Prof. Dr. Konrad Körding**

Lass mich erst einmal kurz herauszoomen. Die Rolle, die ich in der Computational Neuroscience oder allgemein in der Neurowissenschaft habe, ist häufig die eines positiven Skeptikers des Feldes. Ich bin der Meinung, dass man, damit ein wissenschaftliches Feld gut ist, immer ein bisschen nachprüfen muss, ob die Logik auch funktioniert. Das Paper, über das du redest, versucht genau das.

Die Neurowissenschaftler haben eine gewisse Logik, die sie benutzen. Die Logik ist häufig: ich nehme Daten aus dem Gehirn und finde, dass die Daten eine gewisse Sache machen. Stell dir vor, ich stecke eine Elektrode in ein Gehirn, ein dünner Draht, der geht ins Gehirn hinein, über einen Amplifier zum Computer, und wann immer ich dir die Farbe Blau zeige, ist das Neuron, von dem wir unsere Daten bekommen, sehr aktiv, und wann immer ich dir nicht Blau zeige, ist es weniger aktiv. Das ist eine der Hauptweisen, mit der Neurowissenschaftler das Gehirn untersuchen. Das Problem ist: es ist einfach, dem Neuron Blau, Rot, Grün, Gelb zu zeigen, aber es ist unmöglich, das Neuron in allen Situationen zu testen, weil es zu viele Situationen gibt. Vielleicht ist das Neuron auch aktiv, wenn ich ihm die Fragestellung über die existentielle Bedeutung des Menschen zeige. Das weiß ich aber nicht, weil ich in meinem Experiment bloß Blau, Rot, Gelb, Grün zeige. Aber die Logik der Neurowissenschaft ist dann zu sagen: schau mal, ich habe dem zehn Farben gezeigt, und es ist viel aktiver, wenn ich Blau zeige, als bei Rot oder Orange, deswegen ist die Rolle dieses Neurons im Denken, dass es uns sagt: Blau.

Wenn du ein bisschen tiefer nachdenkst, ist „Blau sagen" ein bisschen sinnlos. In der Welt gibt es viele Sachen, die blau sind. Ich will nicht bloß wissen, Konrad ist blau, sondern ich will sagen: Konrad, dein Haar ist blau. Die Idee, dass das Neuron etwas ganz Einfaches machen kann, nämlich sagen, ob Blau da ist oder nicht, macht in gewissem Sinne keinen Sinn.

Jetzt zu dem Paper. Was wir gemacht haben: wir haben genau die gleichen Experimente gemacht, aber in einem Mikroprozessor. Wir nehmen einen Mikroprozessor in einem ganz einfachen Computer, und auf dem spielen wir [Donkey Kong](https://en.wikipedia.org/wiki/Donkey_Kong_(1981_video_game)). Jetzt nehmen wir die Aktivität von einem Transistor und spielen das gleiche Spiel, das die Neurowissenschaftler machen. Da haben wir Transistoren gefunden, die an sind, wenn der letzte Punkt auf dem Bildschirm hell ist, und aus, wenn er dunkel ist. Die alten Computer malen den Bildschirm Punkt für Punkt, fangen oben links an und sind unten rechts fertig. Wenn ein Neurowissenschaftler diese Daten sehen würde, würde er sagen: Hurra, wir haben den Hell-versus-Dunkel-Transistor gefunden.

Aber in Wirklichkeit gibt es den Hell-versus-Dunkel-Transistor nicht. Das Gute am Mikroprozessor ist ja, dass wir wissen, wie er funktioniert. Wenn wir uns das angucken, ist das der Punkt, der sagt, ob die Variable Nummer 3 größer ist als 128. Das hat nichts zu tun mit hell versus dunkel, es hat aber im Kontext von „wir spielen Donkey Kong" damit zu tun, dass die Variable größer als 128 ist, wenn es ein heller Punkt ist. Es hat nichts damit zu tun, wie der Mikroprozessor funktioniert, es hat alles damit zu tun, wie das spezifische Spiel funktioniert. Und das ist eine Kritik an der Logik, die die Neurowissenschaftler benutzen.

### 29:56 – Wie viel wissen wir über das Gehirn?

**Leonard Schmedding**

Dazu habe ich einige Folgefragen, da werden wir gleich tiefer einsteigen. Zunächst würde mich deine übergeordnete Einschätzung interessieren. Wie viel weiß die Neurowissenschaft schon, wenn man das quantifizieren kann, oder auch nur als persönliche Einschätzung? Wie viel wissen wir denn schon darüber, wie das Gehirn wirklich funktioniert?

**Prof. Dr. Konrad Körding**

Ich will zwei Teile davon trennen. Es gibt den Mikromechanismus, den verstehen wir sehr gut. Wir wissen, das Gehirn ist aus [Nervenzellen](https://de.wikipedia.org/wiki/Nervenzelle) gebaut. Wir wissen, zwischen den Nervenzellen gibt es [Synapsen](https://de.wikipedia.org/wiki/Synapse). Wenn eine Nervenzelle aktiv ist, geht das Signal das sogenannte [Axon](https://de.wikipedia.org/wiki/Axon) entlang bis zur Synapse. An der Synapse haben wir einen chemischen Prozess, gewisse Chemikalien werden aus der Zelle herausgeworfen, die nächste Zelle sieht diese Chemikalien und macht daraus ein elektrisches Signal, und so weiter. Wenn wir uns den kleinen Mechanismus angucken, verstehen wir den extrem gut.

Wenn wir jetzt fragen, wie kommt es, dass Konrad und Leonard miteinander reden, verstehen wir das ganz, ganz schlecht. Warum ist das so? Unser Gehirn hat 86 Milliarden Nervenzellen, die haben ungefähr 10 hoch 15 Verbindungen, Synapsen, miteinander, und wir sehen den Wald vor lauter Bäumen nicht. Wir wissen quasi, dass Bäume existieren, aber wir sehen den Wald überhaupt nicht, weil es viel zu viele Parameter sind. Wir als Menschen verstehen das nicht.

### 31:42 – Das Bayesian Brain

**Leonard Schmedding**

Um da den Bogen zu deiner Arbeit als Computational Neuroscientist und natürlich auch zur KI zu schlagen: 2004 schon hast du das meistzitierte Paper mit [Daniel Wolpert](https://en.wikipedia.org/wiki/Daniel_Wolpert) veröffentlicht. Ihr habt darin das [Bayesian Brain](https://en.wikipedia.org/wiki/Bayesian_approaches_to_brain_function) etabliert. Kannst du das näher erläutern, weil das für meine Begriffe unmittelbare Konsequenzen auf das hat, was wir gerade in der KI-Forschung sehen?

**Prof. Dr. Konrad Körding**

Wie in vielen wissenschaftlichen Disziplinen gibt es eine lange intellektuelle Tradition, viele dieser Ideen gab es übrigens schon im 11. Jahrhundert bei [Alhazen](https://de.wikipedia.org/wiki/Ibn_al-Haytham), dem berühmten Optiker. Was wir gezeigt haben, ist: im menschlichen Verhalten gibt es immer zwei Faktoren, die relevant sind. Es gibt mein Hintergrundwissen, das nennen wir als Statistiker den [Prior](https://de.wikipedia.org/wiki/A-priori-Wahrscheinlichkeit), und dann gibt es das, was wir gerade im Moment wahrnehmen. Ich sehe dich, ich höre dich, das ist das, was ich im Moment wahrnehme, aber natürlich habe ich einen Hintergrund, wo ich Sachen weiß, ich weiß von deiner Arbeit und so weiter.

[Bayesianische Statistik](https://de.wikipedia.org/wiki/Bayessche_Statistik) ist jetzt Folgendes: es gibt immer Ambiguitäten, es gibt immer Unsicherheit. Wenn ich wissen will, was in der Welt ist, verbinde ich das, was ich schon vorher weiß, mein Hintergrundwissen, mit dem, was ich neu lerne. Und da gibt es die [Bayes-Regel](https://de.wikipedia.org/wiki/Satz_von_Bayes), die quantifiziert, wie genau wir das machen. Wir haben gezeigt, dass Menschen in ihrem Verhalten nah dran sind an dem, was statistisch optimal ist. Einfach gesagt: wir wissen intuitiv über die Unsicherheit Bescheid, die wir über die Welt haben. Du weißt, wie genau du was weißt, und wenn ich dir etwas Neues zeige, benutzt du das im Hintergrund dessen, wovon du schon ganz sicher bist und wovon du noch nicht ganz sicher bist.

Meine Forschungsrichtung war immer die Frage, wie die Leute das, was sie schon vorher wissen, mit den neuen Sachen integrieren, die sie lernen. Es gibt zwei Interpretationen davon. Die eine: das Gehirn ist kompliziert, das Lernen macht das richtig. Die andere: weil Unsicherheit so wichtig ist, ist das Gehirn gewissermaßen eine Unsicherheitsmaschine, wir sind quasi gebaut, um uns über Unsicherheit zu unterhalten. Diese beiden Interpretationen sind verschieden. In der ersten weiß ich nicht, wie das Gehirn gebaut ist, ich weiß bloß, dass es gut mit Unsicherheit umgeht. Ein Gehirn, das lernen kann, wird selbstverständlich auch lernen, gut zu sein, wenn wir in einer Welt sind, in der wir Unsicherheit haben. Die Interpretation, die ich meiner Arbeit gebe, ist bloß: die Menschen sind gut mit Unsicherheit, und das Gehirn kann offensichtlich lernen. Ich gehe nicht den Schritt zu dem Feld, das sich jetzt Bayesian Brain nennt, wo sie sagen, deswegen ist das Gehirn eine Unsicherheitsmaschine. Wenn das Gehirn eine Lernmaschine ist, eine Idee, die mir philosophisch viel näher ist als die Unsicherheitsmaschine, dann wird das Gehirn lernen, sich so zu verhalten wie eine Unsicherheitsmaschine, weil wir in einer Welt sind, in der es viel Unsicherheit gibt, und im Verhalten kannst du den Unterschied gar nicht mehr sehen.

### 36:39 – Gradient Descent in jeder Zelle

**Leonard Schmedding**

Du gehst sogar noch einen Schritt weiter und beziehst das Ganze nicht nur auf das Gehirn, sondern sagst, dass im Kern jede Zelle so etwas macht wie Gradient Descent. Das ist ja eine fundamentale Erkenntnis, dass das Lernen nicht nur Neuronen und dem Gehirn vorbehalten ist. Kannst du das näher erläutern und auch, was die Implikationen daraus sind, für uns wie auch für die KI-Forschung?

**Prof. Dr. Konrad Körding**

Aus meiner Sicht ist es die Weise, wie wir die Welt am besten verstehen in den Gegenden, wo es interessant ist. Da waren jetzt viele komplizierte Wörter dabei, lass uns die ein bisschen aufteilen. Die zentrale Idee ist [Gradient Descent](https://en.wikipedia.org/wiki/Gradient_descent). Klingt kompliziert, es gibt auch komplizierte Mathematik dazu, aber das Prinzip ist ganz einfach. In unserem Gehirn gibt es ganz viele Variablen, wie stark die Neurone sich beeinflussen und so weiter. Die Idee von Gradient Descent ist bloß: soweit möglich sollen sich alle Variablen in die richtige Richtung bewegen.

Ich benutze gerne Firmen, um über Gradient Descent nachzudenken. Stell dir vor, du bist eine Firma, ein Café, und du bist der Manager. Jemand macht den Kaffee, jemand bringt den Kaffee zu den Leuten. Jetzt geht irgendetwas schief, die Leute an Tisch fünf warten zu lange auf ihren Kaffee. Was willst du machen? Du willst herausfinden, was das Problem ist, und dann die Parameter davon in die richtige Richtung bewegen. Vielleicht ist die Weise, wie wir Bestellungen aufschreiben, nicht gut. In deinem Café hast du vielleicht Hunderte Parameter: wie schreibst du die Bestellung auf, wie bringst du den Kaffee zum Tisch, wie sorgst du dafür, dass der Kaffee noch warm ist, wenn er zum Tisch kommt? Die Idee vom Gradient Descent ist, alle Parameter zu nehmen und sie in die richtige Richtung zu bewegen. Nicht fertig machen, nicht perfekt machen, sondern bloß ein bisschen in die richtige Richtung.

Diese Idee, alles ein bisschen in die richtige Richtung zu bewegen, siehst du überall. Du siehst sie in der Firma, in deinem eigenen Verhalten in deinem Leben, was kann ich nächstes Mal besser machen, und du siehst sie im Bakterium, das herauskriegen kann, was es anders machen könnte, damit es nächstes Mal keinen Hunger hat. Und du siehst sie im Gehirn. Im Gehirn ist es ganz besonders wichtig, weil du 86 Milliarden Nervenzellen hast, die alle irgendwie herauskriegen müssen: hätte ich jetzt aktiver oder weniger aktiv sein sollen? Die Idee von Gradient Descent ist bloß: wir brauchen einen Algorithmus, der herausfindet, wer es gut gemacht hat und wer es verbockt hat, und dann machen wir von den Sachen, die es gut gemacht haben, mehr und von den Sachen, die schlecht gelaufen sind, weniger. In einem großen System können wir nicht sagen, das war dein Fehler, in Wirklichkeit hätten all die Sachen ein bisschen besser sein können. Gradient Descent ist eben das Prinzip: alle Sachen ein bisschen besser machen.

**Leonard Schmedding**

Und das ist ja im Kern auch das, was die KI-Forschung und moderne LLMs mit [Backpropagation](https://en.wikipedia.org/wiki/Backpropagation) machen. Deswegen sage ich, es ist im Wesentlichen eine fundamentale Erkenntnis, weil es Leute gibt, die sagen, das reiche im Zweifel nicht, oder Menschen machen noch etwas fundamental ganz anderes. Das ist ja im Kern vergleichbar, oder?

**Prof. Dr. Konrad Körding**

Die Menschen machen ohne Frage noch viel fundamentalere Sachen, und die LLMs, die wir haben, machen auch fundamentalere Sachen. Aber der Backpropagation-Algorithmus, von dem du geredet hast, das ist ein ganz effizienter Algorithmus, der bloß etwas ganz Einfaches sagt: in einem neuronalen Netzwerk gibt es viele Milliarden Parameter, und der Backpropagation-Algorithmus findet bloß heraus, wenn wir den Parameter Nummer 1 größer machen, ist es besser oder schlechter, wenn wir Parameter Nummer 2 größer oder kleiner machen, ist es besser oder schlechter. Und dann nehmen wir all die Parameter, wo es besser wird, und machen sie ein bisschen größer, und all die, wo es schlechter wird, und machen sie ein bisschen kleiner. Das ist der Backpropagation-Algorithmus.

### 41:56 – Sind LLMs wirklich intelligent?

**Leonard Schmedding**

Da stellt sich immer die Frage: sind die heutigen LLMs, die wir sehen, wirklich intelligent? Das ist ja immer eine hitzige Diskussion, und Kritiker sagen gern, im Kern seien es [stochastische Papageien](https://en.wikipedia.org/wiki/Stochastic_parrot). Mich interessiert zunächst die naive Frage: inwiefern sind LLMs vergleichbar mit dem, was wir machen oder was das Gehirn macht? Man könnte ja auch argumentieren, dass wir Menschen im Kern auch nicht großartig viel anders machen. Was ist deine Einordnung dazu?

**Prof. Dr. Konrad Körding**

Ich glaube, es ist eine falsche Frage. Lass uns über die Sachen sprechen, die die LLMs so wie Menschen machen. Ich gebe dir einen Satz und sage: kannst du die Grammatikfehler hier korrigieren? Und die LLMs machen das wahrscheinlich besser als du. Das ist nicht böse gemeint, aber sie sind ziemlich gut darin, nicht zu übersehen, dass das dritte Komma nicht ganz korrekt ist. Computer sind auch schon ganz lange besser darin, seit 100 Jahren sind sie besser als wir Menschen darin, zwei Zahlen miteinander zu multiplizieren. Die Tatsache, dass sie in gewissem Sinne besser sind, kann man nicht bezweifeln. Wenn die Aufgabe ist, mach mir eine Liste von allen Personen in [Hamlet](https://de.wikipedia.org/wiki/Hamlet) von [Shakespeare](https://de.wikipedia.org/wiki/William_Shakespeare), macht das die KI wahrscheinlich besser als ich, weil ich irgendwen vergesse. Viele Sachen, die wir Intelligenz genannt haben, machen die besser als wir. Die Frage, ob es Sachen gibt, die LLMs machen können, die wir Intelligenz genannt haben, die Antwort ist ja, keine Frage.

Wenn ich dich vor 30 Jahren gefragt hätte, sag mir 50 Sachen, die Teil der Intelligenz sind, dann hätten sich 30 davon so angehört wie Dinge, die die KI heute kann. Was wir auch sehen, ist: mehr und mehr von den Sachen, die wir als Intelligenz wahrgenommen haben, sind eher so wie große Zahlen miteinander zu multiplizieren, Kommas in den Satz zu machen, irgendwie doch mechanisch. Das wussten wir nicht, weil wir sie nicht hatten. Ich denke, die Idee ist eher, dass es eine Illusion gibt, die wirklich schlecht ist für uns Menschen, nämlich die Illusion, dass Intelligenz eine Achse ist. Warum glauben wir, dass Intelligenz eine Achse ist? Weil es für Menschen ganz korreliert ist. Du bist gut in Grammatik, du bist gut darin, dich mit mir über künstliche Intelligenz zu unterhalten, du hast wahrscheinlich eine Meinung zu Kunst und Literatur, hast Bücher gelesen und hast eine Gruppe von Freunden, die sich Sorgen über die Welt machen. Für Menschen sind all diese Sachen korreliert.

Die Art, wie wir Intelligenz traditionell definieren, [IQ](https://de.wikipedia.org/wiki/Intelligenzquotient), ist so definiert: wir nehmen alle Fragen, stellen sie den Leuten und projizieren die Antworten auf eine Achse. Wenn wir sie auf eine Achse projizieren, ist es nun einmal so, dass KI-Systeme wirklich sehr, sehr gut sind, weil sie bei vielen dieser Fragen so wie super intelligente Menschen sind. Aber super intelligente Menschen sind auch gut darin, große Zahlen zu multiplizieren, und niemand hat vor 5 Jahren gesagt: Moment mal, jetzt ist jedes Programm auf dem Computer intelligenter als Menschen, weil es größere Zahlen miteinander multiplizieren kann.

Je länger wir an KI arbeiten, umso mehr sehen wir, dass die KI ganz anders ist als Menschen. Sie ist sehr gut in gewissen Sachen und nicht sehr gut in gewissen anderen. Was ich interessant finde, ist die Frage: wie finden wir heraus, welche Sachen Menschen gut können und welche die KI, und dann arbeiten wir mit der KI zusammen. Menschen sind schon immer gut, weil sie einen Körper und Hände haben und Sachen damit machen können. Aber das geht weiter, selbst in der Intelligenz. Menschen wissen, was es für sie heißt, dass die Welt gut ist, das ist eine Sache, die ein Computer nie für uns lösen wird.

**Leonard Schmedding**

Um noch einmal auf die Eingangsdebatte und die Fragestellung zurückzukommen, ab wann KI-Systeme so weit sind, dass sie die wirtschaftlich relevanten Aufgaben hinterm Bildschirm erledigen können: das ist für viele die [AGI](https://de.wikipedia.org/wiki/K%C3%BCnstliche_allgemeine_Intelligenz), oder bei [Google DeepMind](https://deepmind.google/) nennen sie es die Mini-AGI-Definition, 90 Prozent aller wirtschaftlich relevanten Tätigkeiten zu lösen. Die Frage, die da mitschwingt: reichen LLMs mit ein paar Werkzeugen im Zweifel für diese Zielsetzung, auch wenn wir verstehen, dass es noch viele Bereiche gibt, in denen wir Menschen anders oder intelligenter sind? Reicht das aus, oder braucht es dafür schon wieder fundamental andere Ansätze? Du hast ja schon genannt, dass so etwas wie Bewegung entscheidend sein könnte, das würde wieder für [Physical AI](https://en.wikipedia.org/wiki/Embodied_cognition) oder humanoide Roboter sprechen. Was ist deine Einordnung dazu?

**Prof. Dr. Konrad Körding**

Da höre ich mehrere Fragen. Das erste: in gewissem Sinne haben wir jetzt schon super intelligente KI-Systeme. Ich weiß nicht, wie du das machst, aber für mich ist KI Teil meines Alltags. Ich benutze KI für alles: um meine Urlaube zu planen, um meine E-Mails an den Direktor von meinem Programm freundlich zu machen, um meine Papers zu fact-checken. Für ganz viele Sachen ist KI inzwischen besser als die meisten Menschen. In gewissem Sinne ist es also schon passiert, aber in gewissem Sinne passiert auch etwas ganz anderes.

Ich bin dabei, ein Lehrbuch zu schreiben, das den Leuten KI und Gehirnwissenschaft als ein gemeinsames Buch beibringt. Für das Buch benutze ich KI für viele Sachen, die ich in der Vergangenheit nicht gemacht hätte. Ich frage zum Beispiel: das Paper, das ich zitiere, ist das überhaupt das beste mögliche Paper? Warum brauche ich die KI dafür? Weil ich es nicht selbst machen kann. Wir haben Hunderte Zitate, ich kann die nicht alle noch einmal nachlesen und schauen, ob es zehn andere gibt, die genauso gut oder besser sind. Aber ich kann sagen: geh mal durch die 500 davon und such bei jedem, ob es etwas Besseres gibt.

Aus meiner Sicht ist es eher so, dass durch diese künstliche Intelligenz von der Arbeit hinter dem Bildschirm, wie du sagst, in Zukunft viel mehr brauchen. Denn sobald KI da ist, wird unsere Toleranz dafür, dass hinter dem Bildschirm vielleicht nicht genug passiert, niedriger. Wir werden in Zukunft davon ausgehen, dass die Leute, die auf einem Podcast sind, sich selbstverständlich vorbereitet und alles gelesen haben, dass wir wissen, mit wem genau sie reden. Wir werden davon ausgehen, dass die Arbeit hinter dem Bildschirm viel besser ist, als sie jetzt ist. Auf einmal brauchen wir also viel mehr. Vielleicht werden wir uns mit anderen Menschen mehr treffen und über die großen Ideen reden.

Die Idee, dass wir, wenn wir Teile hinter dem Bildschirm automatisieren können, dann weniger Arbeit hinter dem Bildschirm brauchen, das ist nicht klar. Wenn ich dich produktiver mache, heißt das, dass du wertvoller bist, und wenn du wertvoller bist, will ich dir mehr zahlen und möchte, dass du mehr Stunden für mich arbeitest. Die genauen Dynamiken sind das Wichtige. Es ist eben nicht so, dass wir den Menschen durch die KI ersetzen. Es ist so, dass wir Teile des Menschen durch KI ersetzen und ihn dadurch produktiver machen. Um auf das Paper zurückzukommen: es gibt die Replacement-Dynamik im Intelligenz-Teil, aber es ist nicht klar, ob wir nicht in Wirklichkeit noch produktiver werden auf der Intelligenz-Seite, indem wir mit der künstlichen Intelligenz zusammenarbeiten, statt mit ihr in Konkurrenz zu stehen.

### 51:15 – Die Fruchtfliege hochladen

**Leonard Schmedding**

Ich möchte jetzt auf eine große Story der letzten Monate zu sprechen kommen, an der du unter anderem als Berater im Hintergrund von Eon Systems beteiligt warst, die den digitalen Zwilling einer Fruchtfliege veröffentlicht haben. Der CEO sagte selbst, wir haben eine Fruchtfliege geuploadet. Die Story ging relativ viral in den Kreisen. Kannst du das näher erklären, also was diese Forschung tatsächlich geleistet hat?

**Prof. Dr. Konrad Körding**

Lass uns erst einen Schritt zurückgehen zur Idee vom [Uploading](https://en.wikipedia.org/wiki/Mind_uploading). Das ist ein Staple der [Science-Fiction](https://de.wikipedia.org/wiki/Science-Fiction)-Literatur. Wir nehmen ein Gehirn, wahrscheinlich von jemandem, der stirbt, das Tier muss wahrscheinlich sterben, damit wir sein Gehirn uploaden können, schauen es uns unter einem ganz tollen Mikroskop ganz genau an, wie die Nervenzellen alle funktionieren, und produzieren daraus eine Simulation, die sich jetzt genauso verhält wie das Original. Stell dir vor, du uploadest den Konrad, bitte nicht uploaden, ich bin sehr zufrieden hier, und dann machst du ein Interview mit dem simulierten Konrad, der genauso redet wie der echte Konrad. Das ist der große Traum vom Uploading.

Was sie gemacht haben, ist etwas anderes. Persönlich würde ich das Wort Uploading dafür nicht benutzen. Wenn Uploading mal möglich wird, werden wir natürlich mit etwas ganz Einfachem anfangen. Stell dir vor, [C. elegans](https://de.wikipedia.org/wiki/Caenorhabditis_elegans), so ein kleiner Wurm mit rund 300 Nervenzellen, oder eben die [Drosophila](https://en.wikipedia.org/wiki/Drosophila_melanogaster), die Fliege, die hat grob eine dreiviertel Million Nervenzellen. Was sie gemacht haben, ist eine Simulation von der Fliege. Das ist eine ganz stark vereinfachte Simulation. Ich würde sie nicht wirklich eine Simulation der Fliege nennen. Sie wissen nämlich, dass eine Nervenzelle die andere beeinflusst, aber sie wissen noch nicht einmal, wie sie sie beeinflusst, ob starker Einfluss, schwacher Einfluss, kein Einfluss. Sie wissen bloß, da ist eine Verbindung dazwischen. Das heißt, es ist höchstwahrscheinlich eine ganz schlechte Simulation vom Gehirn einer Fruchtfliege.

Und jetzt brauchst du, um daraus eine Simulation in einer simulierten Welt zu machen, noch zwei Extra-Teile. Du musst einbauen, wie die visuelle Außenwelt ins Gehirn hineingeht, und wie das Gehirn zurückgeht zum Verhalten der Fliege. In dem Paper haben sie sich bei der Übersetzung von der Fliege zur Außenwelt quasi erlaubt, alles einzubauen, was sie wollen. Das ist nicht öffentliche Forschung, das heißt, ich weiß die Details nicht, aber soweit ich weiß, sitzt jetzt viel von der Intelligenz darin, wie das, was aus dem Gehirn herausgeht, zum Verhalten übersetzt wird. Persönlich würde ich das nicht Uploading nennen. Ich würde nicht sagen, dass es eine wirklich simulierte Fliege ist, deren Gehirn sich so verhält wie die echte Fliege. Das haben sie auch nicht gezeigt.

Es gab großen Streit, großes Disagreement in der Wissenschaft. Die Art, wie ich das sehe: die Firma benutzt Uploading als Simulation, während für die meisten Leute in dem Feld Uploading bedeutet, du bekommst bloß das Gehirn und musst dann das Verhalten produzieren, und du darfst nichts extra einbauen. In der Hinsicht benutzen die verschiedenen Gruppen einfach verschiedene Wörter dafür.

**Leonard Schmedding**

Die große These dahinter ist ja, korrigiere mich gerne, ich gebe es in meinen eigenen Worten vereinfacht wieder: im Wesentlichen ist alles Berechnung, und wenn man einfach jedes Neuron Stück für Stück nachbaut, dann hat man plötzlich eine Fruchtfliege erschaffen. Du hast auch C. elegans genannt. Vielleicht kannst du an dem Beispiel noch einmal erläutern, welche Bausteine hier noch fehlen. Ist das tatsächlich so reduktionistisch? So wie ich es verstehe, würdest du dich dem so nicht anschließen.

**Prof. Dr. Konrad Körding**

Aus meiner Sicht fehlen ganz viele. Das erste, um zurück zum Körper zu gehen: einen Körper gibt es nicht. Es gibt einen simulierten Körper, aber dieser simulierte Körper ist kein guter Stand-in für den echten Körper. Wenn du dir eine Fliege genau unter dem Mikroskop anguckst, ist es sagenhaft, wie toll der Körper der Fliege ist. Der Körper der Fliege ist quasi eine Maschine, die über Millionen Jahre optimiert wurde, um eine Fliege zu sein, und die ist unglaublich gut darin, eine Fliege zu sein. Ohne den Körper fehlt uns da etwas ganz Wichtiges. Es wird auch nicht gezeigt, dass die simulierte Fliege Probleme lösen kann. Damit wir sagen, Uploading ist real, müsste sie eigentlich alles können, was die echte Fliege kann, aber zumindest muss sie echte Probleme lösen. Eine Fliege fliegt weg von dem, was gefährlich ist, von gefährlichen Chemikalien, und fliegt dorthin, wo es etwas zu essen gibt. Selbst diese einfachen Bausteine haben sie nicht wirklich gezeigt. Solange wir nicht zeigen, dass sie das Leben einer Fliege lösen kann, würde ich nicht sagen, dass sie nah am Ziel sind.

**Leonard Schmedding**

Es ist super interessant, dass du das noch einmal unterstreichst, auch wie wichtig der Körper und die Bewegung sind. Ich hatte nämlich neulich ein Gespräch mit einem Robotiker, Professor [Alois Knoll](https://en.wikipedia.org/wiki/Alois_Knoll), der genau das gesagt hat, dass es für richtige Intelligenz den humanoiden oder den Roboterkörper bräuchte, wenn wir an KI denken, und mit Professor [Niels Birbaumer](https://de.wikipedia.org/wiki/Niels_Birbaumer) aus neurowissenschaftlicher Sicht, der auch sagte, dass es ohne Bewegung nicht funktioniert.

### 58:17 – Die nächsten großen Durchbrüche

**Leonard Schmedding**

Mit Hinblick auf die Zeit, Konrad, noch eine abschließende Frage. Was sind aus deiner Perspektive die nächsten großen Durchbrüche, mit denen wir rechnen können, in deinem Forschungsfeld, in der KI, aber auch in der Neurowissenschaft? Worauf schaust du gerade gespannt, was wird die nächsten Jahre passieren, was sich die meisten Menschen heute noch nicht vorstellen können oder gar nicht auf dem Radar haben?

**Prof. Dr. Konrad Körding**

In der künstlichen Intelligenz fehlt aus meiner Sicht noch das Weltmodellieren. Du kannst deine Augen zumachen und dir vorstellen, was passiert, wenn ich aufstehe und etwas Verrücktes mache. Stell dir vor, ich stehe auf und gieße meine Wasserflasche aus. Kein Problem, das kannst du dir vorstellen. Die LLMs haben nicht so die Möglichkeit zu sagen: jetzt nehmen wir mal eine Simulation von der Welt und sehen, was dort passiert. [Weltmodelle](https://en.wikipedia.org/wiki/World_model) sind ganz hilfreich, wenn du etwas Neues machen willst. Sie sind nicht sehr wichtig, wenn du das machen musst, was du schon tausendmal gemacht hast. Ein LLM braucht größtenteils keine oder nur limitierte Weltsimulation, in der Hinsicht, dass sie mit sich selbst reden. Aber um in einer physischen Welt effektiv zu sein, brauchen wir eine Simulation in unserem Kopf von der physischen Welt. Diese Simulationen sind noch ganz schlecht. Wenn du dir ein [Videomodell](https://en.wikipedia.org/wiki/Text-to-video_model) anguckst, ist es ganz interessant, wie extra Beine erzeugt werden und wie jemand aus einer Kiste kommt, die vorher leer war. Den Modellen fehlt wirklich ein Modell von der Welt. Wenn du mich fragst, was der nächste große Schritt für die künstliche Intelligenz ist, und daran arbeiten viele Leute, wird es höchstwahrscheinlich sein, dass wir viel bessere Weltmodelle einbauen, als wir gegenwärtig haben.

Was das Gehirn angeht, bin ich der Meinung, dass wir jetzt technisch in der Lage sind, ganze Gehirne zu erfassen, und wir sehen das in der Fruchtfliege. Ich denke, wir haben keine Simulation, aber wir können sie rekonstruieren. Wir können dir eine Liste machen von jeder Zelle, die in der Fruchtfliege ist, und wie die miteinander verbunden sind. Ich bin mir sicher, dass wir das in den nächsten Jahren an Mäusen und wahrscheinlich Menschen machen können.

**Leonard Schmedding**

Super spannend. Vielleicht als letzte Frage: ist das aus deiner Sicht der richtige Weg mit den Weltmodellen? Braucht es die wirklich für richtige Intelligenz, oder ist es vielleicht gar nicht notwendig?

**Prof. Dr. Konrad Körding**

Die Welt denkt so, du hast genau recht, aber es ist nicht so für richtige Intelligenz, sondern Intelligenz hat ganz viele Facetten. Es gibt einige Facetten, wo ein Weltmodell wichtig ist, und dann werden künstliche Intelligenzsysteme, die Weltmodelle haben, besser sein bei Aufgaben, für die Weltmodelle wichtig sind. Und wenn wir Weltmodelle in künstlichen Intelligenzsystemen haben, werden wir die nächste Sache finden, die die künstliche Intelligenz nicht hat, die wir haben. In 20 Jahren werden wir immer noch wichtige Sachen finden, die wir haben und die die künstliche Intelligenz nicht hat. Das ist das, was es interessant macht, ein Forscher im künstlichen Intelligenzfeld zu sein. Es ist nicht so, dass uns eine Sache fehlt und dann haben wir die richtige Intelligenz. Die richtige Intelligenz haben wir schon ganz lange, und die richtige Intelligenz gibt es gar nicht. Stell dir vor, ich möchte eine Intelligenz, die mir bei Sachen hilft. Ich möchte nicht, dass das eine echt menschliche Intelligenz ist, die vielleicht traurig ist, wenn ich gemein zu dir bin. Ich brauche ein Werkzeug, das mir ein Problem löst. Die Idee, dass wir jetzt alles brauchen und dass es dann irgendwann richtig wird, nein, es wird nicht irgendwann richtig, sondern wir bauen Werkzeuge, die gut an den Sachen sind, für die wir sie bauen, und nicht gut an den Sachen, für die wir sie nicht bauen. Jeder Schritt, den wir in der künstlichen Intelligenz machen, macht sie besser für die Probleme, die wir mit ihr lösen wollen. Keiner davon macht uns als Menschen in irgendeiner Weise weniger wertvoll oder weniger wichtig, als wir im Moment sind.

**Leonard Schmedding**

Wichtige Einordnung. Und das Tolle ist, die Gesprächsthemen werden uns die nächsten Jahre sicherlich nicht ausgehen, genauso wenig wie die Durchbrüche in diesem Bereich. Schreibt gerne in die Kommentare, ob ihr einen zweiten Teil mit Konrad wünschen würdet. Konrad, vielen Dank auf jeden Fall für die Einblicke in deine Arbeit, und sehr gerne bis zum nächsten Mal.

**Prof. Dr. Konrad Körding**

Bis zum nächsten Mal. Tschüss.

---

Quelle: https://www.youtube.com/watch?v=lqwJza-EBiY
