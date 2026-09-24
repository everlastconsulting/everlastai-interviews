# Stefan Faistenauer × Leonard Schmedding Interview

Stefan Faistenauer · Co-Founder [Superglue AI](https://superglue.ai/) · [@everlastai](https://www.youtube.com/@everlastai) · 2026-04-01 · 51 Min · Deutsch · [YouTube](https://www.youtube.com/watch?v=YRmZnooY92g)

[Stefan Faistenauer](https://www.linkedin.com/in/stefan-faistenauer/) ist Co-Founder von [Superglue AI](https://superglue.ai/), einer agentischen Integrationsplattform aus München, die im [Y Combinator](https://www.ycombinator.com/) Batch Winter 2025 gestartet ist. Stefan hat am [CDTM](https://www.cdtm.de/) der [TU München](https://www.tum.de/) studiert, danach einen Master an der [Stanford University](https://www.stanford.edu/) absolviert und war Associate Product Manager im legendären [Google APM Programm](https://en.wikipedia.org/wiki/Associate_Product_Manager_program) in Zürich. Im Gespräch geht es um die Frage, warum erst etwa 5% der Unternehmen [KI-Agenten](https://en.wikipedia.org/wiki/Intelligent_agent) wirklich produktiv nutzen, wie [Glue Code](https://en.wikipedia.org/wiki/Glue_code) zwischen [ERP](https://en.wikipedia.org/wiki/Enterprise_resource_planning), [CRM](https://en.wikipedia.org/wiki/Customer_relationship_management) und [APIs](https://en.wikipedia.org/wiki/API) jedes Unternehmen bremst, warum [n8n](https://n8n.io/) und [Zapier](https://zapier.com/) trotz [Claude Code](https://www.anthropic.com/claude-code) relevant bleiben, weshalb Stefan auf [Open Source](https://en.wikipedia.org/wiki/Open_source) setzt, warum [MCP](https://modelcontextprotocol.io/) trotz aktueller Skepsis auf Twitter der Standard für Remote Tool Execution bleibt und wie [Anthropic](https://www.anthropic.com/) mit dem [Skills](https://www.anthropic.com/news/agent-skills)-Konzept das Context-Bloat-Problem löst. Wir sprechen außerdem über die Unterschiede zwischen dem Ökosystem in [San Francisco](https://en.wikipedia.org/wiki/San_Francisco) und München sowie über den Appell, in Deutschland deutlich lauter darüber zu reden, was hier gebaut wird.

## Timestamps

- [00:00](https://www.youtube.com/watch?v=YRmZnooY92g&t=0s) – YC-Gründer aus München
- [01:35](https://www.youtube.com/watch?v=YRmZnooY92g&t=95s) – Stefans Werdegang
- [04:13](https://www.youtube.com/watch?v=YRmZnooY92g&t=253s) – Google APM Programm
- [06:12](https://www.youtube.com/watch?v=YRmZnooY92g&t=372s) – Y Combinator
- [10:21](https://www.youtube.com/watch?v=YRmZnooY92g&t=621s) – Agentic Workflows
- [13:22](https://www.youtube.com/watch?v=YRmZnooY92g&t=802s) – Das Glue Code Problem
- [15:38](https://www.youtube.com/watch?v=YRmZnooY92g&t=938s) – Zukunft von n8n und Zapier
- [17:52](https://www.youtube.com/watch?v=YRmZnooY92g&t=1072s) – Braucht es Workflow-Plattformen noch?
- [19:19](https://www.youtube.com/watch?v=YRmZnooY92g&t=1159s) – Self-Healing Integrationen
- [21:20](https://www.youtube.com/watch?v=YRmZnooY92g&t=1280s) – Warum Open Source?
- [24:40](https://www.youtube.com/watch?v=YRmZnooY92g&t=1480s) – MCP: Ein Auslaufmodell?
- [29:21](https://www.youtube.com/watch?v=YRmZnooY92g&t=1761s) – Nächste Trends in AI Agents
- [34:35](https://www.youtube.com/watch?v=YRmZnooY92g&t=2075s) – Das Bottleneck
- [37:36](https://www.youtube.com/watch?v=YRmZnooY92g&t=2256s) – Wie Unternehmen 2030 arbeiten
- [42:13](https://www.youtube.com/watch?v=YRmZnooY92g&t=2533s) – San Francisco vs. München
- [47:29](https://www.youtube.com/watch?v=YRmZnooY92g&t=2849s) – Appell

## Transcript

### 00:00 – YC-Gründer aus München

**Stefan Faistenauer**

Jetzt, wo die Infrastruktur da ist, wo sie ist, macht es total viel Sinn, sich als Unternehmen zu überlegen: wo sind meine Hebel, wo kann ich mit AI 5x, 10x besser werden und dann vielleicht sogar meiner Konkurrenz einen Schritt voraus sein. Wir haben es Stand heute mit so übermächtigen Tools zu tun. Wir sehen es jeden Tag selbst: du kannst heute ganze Stellen komplett wegrationalisieren. So ehrlich müssen wir sein. Die Hauptchallenge ist nicht, wie machen wir AI besser, sondern wie bringe ich AI so ins Unternehmen, dass ich im Endeffekt wirklich einen krassen Benefit daraus habe. Die Technologie ist da, und die Anwendung ist etwas, das uns wahrscheinlich die nächsten 5 bis 10 Jahre mindestens begleiten wird. AI is here to stay.

**Leonard Schmedding**

Stefan, ich freue mich, dass wir heute gemeinsam sprechen.

**Stefan Faistenauer**

Ich mich auch.

### 01:35 – Stefans Werdegang

**Leonard Schmedding**

Stefan, du hast an der [TU München](https://www.tum.de/) studiert, unter anderem am [CDTM](https://www.cdtm.de/), also dem gleichen Programm, aus dem [Personio](https://www.personio.de/) und [Trade Republic](https://traderepublic.com/) und einige der erfolgreichsten deutschen Startups und Unicorns hervorgegangen sind. Danach hast du einen Master an der [Stanford University](https://www.stanford.edu/) gemacht, warst Associate Product Manager bei [Google](https://www.google.com/) und hast jetzt mit deinem KI-Startup Superglue den [Y Combinator](https://www.ycombinator.com/) Batch Winter 2025 durchlaufen. Wir werden gleich über all diese Themen sprechen, auch über euer Startup. Kannst du uns vielleicht zunächst selbst noch einmal durch die wichtigsten Stationen deines Werdegangs führen?

**Stefan Faistenauer**

Du hast eh schon das Wichtigste aufgezählt. Ich versuche ein bisschen Kontext zu geben. Ich bin in [Innsbruck](https://en.wikipedia.org/wiki/Innsbruck), Österreich aufgewachsen, also gar nicht so weit weg, und habe sehr früh angefangen zu coden. Mit 12 habe ich angefangen, Webseiten zu bauen, mit 15 meinen ersten [Linux](https://en.wikipedia.org/wiki/Linux)-Server aufgesetzt, und von da an ging es immer weiter. Irgendwann habe ich gemerkt: ich will eigentlich Produkte bauen, nicht nur coden. Deswegen habe ich mich entschieden, nicht Informatik zu studieren, sondern TUM-BWL, einen sehr uniken Studiengang in München, was sich als sehr gute Entscheidung herausgestellt hat.

Was meine Journey am stärksten beeinflusst hat: ich habe ein Praktikum bei [Luminovo](https://luminovo.com/) gemacht, einem Münchner Startup, das inzwischen Electronic Supply Chain macht, damals war es General Purpose AI Consulting. Das war 2018, also vor dem großen AI-Hype. Die beiden Gründer waren sowohl CDTM als auch Master in Stanford. Da habe ich gesagt: that's the life I want to have, I want to go to CDTM, I want to go to Stanford and I want to be a founder. Siebeneinhalb Jahre später hat das alles mehr oder weniger geklappt. Im CDTM habe ich meine Co-Founderin kennengelernt, danach bin ich nach Stanford gegangen, dann zu Google nach Zürich für eineinhalb Jahre, und dann ging es richtig los mit Superglue.

### 04:13 – Google APM Programm

**Leonard Schmedding**

Mega interessant, dass du schon mit 12 angefangen hast zu coden. Zunächst noch einmal zum [Google APM Programm](https://en.wikipedia.org/wiki/Associate_Product_Manager_program). Das ist eines der kompetitivsten Nachwuchsprogramme. [Google](https://www.google.com/)-Alumni haben rund 295 Milliarden eingesammelt, über 5000 erfolgreiche Unternehmen wurden gegründet. Trotzdem kennen das viele gar nicht so richtig. Worum geht es genau bei Google APM?

**Stefan Faistenauer**

Das ist grundsätzlich ein Product-Manager-Programm, das Leute dazu ausbildet, Product Manager zu werden. Wichtig ist zu verstehen: es wurde 2005 gegründet von [Marissa Mayer](https://en.wikipedia.org/wiki/Marissa_Mayer), die später [Yahoo](https://www.yahoo.com/) übernommen hat. Product Manager als Konzept gab es 2005 noch nicht wirklich. Es gab Engineering-heavy Organizations, ein paar Designer, und Product war eigentlich eine Leadership-Function, die irgendwo zwischen die Stühle gefallen ist. Google hat gemerkt: da fehlt eine Rolle, die wirklich End-to-End Product Leadership übernimmt, nicht nur technische Aufgaben, sondern Planung, Strategy, Execution. Sie haben das Programm aufgesetzt, um neue Leute mit frischen Ideen reinzubringen, die Across Tech, Across Design, Across Business Kompetenzen mitbringen, und sich so eine starke Product Leadership aufgebaut. Das wurde später sehr breit kopiert von allen möglichen Tech Companies. Es ist gerade im Umbruch durch den Advent of AI und Building Fast, hat sich aber als Industriestandard etabliert.

### 06:12 – Y Combinator

**Leonard Schmedding**

Super spannend. Ich würde gerne noch über [Y Combinator](https://www.ycombinator.com/) sprechen. Ich hatte ja schon einige YC-Gründer auf dem Kanal, auch letztes Jahr in San Francisco. Es ist ein sehr hartes Auswahlverfahren. [Garry Tan](https://en.wikipedia.org/wiki/Garry_Tan) hat letztens gesagt, sie bekommen rund 80.000 Bewerbungen im Jahr, davon nehmen sie 700 bis 800. Also etwa 1% der Gründer werden überhaupt angenommen, und davon haben sich die meisten zwei bis vier Mal beworben. Wie war dein Weg zu YC?

**Stefan Faistenauer**

Mein Weg war so wie der der meisten Gründer und Gründerinnen: bumpy. Wir haben uns viermal beworben, beim vierten Mal hat es geklappt. Die Frage, was YC sehen will, da kann man ganze Bücher drüber schreiben. Ich breche es kurz herunter, weil das auch generell für Startups wichtig ist. YC will sehen: Team, Idea, Traction.

Team bedeutet: tolles Team, toller Hintergrund, haben schon mal etwas gebaut. Aber auch die Verbindung aus Team und Idea, also: ist dieses Team das richtige Team, um diese Idee zu executen. Aus YCs Daten sieht man sehr klar: ein guter Team-Idea-Fit erhöht die Chance, dass das Startup etwas wird, ganz wesentlich.

Idea ist das, wo YC noch am offensten ist. Es gibt aber Ideen, die sie schon tausendmal gesehen haben, Classic Tarpit Trap, klingt gut, ist aber eine furchtbare Idee. Wobei sich das ändern kann: mit AI sind viele Tarpit Ideas auf einmal wieder feasible.

Traction ist Punkt drei. Eine schlechte Idee mit viel Traction wird auf einmal zu einer guten Idee. [Airbnb](https://www.airbnb.com/), eine YC-Company, ist ein gutes Beispiel. Es gab einen US-Investor, der gesagt hat: Airbnb is the worst idea that ever worked. Fremde Leute auf einer Luftmatratze in deinem Wohnzimmer übernachten zu lassen, klingt heute total sinnvoll, ist aber eigentlich eine ziemlich doofe Idee. Couch Surfing has been a thing before. Aber sie hatten gute Traction, sie hatten Signups, sie hatten begeisterte Fans.

Witzigerweise waren wir bei dieser vierten Bewerbung an genau diesem Punkt: super Team mit meiner Co-Founderin und mir, gute Idea (Integrationen mit Fokus auf E-Commerce), guter Idea-Team-Fit, weil meine Co-Founderin aus dem E-Commerce kam und Integrationsprojekte geleitet hatte. Und wir hatten Traction: erste Kunden, erste POCs, erste Deals. Wir haben gezeigt: we can do it. Das war der Punkt, wo wir gesagt haben, jetzt brauchen wir YC eigentlich gar nicht mehr, und genau dann haben sie gesagt: jetzt wollen wir euch.

**Leonard Schmedding**

Wir haben es dann trotzdem gemacht.

**Stefan Faistenauer**

Es war eine großartige Entscheidung.

**Leonard Schmedding**

Spannend. Da gibt es ja auch diese Story von [Twitch](https://www.twitch.tv/), wo man gesagt hat, das wird nie was werden, wir geben euch nur 500.000 Euro, um euch scheitern zu sehen. Wir wissen, was daraus geworden ist.

### 10:21 – Agentic Workflows

**Leonard Schmedding**

Beim vierten Mal hat es dann geklappt mit [Superglue](https://superglue.ai/). Das ist dein aktuelles Startup. Was genau macht Superglue, und welches Problem löst ihr?

**Stefan Faistenauer**

Wir sind eine agentische Integrationsplattform. Wir helfen großen Unternehmen und Silicon-Valley-Startups, schnell System- und Datenintegrationen zu bauen, zu maintainen und zu observen. Beispiel: ein deutscher Großhändler hat mehrere Zulieferer. Er muss schauen: was ist in deren Stock, was sind die Produktdaten, was sind Orderdaten, was kann ich meinen Endkunden verkaufen. Das sind Datensynchronisationen, die im Hintergrund passieren müssen. Genau so etwas automatisieren wir mit unserer Plattform. Quasi ein [Cursor](https://cursor.sh/) oder Claude Code für Daten- und Systemintegrationen.

### 13:22 – Das Glue Code Problem

**Leonard Schmedding**

Spannend. 39% der Entwicklerzeit gehen für sogenannten [Glue Code](https://en.wikipedia.org/wiki/Glue_code) drauf, 71% aller Unternehmensanwendungen sind bis heute nicht miteinander verbunden. Was genau ist Glue Code, und warum ist das so ein massives Problem?

**Stefan Faistenauer**

Die IT-Landschaft von Unternehmen besteht aus sehr vielen unterschiedlichen IT-Systemen. Bleiben wir beim Großhändler: er hat wahrscheinlich ein [Warenwirtschaftssystem](https://de.wikipedia.org/wiki/Warenwirtschaftssystem), ein Kundeninformationssystem, ein Rechnungserstellungssystem. Teilweise ist das im [ERP](https://en.wikipedia.org/wiki/Enterprise_resource_planning) zusammengefasst, teilweise sind das unterschiedliche Systeme. Je größer eine Firma wird, desto komplexer wird die IT-Infrastruktur, und überall liegen Daten. Idealerweise will man diese Daten miteinander synchronisieren, und genau das ist Glue Code.

Das Problem: es gibt sehr selten eine zentrale Plattform oder überhaupt einen Prozess, um Glue Code zu bauen und zu verwalten. Was passiert, sind Skripte, die im besten Fall auf irgendwelchen Servern liegen, irgendjemand mal gebaut hat, schlecht dokumentiert, irgendwann abstürzen, irgendwelche Bugs haben. Das ist das, was Unternehmen umtreibt, wenn sie ein Migrationsprojekt machen oder ein neues System einführen wollen: was machen wir mit diesem ganzen Glue Code, mit dieser Logik, an die sich niemand wirklich rantraut.

Ich habe damals im Studium bei einem großen deutschen Automotive-Konzern gearbeitet. Mein erster Tag: ich komme rein, suche mir einen Tisch. Mein Chef rennt zu mir und sagt: Stefan, hier darfst du nicht sitzen. Ich frage, ob das der Tisch vom Chef ist. Er sagt: nein, aber unter dem Tisch steht ein Rechner, und da laufen ganz wichtige Abteilungsprozesse drüber. Wenn du mit dem Fuß an den Ausschalter kommst, ruft die IT an, und wir haben ein riesen Problem. That's the state of glue code in German companies. Ich glaube, ich brauche nicht darüber zu reden, was für Probleme das erzeugt. Genau das versuchen wir zu lösen.

### 15:38 – Zukunft von n8n und Zapier

**Leonard Schmedding**

Wahnsinn. Viele Unternehmen haben die letzten Jahre gesagt: wir nutzen Workflow-Integration-Plattformen wie [n8n](https://n8n.io/) oder [Zapier](https://zapier.com/), [Make](https://www.make.com/) und so weiter. Wie steht ihr im Vergleich zu diesen Plattformen?

**Stefan Faistenauer**

Großartige Plattformen, die einen Teil des Problems schon lösen. Sie sind ein zentraler Punkt, wo diese Flows laufen, gehostet und executed werden, das ist großartig. Zweitens sind das Tools, die auch Leute verwenden können, die keine Hardcore-Engineers sind. Du brauchst keine 10 Jahre Coding-Erfahrung, um ein n8n zu bedienen. Das ist grundsätzlich gut.

Der Grund, warum wir Superglue gegründet haben, obwohl es das schon gibt: Integrationen und Glue Code zu bauen ist grundsätzlich nicht schwer. API-Calls hier, Datentransformationen da, Reconciliation. Das Problem ist, dass ich genau wissen muss, was ich tue. Welchen API-Call muss ich auf dieses System machen, um einen gewissen Effekt zu erzielen. Da brauche ich unfassbar viel Context Knowledge. Das sind keine [Stripe](https://stripe.com/)-APIs, die wunderbar dokumentiert sind, sondern irgendwelche ERP-APIs, File-based Austauschformate.

Jedes Mal, wenn ich eine neue Integration baue, muss ich nicht nur verstehen, was ich als Integration haben will, sondern auch, wie alle Systeme funktionieren, die ich ansprechen will. Das ist das Problem, das wir on top lösen: wir lesen die Dokumentation ein, wir lesen den Kontext ein, gib uns deinen existierenden Glue Code, gib uns deine existierenden E-Mails, Transcripts, everything you have, und wir bauen einen Systemkontext on top auf. Jede Integration, die du baust, wird einfacher, weil wir den Kontext schon haben, nicht schwerer.

### 17:52 – Braucht es Workflow-Plattformen noch?

**Leonard Schmedding**

Du hast erwähnt, dass du schon 2018 im Bereich AI Consulting Erfahrung gesammelt hast, also lange vor dem [ChatGPT](https://chat.openai.com/)-Hype Ende 2022. Februar 2026 sehen wir aus meiner Sicht erneut so einen Moment, das ist der Claude-Code-Moment. Ist dieser [Claude Code](https://www.anthropic.com/claude-code)-Moment mindestens genauso groß wie der ChatGPT-Moment?

**Stefan Faistenauer**

In gewisser Weise ja. Zumindest in der Developer Community sehe ich einen sehr großen Demand und Impact von Claude Code, in vielen Ausprägungen, von Claude Code über [OpenCode](https://opencode.ai/) bis [Cursor](https://cursor.sh/) davor. Der große Unterschied: Claude Code ist in erster Linie ein Developer-Produkt, es hilft Developern, schneller zu arbeiten, automatisiert einige Sachen. ChatGPT sehe ich in einer anderen Kategorie, einfach weil es viel breitenwirksamer war, weil es Leute verwenden konnten, die keine Entwickler waren. Claude Code richtet sich durch das CLI doch sehr stark an Entwickler. Es hat die Chance, Entwicklung sehr stark zu beeinflussen. Ich glaube aber nicht, dass es den durchschlagenden Effekt von ChatGPT haben wird.

**Leonard Schmedding**

Spannend. Eine Frage, die ich mir stelle: braucht es solche Integration-Platforms wie n8n überhaupt noch? Also, braucht es einen Menschen, der da drin rumklickt, wenn ich mir auch einfach ein [Python](https://www.python.org/)-Skript von Claude Code schreiben lassen kann? Andererseits habe ich dann wieder das Problem: ich habe keinen Überblick darüber, was läuft. Wie nimmst du diese Entwicklung wahr?

**Stefan Faistenauer**

Auf jeden Fall. Vorher hat ein Mensch diese Skripte geschrieben, jetzt kann sie Claude Code schreiben, das ändert nichts daran, dass diese Skripte irgendwo auf einem Server in einem Silo laufen. Was bei Integrationen dazukommt: man verbindet Systeme, die man nicht zu 100% abdeckt und versteht. Man hat immer wieder Edge Cases, Änderungen, neue Anforderungen. Integrationen zu bauen ist not a one-time thing, das ist ein kontinuierlicher Prozess. Da sehe ich Plattformen wie n8n und Superglue in einer sehr starken Position, weil sie der One-Stop-Shop sind, wenn ich sage: ich will meine Integration verändern, monitoren, und das soll auch noch funktionieren, wenn ich nicht drei Systeme habe, sondern 30 oder 300 oder 1000.

### 19:19 – Self-Healing Integrationen

**Leonard Schmedding**

Ihr schreibt, eure Plattform ist Self-Healing. Wenn sich externe APIs ändern, passt sich der Workflow von alleine an. Wie funktioniert das technisch?

**Stefan Faistenauer**

Ein super spannendes Thema. Man kann eine Integration einmal bauen, aber dann kommen Daten durch, die man nicht erwartet hat, oder APIs verändern sich. Integrationen brechen immer wieder, und das ist im Moment ein sehr manueller, sehr schmerzhafter Prozess. Erstens: ist die Integration überhaupt kaputt? Dafür reicht Basic Monitoring. Zweitens: warum ist sie kaputt? Was ist durchgekommen, was ist in diesem System, was ist der Grund, wie muss ich meine Integration abändern, damit die Synchronisation wieder läuft.

Genau diesen Prozess haben wir angefangen zu automatisieren. Wir haben das Context Understanding, wir wissen, wie die Systeme funktionieren, wir haben die Dokumentation. Wir sehen, welche Daten durchkommen und was zu dem Fehler geführt hat. Wir haben einen Coding Agent, wir haben den ganzen Integration Code, wir können sagen, wie der Code angepasst werden muss. Das Endergebnis ist eine [Slack](https://slack.com/)-, [Teams](https://www.microsoft.com/microsoft-teams/)- oder E-Mail-Nachricht mit Zusammenfassung: hier ist das Problem, hier ist der Grund, hier ist die Lösung, bitte accept. Wir haben immer noch einen Human in the Loop, weil das kritische Prozesse sind. Aber das ist der Unterschied zwischen einer vier Stunden langen Eskalation und zwei Minuten: yes, that's how I want it to be changed, thank you so much.

### 21:20 – Warum Open Source?

**Leonard Schmedding**

Es gibt natürlich Leute, die sagen, ja, im Zweifel will jeder etwas verkaufen. Aber bei euch muss man dazu sagen: ihr seid [Open Source](https://en.wikipedia.org/wiki/Open_source). Warum?

**Stefan Faistenauer**

War für uns von Anfang an eine relativ klare Entscheidung, aus ein paar Gründen. Erstens: über unsere Plattform laufen kritische Prozesse, kritische Infrastruktur. Da geht es nicht primär darum, eine Zusammenfassung meiner E-Mails zu schicken, sondern um Prozesse zwischen verschiedenen Enterprise-Systemen. Wir wollten schnell sehr viel Adoption, sehr viel Feedback, dass die Leute es ausprobieren, testen, contributen können, und damit eine Lösung bauen, die schnell Enterprise-Ready ist, anstatt zu sagen, wir entwickeln das alles selber, geben es nicht raus, und beim Deployment kommt heraus: oh Gott, da hat etwas überhaupt nicht funktioniert, weil der negative Impact zu groß wäre.

Was wir bei Open Source gesehen haben: jede Änderung erzeugt Feedback in der Community, positiv oder negativ. Wir sind auf tausenden Instanzen deployed. Wir haben eine Scale erreicht, die uns ohne Open Source Jahre gekostet hätte. Jetzt können wir Service on Top anbieten, Features on Top, größeren Firmen, Enterprises und schnellwachsenden Startups dabei helfen, die Lösung effektiv zu deployen. Das ist unser Business, und die Foundation darunter ist Open Source. Check it out.

**Leonard Schmedding**

Wir verlinken es. Was sind eure Monetarisierungswege, gibt es auch eine Hosted Version wie bei n8n?

**Stefan Faistenauer**

Sehr ähnliches Modell. Wir haben eine Hosted Version, die kann man auch ausprobieren und als Solo-Nutzer gut nutzen. Wir haben Added Enterprise Features, gerade in Richtung Monitoring, [Observability](https://en.wikipedia.org/wiki/Observability_(software)), Role Management, wo sehr große Firmen einen anderen Bedarf haben. Unser Ziel war: wenn ich ein Solo Developer oder ein kleines Team bin, muss ich Superglue nutzen können, ohne sofort einen Contract abschließen zu müssen. Die Hosted Version ist ein guter Entry Point, danach verwendet man das Setup, das am besten passt.

### 24:40 – MCP: Ein Auslaufmodell?

**Leonard Schmedding**

Lass uns tiefer in das Integrations- und AI-Agent-Thema einsteigen. Du hast 2025 auf [Substack](https://substack.com/) geschrieben, dass euer Agent sich nicht mit APIs herumschlagen sollte, dafür sollte es eine Lösung geben, das war [MCP](https://modelcontextprotocol.io/). Seitdem hat sich viel getan, MCP wurde breit integriert, aber jetzt stellt sich die Frage: ist es Token-ineffizient, hat es ausgedient? Was ist deine aktuelle Meinung?

**Stefan Faistenauer**

Etwas technischer, aber dahin wollten wir ja. Ich bin grundsätzlich sehr bullish auf MCP, das ist eine Counter-Opinion zur aktuellen Twitter-Stimmung. Bei MCP muss man unterscheiden: MCP sind eigentlich zwei Sachen. Einerseits ist es ein Protokoll für Remote Tool Execution und Authentication, andererseits geht es um Tool Discoverability und die Agent-Komponente.

Alles, was Remote Tool Execution und Authentication betrifft: MCP ist und bleibt der absolute Standard. Erstens, weil es nichts anderes gibt, zweitens, weil es ein sehr guter Standard ist. Man hat Tool Definitions, MCP Server, Authentication wird über MCP geregelt. So gut wie alle Firmen nutzen das, um Tools zur Verfügung zu stellen, auch innerhalb von Unternehmen, etwa wenn ich einen internen [Microsoft Copilot](https://copilot.microsoft.com/) habe und meinen Mitarbeitern Tools bereitstellen will. There is right now no alternative.

Auf der Agent-Seite gibt es einige super spannende Konzepte, die MCP haushoch überlegen sind. MCP funktioniert so: ich lade alle Tools per Default in meinen Kontext rein. Wenn ich 80 Tools habe, ist mein Kontext im Prinzip voll, bevor ich überhaupt eine Konversation angefangen habe. Im Agent Development sehen wir, dass Effizienz ein guter Weg ist, um gut funktionierende Agents zu bauen, und der Approach ist super ineffizient.

Anthropic hat angefangen, [Skills](https://www.anthropic.com/news/agent-skills) sehr hart zu pushen. Man hat verschiedene Skills, quasi ein Inhaltsverzeichnis: das sind die Sachen, die ich machen kann, das sind die Topics, die ein Agent bearbeiten kann. In der Praxis, auch bei Superglue, funktioniert unser Agent inzwischen so: der Agent ist sehr gut darin, sich die Skills rauszupicken, die er für einen Task braucht. Das kann highly specific sein, sehr allgemein, und kann sogar mit MCP zusammenarbeiten, indem man gewisse MCP Tools exposed.

Das sehen wir als the future of Agent Development: Inhaltsverzeichnis, such dir den Kontext, den du wirklich brauchst, für diesen Task aus. Das löst auch das Context-Bloat-Problem. MCP ist ja Active Development, meine Erwartung wäre, dass so etwas relativ schnell den Weg in den MCP Standard findet. Wir müssen MCP nicht komplett ditchen für ein unstandardisiertes, wildes Skill-System, das einzelne AI-Firmen auf den Markt werfen. Insofern: sehr bullish auf MCP, ich freue mich, wenn es da noch ein paar Developments gibt in Richtung Effective Context Management. Sehen wir in großen Firmen die ganze Zeit implementiert, funktioniert wunderbar.

### 29:21 – Nächste Trends in AI Agents

**Leonard Schmedding**

Der Bereich entwickelt sich super schnell. Einer der besten Wege, mit KI und Agenten zu arbeiten, ist über einen Claude-Code-Workspace mit MCPs, Skills und Plugins. Was werden die nächsten Trends? Was fehlt aktuell noch, was viele vielleicht noch nicht kommen sehen?

**Stefan Faistenauer**

Das ist die Billion-Dollar-Question. Wir sind im Moment vielleicht bei 5% Usage von dem, was eigentlich möglich ist mit AI Agents und [LLMs](https://en.wikipedia.org/wiki/Large_language_model). Wir haben eine unfassbar starke Technologie, die langsam im Mainstream ankommt, aber eigentlich noch im Innovators-Territory ist. Wenn man sich anschaut, wie viele Firmen, Enterprises, selbst Startups wirklich AI-Native sind und Agents im vollen Potenzial ausnutzen, ist das eigentlich niemand. Wir sind in einer sehr frühen Phase von AI Adoption.

Woran liegt es? Die Modelle sind they're just an API away. Der Grund sind zwei Dinge. Erstens: ein starkes LLM zu haben ist eine Sache, aber die eigentliche Frage als Unternehmen, Gründer, Geschäftsführer, [CIO](https://en.wikipedia.org/wiki/Chief_information_officer) oder [CTO](https://en.wikipedia.org/wiki/Chief_technology_officer) ist, wie ich AI so im Unternehmen einsetze, dass es einen Mehrwert bringt. Darauf gibt es keinen One-Size-Fits-All-Approach, das hängt vom Business, von den internen Prozessen, von der Differenzierung ab. Zweitens ist es eine technische Frage: ich habe einen Killer Use Case gefunden, wie greife ich auf meine internen Daten, meinen internen Kontext zu, sodass es wirklich gut funktioniert. Da kommen wir wieder ins Spiel, aber es gibt auch andere Tools.

Die Hauptchallenge ist nicht, wie machen wir AI besser, sondern wie bringe ich AI so ins Unternehmen, dass ich einen krassen Benefit habe. Die Technologie ist da, die Anwendung wird uns die nächsten 5 bis 10 Jahre mindestens begleiten. AI is here to stay, wie sie sich genau entfaltet, sieht man von Unternehmen zu Unternehmen.

**Leonard Schmedding**

Anthropic sagt selbst immer wieder: wir könnten theoretisch die Modellentwicklung stoppen, und trotzdem würden 10 bis 20% aller [White-Collar-Jobs](https://en.wikipedia.org/wiki/White-collar_worker) in den nächsten Jahren ersetzt, weil bis dahin die Integration der aktuellen Modelle stattgefunden hat. [OpenAI](https://openai.com/) und alle anderen haben 2025 als Jahr der KI-Agenten ausgerufen. Jetzt sieht man: für mich persönlich geht es 2026 so richtig los. Agenten werden produktionsreif mit Claude Code und Codings. Du hast eben [Replit](https://replit.com/) erwähnt, [Amjad Masad](https://en.wikipedia.org/wiki/Amjad_Masad) hat gesagt, wir sehen eher die Dekade der AI-Agenten als das Jahr der AI-Agenten. Wie schnell wird die Integration gehen?

**Stefan Faistenauer**

Wir Leute in Tech unterschätzen, wie viel Zeit es benötigt, bis solche Technologien im Unternehmen landen. Selbst ChatGPT ist immer noch nicht da, wo es sein könnte, obwohl es schon lange im Markt ist. Die Adoption von AI startet jetzt erst so richtig. Die Frage, wie ich AI Agents einsetze, ins Unternehmen bringe, wie das technisch funktioniert, welche Tools ich gebe, wo ich aufpassen muss, da sind wir noch ein bisschen early.

YC sagt: AI right now is the worst it will ever be. Ein sehr treffendes Zitat. AI wird nicht schlechter, sondern nur besser, weil die Modelle da sind, jedes neue Modell ist besser. Wenn wir das Adoption-Thema Unternehmen für Unternehmen angehen, dann können wir wirklich noch viel rausholen. Wenn AI-Agenten effektiv deployed sind, mit den richtigen Tools, Zugriffen, Daten, Kontext, sind wir jetzt schon in der Lage, für ein Unternehmen nicht 10, 20% Benefit, sondern wahrscheinlich 50 bis 100% Benefit rauszuholen.

### 34:35 – Das Bottleneck

**Leonard Schmedding**

Die Frage, die ich mir stelle und auf die ich keine abschließende Antwort habe: es scheitert an der Adoption. Wir haben heute mit übermächtigen Tools zu tun. Du kannst ganze Stellen wegrationalisieren, so ehrlich müssen wir sein, gerade wenn man Claude Code richtig verwendet. Wie relevant wird diese Wahl überhaupt noch sein? Die letzten Jahre konnte man sagen: wir müssen Unternehmen überzeugen, jetzt KI zu integrieren. Ich frage mich, ob in einem ansatzweise kompetitiven Markt nicht der eine Spieler, der diese Tools nutzt, einen so großen Vorsprung hat, dass die anderen gar keine Chance mehr haben nachzuziehen. Du bist 10, 20-mal produktiver als deine Konkurrenten.

**Stefan Faistenauer**

Würde ich so unterschreiben. Das ist auch keine Frage von Kosten allein. Wenn ein Konkurrent fünfmal so viele Aufträge bearbeiten, fünfmal so viel Kapazität haben und einen 30% besseren Customer Service bieten kann, zu möglicherweise niedrigeren Kosten, dann ist es keine Frage von Wollen, dann ist es eine Frage von ich muss AI einsetzen. Sonst ist überhaupt nicht mehr die Frage, was ich in 10 Jahren mache. Es ist nichts, was eine Frage von Wochen ist, aber durchaus von den nächsten Monaten. Jetzt, wo die AI-Modelle und die Infrastruktur da sind, macht es total viel Sinn, sich als Unternehmen zu überlegen: wo sind meine Hebel, wo kann ich mit AI 5x, 10x besser werden, und meiner Konkurrenz einen Schritt voraus sein, einen wirklichen Impact schaffen und das Unternehmen sein, das andere outcompetet und den Markt gewinnt.

### 37:36 – Wie Unternehmen 2030 arbeiten

**Leonard Schmedding**

Wie wird ein Unternehmen in drei bis fünf Jahren aus deiner Sicht arbeiten? [Andrej Karpathy](https://en.wikipedia.org/wiki/Andrej_Karpathy) hat gesagt, wir leben den seltsamen Tod der Nutzeroberflächen. Ich finde, da ist viel Wahres dran: der zentrale Zugriffsort auf Agenten ist aktuell die Kommandozeile beziehungsweise das Terminal, danach folgen Lösungen wie Cowork. Das hat viele Implikationen, wie wir im Unternehmen vor und hinter dem Bildschirm arbeiten. Wie werden Unternehmen arbeiten, wie werden wir mit Software arbeiten?

**Stefan Faistenauer**

Ich versuche, ein paar Aspekte herauszupicken und konkret zu werden. Ein großes Thema sind Interfaces: was ist eigentlich das Interface of Work? Wir sehen aktuell sehr viele Nutzeroberflächen aus einer SaaS-Era, einer Pre-AI-Era, die Click- und Boxes-First sind: Forms, Tables und so weiter. Unser konträrer Take dazu ist: die gibt es nicht ohne Grund. Es macht Sinn, der Nutzerin und dem Nutzer Kontext zu geben, was hier gerade passiert. Das wird weniger granular, ich muss nicht mehr zu 100% genau verstehen, wie ein kleines Detail funktioniert, wenn ein Agent es übernimmt. Aber grundsätzlich sind diese Nutzeroberflächen sinnvoll.

Wir sehen den größten Benefit darin, Nutzeroberflächen mit einem [Chat-Interface](https://en.wikipedia.org/wiki/Chatbot) zu verbinden. Nicht Pure Chat, nicht Pure Boxes, Forms, Arrows, sondern ein Chat-Interface, das mit der Nutzeroberfläche zusammenarbeitet, wo ich die Informationen bestmöglich aufbereitet bekomme: Text, Table, Graph, alles möglich, aber whatever helps me to best understand what the heck is going on. Die Industrie divergiert dahin. Claude Code ist auch deshalb erfolgreich, weil es nicht nur eine CLI mit ein bisschen Text ist, sondern ein ganzes Rendering-Interface dahinter hat. Bei Superglue sehen wir das stark: ein Text-Interface allein ist cool, ein Text-Interface verbunden mit den richtigen Komponenten zur richtigen Zeit ist ein Game Changer.

Beyond that gibt es keinen One-Size-Fits-All-Approach für Tooling oder wo ich AI-Agenten gut einsetzen kann. Worauf ich sehr viel Geld verwetten würde: in vielen Industrien werden gerade Supporting Functions wie HR, Accounting, Logistics, Services Functions, die viele Unternehmen haben, als erstes große Veränderungen sehen. In Coding sehen wir es schon, those functions are next. Ich bin außerdem ein Fan von vertikalen Lösungen, die auf eine bestimmte Industrie gehen. In München gibt es so viele tolle Startups, die auf eine Industrie gehen und sagen: wir lösen deinen Workflow agentisch auf, wir bieten dir hier in deinem Business Model einen abgestimmten KI-Agenten. Beides passiert gleichzeitig. In den meisten Industrien sind Agents in 5 bis 10 Jahren nicht mehr wegzudenken.

### 42:13 – San Francisco vs. München

**Leonard Schmedding**

Mich interessiert konkret eine Sache zu YC und dem Vergleich [San Francisco](https://en.wikipedia.org/wiki/San_Francisco) und München. YC will eigentlich, dass man in San Francisco sitzt. Wie ist es bei euch?

**Stefan Faistenauer**

Wir sind sehr oft in San Francisco, wir haben Kunden in den USA und besuchen die. YC sagt: the best place to build a startup is San Francisco. Wir glauben: the best place to build your startup is where your customers are. Da würde YC durchaus zustimmen, sie unterstützen einige Startups, wo von vorne rein klar war, dass die nicht in San Francisco sitzen, gerade wenn man Legal- oder Accounting-Sachen länderspezifisch macht. Wir verkaufen sehr viel in Deutschland und Europa an Mittelständler und Enterprises, wir sind in Stuttgart und Hamburg bei Kunden. Das ist unser Differentiator: die ganzen AI-Startups in San Francisco machen coole Sachen, wir auch, und wir bringen das nach Deutschland, Last Mile Delivery, Cutting Edge AI und Tech, damit du in deinem Markt kompetitiv bist. Die YC-Partner haben gesagt: macht Sinn, go for it.

**Leonard Schmedding**

Welche Vorteile siehst du in San Francisco?

**Stefan Faistenauer**

San Francisco ist ein ganzes, sehr großes Ökosystem mit kurzen Wegen zu sehr viel Know-how und Funding. Ich kann als Founder sagen: ich habe einen guten Grund, mit dem CEO von [Salesforce](https://www.salesforce.com/) zu sprechen. I'm gonna reach out, und die Chance ist hoch, dass wir es schaffen. Selbst als Student, wenn ich einen guten Grund habe, mit wichtigen Leuten zu sprechen: die sind alle an einem Ort, in San Francisco und der South Bay, und das baut Barrieren ab. Was mich am meisten überrascht hat: wie offen die Menschen sind. You want to talk to a CEO, you can talk to a CEO. Bei YC hatten wir [Mike Krieger](https://en.wikipedia.org/wiki/Mike_Krieger) von Anthropic, Leute von Airbnb, [Coinbase](https://www.coinbase.com/) und so weiter, die ganze Community an Leuten mit Erfahrung, die gut informiert sind, was the next big thing ist.

Das ist etwas, was ich mir für München und Deutschland wünsche: dass wir enger zusammenarbeiten. Wir haben tolle Firmen in München, Riesenindustriegiganten, Startups wie [Personio](https://www.personio.de/) und [Helsing](https://helsing.ai/), inzwischen riesengroß. Wenn wir es schaffen, das Ökosystem mehr zusammenzubringen, die Leute mit Erfahrung näher zu jungen Foundern zu bringen und Founder-Aspiranten näher zu uns, das wäre, was ich mir wünschen würde. My calendar is open. Wenn jemand sprechen möchte, schreibt mir eine E-Mail: stefan@superglue.ai. Let's talk.

### 47:29 – Appell

**Leonard Schmedding**

Im Agentenzeitalter kommt es nicht mehr darauf an, was du weißt, sondern wen du kennst. Wissen wird wertloser, Kontakte wichtiger. Wir haben sehr viele Zuschauer, die Unternehmer oder Agenturen sind und von diesen Entwicklungen profitieren wollen. Worauf sollte man sich fokussieren, um als Gewinner aus der KI-Revolution hervorzugehen?

**Stefan Faistenauer**

Ich habe schon einen Appell an Unternehmen gemacht: beschäftigt euch mit AI, schaut, wie kann AI mir wirklich einen Benefit bieten, wie kann ich AI sinnvoll integrieren. Sprecht gerne mit mir, ihr bietet ja auch viel in die Richtung an. Das letzte Wort möchte ich an Leute richten, die selber gründen oder sich aus einem Angestelltenverhältnis oder als Studierende mit AI beschäftigen.

Punkt 1: beschäftigt euch mit AI. Diesen Podcast zu schauen ist ein super Start, aber investiert wirklich Zeit und schaut, wie ich AI heute ansetzen kann, um einen Unterschied zu machen, in meinem Unternehmen, Studium, bei Freunden. Was sind Ideen, wie man AI verwenden könnte, um coole Produkte zu bauen, und dann baut sie einfach. Es war nie so einfach wie heute, Produkte zu bauen und Sachen zu testen.

Punkt 2, vor allem für Leute aus Deutschland: redet darüber. Postet auf [Hacker News](https://news.ycombinator.com/), postet auf [Reddit](https://www.reddit.com/), sprecht darüber, was für coole Sachen ihr baut. Wir bauen in diesem Land extrem viel coole Tech und sprechen viel zu wenig darüber. [OpenCode](https://opencode.ai/) ist ein gutes Gegenbeispiel. Wie wurde OpenCode so groß? Nicht, weil es das erste Produkt war, das macht, was es macht, sondern weil es ein Produkt ist, das viele Leute verwenden können, und weil [Peter](https://github.com/pstadler) sehr gut darin ist, darüber zu sprechen, viral zu gehen, Dinge öffentlich zu machen und Engagement zu erzeugen. Letztendlich ist das es, was in dieser AI-Welt, wenn die Kosten des Produktbaus so sinken, einen Unterschied macht: wie positioniere ich das Produkt am Markt, wie spreche ich darüber, wie erzeuge ich einen Buzz um das Thema. Mein Appell: bitte versucht es, sprecht darüber, macht Videos, macht Posts, zeigt der Welt, was für coole Produkte ihr baut.

**Leonard Schmedding**

Perfektes Schlusswort, das kann ich nur so unterschreiben. Stefan, wenn ihr hier am Puls der Zeit bleiben wollt, erfolgreiche Gründer kennenlernen wollt und Leute, die in diesem Land etwas bewegen, genau darum geht es bei [Everlast AI](https://www.youtube.com/@everlastai). Stefan, danke dir für die spannenden Einblicke in deine Arbeit.

**Stefan Faistenauer**

Wenn ihr noch Fragen habt, die E-Mail werden wir verlinken. Schreibt gerne in die Kommentare.

**Leonard Schmedding**

Ich bin sicher, dass wir in Zukunft wieder von euch hören werden. Stefan, danke dir, und wir sehen uns im nächsten Video wieder.

---

Quelle: https://www.youtube.com/watch?v=YRmZnooY92g
