# Prof. Dr. Alexander König × Leonard Schmedding Interview

Prof. Dr. Alexander König · Professor für Robotik und Systemintelligenz an der [TU München](https://www.tum.de/), Leiter [TUM Campus Geriatronik](https://www.mirmi.tum.de/geriatronik/) und Gründer von [Reactive Robotics](https://reactive-robotics.com/) · [@everlastai](https://www.youtube.com/@everlastai) · 2025-12-25 · 51 Min · Deutsch · [YouTube](https://www.youtube.com/watch?v=aYUxYYLb_2o)

[Prof. Dr. Alexander König](https://www.linkedin.com/in/alexander-h-koenig/) ist einer der führenden deutschen Pioniere an der Schnittstelle von [Künstlicher Intelligenz](https://de.wikipedia.org/wiki/K%C3%BCnstliche_Intelligenz), [Robotik](https://en.wikipedia.org/wiki/Robotics) und Medizin. Nach seiner Promotion an der [ETH Zürich](https://ethz.ch/) und Forschung an der [Harvard Medical School](https://hms.harvard.edu/) mit Publikationen in Nature, Science und Cell gründete er 2015 das MedTech-Startup [Reactive Robotics](https://reactive-robotics.com/), dessen [VEMO-System](https://reactive-robotics.com/de/vemo/) die Genesung intensivpflichtiger Patienten im Schnitt um 20 Prozent beschleunigt. An der TU München entwickelt er mit seinem Team den humanoiden Pflegeassistenten [Garmi](https://www.mirmi.tum.de/geriatronik/forschung/garmi/), der eigenständig Wasser eingießt, beim Bewegungstraining unterstützt und über Telemedizin sogar das Abhören mit dem Stethoskop aus der Ferne ermöglicht. Im Gespräch geht es um die Mythen rund um humanoide Roboter, warum Service-Roboter aktuell sinnvoller sind als zweibeinige Humanoide, wie [Visual Language Action Models](https://en.wikipedia.org/wiki/Vision-language-action_model) zusammen mit physikalischen Simulationen wie [MuJoCo](https://en.wikipedia.org/wiki/MuJoCo) das Trainingsdaten-Bottleneck lösen, warum [China](https://en.wikipedia.org/wiki/Robotics_in_China) mit seinem 10.000 Quadratmeter großen Humanoid Robot Data Training Center in Shanghai gerade davonzieht, weshalb [Zürich](https://en.wikipedia.org/wiki/Z%C3%BCrich) zum europäischen Robotik-Valley wird und welche Jobs in einer Welt mit [Embodied AI](https://en.wikipedia.org/wiki/Embodied_cognition) wirklich zukunftssicher bleiben.

## Timestamps

- [00:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=0s) – Einblick und Teaser
- [01:04](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=64s) – Alexanders beeindruckender Hintergrund
- [04:05](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=245s) – Translation: vom Labor in die Realität
- [05:46](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=346s) – Mythen über Roboter
- [08:43](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=523s) – Garmi: das humanoide Projekt der TUM
- [11:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=660s) – Sicherheit bei Robotern
- [12:40](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=760s) – Sechs Arme, zwei Daumen, ein Formfaktor
- [16:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=960s) – Wie ChatGPT die Robotik verändert
- [21:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=1260s) – Trainingsdaten als Bottleneck
- [24:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=1440s) – Simulation trifft Realität
- [26:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=1560s) – China baut die Infrastruktur
- [28:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=1680s) – Kollektives Lernen funktioniert
- [29:46](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=1786s) – Akzeptanz durch Wertschöpfung
- [32:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=1920s) – Deutschland gegen China
- [37:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=2220s) – On-Premise und Datenschutz
- [39:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=2340s) – Zürich als Robotik-Valley
- [43:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=2580s) – Weltmodelle als nächste Welle
- [45:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=2700s) – Zeithorizont von zehn Jahren
- [48:00](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=2880s) – Jobsicherheit und Empfehlungen
- [51:17](https://www.youtube.com/watch?v=aYUxYYLb_2o&t=3077s) – Fazit und Ausblick

## Transcript

### 01:04 – Alexanders beeindruckender Hintergrund

**Leonard Schmedding**

Hallo Alexander, schön, dass du heute mit dabei bist. Wir werden heute über einige Themen im Bereich der Robotik und der humanoiden Roboter sprechen. Du bist mitverantwortlich für das Forschungszentrum [Geriatronik](https://www.mirmi.tum.de/geriatronik/) an der TU München und hast 2015 [Reactive Robotics](https://reactive-robotics.com/) gegründet, ein MedTech-Startup für KI-gesteuerte Reha- und Intensivpflege-Robotik. Welche Themen interessieren dich gerade besonders?

**Prof. Dr. Alexander König**

Mich interessiert ganz allgemein erst einmal das Thema Translation. Wie kriegen wir Technologie, die in Universitäten entwickelt wurde, in die Realität, also die PS auf die Straße? Mein Hintergrund ist eher in der [Medizintechnik](https://de.wikipedia.org/wiki/Medizintechnik), das heißt Themen, die zulassungspflichtig sind, interessieren mich. Im Bereich Garmisch, [Geriatronik](https://www.mirmi.tum.de/geriatronik/), geht es um die Frage: Wie kann ich als älterer Mensch länger selbstbestimmt zu Hause leben? Bei Reactive Robotics war es die Frage, wie wir Menschen mit Technologie helfen können, schneller aus der Intensivstation rauszukommen. Was mich aktuell sehr fasziniert, sind [Visual Language Action Models](https://en.wikipedia.org/wiki/Vision-language-action_model). Also die Frage, wie wir große KI-Modelle verwenden, um damit wirklich Roboter zu steuern.

### 05:46 – Mythen über Roboter

**Leonard Schmedding**

Wir haben hier schon häufig über Roboter und humanoide Roboter gesprochen, und dann sehe ich immer wieder, dass es scheinbar noch große Vorbehalte gibt. Womit bist du da am häufigsten konfrontiert?

**Prof. Dr. Alexander König**

Mythen eher weniger, würde ich sagen, eher Sorgen. Viele Menschen haben kein wirkliches Verständnis, was KI tut, wie es ihr Leben beeinflusst und wie schnell es kommt. Besonders im Kontext der Pflege älterer Menschen, in einer überalternden Gesellschaft, kommt die Frage: Werde ich in Zukunft in der Ecke geschoben und von Technologie am Leben gehalten, anstatt menschlichen Kontakt zu bekommen? Da versuche ich klarzumachen, dass die Robotik bei weitem noch nicht so weit ist, dass wir robotische Pflegekräfte haben. Robotik kann unterstützen, wo wir Menschen nicht optimal eingesetzt sind: bei Dokumentation, beim Tragen schwerer Sachen. Damit Menschen wieder mehr Zeit für Menschen haben.

Gleichzeitig ist es wichtig aufzuklären, warum es unumgänglich ist, Technologie einzusetzen. Wir werden 2050 meines Wissens nach 9 Millionen Pflegebedürftige in Deutschland haben, bei 80 Millionen Bevölkerung. Das ist nicht durch rein menschliche Pflege darzustellen. Wenn man auf [YouTube](https://www.youtube.com/) Videos sieht, wo Roboter Backflips machen, breakdancen, Karate können, dann gibt es ein relativ großes Gap zwischen dem, was jemand mal gefilmt hat, und dem, was wahrscheinlich erst einmal in die Anwendung kommt. Aber wir stehen vor einer riesengroßen Transformation, und darauf muss man die Leute vorbereiten.

### 08:43 – Garmi: das humanoide Projekt der TUM

**Leonard Schmedding**

Ihr entwickelt selbst einen humanoiden Assistenzroboter namens [Garmi](https://www.mirmi.tum.de/geriatronik/forschung/garmi/) an der TU München. Ihr regelt alle Gelenke drehmomentbasiert, sodass er bei Kontakt mit Menschen oder unbekannten Objekten automatisch abbremst. Was unterscheidet Garmi von anderen humanoiden Robotern?

**Prof. Dr. Alexander König**

Ich habe neulich ein bisschen bösartiges Zitat gehört: Wer was Vernünftiges machen will, der benutzt Service-Roboter, und wer gutes Marketing will, der benutzt Humanoide. Der Humanoide unterscheidet sich vom Service-Roboter durch den Formfaktor. Typischerweise hat diese Maschine Beine, und ganz oft kommt die Frage: Wofür brauche ich eigentlich Beine? Wir Menschen brauchen sie, weil wir uns über hochunstrukturiertes Terrain bewegen. Aber ein Roboter in einer Wohnung, in der es keine Treppen gibt, oder in einer Fabrikhalle, die ich gestalten kann, braucht keine Beine. Ich erzeuge Komplexität, die ich nicht brauche, nämlich die Instabilität der Maschine.

Humanoide haben auch Vorteile. Wenn man eine schwere Feuerschutztür aufmacht, kann man sich richtig reinlehnen, in eine Position, in der man dynamisch stabil, aber statisch instabil ist. Über diese Fähigkeit, Kräfte aufzubringen, die dynamisch größer sind als statisch, hat der Humanoide einen Vorteil. Aber für den Moment haben Service-Roboter, also fahrende Plattformen mit entsprechender Robotik darauf, große Vorteile. Wir haben in Garmisch einen Service-Roboter: keine Beine, aber eine fahrende Plattform, darauf zwei Arme, einen Kopf, Kameras, Sensoren. Sieht am Ende halbwegs menschlich aus. Der USP von Garmi wird sich in Zukunft immer über die Software finden. Roboterarme kann man inzwischen kaufen.

### 11:00 – Sicherheit bei Robotern

**Leonard Schmedding**

Sobald so eine Maschine mit einem Menschen interagiert, kommt das Thema Sicherheit ins Spiel.

**Prof. Dr. Alexander König**

Genau. Sicherheit ist ein extrem komplexes Problem. Wenn ich eine medizintechnische Anwendung habe, mit extrem strukturierter Umgebung, ausschließlich geschulten Benutzern und klaren Vorgaben, kann ich einen Sicherheitsplan erstellen. Wenn ich mich aber im Häuslichen befinde, in einer hochgradig unstrukturierten Umgebung, mit ungeschulten Nutzern, dann potenziert sich das Problem.

### 12:40 – Sechs Arme, zwei Daumen, ein Formfaktor

**Leonard Schmedding**

Das chinesische Haushaltsgeräteunternehmen [Midea Group](https://www.midea-group.com/) stellte neulich den sogenannten Miro vor, einen sechsarmigen fahrbaren Super-Humanoid-Roboter. Wieso beschränkt man sich aktuell bei den meisten Humanoiden auf die menschlichen Unzulänglichkeiten, also zwei Beine, zwei Arme?

**Prof. Dr. Alexander König**

Das ist eine gute Frage, und ich habe ehrlich gesagt keine überzeugende Antwort. Ich habe neulich einen Roboter mit einer Hand gesehen: Wenn das Objekt außerhalb des Workspaces war, hat der Roboter die Hand abgekoppelt, die Hand ist wie das eiskalte Händchen zum Objekt gekrabbelt, hat es zurückgezogen und sich wieder am Roboterarm angekoppelt. Es gibt auch Forschungsansätze mit Händen, die zwei Daumen haben, weil das kinematisch große Vorteile hat. Wir Menschen haben es nicht gebraucht, weil die Natur typischerweise nicht nach dem Optimum strebt, sondern nach gerade gut genug, nach einem robusten Mittelmaß.

Im Pflegekontext wollen wir, dass die zu Pflegenden sich mit der Maschine wohlfühlen und sich identifizieren können. Da helfen menschliche Formfaktoren, aber das ist nicht begrenzt auf den Menschen. Es gibt für demenzkranke oder einsame Menschen Roboterhunde und Roboterrobben, die als künstliches Haustier funktionieren. Sechs Arme schauen fast aus wie eine Spinne, hat bestimmt Vorteile, ist aber kinematisch um einiges schwerer zu regeln. Es gibt keinen Konsens, was das Optimum ist. Unsere gesamte Umwelt ist für zwei Arme, zwei Beine ausgelegt. Im Häuslichen wird der Mensch eher nicht auf seine gewohnte Umgebung verzichten wollen, deswegen hilft es, den Formfaktor Mensch zu berücksichtigen.

### 16:00 – Wie ChatGPT die Robotik verändert

**Leonard Schmedding**

Du bist schon einige Jahrzehnte länger im Feld unterwegs. Was hat [ChatGPT](https://chat.openai.com/) verändert? Ihr setzt mit Garmi auch ChatGPT für die Mensch-Maschine-Interaktion ein. Wie beflügelt die generative KI das Feld der Robotik gerade?

**Prof. Dr. Alexander König**

Wenn man sich mit Sprachmodellen beschäftigt hat, war der ChatGPT-Moment vielleicht gar nicht so aufregend. Aber mit [GPT-3.5](https://en.wikipedia.org/wiki/GPT-3) wurde auf einmal Wert generiert. Wie wir es oft in der technologischen Entwicklung sehen: Entwicklung passiert nicht linear, sondern exponentiell, in exponentiellen Schritten. Es passiert gefühlt lange nichts, dann macht es einen Knall und alles ist anders. Mit [Siri](https://en.wikipedia.org/wiki/Siri) konnte man schon länger reden, aber die Tatsache, dass man hochskalieren konnte, war die Kombination aus sehr viel Compute und der Einsicht, dass [Transformer-Modelle](https://en.wikipedia.org/wiki/Transformer_(deep_learning_architecture)) wesentlich effizienter sind als andere Modelle.

In meinen Vorträgen habe ich eine Folie, da hat in den 60er Jahren der Spiegel getitelt: "Jetzt werden wir alle arbeitslos." Stellt sich heraus: nein. Werden wir denn jetzt endlich alle arbeitslos? Ich glaube auch nein. Ähnlich wie bei der Radiologie, wo vor 10 Jahren prominent gesagt wurde, 2025 sind alle Radiologen arbeitslos. Stellt sich raus: 2025 haben wir mehr Radiologen als je zuvor, weil durch die Verfügbarkeit von Automatisierung der Demand gestiegen ist.

Wir werden in der Robotik eine Explosion von Möglichkeiten sehen. Was wir noch nicht gefunden haben, ist der Killer-Case. Bei der [Apple Watch](https://en.wikipedia.org/wiki/Apple_Watch) hat man es gesehen: Sie dümpelte vor sich hin, dann kam die Tatsache, dass ich ein medizinisch qualifiziertes EKG damit machen kann, und auf einmal brachen die Verkaufszahlen durch die Decke. Ähnliches erwarte ich für die humanoide Robotik beziehungsweise generell für [Embodied AI](https://en.wikipedia.org/wiki/Embodied_cognition), also die verkörperte künstliche Intelligenz. Wir haben einen großen Push gesehen im Bereich Visual Language Action Models. Da wird einem schwindlig: Zwei Tage später ist alles anders. Wann wir alle arbeitslos sind, hängt nicht nur von der KI ab, sondern auch von der Integration in die Gesellschaft und der Verfügbarkeit der Systeme.

### 21:00 – Trainingsdaten als Bottleneck

**Leonard Schmedding**

Das Unternehmen X-Humanoid nutzt das Wan 2.2 Video-to-Video-Modell, um Trainingsdaten für humanoide Roboter zu verbessern, indem sie menschliche Akteure in Roboterakteure verwandeln. Hast du Beispiele, wie Gen-AI das Feld der Robotik beflügelt?

**Prof. Dr. Alexander König**

Da müssen wir ausholen und kommen schon stark in die VLAs rein. Der Grund, warum [Large Language Models](https://en.wikipedia.org/wiki/Large_language_model) und Agentic AI so wahnsinnig gut funktionieren, ist, dass die Trainingsdaten das gesamte Internet gelesen haben, das von Menschen über 40 Jahre befüllt wurde. Wenn wir uns anschauen, wie viele Daten vorhanden sind, um Roboter zu trainieren, dann ist das ein Sandkorn neben einer Sonne. Es gibt einen tollen Artikel inklusive Video von [Ken Goldberg](https://goldberg.berkeley.edu/) von [Berkeley](https://www.berkeley.edu/), der das grafisch dargestellt hat.

Was brauche ich, um Roboter zu trainieren? Nicht nur die Kinematik, sondern auch die Kräfte. Alles, was wir in Videos sehen, in denen Roboter Backflips machen, ist Contact-Poor-Interaction: der Roboter bewegt sich frei, hat nur Kontakt mit dem Boden. Wenn ich aber ein Objekt manipuliere, also Wert in der Gesellschaft bringe, dann nennt man das Contact-Rich. Hier brauche ich zwingend Kraftinformationen. Versuche mal, eine Schraube und eine Mutter ineinander einzuschrauben: einmal blind, aber mit Fühlen, einmal mit Vision, aber Schweißerhandschuhen an. Du wirst sehen, wie wichtig die taktile Information ist.

### 24:00 – Simulation trifft Realität

**Prof. Dr. Alexander König**

[Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion) kann beliebig Videos und Bilder generieren, aber diese haben keine Kraftinformation. Jetzt kommt etwas, das gerade konvergiert: physikalische Simulationen wie [MuJoCo](https://en.wikipedia.org/wiki/MuJoCo). Das sind Systeme, die realistisch Dynamiken, also Kräfte simulieren können. Ich gebe dem ein Modell, sage, wie schwer ein Objekt ist, wo der Massenschwerpunkt liegt, was die Reibungen sind, in welche Richtung die Gravitation geht. Wenn ich darin eine Simulation durchführe, etwa ein Roboter greift in ein Glas, kann ich die Kräfte extrahieren und damit synthetische Trainingsdaten erstellen.

Wir werden es nicht schaffen, die Menge an Trainingsdaten in der echten Welt zu generieren wie im Internet. Wir können nicht 40 Jahre lang die halbe Menschheit mit taktilen Roboteranzügen ausstatten. Hier kommen Gen-AI und Embodied AI zusammen. Wenn diese Simulationsumgebungen mir nicht nur eine realistische physikalische Simulation, sondern auch eine realistische visuelle Simulation geben, dann kann ich Trainingsdaten erzeugen. Die Basis ist [Reinforcement Learning](https://en.wikipedia.org/wiki/Reinforcement_learning): Ich habe eine Loss-Function, die sagt, ob ich in die richtige Richtung gehe, wie beim Topfschlagen. Reinforcement Learning muss einen riesigen Haufen Parameter optimieren. Wenn ich einen guten Startpunkt geben kann, konvergiert es viel schneller. Aus der Simulation erzeuge ich einen Datensatz, den ich in die Realität bringe. Das nennt sich [Sim-to-Real Transfer](https://en.wikipedia.org/wiki/Sim-to-real_transfer). In Echtzeit nachoptimieren, und so konvergieren Simulation, Generative AI und Echtzeitoptimierung.

### 26:00 – China baut die Infrastruktur

**Leonard Schmedding**

In [China](https://en.wikipedia.org/wiki/Robotics_in_China) eröffnete neulich das größte Trainingszentrum für humanoide Roboter, das Humanoid Robot Data Training Center in Shanghai mit 10.000 Quadratmetern und 16 Szenarien. Was ist aus deiner Sicht der größte Bottleneck bei humanoiden Robotern?

**Prof. Dr. Alexander König**

Der größte Bottleneck sind meiner Meinung nach Daten. Es wird an allen Ecken optimiert. Ich hatte gestern ein Meeting mit einem Professor, der hat es geschafft, dass seine Trainingsmodelle substanziell weniger Zeit, Energie und Computing benötigen und die [Inferenz](https://en.wikipedia.org/wiki/Statistical_inference) wesentlich schneller funktioniert. Aber der große Bottleneck sind aktuell Daten. China macht es sehr gut, eröffnet Roboter-Trainingsfarmen.

### 28:00 – Kollektives Lernen funktioniert

**Prof. Dr. Alexander König**

Wir haben das in 2018 bereits gemacht. Es gibt das Projekt Collective Learning an der TU München. Dort waren jahrelang etwa 35 bimanuelle Roboter, die Tag und Nacht Muttern in Schrauben eingedreht und Stecker in Steckdosen gesteckt haben, jeder Roboter hatte einen Task und versuchte den rein taktil zu lösen. Wann immer ein Roboter die Lösung hatte, konnte er die anderen informieren. Es stellt sich heraus, dass kollektives Lernen schneller geht als individuelles. Wir Menschen sind da begrenzt: Was ich lerne, kann ich dir nicht beibringen, ich kann es nur zeigen. Aber Roboter können Informationen und Lernen teilen.

Wenn 10 Roboter eine Stunde lernen, ist das effizienter als wenn ein Roboter 10 Stunden lernt. Wir sehen eine exponentielle Steigerung der Fähigkeiten von Robotern. Wir haben auch eine solche Roboterfabrik in München, die wird demnächst aufgemacht. Da darf ich noch nicht zu viel sagen, aber wir wollen uns auf gar keinen Fall abhängen lassen.

### 29:46 – Akzeptanz durch Wertschöpfung

**Leonard Schmedding**

In [Beijing](https://en.wikipedia.org/wiki/Beijing) fanden die World Humanoid Robot Games statt, mit über 500 Robotern aus 16 Ländern. Vor allem bereitet man die Bevölkerung auf Humanoide vor. Bräuchten wir in Deutschland auch eine Roboterolympiade, um Akzeptanz zu fördern?

**Prof. Dr. Alexander König**

Ich würde mir nicht zutrauen, eine qualifizierte Meinung dazu zu sagen, ob China auf dem richtigen Weg ist. Aus meiner Perspektive sieht es so aus. Wir haben in Deutschland aber auch viele Aktivitäten. Wir haben Ausstellungen in München, etwa in der [Pinakothek der Moderne](https://www.pinakothek.de/), im [Deutschen Museum](https://www.deutsches-museum.de/) gibt es einen eigenen Ausstellungsbereich zur Robotik.

China hat ein riesiges Problem mit Überalterung: 2050 werden 100 Millionen Menschen den Arbeitsmarkt verlassen haben. Bei uns in Deutschland sind auf dem Land Cafes und Bäcker nur noch drei Tage die Woche offen, weil 2 Millionen Menschen fehlen. 100 Millionen ist eine Hausnummer. Alle überalternden Gesellschaften, also China, Südkorea, Deutschland, werden Technologie benötigen, um den Lebensstandard zu halten.

Meine Erfahrung mit der Akzeptanz: Egal wie ablehnend Menschen gegenüber Technologie sind, in dem Moment, wo diese Technologie wirklich Wert bringt, passiert der Flip, dass sie das Ganze sehr schnell akzeptieren. Es gibt eine Firma in München, [Devanthro](https://www.devanthro.com/), die haben einen teleoperierten Roboter, der bei älteren Menschen zu Hause Pflegeaufgaben übernimmt. Dinge bringen, holen, Sachen vom Boden aufheben. Sie stellen den Roboter eine Woche lang zu einem älteren Menschen, sammeln Erfahrung, iterieren. Von dem Team höre ich: Die Senioren weinen teilweise, wenn der Roboter wieder geht. Wir Menschen sind extrem adaptiv. Wenn ich sehe, dass der Roboter mir Wert bringt, akzeptiere ich es schnell.

### 32:00 – Deutschland gegen China

**Prof. Dr. Alexander König**

Die Roboterolympiade hat nicht nur das Ziel, Menschen zu gewöhnen, sondern auch den Aufbau einer vernetzten Infrastruktur. Diese Vernetzung sorgt dafür, dass gute Ideen weitergebracht werden. Die Thematik ist so komplex, dass kein Mensch und keine einzelne Fachrichtung es allein machen kann. Real World Exposure ist wichtig: Rausbringen in die Welt, auch mal versagen, daraus lernen, iterieren. Da können wir Deutschen uns mal an die eigene Nase fassen.

Wenn 100 Prozent meiner Experimente funktionieren, habe ich was falsch gemacht, dann bin ich nicht genug Risiko eingegangen. Erfolg lehrt nichts. Misserfolg lehrt. Mehr Akzeptanz für Misserfolg wäre wünschenswert. Es gibt ein No-Go: die Sicherheit der Menschen, da gibt es keine Toleranz für Fehler. Solange diese gewährleistet ist, mein Gott, dann schafft der Roboter halt nicht. Aber besser, ich gehe aus dem Labor in die echte Welt.

In der Schweiz gibt es den [Cybathlon](https://cybathlon.ethz.ch/), die Olympiade für Cyborgs. Dort treten körperlich eingeschränkte Menschen, also Amputierte, Rollstuhlfahrerinnen, gegeneinander an in echten Welt-Challenges. Sie haben das Zürcher Hallenstadion gemietet. Da müssen die Forscher aus ihren Laboren raus in die echte Welt. Nur weil es im Labor funktioniert, heißt es gar nichts darüber, wie weit es in der echten Welt funktioniert.

### 37:00 – On-Premise und Datenschutz

**Leonard Schmedding**

Hätte man vor 5 Jahren gefragt, würdest du dein Privatleben mit einem KI-Chatbot teilen? Die meisten hätten Nein gesagt, heute machen es viele.

**Prof. Dr. Alexander König**

Die Technologie kommt zuerst, dann das Bewusstsein, dann die Regulierung, die kommt 20 Jahre später. Ähnliches sehen wir bei sozialen Medien. 2005, 2006, 2007 haben Menschen ohne Datenschutz alle Fotos hochgeladen, weil sie dachten, niemand könne sie auf einem Foto identifizieren. Lächerlich, dass jemals Menschen auf Fotos identifiziert würden.

Ich glaube, dass der Trend zu datensicheren KI-Modellen geht. Das nennt man On-Premise, also auf dem eigenen Gelände. Im [iPhone](https://www.apple.com/iphone/) habe ich bereits ein lokales Modell, das fragt, ob es nach außen gehen und ChatGPT anfragen soll. Wir haben an der TU München eine eigene Instanz von [Microsoft Copilot](https://www.microsoft.com/copilot), die im eigenen Leibniz-Rechenzentrum gehostet ist. Da geht nichts raus. In Garmisch arbeiten wir mit solchen Modellen immer On-Premise, sonst bekämen wir keine Freigabe von der Ethikkommission. Stell dir vor, du hast einen Roboter zu Hause, der dir beim Aufmachen des Safes zuschaut, der dir beim Duschen zuguckt. Das sind nicht Dinge, die ich geteilt haben will. Es gibt sehr viele Ansätze, die Effizienz dieser Algorithmen massiv zu erhöhen, auch weil der Stromverbrauch unanständig hoch ist.

### 39:00 – Zürich als Robotik-Valley

**Leonard Schmedding**

Das Unternehmen [Neura Robotics](https://neura-robotics.com/) hat bekannt gegeben, dass sie die komplette Entwicklung des Gehirns ihres 4NE-1 nach [Zürich](https://en.wikipedia.org/wiki/Z%C3%BCrich) verlagern und im [ETH](https://ethz.ch/)-Umfeld bündeln. Das Startup [Flexion Robotics](https://flexion.ai/), gegründet von ETH-Alumni, hat 50 Millionen Funding eingesammelt und will das Android für Robotics bauen. Wieso wird Zürich gerade das neue Robotics-Valley in Europa?

**Prof. Dr. Alexander König**

Da bin ich im Interessenskonflikt: Auf der einen Seite ist die ETH meine Alma Mater, auf der anderen Seite bin ich großer Fan des Münchner Ökosystems. Ich kann nur spekulieren. Zürich hat eine wahnsinnig hohe Lebensqualität, München auch. Aber wenn man Top-Leute anziehen will: Ein wirklich guter Programmierer ist nicht doppelt so gut, sondern zehnmal, fünfzigmal so gut. Denen muss man viel bieten. Die Schweiz hat hohe Lebensqualität und niedrige Steuern.

Was [GDPR](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation), AI Act und Datenschutz angeht, hat die Schweiz nicht so hohe Hürden, das ist mein Verständnis. Außerdem brauche ich eine kritische Masse: Wo viele gute Leute sind, kommen mehr gute Leute hin, wie im Silicon Valley. Alle Tech-Unternehmen sind in Zürich mit ihren KI-Systemen: [Google](https://www.google.com/), [Microsoft](https://www.microsoft.com/), alle. Hohe Dichte an guten Leuten zieht Firmen an, die Geld haben, sich das zu leisten. Ich würde nicht sagen, dass München verliert. Der Kuchen wächst gerade so gigantisch, dass Zürich auch wächst. Gleichzeitig dürfen wir uns nicht auf den Lorbeeren ausruhen.

### 43:00 – Weltmodelle als nächste Welle

**Leonard Schmedding**

[Fei-Fei Li](https://en.wikipedia.org/wiki/Fei-Fei_Li), die Gründerin von [World Labs](https://www.worldlabs.ai/), sagt, dass [Weltmodelle](https://en.wikipedia.org/wiki/World_model) und Embodied AI die nächste große Welle nach LLMs sind, aber deutlich schwieriger. Was ist deine zeitliche Einschätzung?

**Prof. Dr. Alexander König**

Prädiktionen sind besonders schwer, wenn sie die Zukunft betreffen. Die ehrliche Antwort: Ich weiß es nicht. Die Rotationsgeschwindigkeit wird immer schneller. Die Zeit, bis etwas veraltet ist, kann man inzwischen in Tagen messen. Wir sind technisch in vielen Punkten theoretisch sehr weit. Die Frage ist: Kann ich damit einen kommerziellen Business Case bauen, der die großflächige Translation in die echte Welt ermöglicht? Es gibt eine begrenzte Menge Menschen, die bereit sind, 15.000 bis 20.000 Dollar für einen Humanoiden mit begrenzten Fähigkeiten zu zahlen.

### 45:00 – Zeithorizont von zehn Jahren

**Prof. Dr. Alexander König**

Ich habe eine Wette laufen mit einem Experten vom Mechatronikinstitut des [Deutschen Zentrums für Luft- und Raumfahrt](https://www.dlr.de/) außerhalb Münchens. Er sagt, in 5 Jahren können Roboter älteren Menschen Stützstrümpfe anziehen. Das würde hohe taktile Manipulationsfähigkeit bedeuten. Ich habe Nein gesagt. Konservativ würde ich den Zeithorizont auf 10 Jahre setzen, bis wir wirklich großflächig Wert mit humanoiden Robotern schaffen. Die Frage ist, ob die Gesellschaft akzeptiert und ob sich ein Knaller-Use-Case wie das EKG bei der Apple Watch findet.

Die erste Innovation wird im Manufacturing kommen, weil dort die Umgebung am höchsten strukturiert ist und ich sie am leichtesten anpassen kann. Millionen Wohnungen umzubauen ist eine andere Sache. Eine große Fabrik so zu gestalten, dass sie roboterready ist, ist substantiell einfacher. Die erste Revolution wird meiner Meinung nach im [autonomen Fahren](https://en.wikipedia.org/wiki/Self-driving_car) kommen, denn auch das ist ein Roboter, der hochabgesichert mit der Umwelt interagieren muss. Dann kommt eine Ausweitung im Bereich Manufacturing, das werden wir zuerst in China sehen. Da würde ich mir wünschen, dass wir in Deutschland mehr Gas geben.

### 48:00 – Jobsicherheit und Empfehlungen

**Leonard Schmedding**

Wir haben hier viele Zuschauer, die sich für Chancen interessieren und sich zukunftssicher aufstellen wollen. Wie sollte man sich positionieren, was sollte man lernen?

**Prof. Dr. Alexander König**

Eine der schwersten Fragen, die mir in den letzten Jahren gestellt wurden. Alles, wo menschliche Interaktion und Empathie eine große Rolle spielen, wird weiterhin existieren. Wir werden Pflegekräfte nicht ersetzen, das ist weder das Ziel, noch sinnvoll, noch gewünscht. Wir automatisieren Aspekte, sodass Pflegekräfte sich auf Tätigkeiten konzentrieren, in denen sie wirklich gut sind. Sachen heben kann ein Roboter besser, bevor ich Rückenschaden habe. Aber empathisch mit einem älteren Menschen umgehen, dem das Gefühl geben, wichtig zu sein: Das sind Dinge.

Programmieren lernen ist nie eine dumme Idee, aber auch hier werden wir viel Automatisierung sehen. Es wird immer schwerer für unerfahrene Softwareentwickler, einen Job zu finden. Auf der anderen Seite: Alles, wo wir Empathie und hohe Adaptionsfähigkeit brauchen, wird gebraucht. Pflegekräfte werden wir ohne Ende brauchen. Wenn ich aktuell Taxi fahre und mir das mit Menschen vorstellen kann, vielleicht da habe ich Spaß dran. Pflegekraft ist ein zukunftssicherer Job. Vielleicht wird es so sein, wenn das autonome Taxi kommt, dass nicht die Taxifahrer ersetzt werden, sondern die Menschen viel mehr Auto fahren, weil die Dienstleistung verfügbar ist. Geh dorthin, wo der größte Bedarf ist. Pflege ist einer der größten Bedarfe.

### 51:17 – Fazit und Ausblick

**Leonard Schmedding**

Alexander, danke dir auf jeden Fall für die sehr wertvollen Einblicke in deine Arbeit. Wir können in Zukunft noch einen zweiten Teil ansetzen.

**Prof. Dr. Alexander König**

Sehr gern. Danke.

---

Quelle: https://www.youtube.com/watch?v=aYUxYYLb_2o
