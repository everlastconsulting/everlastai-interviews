# Prof. Dr. Jan Peters × Leonard Schmedding Interview

Prof. Dr. Jan Peters · Professor für Intelligente Autonome Systeme an der [TU Darmstadt](https://www.tu-darmstadt.de/) · Co-Founder [Telekinesis](https://telekinesis.ai/) · [@everlastai](https://www.youtube.com/@everlastai) · 2025-09-11 · 45 Min · Deutsch · [YouTube](https://www.youtube.com/watch?v=RcXA8paGbdQ)

[Prof. Dr. Jan Peters](https://www.ias.informatik.tu-darmstadt.de/Member/JanPeters) gehört zu den weltweit führenden [Robotik](https://en.wikipedia.org/wiki/Robotics)-Forschern, ist [IEEE Fellow](https://www.ieee.org/membership/fellows/index.html) mit über 45.000 Zitationen, leitet den Lehrstuhl für Intelligente Autonome Systeme an der [TU Darmstadt](https://www.tu-darmstadt.de/) und hat als erster Europäer den hochdotierten [ERC](https://erc.europa.eu/) bzw. [EIC Transition Grant](https://eic.ec.europa.eu/eic-funding-opportunities/eic-transition_en) gewonnen. Mit seinem Spin-off [Telekinesis](https://telekinesis.ai/) will er Roboter-Programmierung so einfach machen wie die Bedienung eines Smartphones. Im Gespräch geht es um den Einbruch der Hardware-Preise für [humanoide Roboter](https://en.wikipedia.org/wiki/Humanoid_robot) auf 6000 Euro, die Rolle von [Reinforcement Learning](https://en.wikipedia.org/wiki/Reinforcement_learning) (mit Verweisen auf [Rich Sutton](https://en.wikipedia.org/wiki/Richard_S._Sutton), [Andy Barto](https://en.wikipedia.org/wiki/Andrew_Barto), [Pieter Abbeel](https://en.wikipedia.org/wiki/Pieter_Abbeel) und [Sergey Levine](https://people.eecs.berkeley.edu/~svlevine/)), [NVIDIA](https://www.nvidia.com/) und [CUDA](https://developer.nvidia.com/cuda-toolkit) als KI-Plattformmonopol, den Verkauf von [KUKA](https://www.kuka.com/) nach China, die Demografielücke in Pflege und Industrie und warum Deutschland den Hardware-Wettlauf verloren hat, aber bei Software und Nischen weiter vorne mitspielen kann.

## Timestamps

- [00:00](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=0s) – Kurzer Einblick
- [00:39](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=39s) – Worum geht es
- [03:26](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=206s) – Warum Robotik?
- [05:35](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=335s) – Die frühen Herausforderungen
- [09:58](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=598s) – Forschung an Algorithmen
- [11:53](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=713s) – Reinforcement Learning
- [14:16](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=856s) – Telekinesis
- [18:48](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=1128s) – Die Entwicklung des Marktes
- [21:29](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=1289s) – NVIDIA & Robotik
- [24:52](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=1492s) – Zukunft humanoider Roboter
- [31:24](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=1884s) – Roboter & Jobchancen
- [39:36](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=2376s) – Für Unternehmer & Gründer
- [44:41](https://www.youtube.com/watch?v=RcXA8paGbdQ&t=2681s) – Fazit & Abschied

## Transcript

### 00:00 – Kurzer Einblick

**Prof. Dr. Jan Peters**

Es wird bald die ersten Humanoiden für 6000 Euro geben. Da hat es letztes Jahr eine Riesenrevolution gegeben, wir haben diesen Punkt erreicht. Jetzt ist die große Frage nur noch: wie lange dauert es. In 30 Jahren werden wir garantiert Roboter in jedem Haushalt haben. Wir werden die Fehlentscheidungen der letzten 50 Jahre aus Politik, Gewerkschaften und Wirtschaft nicht revidieren können. Der Robocop bei unserer Polizei, die sich als Freund und Helfer ansieht, wird nicht so gerne gesehen, aber ich denke, das wird sehr breit kommen. Einzelne Länder haben schon ganz massiv investiert.

### 00:39 – Worum geht es

**Leonard Schmedding**

Das Folgende ist ein Gespräch mit Prof. Dr. Jan Peters, einem der weltweit führenden Robotikforscher und KI-Pioniere, der Maschinen das Lernen beibringt. Als Professor für Intelligente Autonome Systeme an der [TU Darmstadt](https://www.tu-darmstadt.de/) und als [IEEE Fellow](https://www.ieee.org/membership/fellows/index.html), der höchsten Auszeichnungsstufe der weltweit größten Ingenieursvereinigung, mit über 45.000 Zitationen gehört er zu den Top 0,1 Prozent Robotikforschern weltweit und hat bahnbrechende Algorithmen entwickelt, die es Robotern ermöglichen, komplexe Fähigkeiten durch reines Ausprobieren zu erlernen. Bereits vor über zehn Jahren hat Jan Peters Robotern beigebracht, [Tischtennis](https://en.wikipedia.org/wiki/Table_tennis) zu spielen, zu jonglieren und Airhockey zu beherrschen. Als erster Europäer gewann er den hochdotierten [EIC Transition Grant](https://eic.ec.europa.eu/eic-funding-opportunities/eic-transition_en) und sammelte in Summe über vier Millionen Euro für ein Projekt, das nun die Art revolutionieren könnte, wie wir mit Robotern arbeiten und ihnen Dinge beibringen. 2023 gründete er mit seinen Studenten das deutsche Startup [Telekinesis](https://telekinesis.ai/), das aus seinem Labor hervorgegangen ist und mit dem Ziel antritt, Roboter-Programmierung so einfach zu machen wie die Bedienung eines Smartphones.

In diesem Gespräch machen wir eine kurze Zeitreise und schauen, wieso es bereits 1969 die ersten Werbespots für Haushaltsroboter gab, welche Jobs als erstes von humanoiden Robotern übernommen werden, wann die große Roboter-Revolution wirklich kommt und was jeder Deutsche, egal ob Angestellter oder Unternehmer, über die Entwicklung von KI-Robotern jetzt wissen muss.

### 03:26 – Warum Robotik?

**Leonard Schmedding**

Hallo Jan, vielen Dank, dass du dir die Zeit genommen hast. KI und Robotik sind die zwei großen Themen, die viele Zuschauer und auch die Menschheit allgemein beschäftigen. Bei dir ist besonders interessant: du beschäftigst dich schon seit du ein Kind bist mit Robotik. Ich habe in Vorbereitung einen [TED Talk](https://www.ted.com/) von dir vor sechs Jahren gesehen, in dem du über deinen Werdegang erzählt hast. Was war für dich der Auslöser, dich mit diesem Themenfeld so intensiv zu beschäftigen?

**Prof. Dr. Jan Peters**

Im Endeffekt bin ich sehr jung zum Computer gekommen, mein Vater hat schon einen Computer mitgebracht, als ich in der Grundschule war. Ich habe mich sehr früh mit KI beschäftigt, und KI war damals: wir werden alle Regeln aufschreiben und versuchen, anhand dieser Regeln ein Programm zu schreiben, das Intelligenz macht. Ich fand diese Idee unglaublich frustrierend, weil mir klar war, dass es nicht funktionieren würde. Weiter als bis zum Niveau eines vierjährigen Kindes, also vergleichbar mit [GPT-1](https://en.wikipedia.org/wiki/GPT-1), ist man mit diesem Ansatz auch nie gekommen.

Dann habe ich angefangen zu schauen, was es sonst gibt, und kam auf [Maschinelles Lernen](https://en.wikipedia.org/wiki/Machine_learning). Ich habe sogar überlegt, ob ich vielleicht die Börse vorhersagen könnte. Das Blöde war nur: man musste die Daten damals noch selbst eingeben, also genug Daten konnte man nicht hinkriegen. Aber die Idee aus Statistik und statistischem maschinellem Lernen kam mir tatsächlich schon in der fünften oder sechsten Klasse. Roboter waren von Anfang an total faszinierend, und ich habe immer wieder versucht, Sachen zu basteln und mit dem Computer zu steuern. Wenn man erstmal mit dem Virus des Programmierens infiziert ist, ist es fast natürlich, dass man die Welt direkt beeinflussen will. Und es hat einfach eine Menge Spaß gemacht.

### 05:35 – Die frühen Herausforderungen

**Leonard Schmedding**

Für die meisten ist KI seit dem [ChatGPT](https://chat.openai.com/)-Hype präsent. Du hast erzählt, dass es kein neues Thema ist und schon 1969 der erste Roboter-Werbespot veröffentlicht wurde. Was war damals und heute das Problem, dass wir bis dato keine wirklich funktionierenden Humanoiden zu Hause rumlaufen haben?

**Prof. Dr. Jan Peters**

Am Ende des Tages ist das das größte Technikthema, vielleicht neben der Energieversorgung. Wenn man einen humanoiden Roboter zu Hause haben möchte, kommt alles zusammen. Am Anfang haben wir vor allem auf die Körper und auf die Rechenleistung gewartet. Als man in den 60er Jahren mit den ersten [Industrierobotern](https://en.wikipedia.org/wiki/Industrial_robot) anfing, hatten die fast überhaupt keinen Computer dahinter. Da gab es ein paar vorgegebene Bahnen, und dazwischen haben Analogcomputer interpoliert. Das war mit minimalstem Rechenaufwand. Erst seit etwa fünf, sechs Jahren haben wir überhaupt die Rechenleistung, damit wir Roboter bauen können, die intelligent in offenen Umgebungen handeln.

Man darf nicht vergessen: unser Gehirn schafft 20 Watt, das ist eine unglaubliche Leistung. Aber an Rechenleistung entspricht es etwa der eines Computers von vor fünf Jahren. Was das Gehirn berechnet, weiß man bei Menschen ja noch gar nicht, da haben wir noch viele offene Baustellen.

Wir haben also auf zwei Sachen gewartet: Rechenleistung und Körper. Körper sind kontinuierlich besser geworden, und letztes Jahr gab es eine Riesenrevolution. Anfang des Jahres hieß es noch, für einen humanoiden Roboter müsse man eine Million Euro hinlegen, ein paar Jahre davor sogar zwei Millionen, um einen funktionalen zu bekommen. Im Laufe des Jahres fiel es auf 100.000, dann 50.000, dann 20.000, und jetzt sieht es so aus, als wird es bald die ersten Humanoiden für 6000 Euro geben. Das ist eine Körperqualität, wie wir sie uns vor zehn Jahren nicht hätten erträumen können. Die Ausrede, wir hätten nicht die richtigen Körper, ist der Robotik abhanden gekommen.

In der Robotik haben wir lange gesagt, wir können enorm viel: Aktionen planen, komplexe Verhalten lernen. Aber uns fehlten ganz andere Dinge, etwa die natürlichsprachliche Verarbeitung, damit man nicht jedes Verhalten programmieren oder eintrainieren muss, sondern verbal das Kommando geben kann. Durch die Revolution mit ChatGPT ist das auf einmal kein Problem mehr. Auch [Computer Vision](https://en.wikipedia.org/wiki/Computer_vision), wo wir Robotiker uns immer rausgeredet haben, das funktioniere nicht und löse nicht die richtigen Probleme, kann man mittlerweile abhaken. Wir sind jetzt endlich nah an dem heiligen Gral der Technik, dass man Roboter bauen kann, die in offenen Umgebungen komplexe Aufgaben lösen können. Alle Komponenten sind eigentlich da. Die große Frage ist nur, wie lange es dauert. Das können zwei Jahre sein, das können auch zehn Jahre sein. Das ist verflixt schwer abzusehen.

### 09:58 – Forschung an Algorithmen

**Leonard Schmedding**

Du gehörst zu den weltweit führenden Robotik-Forschern, zu den Top 0,1 Prozent mit über 45.000 Zitationen. Wo sieht man deine Forschung, oder wo sieht man sie eben nicht? Welche Unternehmen arbeiten mit den Algorithmen, die du und dein Team entwickelt habt?

**Prof. Dr. Jan Peters**

Ich habe ursprünglich sehr viel von diesen [Policy-Search](https://en.wikipedia.org/wiki/Reinforcement_learning#Policy_search)-Reinforcement-Learning-Algorithmen entwickelt, und die kommen heute fast überall zum Einsatz. Fast überall, wo Reinforcement Learning draufsteht, kommen leichte Variationen meiner Algorithmen zum Einsatz. Es ist leider nicht bei meinen Originalalgorithmen geblieben, sondern leichte Variationen aus [Berkeley](https://www.berkeley.edu/) wie [PPO](https://en.wikipedia.org/wiki/Proximal_Policy_Optimization) oder TRPO, wo Algorithmen von mir verwendet wurden, etwa Natural Actor-Critic oder die ganzen Entropy-Regularization-Algorithmen mit Relative Entropy Policy Search. Die heißen heute leicht anders, sind aber flächendeckend in nahezu allen Reinforcement-Learning-Anwendungen auf realen Robotern enthalten. Darüber hinaus habe ich mit vielen Firmen zusammengearbeitet. Das ist mittlerweile eine sehr lange Liste, ich weiß nur nicht, wie weit ich die nennen darf, weil bei der einen oder anderen Firma eine NDA dazwischen ist.

### 11:53 – Reinforcement Learning

**Leonard Schmedding**

Vielleicht für die Zuschauer ganz kurz: was genau ist Reinforcement Learning, und warum ist es so wichtig?

**Prof. Dr. Jan Peters**

Wenn wir Menschen lernen, brauchen wir eine Kombination von Lernalgorithmen. Wir werden mit ein paar Reflexen geboren, die uns Basisverhalten geben. Dann haben wir den Reflex zu imitieren, damit kriegen wir einen Teil unserer Basisprogrammierung hin. Und dann kommt die Selbstverbesserung. Die passiert basierend auf Signalen wie Schmerz, Freude, Geld: Signalen, die uns sagen, hier möchte ich ein Signal maximieren, also Schmerz minimieren, Freude maximieren, Geld maximieren. Genau das tun Reinforcement-Learning-Algorithmen.

Reinforcement Learning ist eine sehr alte Idee, die bis in die 60er Jahre zurückgeht. Sie wurde durch [Rich Sutton](https://en.wikipedia.org/wiki/Richard_S._Sutton) und [Andy Barto](https://en.wikipedia.org/wiki/Andrew_Barto) toll formalisiert und in einen Framework gepackt. Als ich anfing, gab es schon ein paar tolle Anwendungen wie [Backgammon](https://en.wikipedia.org/wiki/TD-Gammon) auf hohem Level, aber für die Robotik fast keine anwendbaren Algorithmen. Das lag daran, dass man sich zu sehr auf Spiele und diskrete Welten geworfen hatte, wo Aktionen diskret voneinander getrennt sind. Bei Robotern hat man kontinuierliche Aktionen, etwa Kraftvektoren, die über die Zeit ausgegeben werden. Deshalb haben mein Doktorvater und ich, und auch viele andere wie Drew Bagnell, später [Pieter Abbeel](https://en.wikipedia.org/wiki/Pieter_Abbeel) und [Sergey Levine](https://people.eecs.berkeley.edu/~svlevine/), dafür gepusht, dass es die sogenannten Policy-Search-Methoden gibt. Die versuchen, die Handlungsstrategie direkt zu lernen, statt nur über die unterschiedlichen Aktionen zu bewerten und daraus die Handlung abzuleiten.

### 14:16 – Telekinesis

**Leonard Schmedding**

Bei dir ist auch besonders, dass du nicht nur in der Forschung führend, sondern auch unternehmerisch tätig bist. Mit Studenten von dir hast du 2023 das Startup [Telekinesis](https://telekinesis.ai/) gegründet. Ihr habt 1,4 Millionen von der EU und 2 Millionen von Investoren eingesammelt, also fast vier Millionen. Welches Problem löst Telekinesis?

**Prof. Dr. Jan Peters**

Bei Telekinesis geht es uns darum, eines der größten Probleme des deutschen Mittelstands zu lösen. Wir haben in Deutschland tolle Industrieunternehmen, [BMW](https://www.bmw.com/), [Mercedes](https://www.mercedes-benz.com/) und so weiter, die produzieren in großen Stückzahlen und konnten schon immer Roboter einsetzen. Im Mittelstand hingegen ist der Einsatz von Robotern kompliziert. Gleichzeitig ist der Mittelstand eigentlich das, wovon Deutschland lebt, weil der Großteil der produktiv Beschäftigten dort arbeitet. Und der Mittelstand kann keine Roboter einsetzen, weil die Stückzahlen zu klein sind.

Bei Telekinesis haben wir voll darauf gesetzt, mit Robot-Learning-Methoden zu ermöglichen, dass ein Mittelständler Roboter einsetzen kann, auch bei sehr kleinen Stückzahlen, ohne eigenen Roboterprogrammierer. Ein normaler Sterblicher nimmt den Roboter bei der Hand, zeigt ihm die erste Aufgabe, und dann wird der Roboter durch Selbstverbesserung gut genug.

Ich hätte das nie selbst geschafft. Ich bin Professor und kein Unternehmer. Ich hatte aber irres Glück: ein Masterstudent kam zu mir und sagte, er möchte bei mir promovieren und gleichzeitig ein Startup gründen. Ich habe ihm gesagt: Doktorarbeit willst du nicht schreiben, wenn du ein Startup machst. Ein Startup brauchst du jung und hungrig, dafür musst du die richtigen Jahre deines Lebens nutzen. Er hat auf mich gehört. Wir haben zusammen erst einen Grant von [HIGHEST](https://www.tu-darmstadt.de/highest/), dem Gründerzentrum der TU Darmstadt, bekommen, ein Jahresstipendium, um die Software zu konsolidieren. Dann haben wir öffentliche Förderung und später Investoren gefunden. Mittlerweile ist die Firma vollständig als GmbH gegründet.

**Leonard Schmedding**

Das fand ich super sympathisch: dass du den Studenten ermutigt hast, gleich zu gründen statt erst zu promovieren. Das fehlt in Deutschland, viele trauen sich zu wenig zu gründen.

**Prof. Dr. Jan Peters**

Wir müssen junge Leute dazu bringen, Unternehmen zu gründen. Das Komische in Deutschland ist, dass gerne Leute in meinem Alter oder älter, die Professoren sind, denken, sie könnten Unternehmen gründen. Was man als allererstes braucht, ist jemanden, der jung ist und die ganze Learning Curve einer Unternehmensgründung mitnehmen kann. Wenn man erstmal eine Professorenkarriere hat, kriegt man das gar nicht mehr hin. Uns fehlen zwei Mechanismen: junge Leute richtig zu finden, einzubinden und zu fördern, und auf der anderen Seite eine ausreichend große Zahl von jungen Leuten, die bereit sind, dieses Risiko einzugehen, statt eine einfachere, langweiligere Karriere zu machen.

### 18:48 – Die Entwicklung des Marktes

**Leonard Schmedding**

Mich würde noch mal interessieren: ist eure Software speziell für humanoide Roboter, etwa mit einem Brainwave-System, oder breiter aufgestellt?

**Prof. Dr. Jan Peters**

Für alle Roboter. Bei Telekinesis ist uns besonders wichtig, dass wir nicht von einer Roboter-Plattform eingesperrt werden, sondern über möglichst viele Bodyplans und Hersteller hinweg Software liefern können. Wir bauen den Wrapper kontinuierlich aus, sodass wir nicht sagen müssen, wir sind im Universum der Firma [KUKA](https://www.kuka.com/) gefangen, deshalb können wir keinen [Franka](https://franka.de/)-Roboter unterstützen. Mit dem gleichen Wrapper kann man direkt beide Roboter gleichermaßen nutzen.

**Leonard Schmedding**

Wer ist die Zielgruppe, die mittelständischen Unternehmen selbst oder Hardware-Hersteller wie [Neura Robotics](https://neura-robotics.com/)?

**Prof. Dr. Jan Peters**

Wir reden mit allen. Wir haben mit sehr vielen Firmen Use-Cases und Pilotprojekte angefangen. Da ist alles dabei: große Staatsunternehmen wie die [Deutsche Bahn](https://www.deutschebahn.com/) haben ein Pilotprojekt mit uns. Wir reden mit Neura Robotics, mit verschiedensten Mittelständlern. Wichtig ist, dass die Firmen einen langen Atem haben, denn wir sind im Augenblick noch ein sehr kleines Unternehmen und müssen Sachen langfristig angehen. Das ist nicht für jeden Mittelständler im Moment gut geeignet, aber langfristig werden alle davon profitieren.

**Leonard Schmedding**

[David Reger](https://www.linkedin.com/in/david-reger-8b21b711/) von Neura hatten wir auch im Interview auf dem Kanal. Ist Telekinesis eine Konkurrenz zum Neuraverse oder baut das eher darauf auf?

**Prof. Dr. Jan Peters**

Es ist komplementär. Ich möchte nicht zu viel über David Reger sagen, das will ich mir nicht anmaßen.

### 21:29 – NVIDIA & Robotik

**Leonard Schmedding**

Vielleicht zu [NVIDIA](https://www.nvidia.com/), die sind im Robotikbereich sehr groß unterwegs, haben kürzlich [Thor](https://developer.nvidia.com/blog/announcing-jetson-thor/) vorgestellt und bauen am [Omniverse](https://www.nvidia.com/en-us/omniverse/) für virtuelle Lernumgebungen. Welche Rolle spielt NVIDIA für deine Forschung?

**Prof. Dr. Jan Peters**

Mein Lehrstuhl hat viele Jahre Förderung von NVIDIA bekommen, im Millionenbereich. NVIDIA ist essentiell in der KI. Das ist eigentlich relativ banal: NVIDIA hat eine Zwischenschicht zwischen Grafikkarten und der höheren Programmierung geschaffen, das sogenannte [CUDA](https://developer.nvidia.com/cuda-toolkit). Nahezu alle KI-Algorithmen bauen darauf auf. Solange das niemand anderes hat, sind die Grafikkarten von NVIDIA unschlagbar, auch wenn es von der Rechenleistung her gar nicht schwer wäre, vergleichbare Karten zu bauen.

Hier fehlt noch ein Moment wie früher beim [IBM PC](https://en.wikipedia.org/wiki/IBM_Personal_Computer): IBM hatte sein eigenes BIOS, und irgendwann hat sich [Compaq](https://en.wikipedia.org/wiki/Compaq) hingesetzt und das BIOS mit den gleichen Schnittstellen nachprogrammiert, ohne eine einzige Zeile Original-Code zu verwenden. Dadurch wurde der IBM-kompatible PC geschaffen. Wenn es irgendwann die NVIDIA-kompatible Grafikkarte gibt, die CUDA umgeht oder kompatibel macht, ist NVIDIA aus dem Geschäft raus. Dieses hochprofitable Unternehmen wäre auf einmal weitgehend wertlos. Viele arbeiten daran, aber es ist nicht ganz so einfach wie beim BIOS damals, weil viel mehr nachprogrammiert werden muss.

Allein aus Rechenleistungsgründen brauchen wir NVIDIA, und sie machen auch tolle Software, mit der man [Digital Twins](https://en.wikipedia.org/wiki/Digital_twin) und massive Simulationen von Millionen Robotern bauen kann, die alle gleichzeitig die gleiche Aufgabe trainieren. Solange die Digital Twins gut genug sind, kann man darin sehr viel schneller lernen.

### 24:52 – Zukunft humanoider Roboter

**Leonard Schmedding**

Was siehst du als die ersten Bereiche, in denen Humanoide Einzug finden? Industrie, Haushalt, Pflege?

**Prof. Dr. Jan Peters**

Bei Humanoiden ist das schwer vorherzusagen. Logistik ist ein natürlicher Anwendungsfall. Die Frage ist immer, ob man echte Humanoide oder Halbhumanoide braucht, denn ein Oberkörper auf Rädern ist für die meisten Aufgaben viel praktischer als Beine. Es gibt wenige Aufgaben, wo man wirklich Beine braucht, was schade ist, denn Gehen und Laufen halte ich mittlerweile für weitgehend gelöst. Da ist noch ein Potenzial von 20 bis 30 Prozent drin, aber es ist nicht mehr die Unmöglichkeit von früher, als ich angefangen habe und wir Generationen im [Legged Locomotion](https://en.wikipedia.org/wiki/Legged_robot)-Programm der [DARPA](https://www.darpa.mil/) gemacht haben. Heute kann man mit Reinforcement Learning und genügend [Domain Randomization](https://lilianweng.github.io/posts/2019-05-05-domain-randomization/) Dinge trainieren, die nahezu perfekt auf vier Beinen, auf zwei Beinen und sogar mit demselben Algorithmus über viele Bodyplans hinweg funktionieren. Das hat einer meiner Doktoranden, Nico Bohlinger, fantastisch gezeigt.

Gehen wird vor allem relevant, wenn man im Wald ist oder in Umgebungen, wo Räder nutzlos werden, und das sind im Allgemeinen wenige. Es gibt aber viele Bereiche, wo Humanoide schnell kommen werden. Ein Beispiel ist die Polizei: wenn man mit jemandem mit einem Messer eine Verhandlung führen möchte, ist es durchaus sinnvoll, das mit einem menschlichen Körper zu machen, der unter anderem auch kampfbereit werden kann. Das wird sich relativ schnell durchsetzen. Da sind einige Länder schneller als wir, weil der Robocop bei einer Polizei, die sich als Freund und Helfer ansieht, nicht so gerne gesehen wird, aber das wird sehr breit kommen. Einzelne Länder haben schon massiv investiert.

In der Logistik werden Transportaufgaben zunehmend gut durch Humanoide lösbar. Gleichzeitig gehen uns die Menschen aus. In den nächsten 60 Jahren wird, mit Ausnahme von [Subsahara-Afrika](https://en.wikipedia.org/wiki/Sub-Saharan_Africa) und Afghanistan, alle Länder der Welt eine Arbeitskräftemangel-Krise erfassen. Die Geburtenrate ist außerhalb dieser Regionen überall zusammengebrochen. Wir müssen uns auf ein halbes Jahrhundert einstellen, in dem uns die Leute fehlen und wir mehr und mehr Roboter brauchen.

Wenn man 20 Jahre weiterspult: wir werden eine Unmenge älterer Menschen haben, die ein bisschen desorientiert durch die Gegend laufen, aber eigentlich noch in der Lage wären, sich selbst zu bewegen und etwas Glück im Leben zu empfinden. Es gibt zwei Szenarien. Entweder kriegen wir die Sache nicht in den Griff, weil uns die Menschen fehlen, und wir haben hilflose ältere Herrschaften, zu denen ich in 20 oder 30 Jahren auch gehören werde, die niemand vernünftig unterstützen kann, fast wie eine Gesellschaft mit Zombies. Oder wir kriegen es hin, dass wir genug humanoide Roboter haben, auf die sich Menschen einlassen, weil sie ein menschenähnliches Embodiment haben, die sich um ältere Menschen kümmern und für ein selbstbestimmtes Leben sorgen. Das ist nicht das, was in der ersten Welle der Pflegeautomatisierung in [Japan](https://en.wikipedia.org/wiki/Robotics_in_Japan) passiert ist, wo man quasi Fabriken um ältere Menschen herum gebaut hat, in denen sie sediert wurden, damit sie keine Schwierigkeiten machen. Mit Humanoiden können wir selbstbestimmtes Altern, auch mit [Demenz](https://en.wikipedia.org/wiki/Dementia), möglich machen.

In 30 Jahren werden wir garantiert Roboter in jedem Haushalt haben. Ob das Halbhumanoide sind oder ganz humanoide, da bin ich mir nicht sicher, denn Räder wären sehr praktisch. Die Gefahr, dass ein Roboter hinfällt, ist da, also muss man ihn so leicht und weich machen, dass er nicht gefährlich ist, auch für ein kleines Kind. Andererseits: ein Kinderzimmer aufzuräumen, das weiß ich als Vater von vier Kindern, macht Erwachsenen keinen Spaß. Eine Aufgabe, die sich mit Robotikmethoden in den nächsten fünf Jahren problemlos lösen lassen sollte.

### 31:24 – Roboter & Jobchancen

**Leonard Schmedding**

In China sterben aktuell 15 Prozent mehr Menschen als geboren werden. Das erste Argument ist meist: es werden gar keine Jobs ersetzt, sondern wegfallende Stellen werden von Humanoiden übernommen. Wie siehst du die weiteren Auswirkungen?

**Prof. Dr. Jan Peters**

Ich würde noch einen Schritt weitergehen. Es hat eigentlich nie einen Punkt gegeben, an dem Roboter Jobs zerstört haben. Sie haben Jobs immer geschafft zu veredeln. Es sind vielleicht Jobs verloren gegangen, die nicht so gut waren, aber im Nachgang sind durch die Robotik immer Jobs entstanden, die besser und hochwertiger waren und es Leuten ermöglicht haben, ein schöneres Leben zu führen, weil sie nicht so viele repetitive, langweilige und schmerzhafte Aufgaben übernehmen mussten. Das ist anders zu sehen als bei der Automatisierung geistiger Tätigkeiten.

**Leonard Schmedding**

In welchen Bereichen siehst du, dass die größten Jobchancen entstehen, abseits der offensichtlichen Robotik-Forschung und Wartung?

**Prof. Dr. Jan Peters**

Die Möglichkeiten sind gigantisch. Im [Rehabilitations](https://en.wikipedia.org/wiki/Physical_medicine_and_rehabilitation)-Bereich kann man die Symbiose zwischen Mensch und Roboter nutzen, sodass die Fachkraft sich auf den Menschen fokussiert, während der Roboter dabei hilft, genug Therapiestunden hinzukriegen. Statt nur ein, zwei Stunden mit einer Fachkraft sind es plötzlich täglich Übungen. Auch in der Chirurgie kann man eine Riesenmenge gewinnen, wenn man das Verhalten der besten Chirurgen der Welt durch [Imitation Learning](https://en.wikipedia.org/wiki/Imitation_learning) lernt und in jedem Krankenhaus der Welt verfügbar macht.

Am Ende des Tages wollen wir Menschen am liebsten mit Menschen interagieren, und wir können uns mehr auf Aufgaben fokussieren, die menschlicher Intelligenz bedürfen, statt stupide repetitive Aufgaben zu machen. Je seltener eine Aufgabe aufkommt, desto mehr braucht man menschliche Intelligenz und desto interessanter ist sie. Kaum jemand möchte den [Groundhog Day](https://en.wikipedia.org/wiki/Groundhog_Day_(film)) erleben und sein Leben jeden Tag identisch durchleben. Die meisten von uns wollen Herausforderungen, Neues lernen, dass die Welt sich weiterentwickelt. Robotik macht das möglich, indem sie genau die Aufgaben automatisiert, die immer wieder kommen.

**Leonard Schmedding**

Du hast vorhin skizziert, wie die Preise gefallen sind. [Unitree](https://www.unitree.com/) hat einen Humanoiden für 5900 Dollar angekündigt. Können deutsche Anbieter bei diesen Preisen mithalten?

**Prof. Dr. Jan Peters**

Bei der Hardware fürchte ich, wir werden es schwer haben. Wir haben in Deutschland einen riesigen Fehler gemacht: wir haben bereits im letzten Jahrhundert unsere Elektroindustrie weitgehend geschlachtet. Das hatte mit Gewerkschaften zu tun, die verhindert haben, dass [Transistoren](https://en.wikipedia.org/wiki/Transistor) rechtzeitig eingesetzt wurden, weil das Jobs gekostet hätte. Später haben Mikrochips die Transistoren ersetzt, das hat viele Firmen gekostet. Es gab schlechte Management-Entscheidungen, etwa die Behauptung, Handys mit Kameras werde nie jemand brauchen, was den erfolgreichen Handyhersteller [Siemens](https://www.siemens.com/) gekillt hat. Und es gab katastrophale politische Entscheidungen, vielleicht die schlimmsten von allen. Die Politik hat die Firma [KUKA](https://www.kuka.com/) für ein Apfel und Ei verkauft, was den Chinesen erst das Know-how gegeben hat, in die Robotik einzusteigen. Davor hatten sie das nicht. Jetzt beherrschen die Chinesen die gesamte Pipeline: sie können die Motoren besser als wir, die Boards besser, die Chips besser. Und durch KUKA können sie auch [Franka](https://franka.de/) und alles, was an Wissen aus KUKA herausgesaugt wurde, jetzt besser als wir.

Wir haben jetzt eine Situation, wie sie klassisch eher die Schweiz hatte. Wir müssen mit China zusammenarbeiten, ohne China geht es nicht. Andererseits dürfen wir die Amerikaner nicht verärgern. Wir werden den technologischen Vorsprung, den China sich aufgebaut hat, mit einer schrumpfenden, alternden Bevölkerung nicht aufholen. Wir werden die Fehlentscheidungen der letzten 50 Jahre aus Politik, Gewerkschaften und Wirtschaft nicht revidieren können.

Unsere Chance besteht darin, auf verschiedenen Ebenen so viel beizutragen, dass wir vorne mit dabei sind. Wir brauchen einen massiven Anstieg in der Zahl der [Informatiker](https://de.wikipedia.org/wiki/Informatik), damit wir bei Softwareentwicklung und KI vorne mitspielen. Wir sollten weiter schauen, ob wir bei Hardware tolle Nischen finden, die wir identifizieren, bevor die Chinesen sie identifizieren, oder die zu klein für China sind. Bei kleineren Stückzahlen können wir Dinge tun, die in China nicht gehen. Aber wir müssen unseren deutschen Hochmut, mit dem wir manchmal arrogant auf die Welt geschaut haben, vermeiden. Wir sollten unsere Chancen und Stärken sehen. Wir waren in der Lage, Dinge wie KUKA und [Franka Arme](https://franka.de/) zu entwickeln, weil man in Deutschland einen langen Atem hatte und nicht wie in den USA jedem schnellen Trend hinterhergelaufen ist. Wenn wir das, was wir entwickeln können, geeignet verteidigen und sinnvoll kommerzialisieren, haben wir als Land enorm viele Möglichkeiten.

### 39:36 – Für Unternehmer & Gründer

**Leonard Schmedding**

Ich hatte hier auf dem Kanal Gespräche mit [Prof. Dr. Gunter Dueck](https://de.wikipedia.org/wiki/Gunter_Dueck), der sagte: der Deutsche muss am Boden liegen, bevor er aufwacht und endlich wieder anpackt. Wir haben hier viele Zuschauer, mittelständische Unternehmer, Arbeitnehmer und Studierende. Was würdest du jemandem raten, der vor der Wahl steht?

**Prof. Dr. Jan Peters**

Ich würde raten, entweder Informatik oder Ingenieurwissenschaften zu studieren. Alles andere kann man später lernen. Ich hatte ursprünglich selbst mit BWL und Informatik angefangen. Ein Vorstand eines größeren deutschen Unternehmens, sehr erfolgreich in seiner Karriere, hat mir gesagt: BWL würde er an meiner Stelle lassen, das könne man später viel besser lernen, dann sei man viel näher an den Themen dran. BWL ohne andere Grundlage landet entweder in Jobs, die früher Industriekaufmann oder Bankkaufmann gemacht hat, oder man braucht es erst nach Jahrzehnten. Informatik und Ingenieurwissen kann man nie mehr nachholen.

Bei der Wahl zwischen beiden: wenn man Physik mag, sollte man Richtung Ingenieurwesen gehen, vielleicht etwas wie Ingenieursinformatik oder einen Schnittstellen-Studiengang, denn die Software-Technik in Ingenieurstudiengängen ist meist zu schlecht. In Darmstadt haben wir extra deshalb [Computational Engineering](https://www.tu-darmstadt.de/studieren/abschluesse-und-studiengaenge/studiengang/index.de.jsp) geschaffen, eine 50-Prozent-Informatiker-Ausbildung kombiniert mit 50 Prozent Ingenieursausbildung. Wenn man nicht Physik-affin ist, würde ich rein in die Informatik gehen. Informatiker sind im Augenblick das Nadelöhr des deutschen Wirtschaftswachstums. Wenn wir 10.000 mehr Informatiker hätten, hätten wir vermutlich 1 Prozent mehr Wirtschaftswachstum.

**Leonard Schmedding**

Ein Founder hat mir aus dem Silicon Valley berichtet, dass [Y Combinator](https://www.ycombinator.com/) deutlich lieber in technische Gründer investiert als in BWLer, genau weil sie näher an den Themen sind. Was würdest du einem Unternehmer mitgeben, der jetzt auf KI und Robotik setzen möchte?

**Prof. Dr. Jan Peters**

Das Erfolgsrezept des deutschen Mittelstands ist eigentlich genial. Mittelständische Unternehmen sind in der Lage, das beste Produkt weltweit zu liefern und ihren kleinen Markt mit fast 95 Prozent zu dominieren. Sich den Markt so gut auszusuchen, das ist etwas, was in Deutschland funktionieren kann. Nicht einfach Trends und leeren Hüllen nachzulaufen, wie es in Amerika gerne gemacht wird. Dafür haben wir kein System, das [Fake it until you make it](https://en.wikipedia.org/wiki/Fake_it_till_you_make_it) funktioniert hier nicht. Wir müssen Substanz liefern. Die deutschen Mittelständler sind dafür ein tolles Vorbild. Ich würde jedem, der Unternehmer werden will, empfehlen, sich einen Mentor in einem deutschen Mittelständler zu suchen, der einem beibringt, wie man dahin kommt und wie man das über Generationen bewahrt. Wenn man den Unternehmer aus einem Unternehmen herausnimmt, stirbt das Unternehmen oder wird herzlos und unpersönlich. Daher halte ich den Unternehmer als Person für unglaublich wichtig.

### 44:41 – Fazit & Abschied

**Leonard Schmedding**

Das kann ich aus eigener Erfahrung bestätigen. Man redet Deutschland gerne schlecht, du hast die düsteren Aussichten skizziert, die man kennen sollte, aber viele deutsche Unternehmen sind sehr weitsichtig und sich der Probleme bewusst. Sie wollen jetzt in KI und Robotik investieren. Jan, vielen Dank für das super interessante Gespräch und die wertvollen Einblicke. Wenn ihr einen zweiten Teil mit Jan sehen wollt, schreibt es in die Kommentare. Jan, danke für deine Zeit, bis zum nächsten Mal.

**Prof. Dr. Jan Peters**

Hat Spaß gemacht. Bis zum nächsten Mal.

---

Quelle: https://www.youtube.com/watch?v=RcXA8paGbdQ
