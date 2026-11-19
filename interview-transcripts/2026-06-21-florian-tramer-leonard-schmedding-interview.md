# Prof. Dr. Florian Tramèr × Leonard Schmedding Interview

Prof. Dr. Florian Tramèr · KI-Sicherheitsforscher [ETH Zürich](https://ethz.ch/) · [@everlastai](https://www.youtube.com/@everlastai) · 2026-06-21 · 30 Min · Deutsch · [YouTube](https://www.youtube.com/watch?v=eg3GcZEnbHQ)

[Prof. Dr. Florian Tramèr](https://floriantramer.com/) forscht an der [ETH Zürich](https://ethz.ch/) seit rund 10 Jahren zu [KI-Sicherheit](https://en.wikipedia.org/wiki/AI_safety) und [adversarialem maschinellem Lernen](https://en.wikipedia.org/wiki/Adversarial_machine_learning) und zählt zu den weltweit führenden Stimmen, wenn es um [Jailbreaks](https://en.wikipedia.org/wiki/Jailbreak_(computer_science)) und [Prompt Injection](https://en.wikipedia.org/wiki/Prompt_injection) geht. In dieser KI-News-Ausgabe ordnet [Leonard Schmedding](https://www.youtube.com/@everlastai) zunächst die Woche ein, von [Codex](https://openai.com/codex/), das sich jetzt selbst Ziele setzt, über [Googles](https://www.google.com/) neuen Standard Agent Resource Discovery bis zu [Claude](https://www.anthropic.com/claude) Design Updates, bevor Tramèr im Interviewausschnitt erklärt, warum die Sicherheitsmaßnahmen rund um [Anthropics](https://www.anthropic.com/) gesperrtes Mythos-Modell und Claude Fable 5 so heikel sind. Er zeigt, wie sich gefährliche Anfragen in harmlose Teilfragen zerlegen lassen, warum die Grenze in der [Cybersicherheit](https://en.wikipedia.org/wiki/Computer_security) zwischen legitimer Code-Analyse und Angriff fließend ist und weshalb übermäßig strenge Filter ein Modell sogar bei der Addition zweier Sicherheitslücken blockieren. Außerdem geht es um die Open-Source-Aufholjagd mit [GLM 5.2](https://z.ai/), das neue 3-Milliarden-Parameter-Modell VibeThinker, eine [Scale-AI](https://scale.com/)-Studie zur produktiven KI-Nutzung, den geplanten Kauf von [Cursor](https://cursor.com/) durch [SpaceX](https://www.spacex.com/) und [Mistral](https://mistral.ai/)-CEO [Arthur Mensch](https://en.wikipedia.org/wiki/Arthur_Mensch). Das vollständige, über einstündige Interview mit Tramèr erscheint separat auf dem [KI-Bubble-Kanal](https://www.youtube.com/@ki-bubble).

## Timestamps

- [00:00](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=0s) – Worum geht es?
- [01:06](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=66s) – Humanoide Roboter
- [03:20](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=200s) – Codex setzt Ziele
- [04:04](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=244s) – Record Replay Skill
- [06:30](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=390s) – Computer Use
- [07:57](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=477s) – Claude CAD Skills
- [08:33](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=513s) – GPT 5.6 Leaks & GPT-Bidi-1
- [10:10](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=610s) – Agent Resource Discovery
- [11:32](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=692s) – Claude Design Updates
- [12:12](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=732s) – Interview Florian Tramèr
- [18:03](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1083s) – VibeThinker 3B
- [18:35](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1115s) – GLM 5.2 überrascht
- [21:38](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1298s) – Open Source Aufholjagd
- [22:19](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1339s) – Chart der Woche
- [25:38](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1538s) – KI Kostenvergleich
- [26:21](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1581s) – SpaceX kauft Cursor
- [27:20](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1640s) – Neues Cursor Modell
- [27:53](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1673s) – ChatGPT im freien Fall
- [28:29](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1709s) – Mistral Ankündigung
- [29:02](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1742s) – Pay per Use Pricing
- [29:21](https://www.youtube.com/watch?v=eg3GcZEnbHQ&t=1761s) – So geht's weiter

## Transcript

### 00:00 – Worum geht es?

**Leonard Schmedding**

Ein unscheinbarer Tweet: [Codex](https://openai.com/codex/) setzt sich jetzt selbst Ziele, ohne dass du /goal eingibst, ohne dass du überhaupt noch prompten müsstest. Du nimmst einfach deine Arbeitsabläufe als Video auf, schmeißt sie in Codex rein und bekommst anschließend einen wiederverwertbaren Skill. Gleichzeitig überholen Open-Source-KI-Modelle jetzt schon [Claude Fable 5](https://www.anthropic.com/claude). Ich zeige dir gleich alles in der Praxis und spreche mit einem der weltweit führenden KI-Sicherheitsforscher, Professor Dr. Florian Tramèr, dessen engster Forschungspartner von [Anthropic](https://www.anthropic.com/) gerade selbst im Weißen Haus war, um über die Mythos-Situation zu diskutieren. Wir sprechen darüber, wieso diese [Jailbreaks](https://en.wikipedia.org/wiki/Jailbreak_(computer_science)) eigentlich so einfach sind, was wirklich dahinter steckt, wie sie funktionieren und wie du dich selbst schützen kannst.

Diese Woche war etwas ruhiger in der KI-Welt, dafür reifen gerade diese ganzen Metatrends, also lokale KI und agentenatives Arbeiten, die die nächsten Monate definitiv dominieren werden. Da freue ich mich, jetzt mit dir etwas tiefer einzutauchen, sodass du die Abkürzung zu allem hast, was jetzt wirklich relevant ist, um Kosten zu sparen und mehr Geld zu verdienen. Mein Name ist Leonard Schmedding, also starten wir rein.

### 01:06 – Humanoide Roboter

**Leonard Schmedding**

Wie immer der ganz kurze Blick darauf, was gerade bei humanoiden Robotern passiert. Diese Woche wurde weniger an der Hardware und viel mehr am Gehirn gearbeitet. Chinesische Forscher haben mit Humanoid-GPT ein auf rund 2 Milliarden Bewegungsframes trainiertes KI-Modell entwickelt, das einen Roboter per [Zero-Shot](https://en.wikipedia.org/wiki/Zero-shot_learning) in Echtzeit per Ganzkörpersteuerung dirigiert und ihn nie trainierte Bewegungen aus dem Stand ausführen lässt, vorgeführt am [Unitree](https://www.unitree.com/) G1, der so von körperlicher Arbeit bis Sport die unterschiedlichsten Aufgaben meistert. Noch einen Schritt weiter geht das Shenzhen-Startup Mind On: Ein einziges Modell dirigiert jetzt mehrere völlig verschiedene Roboterkörper, die zusammenarbeiten, und das ohne eine einzige von Robotern gesammelte Trainingsaufnahme, allein aus dem Beobachten von Menschen gelernt.

Was man jetzt realisieren muss: Tanzroboter sind längst eine eigene Entertainment-Industrie. [LimX Dynamics](https://www.limxdynamics.com/) hat mit Luna einen 1,60 m großen Humanoiden vorgestellt, der ganz auf Unterhaltung und Interaktion ausgelegt ist, also tanzt, gestikuliert und über ein digitales Gesicht echte Mimik zeigt, dazu seine Bewegungen per KI selbst generiert und sich ohne eine einzige Zeile Code programmieren lässt. Für alle, die mal einen Überblick brauchen: Hier siehst du eine aktuelle Marktübersicht über Humanoide vom Juni 2026, und was sofort auffällt, ist, wie sehr das gesamte Feld inzwischen von China dominiert wird.

Genau hier kommt der eigentliche Paukenschlag der Woche: Chinas Regierung hat per Anordnung festgelegt, dass bis zum 31. Dezember 10.000 humanoide Roboter nicht mehr auf der Straße tanzen, sondern in echte Fabriken, Lager, Krankenhäuser und Katastrophenschutz einziehen und dort arbeiten sollen. Sie zwingen die lokalen Behörden schon bis Ende dieses Monats, konkrete Einsatzpläne vorzulegen. Von den über 13.000 Humanoiden, die 2025 weltweit ausgeliefert wurden, kamen rund 90 % aus chinesischer Produktion, verteilt auf über 140 heimische Hersteller und mehr als 330 vorgestellte Modelle.

### 03:20 – Codex setzt Ziele

**Leonard Schmedding**

Aber was, wenn wir der KI jetzt gar keine Ziele mehr selbst vorgeben müssen, sondern sie sich die Ziele selbst setzt? Genau das macht Codex seit dieser Woche. Bisher kannst du mit /goal Codex dein Ziel vorgeben, welches der Agent dann stundenlang, teilweise sogar tagelang abarbeitet. Doch dieses Ziel kann Codex jetzt selbst erkennen und sich selbst setzen. Sie nennen das eine Verallgemeinerung des [Meta-Prompts](https://en.wikipedia.org/wiki/Prompt_engineering), bei der der Agent seine konkrete Aufgabe nicht mehr Schritt für Schritt vorgegeben bekommt, sondern sich allein aus deiner übergeordneten Absicht, also der groben Aufgabenstellung, ableitet. Und [OpenAI](https://openai.com/) sagt, dass sie inzwischen alles, was sie bauen, zugleich als Werkzeug für den Agenten selbst bauen. Eines der wichtigsten Werkzeuge für solche Agenten sind die Skills, und hier gibt es eine echt spannende neue Funktion, hören wir mal rein.

### 04:04 – Record Replay Skill

**Leonard Schmedding**

Aus dem eingespielten Demo-Clip: Unser Team folgt jedes Mal einem Standardprozess, wenn wir ein YouTube-Video veröffentlichen. Manuell müssen wir die Metadaten aus unserer Veröffentlichungstabelle ziehen, die passenden Assets finden und alle Einstellungen in YouTube Studio durchgehen. Diesmal lasse ich Codex zusehen, damit es lernen kann, wie wir es machen. Dabei setze ich Titel und Beschreibung, ergänze Thumbnail sowie englische Untertitel und stelle es auf privat. Wenn ich fertig bin, überprüft Codex die Aufzeichnung und verwandelt das Gelernte in eine Fähigkeit. Es merkt sich, wo unsere Metadaten gespeichert sind, wie das Upload-Paket organisiert ist und wie wir Untertitel hinzufügen, speichern und jeden Upload überprüfen. Jetzt öffne ich einen neuen Thread, hänge das nächste Videopaket an und bitte Codex, es zu übernehmen. Codex weist das Paket der Tabellenzeile zu, füllt Metadaten aus, ergänzt Thumbnail sowie englische Untertitel, lädt das Video privat hoch und prüft abschließend die Speicherung.

Das ist eine wirklich interessante Idee, da man hier mehrere Fähigkeiten von Codex integriert: Videos verstehen, daraus Arbeitsabläufe, also Skills bauen, und dann die [Computer-Use](https://www.anthropic.com/news/3-5-models-and-computer-use)-Fähigkeiten nutzen. Das Ganze ist ein Plugin in Codex, das nennt sich Record and Replay. Anstatt dem Agenten über Prompting oder Spracheingabe zu erklären, was er tun soll, machst du einfach ein Video von deinem Arbeitsablauf, und Codex steuert dann deinen gesamten Computer über Computer Use. Es ist ein Plugin in der Codex App und, wie man unschwer vermuten kann, in der EU noch nicht verfügbar. Ich habe allerdings Zugriff und zeige es dir mal. Du klickst in der Codex App auf Plugins, suchst nach Record Replay, aktivierst es einmal, gehst auf "im Chat ausprobieren" und klickst auf absenden, also: nimm meinen Workflow auf und packe ihn in eine wiederverwertbare Fähigkeit. Codex denkt kurz nach, liest den Skill durch, denn Record and Replay ist letztlich selbst ein Skill, und realisiert: Ich muss die Video-Recording-Funktion öffnen. Mein Screen wird in diesem Moment bereits aufgezeichnet, ich gehe auf die Website, markiere ein paar Texte oder drucke die Website, breche das Ganze wieder ab, und das Recording wird zurück an Codex geschickt, woraus ein wiederverwertbarer Skill gebaut wird.

### 06:30 – Computer Use

**Leonard Schmedding**

Dazu folgende drei Meinungen und Thesen. Erstens: Das ist natürlich echt interessant für alle, die mit lokalen Desktop-Anwendungen arbeiten, vielleicht keine [API](https://en.wikipedia.org/wiki/API)-Anbindung haben, irgendwelche alten Buchhaltungssysteme oder [ERP-Systeme](https://en.wikipedia.org/wiki/Enterprise_resource_planning). Für so etwas kann das durchaus interessant sein, und das liegt oft im deutschen Mittelstand vor. Das ist eben dieser übergeordnete Trend, über den ich schon lange spreche: Öffentliche APIs werden im Agentenzeitalter immer unwichtiger.

Zweitens: Ich persönlich sehe nicht so viele Use Cases dafür. Das Beispiel aus dem Video, der YouTube-Upload, ist etwas spärlich, da das vielleicht 30 Sekunden Zeit spart, die ich den Workflow selbst schneller mache. Und die Frage ist: Will ich wirklich einem Computer-Use-Agenten vollen Zugriff auf meinen gesamten Computer und kritische Systeme wie das YouTube Studio geben? Das ist auch der dritte Gedanke: Ich würde Stand heute definitiv die Finger davon lassen, rein aus [Prompt-Injection](https://en.wikipedia.org/wiki/Prompt_injection)-Gründen. Du musst immer damit rechnen, dass auch du mal von Prompt Injections betroffen wirst, und so berechtigst du Codex den Zugriff per Computer Use auf deinen gesamten Rechner, und das ist etwas, das man nicht haben will. Oft ist es gar nicht nötig: Du kannst fast immer über agentenatives Arbeiten diese Computer-Use-Einstellung mit dem gleichen Effekt völlig vermeiden. Ich werde dir gleich noch ein Praxisbeispiel dazu zeigen.

### 07:57 – Claude CAD Skills

**Leonard Schmedding**

Viel relevanter sind natürlich die Skills. Ein interessantes Beispiel im [Text-to-CAD](https://en.wikipedia.org/wiki/Computer-aided_design)-Kontext: Man stellt jetzt fest, dass Skills Agenten dabei helfen, besser im CAD zu sein. Ein User hat die CAD-Gen-Bench durchlaufen lassen und dabei 0,04 Punkte besser abgeschnitten als die Standardmodelle, einfach nur dadurch, dass er Text-to-CAD-Skills verwendet hat. Da muss man sich fragen: Sind meine Arbeitsabläufe, ist vielleicht mein ganzes Unternehmen, meine ganze Idee nicht einfach nur eine [Markdown](https://en.wikipedia.org/wiki/Markdown)-Datei, ein wiederverwertbarer Skill, den ein Agent ausführen kann?

### 08:33 – GPT 5.6 Leaks & GPT-Bidi-1

**Leonard Schmedding**

Wie weit das gehen kann, zeigen diese Leaks von GPT 5.6 Pro, das schon nächste Woche veröffentlicht werden könnte. Besonders wichtig für diese Superagenten ist natürlich auch das Sprechen mit ihnen. Hier wird es sehr zeitnah ein großes Update von OpenAI geben, mit dem GPT-Bidi-1-Modell. Der Name könnte sich noch ändern, es handelt sich um einen Leak, aber wie der Name durchklingen lässt, geht es um ein bidirektionales Modell. Das bedeutet, das Modell kann gleichzeitig zuhören und sprechen und auch Tool Calls ausführen. Aktuelle Voice-Modelle, auch der Advanced Voice Mode, den du heute kennst, sind meist halb-duplex, das heißt, sie sprechen oder hören zu. Sobald du das Modell unterbrichst, frieren sie oft kurz ein oder brauchen einen Moment, bis sie wieder reagieren. Bidi-1 soll echt [duplex](https://en.wikipedia.org/wiki/Duplex_(telecommunications)) sein: Es hört kontinuierlich zu, verarbeitet Unterbrechungen in Echtzeit und kann mitten im Satz umschwenken.

Ich weiß nicht, ob es dir auch schon aufgefallen ist: Wenn du den Advanced Voice Mode nutzt, kann es sein, dass da schon getestet wird, oder vor allem das neue GPT-Realtime-2-Modell ist schon dramatisch besser. Ich habe die letzten ein, zwei Wochen deutlich bessere Erfahrungen gemacht, vor allem, wenn du Internetrecherchen machen lässt. Wenn du sagst, recherchiere dies und jenes, kann das Modell das jetzt gleichzeitig tun, während es mit dir spricht. Und Bidi-1 geht noch einen Schritt weiter. Die nächsten Voice-AI-Durchbrüche stehen also echt kurz bevor. Zudem soll ChatGPT dann wohl ein iPad oder einen Orb triggern, und dadurch wird die Nutzererfahrung in dieser neuen Super-App noch spielerischer gestaltet.

### 10:10 – Agent Resource Discovery

**Leonard Schmedding**

Dein großes Problem, zumindest ein Token-Fresser, ist häufig: Wenn du deine Agenten Dinge automatisieren lassen möchtest, müssen sie erst einmal recherchieren, ob ein Tool einen [MCP-Server](https://modelcontextprotocol.io/) hat, ob es ein CLI-Tool hat, ob es Skills hat. Das verschlingt unfassbar viel Zeit und viele Tokens. Genau dieses Problem adressiert jetzt [Google](https://www.google.com/) mit einem neuen offenen Standard: Agent Resource Discovery, kurz ARD. Das sieht im Wesentlichen so aus: Du hinterlegst bei deiner Website, wenn du ein Agent-Tool anbietest. Ein einfaches Beispiel: Sagen wir, du bist eine Fluggesellschaft wie [Lufthansa](https://www.lufthansa.com/), und wieso sollte ein Mensch heutzutage noch Flüge buchen? Macht keinen Sinn. Du bietest Skills an, du bietest MCPs an, du hast gewisse Verifizierungen, und dann stellst du das unter diesem offenen Standard bereit. Du richtest das .well-known-Verzeichnis ein und darunter den AI-Catalog. Darin befinden sich dann die Fähigkeiten: MCP-Server, [Agent2Agent](https://a2aproject.github.io/A2A/), das ist ja auch ein Google-Protokoll, Open-API-Tools, die Signaturen, die Identität, also dass du die Domain besitzt. Wenn das wirklich zum Branchenstandard wird, bedeutet das, dass deine Agenten wie Codex oder [Claude Code](https://www.anthropic.com/claude-code) einfach immer nach diesen Katalogen schauen und du nie wieder selbst nach MCPs oder sonstigem suchen musst. Letztendlich ist das nur ein weiterer von vielen Schritten in Richtung Agent Economy und Agent Web.

### 11:32 – Claude Design Updates

**Leonard Schmedding**

Standardisierter arbeitest du jetzt auch in Claude Design: Du kannst dein Branddesign jetzt in Claude Design speichern, und das wird dann über alle Ressourcen und Projekte hinweg angewandt, ohne dass du es immer wieder explizit vorgeben musst. Zudem gibt es jetzt Artefakte in der Beta im Teams- und Enterprise-Plan in Claude Code. Die Artefakte, wie du sie sicher schon aus der Web-App kennst, die visuellen Ansichten deiner Minis, deiner Dashboards, deiner Websites, deines Codes, den du von Claude schreiben und testen lässt, das gibt es jetzt auch als Artefakt innerhalb von Claude Code. Besonders spannend wird es, wenn es auch an die Pro- und Max-Pläne ausgerollt wird, die wahrscheinlich die meisten von uns haben.

### 12:12 – Interview Florian Tramèr

**Leonard Schmedding**

Die größten News spielen sich natürlich rund um die Mythos- und Fable-5-Situation ab. Wer weiß, vielleicht ist bei Veröffentlichung dieses Videos Fable 5 schon wieder live, es ist eine sich laufend weiterentwickelnde Story. Deswegen ist es besonders spannend, mal darüber zu sprechen: Was sind eigentlich diese Jailbreaks, was hat es damit auf sich, und wieso wurde das Modell seitens der US-Regierung gesperrt? Diese Frage reiche ich direkt weiter an Professor Dr. Florian Tramèr von der ETH Zürich, der seit 10 Jahren im Bereich AI Security unterwegs ist und uns das Ganze in einfachen Worten erklärt.

**Prof. Dr. Florian Tramèr**

Das Problem ist, dass diese Maßnahmen, mit denen man versucht, dass die Modelle keine gefährlichen Antworten geben, nie hundertprozentig sicher sind. Und da kommen eben die Jailbreaks. Einen Jailbreak kann man so verstehen: Das ist einfach eine Art und Weise, das Modell zu tricksen, sodass es eine Aufgabe dann trotzdem löst, weil es nicht merkt, dass das eigentlich etwas Gefährliches sein könnte. Oder indem man eine gefährliche Frage nimmt und sie in verschiedene Teile zerteilt, das Modell die verschiedenen Teile unabhängig löst und nicht merkt, dass das alles zusammen zu einem Puzzle führt, das eigentlich sehr gefährlich sein könnte.

Es ist ein sehr schwieriges Thema, weil in gewissen Bereichen die Grenze zwischen etwas, das okay ist, und etwas, das nicht okay ist, eigentlich ziemlich klar ist. Wenn ich jetzt zu einem Chatbot gehe und sage, erkläre mir, wie ich eine Bombe bauen kann, ist das wahrscheinlich nicht etwas, worauf ein Chatbot eine Antwort geben muss. In der Cybersicherheit gibt es aber sehr wenig Unterschied zwischen Fragen, die eigentlich jeder Software-Ingenieur irgendwann stellen möchte, also: Wie kann ich diesen Code verbessern? Gibt es in meinem Code irgendwelche Fehler, die ich beheben sollte? Und für einen Angriff nimmt man einfach einen anderen Code und sagt: Hier ist der Code vom [Linux](https://en.wikipedia.org/wiki/Linux)-Betriebssystem, gibt es da eine Lücke drin? Es ist eigentlich dasselbe.

Da haben sich auch ziemlich viele Leute ein bisschen Sorgen gemacht mit diesem Fable, weil die Maßnahmen, die Anthropic genommen hat, so streng waren, dass man dem Modell quasi nur das Wort Cybersicherheit oder Biologie oder Chemie sagen musste, und dann sagte es: Nein, da kann ich nicht helfen. Ich habe auch Beispiele gesehen, wo jemand fragt: Ich habe eine Sicherheitslücke und eine zweite Sicherheitslücke, wenn ich diese addiere, wie viele Sicherheitslücken habe ich dann? Und das Modell sagt: Nein, das kann ich nicht helfen, das ist gefährlich. Da merkt man, diese Art und Weise, diese Modelle zu kontrollieren, was sie machen sollen und was nicht, ist eine Wissenschaft. Man trainiert das Modell einfach auf gewissen Fällen und versucht dann, eine Balance zu finden zwischen Modellen, die hilfreich sind, und solchen, die manchmal Antworten geben, die sie eigentlich nicht sollten. Aber die gute Grenze zu finden, ist ziemlich schwierig. Und dann kommen noch diese direkten Angriffe dazu, diese Jailbreaks, die alles noch schwieriger machen.

Ich war in den Ferien, als Fable 5 rauskam, habe es aber trotzdem ein bisschen ausprobiert und gewisse Sachen gefragt. Ich habe dem Modell einen Draft von einem Artikel gegeben, den ich gerade über KI-Sicherheit schrieb. Dann hat es sehr gute Kommentare gegeben, und plötzlich sagt es: Ah, aber da gibt es auch noch eine Möglichkeit, deine Argumente und deine beschriebene Attacke auf KI-Modelle viel besser zu machen, zu verstärken. Und dann wurde der Chat abgebrochen. Da war ich ein bisschen enttäuscht, und das war eben, weil sie für dieses Modell sehr starke Sicherheitsmaßnahmen benutzen.

So wie ich es verstehe, haben sie dieses Mythos-Modell trainiert, das sehr starke Fähigkeiten in gewissen Bereichen hat, die gefährlich sein könnten, also in der Cybersicherheit, vielleicht auch in der Biologie und Chemie. Das Problem ist: Wenn man diese KI-Modelle trainiert, sind sie zuerst einfach so trainiert, dass sie hilfreich sind, dass man zu einem Claude-Modell oder zu [ChatGPT](https://chatgpt.com/) gehen und sagen kann: Hey, gib mir Auskunft, wie ich dieses Problem lösen kann. Und dann kann man diese Modelle natürlich auch um Auskunft oder Hilfe für Sachen bitten, die eigentlich ein bisschen gefährlich sein könnten. In der Cybersicherheit ist das ein großes Thema, weil diese KI-Modelle, vor allem die von Anthropic, sehr gut im Programmieren sind. Seit etwa sechs Monaten hat es da wirklich einen großen Aufschwung gegeben. Aber ein KI-Modell, das versteht, wie man gut programmiert, versteht eben auch, wie man Lücken in Code finden kann. Und das ist natürlich ein Problem, wenn man das für Angriffe benutzen kann. Für Zwecke, die nicht gut sein könnten, ist das Modell einfach trainiert, um Nein zu sagen. Und im Fall von Fable war es so eingestellt, dass, wenn Fable sagte, nein, das kann ich nicht machen, das Modell quasi durch das alte Opus-Modell ausgetauscht wurde, und dann gab ein eigentlich schwächeres Modell die Antwort.

**Leonard Schmedding**

Wirklich super spannend. In Summe habe ich über eine Stunde mit Florian Tramèr gesprochen. Das ganze Interview wird schon nächste Woche auf dem [KI-Bubble-Kanal](https://www.youtube.com/@ki-bubble) von uns zu sehen sein. Im Übrigen wird nächste Woche der letzte Live Agentic Coding Workshop stattfinden. Wenn du es bisher nicht geschafft hast, dann nutze jetzt deine letzte Chance. Den Link findest du in der Videobeschreibung oder einfach auf aicoding.de. Sichere dir deinen Platz, und dann sprechen wir nächste Woche live darüber, wie du Agentic Coding jetzt für dich einsetzt, um wirklich produktionsreife Apps zu bauen.

### 18:03 – VibeThinker 3B

**Leonard Schmedding**

Immer schneller geht es jetzt auch im Bereich Open Source voran. Ein neues 3-Milliarden-Parameter-Modell, also ein Modell, das wirklich jeder auf seiner Hardware laufen lassen kann, nennt sich VibeThinker. Es soll im Bereich Vibe Coding besonders gut sein und schneidet wie so häufig auf einigen Benchmarks auch echt gut ab, wie man hier sieht. Ich habe es getestet, und die Ergebnisse gerade im Agentic Coding sind ernüchternd. Höchstens, wenn du Mathematikaufgaben hast und solche Modelle lokal laufen lassen möchtest, könnte es interessant sein. Für reale Coding-Aufgaben sicherlich nicht.

### 18:35 – GLM 5.2 überrascht

**Leonard Schmedding**

Viel spannender ist [GLM 5.2](https://z.ai/). Dieses Modell ist auch Open Source und jetzt überall verfügbar. Es hat ein Kontextfenster von einer Million Tokens. Du siehst hier ein erstes Ergebnis, eine 3D-Uhr, das gleiche Ergebnis, das auch GPT 5.6 Pro vorhin nachgebaut hat, aber hier kann GLM 5.2 definitiv mithalten. Und auf der Design Arena räumt GLM 5.2 sogar den ersten Platz ab. Nur noch mal zur Erinnerung: Die Design Arena ist kein wirklich gut manipulierbarer Benchmark, denn die User bestimmen ja selbst, welches Modell die besten Designs liefert. Deswegen habe ich das natürlich selbst getestet. Wenn du letzte Woche dabei warst, erinnerst du dich, dass das die Website von Claude Fable 5 war, also One-Shot von Claude Fable 5, ein echt solides Design. Claude Fable 5 ist für mich persönlich das beste Modell, das ich je für Websites und Front-End-Designs genutzt habe. Hier links daneben siehst du jetzt GLM 5.2, und ich muss sagen, das Modell kann definitiv mithalten. Es braucht sich in keinster Weise vor Opus oder auch Claude Fable 5 zu verstecken. Fairerweise muss ich auch sagen: 100 % kommt das Modell für mich nicht an Fable 5 heran, und gerade Design ist immer etwas subjektiv.

### 21:38 – Open Source Aufholjagd

**Leonard Schmedding**

Deswegen fasst das hier auch meine Erfahrung perfekt zusammen: Nach fast einem ganzen Tag des Testens von GLM 5.2 gibt es keinen Weg, dass irgendjemand noch glaubt, dass Open-Weight-Modelle 6 bis 8 Monate hinterherhängen. Ich würde sagen, es ist nur noch eine Veröffentlichung davon entfernt, GPT 5.5 oder Opus 4.8 ernsthaft herauszufordern. Und der gruselige Teil für OpenAI und Anthropic ist nicht, dass GLM bereits heute überall gewinnt, sie liegen ja immer noch vorne, aber der Abstand fühlt sich nicht mehr unantastbar an. GLM muss sie nicht meilenweit schlagen, es muss nur nah genug herankommen, denn sobald die Intelligenz nah wirkt, wird der Preis zum entscheidenden Faktor.

Genau das ist jetzt wichtig: unabhängig von einzelnen Anbietern zu sein. Genau dafür sind [Corporate-LLM](https://corporatellm.de/)-Systeme gedacht. Du kannst GLM 5.2 natürlich auch hier nutzen. Genauso wie du lokale Modelle kostenlos und unlimitiert anbinden kannst, kannst du auch GLM 5.2 kostenlos und unlimitiert im Corporate LLM anbinden. Du gehst einfach auf Modelle und nutzt z. B. [OpenRouter](https://openrouter.ai/), wo GLM 5.2 schon vorgeschlagen wird. Du klickst auf aktivieren, stellst sicher, dass du GLM 5.2 erlaubt hast, gehst zurück in deine Modelle und findest jetzt unten neben deinen lokalen Modellen auch GLM 5.2 und kannst es zusammen mit allen anderen Modellen innerhalb deines gesamten Workspaces nutzen. Du kannst es sogar lokal probieren, wenn du die richtige Hardware hast. Das normale Modell hat über eine Billion Parameter, damit wird es nichts, aber [Unsloth AI](https://unsloth.ai/) hat eine auf 2 Bit [quantisierte](https://en.wikipedia.org/wiki/Quantization_(signal_processing)) Version mit 82 % Genauigkeit bereitgestellt, und die läuft auf einem 256-GB-Mac. Wenn du z. B. ein Mac Studio mit 256 GB hast, könntest du es sogar komplett lokal betreiben.

[Elon Musk](https://en.wikipedia.org/wiki/Elon_Musk) wurde gefragt, wie weit Open-Source-AI aus China wirklich noch hinter Mythos-Level-Modellen hinterherhinkt, und er schreibt: wahrscheinlich Q1 2027. Daraufhin antwortet der Gründer von Z.ai, also von GLM, dass sie noch dieses Jahr Mythos-Level-Fähigkeiten erreichen werden. Das macht auch nur Sinn, denn wenn man sich zahlreiche Studien anschaut, hinken Open-Source-Modelle nur noch drei bis vier Monate hinterher.

### 22:19 – Chart der Woche

**Leonard Schmedding**

Damit kommen wir zu einer neuen Sektion in diesen KI-News, dem Chart der Woche. Es schaffen erstaunlich wenige Unternehmen, KI heute wirklich produktiv einzusetzen. Diese Zahl ermittelt [Scale AI](https://scale.com/) in seiner neuesten Studie. Dabei haben sie 494 Organisationen untersucht, und davon schaffen es gerade einmal 32, also 6,5 %, KI wirklich zum Laufen zu bringen, und das nach folgender Definition: Erstens, KI ist über die meisten Funktionen hinweg im Unternehmen integriert. Zweitens, mehr als die Hälfte der Pilotprojekte landet in echter Produktion. Drittens, die eigenen Ziele werden deutlich übertroffen. Der eigentliche Erfolgsfaktor dieser nur 6,5 % der Unternehmen ist dabei vor allem die Geschwindigkeit, denn 53 % bringen ihre Piloten in unter 6 Monaten in Produktion, und zwei Drittel sehen in derselben Zeit ein messbares Geschäftsergebnis, also mehr als doppelt so oft wie der ganze Rest des Marktes. Genau das ist entscheidend, denn fertige Tools von der Stange tauchen bei nur 6 % dieser Erfolge auf. Das bedeutet, die echten Gewinner bauen dreimal so oft hybrid, also intern zusammen mit einem strategischen Partner, statt mit irgendeinem Tool von der Stange. Die erfolgreichsten Unternehmen integrieren ihre KI also gemeinsam mit Partnern, anstatt mit irgendwelchen Standard-Tools. Das Überraschende dabei: Für diese 6 % ist Führungssupport der unwichtigste Beschleuniger, weil sie ihn längst haben. Der wahre Hebel sind eigene Daten, deren Architektur sie festlegen, bevor sie überhaupt eine Zeile Code schreiben. Genau das, was ich hier immer wieder predige: Du brauchst erst einmal ein solides Datenfundament, einen Wissensspeicher, auf den du deine KI-Systeme dann draufsetzt.

Und zurück zum Computer-Use-Beispiel von mir, weil das ein Workflow ist, den du vielleicht kennst: Hier auf der Website kannst du den Report als PDF downloaden. Dafür musst du nach unten gehen, deinen Namen eintragen, eine E-Mail hinterlegen, dann landest du im E-Mail-Newsletter, musst dich wieder abmelden, die PDF herunterladen, irgendwo hochladen, wieder öffnen. Das brauchst du nicht mehr zu machen, das ist agentenatives Arbeiten. Ich habe Claude Code einfach gesagt: Zieh mir die PDF von dieser Website. Das hat im ersten Moment nicht funktioniert, logischerweise, er konnte sich ja nicht einloggen. Dann habe ich gesagt: Hol dir die PDF über AgentMail. Das ist ein E-Mail-Postfach, das du deinen Agenten wie Claude Code geben kannst. Ich habe ihm nicht mal meinen Account bei AgentMail gegeben, das heißt, er hat selbst einen neuen Wegwerf-Account unter AgentMail erstellt, hat über Browser Use die Daten eingetragen, dann die E-Mail-Adresse von AgentMail genutzt, aus seinem E-Mail-Postfach die PDF heruntergeladen und anschließend bei mir im Browser geöffnet. Und das ist genau das, was ich meine, wenn ich sage, du brauchst oft gar keinen Computer Use, weil es mittlerweile zahlreiche dieser Agent Building Blocks gibt. Man nennt es auch die Building Block Economy. Mach dir also Gedanken, das haben wir auch mit ARD von Google diese Woche gesehen: Wie kannst du deine Agenten noch nützlicher machen? Über Skills, Tools und Fähigkeiten, die du deinen Agenten gibst, sodass du Nutzeroberflächen und Browser gar nicht mehr verwenden brauchst. Das ist der größte gedankliche Shift, den man machen sollte: dass du heute nie mehr irgendwelche Nutzeroberflächen oder Tools manuell bedienen musst, weil es immer Wege gibt, über MCP, über API, über CLI, über Browser Use, vielleicht im Zweifel Computer Use, die Aufgabe von deinem Agenten erledigen zu lassen. So muss heute jeder einzelne Arbeitsprozess hinterfragt werden, und genau das machen auch diese 6 %.

### 25:38 – KI Kostenvergleich

**Leonard Schmedding**

Eine weitere Zahl, weil das immer wichtiger wird, sind natürlich die Kosten. Hier hat jemand gemessen, wie viele Tokens ich mir für einen bestimmten Betrag kaufen kann. Fairerweise muss ich sagen, das ist nicht sonderlich aussagekräftig, weil [Reasoning](https://en.wikipedia.org/wiki/Reasoning_system)-Tokens dir z. B. relativ wenig bringen. Im Endeffekt ist nur interessant, wie gut das Ergebnis für den Preis ist, den du bekommst, und nicht, wie viele Tokens du bekommst. Aber nichtsdestotrotz ist es ein spannender Indikator: Für die gleichen 3.000 $ kannst du fast sechsmal so viel Tokens bei GLM 5.2 einkaufen wie bei Opus 4.8, und bei [DeepSeek](https://www.deepseek.com/) etwa das 30-fache.

### 26:21 – SpaceX kauft Cursor

**Leonard Schmedding**

Damit kommen wir noch mal zur Sektion des AI-Dramas: [SpaceX](https://www.spacex.com/) kauft [Cursor](https://cursor.com/) für 60 Milliarden US-Dollar. Kurz zur Rekapitulation: SpaceX hatte sich im Vorjahr zunächst das Kaufrecht an Cursor für 60 Milliarden gesichert. Sie hätten für 10 Milliarden auch wieder einen Rückzug machen können, aber dagegen entscheidet man sich jetzt und möchte Cursor wirklich für 60 Milliarden einkaufen. Besonders spannend wird es in dieser neuen Ankündigung von Cursor, und sie unterscheidet sich in drei Punkten: Erstens ist es groß, genauso groß wie Opus und GPT. Zweitens ist es eigenständig trainiert und basiert nicht auf Open-Source-Modellen. Aus der Ankündigung: Wir schätzen Open Source sehr, doch ein Training von Grund auf erlaubt uns volle Kontrolle und eine bessere Optimierung für ihre spezifischen Arbeitslasten. Entscheidend ist, dass wir mit der 10- bis 20-fachen Leistung arbeiten, die wir je hatten. Unser letztes Modell nutzte zwar mehr als zuvor, aber diesmal skalieren wir die Rechenleistung wirklich massiv hoch.

### 27:20 – Neues Cursor Modell

**Leonard Schmedding**

Cursor hat soeben ein 1,5-Billionen-Parameter-Modell angekündigt, das offen mehr als 100.000 [GPUs](https://en.wikipedia.org/wiki/Graphics_processing_unit) im Pretraining nutzte. Damit ist ein weiterer Spieler im Markt, und das könnte die große Chance für ein riesiges Comeback auch von Cursor im Bereich Agentic Coding sein. Genau deswegen, so habe ich es schon vor Monaten gesagt, will SpaceX Cursor kaufen, weil sie unfassbar wertvolle Daten aus den ganzen User-Sessions haben, die reale Coding-Anwendungen bauen. Mehr Konkurrenz im Agentic Coding ist natürlich zu befürworten.

### 27:53 – ChatGPT im freien Fall

**Leonard Schmedding**

Gleichzeitig fällt auch der Marktanteil von ChatGPT jetzt erstmals unter 50 %. Man sieht hier etwa seit Anfang dieses Jahres auch den starken Anstieg durch Claude sowie durch [Google Gemini](https://gemini.google.com/). Claude befindet sich jetzt bei 10,3 % Marktanteil, wohingegen ChatGPT auf 46,4 % gefallen ist, also erstmals unter die 50-%-Marke. Das zeigt, wie wichtig es jetzt ist, immer modellagnostischer zu werden und nicht alles auf eine Karte und auf ein System zu setzen, sondern eben ein Corporate-LLM-System, in dem du alle Modelle integriert hast.

### 28:29 – Mistral Ankündigung

**Leonard Schmedding**

So wie vielleicht auch bald [Mistral](https://mistral.ai/), wenn es gut läuft. Denn [Arthur Mensch](https://en.wikipedia.org/wiki/Arthur_Mensch), der CEO von Mistral, sagt: Wir werden ein schönes Modell diesen Sommer lancieren. Es wird definitiv eine Überraschung sein, es wird neue Fähigkeiten haben und definitiv groß sein. Early Access gibt es ab Juli. Man kann nur hoffen, dass endlich mal ein vernünftiges Modell von Mistral kommt, denn das aktuell führende Mistral-Modell ist nicht mal so gut wie GPT 5.4 Nano und dabei etwa 14-mal so teuer. Damit kann in der Praxis natürlich kein Mensch ernsthaft etwas anfangen.

### 29:02 – Pay per Use Pricing

**Leonard Schmedding**

Und [Polymarket](https://polymarket.com/) schreibt, dass OpenAI, Anthropic und andere jetzt ein Pay-per-Use-Pricing einführen planen. Die Pläne rücken in immer weitere Nähe, und die subventionierten AI-Pläne in Codex und Claude Code könnten schon bald für immer der Vergangenheit angehören.

### 29:21 – So geht's weiter

**Leonard Schmedding**

Umso wichtiger wird es jetzt, sich mit lokaler KI auseinanderzusetzen, wenn auch nur als Versicherung. Jeder braucht jetzt eine lokale KI-Backup-Strategie, und genau dazu habe ich diese Woche ein 30-minütiges ausführliches Video aufgenommen über alles, was du jetzt darüber wissen musst. Das habe ich dir hier noch mal verlinkt. Und wenn du noch mehr über die Chip-Durchbrüche aus China erfahren möchtest, die diese Open-Source-Modelle überhaupt erst möglich machen, dann schau gerne mal in dieses Video hier mit Wolfgang Hirn. Ich freue mich, dich dort wiederzusehen. Bis dahin, mach's gut. Ciao.

---

Quelle: https://www.youtube.com/watch?v=eg3GcZEnbHQ
