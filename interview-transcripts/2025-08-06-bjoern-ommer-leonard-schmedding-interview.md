# Prof. Björn Ommer × Leonard Schmedding Interview

Prof. Dr. Björn Ommer · Leiter [Computer Vision & Learning Group](https://ommer-lab.com/) an der [LMU München](https://www.lmu.de/) · [@everlastai](https://www.youtube.com/@everlastai) · 2025-08-06 · 41 Min · Deutsch · [YouTube](https://www.youtube.com/watch?v=CssEFTqn5LU)

[Prof. Björn Ommer](https://ommer-lab.com/people/ommer/) ist einer der einflussreichsten Köpfe der europäischen [generativen KI](https://en.wikipedia.org/wiki/Generative_artificial_intelligence) und die treibende Kraft hinter [Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion), dem [Open-Source-Bildgenerator](https://github.com/CompVis/stable-diffusion), der 2022 weltweit eine Welle losgetreten hat. Ommer hat in Bonn und an der [ETH Zürich](https://ethz.ch/) studiert, war Postdoc an der [UC Berkeley](https://www.berkeley.edu/), wurde Professor in [Heidelberg](https://www.uni-heidelberg.de/) und leitet seit 2021 die [Computer Vision & Learning Group](https://ommer-lab.com/) an der [LMU München](https://www.lmu.de/). Er ist Träger des [Deutschen KI-Preises](https://www.welt.de/kuenstliche-intelligenz/article248002822/) und Mitglied im [Deutschen KI-Rat](https://www.bmftr.bund.de/). Im Gespräch geht es um den Latent-Diffusion-Trick, der Bildgenerierung erstmals auf Consumer-Hardware brachte, warum sogar [Veo 3](https://deepmind.google/technologies/veo/) auf seinem Ansatz aufbaut, was [AGI](https://en.wikipedia.org/wiki/Artificial_general_intelligence) wirklich bedeutet, weshalb [agentic AI](https://en.wikipedia.org/wiki/Intelligent_agent) und [Physical AI](https://en.wikipedia.org/wiki/Embodied_cognition) die nächsten großen Schritte werden, warum [Deepfake-Wasserzeichen](https://en.wikipedia.org/wiki/Digital_watermarking) wie [SynthID](https://deepmind.google/technologies/synthid/) und [C2PA](https://c2pa.org/) das Problem nur halb lösen und warum Deutschland mit seinem Mittelstand trotz aller Verspätung noch eine reelle KI-Chance hat.

## Timestamps

- [00:00](https://www.youtube.com/watch?v=CssEFTqn5LU&t=0s) – Vorschau
- [00:57](https://www.youtube.com/watch?v=CssEFTqn5LU&t=57s) – Intro
- [02:42](https://www.youtube.com/watch?v=CssEFTqn5LU&t=162s) – Stable Diffusion erklärt
- [05:09](https://www.youtube.com/watch?v=CssEFTqn5LU&t=309s) – Vergleich mit anderen Modellen
- [06:18](https://www.youtube.com/watch?v=CssEFTqn5LU&t=378s) – Tools & Plattformen
- [07:19](https://www.youtube.com/watch?v=CssEFTqn5LU&t=439s) – Kritik an Generativer KI
- [09:59](https://www.youtube.com/watch?v=CssEFTqn5LU&t=599s) – KI mit Analogien erklärt
- [11:42](https://www.youtube.com/watch?v=CssEFTqn5LU&t=702s) – Zukünftige KI-Anwendungen
- [14:26](https://www.youtube.com/watch?v=CssEFTqn5LU&t=866s) – Nächste Durchbrüche
- [16:43](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1003s) – Zukunft humanoider Roboter
- [18:35](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1115s) – Was ist AGI?
- [20:21](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1221s) – Zukunfts-Einschätzung
- [22:09](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1329s) – Jobverluste durch KI
- [24:41](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1481s) – Neue KI-Berufsfelder
- [26:16](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1576s) – Arbeiten mit KI
- [27:00](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1620s) – Bequemlichkeit & Privatsphäre
- [28:31](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1711s) – Deepfakes & Schutzmaßnahmen
- [30:11](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1811s) – Fakes vs. Wahrheit
- [31:13](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1873s) – KI-native Generation
- [33:19](https://www.youtube.com/watch?v=CssEFTqn5LU&t=1999s) – Einfluss auf deutschen Arbeitsmarkt
- [34:51](https://www.youtube.com/watch?v=CssEFTqn5LU&t=2091s) – Deutschlands KI-Rolle
- [39:01](https://www.youtube.com/watch?v=CssEFTqn5LU&t=2341s) – Fazit & Appell

## Transcript

### 00:00 – Vorschau

**Prof. Dr. Björn Ommer**

Generelle Intelligenz im Gegensatz zu der Nischenintelligenz, die nur Hunde von Katzen unterscheiden kann. Ein Foundation Model ist ja nichts anderes als das. Dementsprechend können wir uns, glaube ich, noch gar nicht ausmalen, was dort alles zukünftig noch auf uns zukommen wird. Die Grenze zwischen Science und Science Fiction verläuft hier sicherlich fließend. Es wird vorhergesagt, dass in sehr baldiger Zeit, noch in diesem Jahrzehnt, Roboter zu verträglichen Preisen für die Allgemeinheit zur Verfügung stehen würden. Dann bekommen sie das Privateste, was man bekommen kann, nämlich eine KI, die mich im Alltag begleitet und so ziemlich alles mitbekommt, was ich zumindest digital, vielleicht sogar offline mache. Das größere Problem sind nicht die Fakes, sondern dass mit diesen Fakes auch die Wahrheit angefangen wird in Frage zu stellen. Sonst würde ich vorhersagen, dass wir in sehr baldiger Zukunft eine vollständige Abhängigkeit von diesen Tools haben, die aus dem Ausland über uns kommen, und dann ist es mit der Souveränität nicht mehr ganz so weit her.

### 00:57 – Intro

**Leonard Schmedding**

Das folgende ist ein Gespräch mit [Prof. Dr. Björn Ommer](https://ommer-lab.com/people/ommer/). Er ist einer der führenden Köpfe im Bereich generative KI und Schlüsselfigur hinter [Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion), dem Bildgenerator, der 2022 weltweit eine Revolution ausgelöst hat. Björn Ommer hat in Bonn und an der [ETH Zürich](https://ethz.ch/) studiert, war Postdoc an der [University of California Berkeley](https://www.berkeley.edu/) und wurde anschließend Professor in [Heidelberg](https://www.uni-heidelberg.de/), bevor er 2021 an die [LMU München](https://www.lmu.de/) wechselte. Dort leitet er die Computer Vision and Learning Group und forscht an den Schnittstellen von [maschinellem Lernen](https://en.wikipedia.org/wiki/Machine_learning), generativer KI und erklärbaren Modellen. Seine Arbeit hat nicht nur die Forschung, sondern auch die Kreativwirtschaft nachhaltig verändert. Er wurde mehrfach ausgezeichnet, unter anderem mit dem [Deutschen KI-Preis](https://www.welt.de/kuenstliche-intelligenz/article248002822/) und dem Eduard-Rhein-Technologiepreis, und ist Mitglied im Deutschen KI-Rat. In diesem Gespräch sprechen wir über die Entstehungsgeschichte von Stable Diffusion, wie es sich von Modellen wie [DALL-E](https://openai.com/index/dall-e-3/) oder der aktuellen [ChatGPT](https://chat.openai.com/) Image-Funktion unterscheidet, sowie welche Plattformen und Tools heute darauf aufbauen. Wir diskutieren außerdem, wie sich KI in den nächsten Jahren in Bereichen wie Bild, Video und Audio weiterentwickeln wird, welche Chancen Deutschland wirklich noch hat im KI-Wettrüsten, welche Rolle Standards wie [SynthID](https://deepmind.google/technologies/synthid/) bei der Bekämpfung von Deepfakes spielen und welche technologischen Trends die nächsten 5 bis 10 Jahre prägen werden. Björn Ommer ist einer der Vordenker, die den aktuellen KI-Boom überhaupt möglich gemacht haben, und es war mir eine große Freude, dieses Gespräch zu führen.

### 02:42 – Stable Diffusion erklärt

**Leonard Schmedding**

Hallo Björn, schön, dass du heute mit dabei bist. Ich würde mit dir gerne einmal auf das Thema Stable Diffusion schauen. Dort warst du die treibende Kraft hinter dem ganzen Projekt. Wie würdest du jemandem, der vielleicht nur davon gehört hat, aber nicht wirklich mehr darüber weiß, erklären, was Stable Diffusion ist und was ihr da damals gemacht habt?

**Prof. Dr. Björn Ommer**

Fangen wir mit Diffusion an. Die Frage ist, wie wir dem Computer beibringen, was in Bildern drinsteckt. Bei generativer KI nehme ich ein Bild und füge ein kleines bisschen [Rauschen](https://en.wikipedia.org/wiki/Image_noise) hinzu. Ich wiederhole das viele Male. Bei jedem einzelnen Schritt ist der Unterschied kaum erkennbar, aber wenn ich das Hunderte oder Tausende Male mache, sieht das Ergebnis aus, als hätte ich aus meinem Fernseher das Antennenkabel gezogen, nur Rauschen. Warum mache ich das? Um den Prozess umdrehen zu können. Der Computer hat dann das verrauschte Bild und das Bild, das ein kleines bisschen weniger verrauscht ist. Man kann ein [neuronales Netz](https://en.wikipedia.org/wiki/Neural_network) bitten, aus dem verrauschten das etwas weniger verrauschte Bild zu generieren. Dabei lernt der Computer, in kleinen Stücken Inhalte hinzuzufügen. Wenn ich diesen Prozess hundert- oder tausendmal wiederhole, starte ich mit purem Rauschen, und am Ende kommt nicht genau das Bild raus, mit dem ich gestartet habe, aber etwas einigermaßen Ähnliches. Der Computer hat gelernt, langsam Bilder zu generieren.

Das Problem war, dass das bisher immer im Raum der Bildpunkte gemacht wurde. Wenn ich so einen Prozess mit Millionen von Pixeln laufen lasse, sieht der Computer den Wald vor lauter Bäumen nicht mehr. Was wir gemacht haben, war, dem Computer eine neue Beschreibungssprache beizubringen, einen [Latent Space](https://en.wikipedia.org/wiki/Latent_space), in dem er Bilder effizienter darstellen kann als im Raum der Bildpunkte. Auf diese Weise kann er lange Zusammenhänge in Bildern, an denen es bisher gemangelt hatte, effizienter erfassen. Unser Ziel war es, diese KI lauffähig zu machen auf Consumer-Hardware, die nur 300 oder 400 Dollar kostet. Mittlerweile läuft sie auf dem Mobiltelefon und nicht mehr nur auf Hardware-Clustern, die für viel Geld in großen Firmen vorgehalten werden müssen.

### 05:09 – Vergleich mit anderen Modellen

**Leonard Schmedding**

Jetzt nutzen die meisten, die mit KI Bilder erstellen wollen, ChatGPT, früher die DALL-E-Modelle, jetzt das neue [ChatGPT Image](https://openai.com/index/introducing-4o-image-generation/) oder [Midjourney](https://www.midjourney.com/). Was sind die Unterschiede von Stable Diffusion zu diesen Modellen?

**Prof. Dr. Björn Ommer**

Man kann auch Videomodelle nennen. Jetzt kam [Veo 3](https://deepmind.google/technologies/veo/) raus, und im White Paper haben sie sehr schön dargestellt, dass sie auch einen latenten Diffusionsansatz, also unseren Ansatz, verwenden. Der ist der De-facto-Standard für die Bildgenerierung geworden. Was wir mit dieser Sprache gemacht haben, ist eine effiziente Art und Weise, Bilder oder Videos darzustellen, und die ist mittlerweile in nahezu allen Bild- und Videogeneratoren drin. Das hilft den kleinen Anwendern, die nicht so viel Hardware haben, aber den großen Firmen hilft es auch, weil sie ihre Modelle dadurch noch besser hochskalieren können. Selbst die neuesten Modelle wie Veo 3 verwenden diesen Ansatz. An den technischen Details ändert sich ein bisschen was, man verwendet kein [Faltungsnetz](https://en.wikipedia.org/wiki/Convolutional_neural_network) mehr, sondern eine [Transformer-Architektur](https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)), aber am Latentansatz ändert das nichts.

### 06:18 – Tools & Plattformen

**Leonard Schmedding**

Welche Tools und Plattformen gibt es momentan, die auf Stable Diffusion aufbauen? Du hast Veo 3 genannt. Gibt es vielleicht noch ein paar Beispiele, an die die meisten gar nicht denken würden?

**Prof. Dr. Björn Ommer**

Es ist ziemlich breit eingesetzt worden. Ein bekannter Prozessorhersteller hat immer Aufkleber gemacht, "Intel Inside" auf die Hardware gedruckt. Das ist bei Stable Diffusion nicht der Fall, weil wir es Open Source released haben, aber [Apple](https://www.apple.com/) hat es zum Beispiel sehr früh in seinen [Core ML](https://developer.apple.com/documentation/coreml) Stack integriert und bei der Bildgenerierung verwendet. Es ist in vielen weiteren Bildgenerierungs-Tools, aber auch in der Bildanalyse drin, die dadurch befeuert wurde. Bildanalyse zum Beispiel im biomedizinischen Bereich, [Krebserkennung](https://en.wikipedia.org/wiki/Computer-aided_diagnosis), Hautkrebs, Analyse von [Röntgenbildern](https://en.wikipedia.org/wiki/X-ray) oder bis zum [autonomen Fahren](https://en.wikipedia.org/wiki/Self-driving_car).

### 07:19 – Kritik an Generativer KI

**Leonard Schmedding**

Bemerkenswert, was ihr da ins Rollen gebracht habt. Wenn wir heute über generative KI sprechen, viele setzen das fast synonym mit ChatGPT. Dann sagen Kritiker, die ich teilweise auch im Gespräch hatte: das ist im Endeffekt nur ein [stochastischer Papagei](https://en.wikipedia.org/wiki/Stochastic_parrot), und viel wird das am Ende nicht verändern, das wird auch niemals Jobs ersetzen können. Ich weiß, du blickst da ein bisschen anders drauf. Was würdest du so jemandem entgegnen?

**Prof. Dr. Björn Ommer**

Fangen wir vorne an: warum wird es als stochastischer Papagei bezeichnet? Generative KI wird selbstüberwacht trainiert. Bei ChatGPT nehme ich eine ganze Menge an Texten und gebe den Anfang des Satzes vor und sage: "Mach bitte weiter." Bei Bildern zeige ich ein Bild, halte einen Teil zurück und sage: "Ergänze bitte den Rest." Man kann nicht sicher die Vorhersage machen, weil ein Satz auf verschiedene Arten weitergehen kann. Daher kommt der stochastische Papagei, weil eine gewisse Statistik dahintersteckt. Insofern passt die Analogie zuerst auf das, was gelernt wird.

Das Interessante ist jedoch, dass beim Trainieren mehr als nur diese statistische Vorhersage herauskommt. Wir sehen [emergente Eigenschaften](https://en.wikipedia.org/wiki/Emergent_abilities). Als wir Stable Diffusion und schon den Vorgänger, das [VQ-GAN](https://compvis.github.io/taming-transformers/)-Modell, trainiert hatten, konnten wir beobachten, dass etwas passiert, was sich in meiner akademischen Karriere so nicht immer eingestellt hatte. Wir haben Bilder reingesteckt, und auf einmal hat das System etwas gelernt, was wir nicht direkt beigebracht haben. Es hat Schattenwürfe und Reflexionen gelernt, obwohl wir es nur Bilder generieren lassen wollten. Diese emergenten Eigenschaften erheben so ein System darüber, dass es nur nachplappert. Man kann sich vorstellen, die Trainingsdatenpunkte sind wie Inseln im Pazifik, und dazwischen ist sehr viel Wasser. Was die KI macht, ist, langsam Landbrücken zu erzeugen. Man spricht auch von [Interpolation](https://en.wikipedia.org/wiki/Interpolation). Neues Wissen entsteht durch das Verbinden der Trainingsdatenpunkte. Das erhebt das System über reines Nachplappern.

### 09:59 – KI mit Analogien erklärt

**Leonard Schmedding**

Das war eine sehr gute Erklärung. Es gibt ja viele Analogien, zum Beispiel Elektrizität, oder ich hatte letztens den Vergleich gehört, KI ist wie Transport, das kann eine Rakete sein, aber auch ein altes Fahrrad. Wie würdest du generative KI beschreiben? Was wäre für dich die beste Analogie?

**Prof. Dr. Björn Ommer**

Ich bezeichne es gerne als [Ermöglichungstechnologie](https://en.wikipedia.org/wiki/General-purpose_technology), um das über banale Ansätze hinauszuheben. Eine Ermöglichungstechnologie wie die Elektrizität, der Personal Computer oder das Internet zuvor. Wir erzeugen Strom ja nicht, weil Strom schön wäre, sondern wegen der Millionen von anderen Technologien, die darauf aufbauen können. So verhält es sich bei generativer KI auch. Sie wird zum Ermöglicher für zukünftigen technologischen Fortschritt für viele Technologien, die bisher nicht entwickelt worden sind oder dadurch verbessert werden. Wir können uns noch gar nicht ausmalen, was dort alles auf uns zukommen wird. Wichtig ist: generative KI erfüllt in der Zukunft Aufgaben jenseits des reinen Generierens von Content, und dort liegt sehr viel Wertschöpfung und Potenzial.

### 11:42 – Zukünftige KI-Anwendungen

**Leonard Schmedding**

Was sind aus deiner Sicht die nächsten Use Cases nach der generativen KI, wenn wir mal überall richtig gut sind, bei Texten, Bildern, Videos, Audios?

**Prof. Dr. Björn Ommer**

Lass mich das festhalten: generative KI muss nicht verschwinden. Es werden Use Cases danach kommen. Aber zur Kontextualisierung: wir sprechen von generativer KI im Gegensatz zur diskriminativ trainierten KI. Bei diskriminativer KI habe ich dem Bildmodell Hunde- und Katzenbilder gezeigt und gesagt: finde heraus, was Hunde und Katzen unterscheidet. Das Problem ist, dass die KI relativ schnell faul wird und nach dem einen Pixel sucht, mit dem man beides trennen kann, ohne wirklich zu lernen, was eine Katze oder einen Hund ausmacht. Bei der generativen KI haben wir den Prozess umgedreht und gesagt: wenn du verstanden hast, was einen Hund ausmacht, dann synthetisier mal einen. Wenn die KI bisher die Abkürzung gegangen ist und sagt, ein Hund hat einen Knochen im Maul, dann würde bei der Generierung halt der Knochen herauskommen. Dieses selbstüberwachte Training macht das Generative aus.

Wir können mit generativer KI deutlich über das Generieren von Bildern hinausgehen. Wir sehen jetzt das Zeitalter der Apps, der Applikationen, die auf [Foundation Models](https://en.wikipedia.org/wiki/Foundation_model) aufbauen. Anwendungen im biomedizinischen Bereich, überall dort, wo Bilder aufgenommen werden, sei es Röntgen, [MRT](https://en.wikipedia.org/wiki/Magnetic_resonance_imaging), Hautkrebs-Analyse. Im textgestützten Bereich gibt es unendlich viel Potenzial: Inhalte persönlich erklären lassen, Lernunterstützung, persönliche Beratung, Lebenshilfe. Autonomes Fahren wird immer als Standardanwendung erwähnt. Da ist Sky the Limit.

### 14:26 – Nächste Durchbrüche

**Leonard Schmedding**

Was glaubst du werden die nächsten Durchbrüche sein? Bei Fotos und Bildern sind wir auf gutem Level. Veo 3 hat Augen geöffnet, aber abschließend perfekt ist es noch nicht. Was werden wir als Nächstes sehen?

**Prof. Dr. Björn Ommer**

Wir beobachten, dass generative KI sehr gut ist, wenn ich ihr alle Freiheiten lasse. Sobald ich sie an die Zügel nehmen, kontrollieren möchte, wird es schwierig. Mehr Kontrolle in den Generierungsprozess hineinzubekommen, ist sicherlich der nächste Punkt. Bei Videos sehen wir, dass schon einiges vorangegangen ist, aber es ist enorm teuer. Man sieht es an den Preisen bei den großen Plattformen. Auch für sie ist das im Moment kein wirtschaftlicher Prozess, das in Millionen oder Milliarden hochzuskalieren, ist nicht direkt machbar. Da wird an der Effizienz noch viel Arbeit nötig sein.

Wir haben über lange Zeit ein exponentielles Wachstum gesehen, und viel in der generativen KI ist durch reines Hochskalieren gelöst worden. Wir haben dafür einen sehr hohen Preis gezahlt, auch die großen Firmen. Jetzt geht es darum, neue Entwicklungen zu machen, die diesen Preis runterdrücken und uns wieder in exponentielles Wachstum hineinbringen, idealerweise in der Breite. Deswegen haben wir ursprünglich auch für die Demokratisierung von generativer KI plädiert und mit Stable Diffusion in dieser Richtung gearbeitet.

### 16:43 – Zukunft humanoider Roboter

**Leonard Schmedding**

Ich hatte zuletzt mit [David Reger](https://www.linkedin.com/in/david-reger-neura-robotics/), CEO von [Neura Robotics](https://neura-robotics.com/), gesprochen. Er sagte, wir werden 2026 einen großen Umbruch erleben. Du beschäftigst dich auch mit Physical AI. Wann gibt es den großen Umbruch bei [humanoiden Robotern](https://en.wikipedia.org/wiki/Humanoid_robot)?

**Prof. Dr. Björn Ommer**

[Agentic](https://en.wikipedia.org/wiki/Intelligent_agent) und Physical AI sind die nächsten großen Themen, bei denen die generative KI in unsere Wirklichkeit ausstrahlt. Bei Physical AI geht es darum, sie mit Robotern in unsere physische Wirklichkeit hineinzubringen, dass sie selbst physisch handeln kann. Wir sehen, dass die Skalierung der Robotik hochgeht. Es wird vorhergesagt, dass noch in diesem Jahrzehnt Roboter so erschwinglich werden, dass sie in einem Haushalt einsetzbar sind, sogar humanoide Roboter zu verträglichen Preisen. Es gibt auch Mietsysteme, sodass sie Alltagsaufgaben erledigen können.

Ich sehe sie zuerst im industriellen Kontext. Generative KI ist essentiell, damit diese Systeme im Alltag mit uns Menschen interagieren können. Bisher baut man auch im industriellen Kontext Zäune um Roboter, weil es schwierig wird, sobald ein Mensch in Reichweite ist. Generative KI ist das Mittel der Wahl, um die Interaktion zwischen Menschen und Robotern besser herauszuarbeiten.

### 18:35 – Was ist AGI?

**Leonard Schmedding**

Eines der heiß diskutiertesten Themen ist [AGI](https://en.wikipedia.org/wiki/Artificial_general_intelligence), die allgemeine künstliche Intelligenz. Die einen sagen, wir haben sie bald erreicht, andere sagen, humanoide Roboter muss man mitdenken. Wie würdest du AGI definieren, und wie ist deine Einschätzung zur Timeline?

**Prof. Dr. Björn Ommer**

Definition ist gut. Es werden ständig Akronyme herumgeworfen, interessanterweise von denselben Leuten zuerst etwas abschreckend benutzt: "Bald kommt die AGI, und das Ende ist nah", und gleichzeitig: "Wir haben sie schon erreicht, deswegen kauft unsere Produkte." Wenn man es nüchtern sieht, kontrastiere ich Artificial General Intelligence mit Nischenintelligenz. Woran wir arbeiten, ist eine generelle Intelligenz im Gegensatz zu der Nischenintelligenz, die nur Hunde von Katzen unterscheiden kann. Das ist faktisch etwas, was schon die ganze Zeit passiert. Ein Foundation Model ist nichts anderes. Wir haben es bei [GPT](https://en.wikipedia.org/wiki/Generative_pre-trained_transformer) und ähnlichen Systemen mit Modellen zu tun, die nicht nur Kochrezepte produzieren, sondern auch programmieren, Musik machen und schreiben können. Dort haben wir es bereits mit der generelleren Intelligenz zu tun. An der Qualität hat es noch gemangelt. Das Absichern der Technologie war bisher sehr teuer. Man spricht vom [Reinforcement Learning](https://en.wikipedia.org/wiki/Reinforcement_learning_from_human_feedback), das viel menschliches Feedback erfordert. Da ist die Frage, ob man das in Zukunft effizienter hinbekommt.

### 20:21 – Zukunfts-Einschätzung

**Leonard Schmedding**

Vielleicht noch eine Einschätzung zur Timeline: wann werden wir AGI erreicht haben?

**Prof. Dr. Björn Ommer**

Eine generelle Intelligenz haben wir schon mit den [Vision-Language-Modellen](https://en.wikipedia.org/wiki/Multimodal_learning), die da sind. Was uns fehlt, sind weitere Modalitäten zu integrieren, Robotik zum Beispiel. Aber die Qualität ist die andere Frage. Eine sehr performante generelle Intelligenz ist das, worum es jetzt geht. Viele große Firmen sprechen dann auch von Superintelligence, der [Artificial Superintelligence](https://en.wikipedia.org/wiki/Superintelligence). Wenn es nicht mehr ausreicht, dass die KI generell ist, muss sie besser werden als wir Menschen. Auch das war nüchtern betrachtet das Ziel. Keiner hätte gesagt, ich setze mich daran, eine Intelligenz zu bauen, die schlechter als Menschen wird. Es ist eine Richtung, auf der wir uns immer bewegt haben. Es ist schwer, das in Gänze zu messen. Wir werden wie in der Vergangenheit sehen, dass die KI in immer mehr Anwendungsfällen besser wird, menschliche Performance schlägt oder zumindest zu einem nützlichen Werkzeug wird. In allen Dingen gleichzeitig wird das so schnell nicht passieren.

**Leonard Schmedding**

Sehr interessant, dass du sagst, im Prinzip arbeiten wir die ganze Zeit schon an dieser generellen Intelligenz. Manche sagen, es wird einen komplett neuen Ansatz brauchen.

**Prof. Dr. Björn Ommer**

Für die Skalierung wird es einen neuen Ansatz brauchen, damit es effizienter wird.

### 22:09 – Jobverluste durch KI

**Leonard Schmedding**

Ein heiß diskutiertes Thema sind Jobverluste durch KI. Viele sagen: ich sehe es noch nicht so wirklich. Ich hatte zuletzt eine Aussage von [Anthropic](https://www.anthropic.com/) Co-Founder [Benjamin Mann](https://www.linkedin.com/in/benjamin-mann/) gehört: es liegt an unserem linearen Denken, es wird schneller gehen, als die meisten sich vorstellen. Wie siehst du das, auch im Hinblick auf die exponentielle Kurve generativer KI?

**Prof. Dr. Björn Ommer**

Das hört sich so an, als wäre das das Ziel. Es ist natürlich nicht das Ziel, Menschen arbeitslos zu machen, sondern das Gegenteil: ein Werkzeug, das uns das Leben und Arbeiten einfacher machen sollte. Wir beobachten heute viel Klagen über Frustration im Job. Einiges liegt an Boilerplate-Dingen, die wir nicht machen wollen, für die wir nicht berufen sind. Wenn man diesen Teil wegnähme und die Leute das machen ließe, worin sie am besten sind, könnten Arbeiten deutlich interessanter werden.

Was den Verlust angeht: das Naheliegendste ist, dass das Bestehende automatisiert wird, höher, schneller, weiter. Was man aber nicht so sehr sieht, sind die Dinge, die sich neu auftun. Ganz neue Geschäftsfelder. Es wäre einfach gewesen, beim Aufkommen der Telekommunikationstechnologie darauf zu verweisen, dass die [Brieftaubenzüchter](https://en.wikipedia.org/wiki/Carrier_pigeon) jetzt ein hartes Leben haben werden. Aber man konnte nicht sehen, dass Menschen wie du dadurch erst ihren Job bekommen, dass der gesamte Bereich der neuen Medien und Telekommunikation Millionen von Jobs verschafft hat. Durch die neue Technologie ergeben sich Möglichkeiten, weil etwas hochskaliert wird und Dinge bezahlbar werden. Diesen Bereich vorherzusagen, machen wenige. Wenn jemand eine Idee hat, verwandelt er sie in ein Geschäftsmodell, anstatt sie zu publizieren. Deswegen ist der Fokus immer auf dem, was vielleicht verschwindet, weniger auf dem Neuen.

### 24:41 – Neue KI-Berufsfelder

**Leonard Schmedding**

Was siehst du, was sich an neuen Berufsfeldern abzeichnet? Es gibt banale Beispiele wie [Prompt Engineer](https://en.wikipedia.org/wiki/Prompt_engineering).

**Prof. Dr. Björn Ommer**

Das würde ich gerade nicht sagen. Prompt Engineering ist für mich ein Problem der Anfangsphase gewesen. Wenn wir uns die LLMs anschauen, ist es ein bisschen so, als würden wir mit dem Betriebssystem selbst sprechen. Es kann nicht das Endprodukt sein, dass ich durch ein Textterminal mit dem Computer spreche und Empfehlungen bekomme, was ich tun sollte. Mit Robotic und Agentic AI setzt die Maschine ihre Vorschläge selbst um. Dieser Teil liegt nahe, dass ich das Ganze in Apps gieße und nicht mehr über ein Textterminal interagiere. Bei Ärzten ist das naheliegend. Im Straßenverkehr werde ich dem autonom fahrenden Auto nicht reintippen, was ich tun sollte. Da gibt es enorm viel Potenzial für Applikationen, bei denen die LLMs nur noch eine [Reasoning Engine](https://en.wikipedia.org/wiki/Inference_engine) unter der Haube sind. Bei unserem Betriebssystem klicke ich auch herum und sehe nicht, was im Terminal passiert.

### 26:16 – Arbeiten mit KI

**Leonard Schmedding**

Wie könnten wir in Zukunft mit KI arbeiten? Voice ist ein großes Thema, langfristig vielleicht [Brain-Computer-Interfaces](https://en.wikipedia.org/wiki/Brain%E2%80%93computer_interface).

**Prof. Dr. Björn Ommer**

Idealerweise gar nicht. Im Moment müssen wir der KI noch sehr stark beschreiben, was wir denken. Wenn die KI im Sinne von Agentic AI in unseren Alltag integriert ist, weiß sie idealerweise, was ich will, bevor ich es überhaupt sagen muss. Sie kann dadurch, dass sie mich im Alltag begleitet, das mitbekommen, und dann ist nur noch wenig Input nötig, um sie zu steuern.

### 27:00 – Bequemlichkeit & Privatsphäre

**Leonard Schmedding**

Interessant. Die KI würde alles über uns kennen und schon wissen, was wir brauchen, bevor wir es selbst wissen. Das geht logischerweise mit neuer Hardware einher.

**Prof. Dr. Björn Ommer**

Nicht notwendigerweise. Die KI ist schon in die meiste Hardware integriert, in Betriebssysteme. Sie wird viel mitbekommen, was ich digital mache. Inwiefern man sie ins nicht digitale Leben hineinlässt, ist eine andere Frage. Was ich gerade positiv gesagt habe, hat seine offensichtlichen Schattenseiten. Die KI hat dadurch, dass sie agentic wird, für die Hersteller einen großen Vorteil: bisher ist das Problem, an weitere Trainingsdaten heranzukommen. Dann bekommen sie das Privateste, was man bekommen kann, eine KI, die mich im Alltag begleitet und alles mitbekommt, was ich digital, vielleicht sogar offline mache. Mit dieser Währung würde man bezahlen. Wir müssen uns überlegen, ob und in welchem Grad wir das wollen, insbesondere mit welchen Herstellern, gerade wenn sie im Ausland sitzen. Die KI wird unglaublich bequem werden, viele werden das einfach tun wollen. Es wird eine große Herausforderung, bei der Bequemlichkeit auch Abstriche zu machen, weil man Gewisses nicht preisgeben möchte.

### 28:31 – Deepfakes & Schutzmaßnahmen

**Leonard Schmedding**

Ein großes Risiko ist das Problem der [Deepfakes](https://en.wikipedia.org/wiki/Deepfake). Google arbeitet an [SynthID](https://deepmind.google/technologies/synthid/), ChatGPT hat den [C2PA-Standard](https://c2pa.org/) eingeführt. Die Bilder werden über ein [Wasserzeichen](https://en.wikipedia.org/wiki/Digital_watermarking) als KI-generiert gekennzeichnet. Wird das was bringen, und wie kann man langfristig vorbeugen?

**Prof. Dr. Björn Ommer**

Die Frage ist, gegen wen man sich vorbereiten will. Leute, die Fakes generieren, wollen nicht, dass das als solches erkannt wird. Wenn die nicht aus dem Inland kommen, sondern aus dem Ausland, gibt es Gegenspieler, die wir alle auf dem Radar haben, die im politischen Wettstreit oder im offensiven Kampf mit uns stehen. Man kann sich vorstellen, dass sie nicht unbedingt ein Wasserzeichen draufmachen, mit dem sie unsere Gesellschaft in den Abgrund stürzen wollen. Da hilft das nicht besonders viel. Ich kann mir aber das Gegenteil vorstellen: dass vertrauenswürdige Quellen, Medienplattformen, Journalisten nicht nur ein Copyright reintun, sondern kundtun wollen, dass das durch ihre Feder gelaufen ist, etwas, dem sie trauen. Ein Fotojournalist, der dieses Bild gemacht hat, möchte es signieren, um seinen Stempel der Trustworthiness draufzumachen. So herum kann es funktionieren. Sich darauf zu verlassen, dass alle, die Fakes produzieren, ihre Bilder als solche signieren, wird nicht hilfreich sein.

### 30:11 – Fakes vs. Wahrheit

**Leonard Schmedding**

Aufklärung wird der beste Weg sein. Prinzipiell alles in Frage zu stellen, was man online sieht.

**Prof. Dr. Björn Ommer**

Ein kritischer Blick, den sollte man nicht erst ab sofort, sondern in der Vergangenheit schon gehabt haben. Das nimmt in Zukunft weiter zu. Bei allem kritisch zu sein, da bin ich vorsichtig, weil das für mich das größere Problem ist: nicht die Fakes, sondern dass mit diesen Fakes auch die Wahrheit angefangen wird in Frage zu stellen. Wir Menschen können uns nur durch diese Wirklichkeit bewegen, wenn wir auch vertrauen. Wir müssen kritisch befragen, wem wir vertrauen, aber ich kann mich in kein Flugzeug, in kein Auto setzen, wenn ich nicht vertraue, dass die anderen zumindest vertrauenswürdig sind.

### 31:13 – KI-native Generation

**Leonard Schmedding**

Wie wird sich das auf die nächste Generation auswirken, die kein Leben ohne generative KI mehr kennt? Es gibt erste [Studien zu Schülern](https://www.media.mit.edu/projects/your-brain-on-chatgpt/overview/), die rein mit KI arbeiten und Texte sofort für Münze nehmen. Wie blickst du auf die [AI-Native Generation](https://en.wikipedia.org/wiki/Generation_Alpha)?

**Prof. Dr. Björn Ommer**

Bildung ist ein wichtiges Stichwort. Wir haben von [Digital Literacy](https://en.wikipedia.org/wiki/Digital_literacy) gesprochen, jetzt wird es vermutlich AI Literacy sein. Wir haben eine Generation, die in Zukunft auf dem internationalen Arbeitsmarkt mit anderen Ländern konkurrieren wird, bei denen das von vornherein drin ist. Es ist wichtig, die nächste Generation mit diesen Werkzeugen vertraut zu machen. Es bleiben Grundkenntnisse wichtig, auch nicht digitale, denn bei einer rapide entwickelnden Technologie ist schwer vorherzusagen, wo es hingeht. Eine breite Ausbildung wird weiterhin wichtig sein. Darüber hinaus, dieses kritische Hinterfragen, etwas, was man im Wissenschaftsbetrieb täglich macht, müssen junge Menschen weiterhin lernen. Dazu ist es wichtig, diese Technologie in den Alltag im Unterricht zu integrieren. Mir wurde mal eine Studie genannt, dass drei Viertel der jungen Menschen ChatGPT für Hausaufgaben verwenden. Ich vermute, die Dunkelziffer ist nochmal ein Viertel, sodass eigentlich jeder es einsetzt. Die bisherige Lehrergeneration ist nur bedingt darauf vorbereitet. Wir werden viel tun müssen, um uns an diese schnelle Entwicklung anzupassen.

### 33:19 – Einfluss auf deutschen Arbeitsmarkt

**Leonard Schmedding**

Was ich noch unterstreichen will: die Folgegeneration wird auf dem internationalen Arbeitsmarkt konkurrieren, durch [Live Translation](https://en.wikipedia.org/wiki/Machine_translation) und Remote-Arbeit. Das ist eine massive Verwerfung für den deutschen Arbeitsmarkt, der noch sehr auf [Fachkräftemangel](https://de.wikipedia.org/wiki/Fachkr%C3%A4ftemangel) schaut.

**Prof. Dr. Björn Ommer**

Wir sehen enorme Produktivitätsgewinne durch KI, Qualitätszuwächse, die sich einstellen, nicht in den Anfangsphasen, aber mit dieser Technologie, die jetzt besser wird. Verbesserung für Teams, die kooperieren. Es wird schwer sein, international zu konkurrieren, wenn diese Technologie nicht da ist. Deswegen ist es wichtig, dass wir in die technologische Entwicklung in Europa und gerade in Deutschland einsteigen, damit wir den Anschluss nicht verlieren. Sonst würde ich vorhersagen, dass wir in baldiger Zukunft eine vollständige Abhängigkeit von Tools haben, die aus dem Ausland über uns kommen. Mit der Souveränität ist es dann nicht mehr weit her. Es wird uns gehen wie mit Strom und Gas vor kurzem, wo wir vielleicht andere Meinungen hätten, aber wenn es kalt und dunkel wird, behalten wir die für uns. Wir müssen vielleicht nicht jede Schraube kennen, aber in den Grundzügen, in der Breite eine gewisse Souveränität aufbauen, damit wir nicht komplett abhängig werden und diesen Wandel nicht verschlafen.

### 34:51 – Deutschlands KI-Rolle

**Leonard Schmedding**

Du und dein Team habt im wissenschaftlichen Arbeiten Pionierarbeit geleistet. Häufig wird kritisiert, Deutschland sei gut in der Grundlagenforschung, aber im Unternehmerischen abgeschlagen. Du bist da optimistischer. Was sind die Chancen für Deutschland, international die nächsten Jahre noch mitzumischen?

**Prof. Dr. Björn Ommer**

Wir hatten nicht nur die Forschung, sondern aus dem Lehrstuhl heraus auch erfolgreiche Startups. Grundständig denke ich, dass wir in Deutschland noch das Potenzial haben. Es liegt nahe, auf den Status quo zu schauen und zu sagen, schaut, wie gut wir in generativer KI weltweit sind, eigentlich ist die Entwicklung abgeschlossen im Vergleich zu vor 10 Jahren. Aber wir befinden uns in etwa dort, wo [Ford mit dem Model T](https://en.wikipedia.org/wiki/Ford_Model_T) vor 100 Jahren gewesen ist. Da konnte man auch sagen: das Auto fährt, was will man mehr? Vielleicht ein bisschen schneller. Aber wir haben 100 Jahre der Entwicklung danach gesehen, in Deutschland sehr stark profitiert. Genauso jetzt mit der Demokratisierung der generativen KI.

Was haben wir? Wir haben sehr viele [SMEs](https://en.wikipedia.org/wiki/Small_and_medium-sized_enterprises), kleine und mittelständische Unternehmen, und die haben etwas, was Millionen von Bildern auf sozialen Netzwerken nicht bieten können: proprietäre Informationen, direkten Kontakt zu Kunden, die ihnen vertrauen, und [Expertenwissen](https://de.wikipedia.org/wiki/Hidden_Champion). Das ist das Öl der neuen Welt, diese Daten, die orthogonal sind zu den übrigen Daten, die in sozialen Netzwerken herumgeistern. Plus das Wissen darüber, wie sich so eine KI verhalten sollte, denn wir machen viel [Fine-Tuning](https://en.wikipedia.org/wiki/Fine-tuning_(deep_learning)). Da haben unsere mittelständischen Firmen Vorteile. Umgekehrt bedeutet generative KI für sie einen Vorteil, denn bisher hatten die Big-Tech-Firmen, die KI in der DNA haben, den großen Vorteil, weil sie an der Quelle waren. Jetzt sehen wir, dass auch kleine Firmen ohne Riesen-Entwicklungsabteilung in die Lage versetzt werden, angepasste Software-Lösungen für ihre Probleme zu entwickeln.

Wir sehen im Software Engineering eine Transition. Erst handgetriebenes Coden, dann in den Nullerjahren das klassische [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning), bei dem die Daten die Erzeugung vorangetrieben haben. Damit sind die großen Tech-Firmen nach vorne gekommen. Jetzt mit generativer KI sehen wir einen massiven Umbruch. Auf einmal muss ich die Software nicht mehr selbst generieren, ich muss nicht mehr das Lernverfahren erzeugen, sondern ich kann das Problem beschreiben, von der KI eine Lösung generieren lassen und in einen Dialog eintreten. Das kann ich ohne Riesen-Team. Dort sehe ich große Vorteile als Ermöglicher für den Mittelstand.

### 39:01 – Fazit & Appell

**Leonard Schmedding**

Wir haben viele Zuschauer, Arbeitnehmer und Unternehmer, die sich fragen, wie sie profitieren und nicht den Anschluss verlieren. Was ist dein abschließender Appell?

**Prof. Dr. Björn Ommer**

Wir haben eine sich rapide entwickelnde Technologie. Das Erste ist also: ausprobieren. Ich muss verstehen und begreifen, wie sie sich verhält. Der zweite Teil: wir sehen eine Transition dazu, dass Intelligenz zu einer neuen [Commodity](https://en.wikipedia.org/wiki/Commodity) wird, künstliche Intelligenz, die verfügbar wird, schnell, breit und tief. Es gibt keinen 5-Punkte-Plan, wie ich mit KI mein Business mache, sondern es braucht ein neues Mindset, das begreift, was es bedeutet, wenn AI zu einer skalierbaren Commodity wird, dass sich gewissermaßen eine neue Dimension aufgetan hat. Bisher war ich zweidimensional in der Ebene, auf einmal kann ich wie mit dem Flugzeug darüber hinwegfliegen. Das muss jeder für sein eigenes Geschäftsmodell ausbuchstabieren. Wenn ich mein Business durch die Augen einer so mächtigen Technologie neu betrachte, tut sich ganz neues Land auf.

**Leonard Schmedding**

Perfektes Schlusswort. Björn, ich wünsche dir weiterhin viel Erfolg, alles Gute, super gerne bis zum nächsten Mal.

**Prof. Dr. Björn Ommer**

Vielen Dank.

---

Quelle: https://www.youtube.com/watch?v=CssEFTqn5LU
