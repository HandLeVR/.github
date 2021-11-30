![](Images/HandLeVR_BMBF.jpg)

Virtual-Reality-(VR) und Augmented-Reality-(AR-)Technologien bieten das Potenzial, das praxis- und arbeitsplatznahe Lernen in der beruflichen Aus- und Weiterbildung deutlich zu verbessern. Zusätzlich weiten sich mit der technischen Weiterentwicklung und den sinkenden Anschaffungskosten der Endgeräte die Einsatzmöglichkeiten von VR und AR derzeit rasant aus.

Im Sinne der Kompetenzorientierung ist es notwendig, handlungsorientierte Lerneinheiten mit Lernfortschrittskontrollen in der Berufsbildung zu implementieren. Diese Entwicklung beruflicher Handlungskompetenz wird auch im Rahmenlehrplan des Ausbildungsberufes Fahrzeuglackierer/Fahrzeuglackiererin gefordert – aber bisher nur unzureichend bzw. ineffizient in Bezug auf die genutzten Ressourcen umgesetzt.

Zentrales Ziel dieses Projekts ist daher der ergänzende Einsatz von VR-Technologien, mit denen Auszubildende beim handlungsorientierten Erlernen von verschiedenen Techniken zum Anbringen einzelner Lackschichten auf Kfz-Werkstücken gefördert werden sollen. Dazu wurde zunächst grundlegend untersucht, welchen Beitrag VR-Technologien leisten können, um handlungsorientiertes Lernen in der Berufsausbildung zu ermöglichen, bzw. wie diese Technologien didaktisiert werden können, um entsprechende Lernerfolge sicherzustellen.

Dabei wird der rein explorative Zugang einem stärker didaktisierten Zugang gegenübergestellt und die motivationalen, (meta-)kognitiven und sozialen Effekte werden differenziert erfasst. Für die gezielte Optimierung der Lern- und Trainingseffekte lässt sich das Simulationssetting anpassen. Den Überlegungen des 4C/ID-Modells folgend setzt das didaktische Konzept vor allem auf die Parametrisierung der VR-Lehr-/Lernszenarien. Dementsprechend kann die Trainingssituation in der VR-Lackierwerkstatt durch Variation einer definierten Anzahl von Parametern – wie etwa die physikalischen Eigenschaften der gewählten Lackart –, die für das berufliche Handlungsfeld relevant sind, modifiziert werden.

Zentrales Werkzeug für dieses Vorhaben ist eine dreidimensionale VR-Lernumgebung: die VR-Lackierwerkstatt. Sie besteht aus einem Autorenwerkzeug für Lehrende sowie einer VR-Trainingsanwendung und einer Reflexionsanwendung für Auszubildende. 

Das Projekt wird durch einen Verbund aus ausgewiesenen Expertinnen und Experten in den Bereichen der Entwicklung von VR-Anwendungen (Universität Potsdam), der digital ausgerichteten Didaktik (Learning Lab der Universität Duisburg-Essen) sowie der beruflichen Qualifizierung und Weiterbildung im Handwerk (ZWH e. V.) getragen. Anwendungspartnerin im Rahmen des Projekts ist die Mercedes-Benz Ludwigsfelde GmbH mit einem Schwerpunkt in der Ausbildung von Fahrzeuglackierern/Fahrzeuglackiererinnen.

# Struktur

Die Projektergebnisse sind in folgende Repositories unterteilt:

**Autorenwerkzeug** ([https://github.com/HandLeVR/autorenwerkzeug](https://github.com/HandLeVR/autorenwerkzeug)): Das Autorenwerkzeug ermöglicht das Erstellen, Bearbeiten und Löschen von Nutzer/innen, Gruppen, Aufgaben, Aufgabensammlungen, Medien, Lacken und Aufnahmen, sowie das Zuweisen von Aufgaben.

**Trainingsanwendung/Reflektionswerkzeug** ([https://github.com/HandLeVR/trainingsanwendung](https://github.com/HandLeVR/trainingsanwendung)): In der Trainingsanwendung können zugewiesene Aufgaben in VR durchgeführt werden. Das Reflekionswerkzeug ermöglicht es Farbauftrage, die bei der Durchführung von Aufgaben entstanden sind, am PC anzuschauen und mit Hilfe verschiedener Erfolgskriteren zu reflektieren.

**Shared Library** ([https://github.com/HandLeVR/shared-library](https://github.com/HandLeVR/shared-library)): Die Shared Library enthält Skripte, Prefabs und Ressourcen, die sowohl in Autorenwerkzeug als auch in der Trainingsanwendung bzw. im Reflektionswerkzeug verwendet werden. Die Bibliothek wird automatisch von den beiden Unity-Projekten geladen.

**Server** ([https://github.com/HandLeVR/server](https://github.com/HandLeVR/server)): Der Server stellt REST-Webservices zur Verfügung über die Daten gespeichert und geladen werden können.

**Begleitmaterialien** ([https://github.com/HandLeVR/begleitmaterialien](https://github.com/HandLeVR/begleitmaterialien)): Dieses Repository enthält Materialien, um die Nutzung der VR-Lackierwerkstack und die Umsetzung neuer Lernaufgaben zu unterstützen.

**Materialien Lackierpistole** ([https://github.com/HandLeVR/lackierpistole](https://github.com/HandLeVR/lackierpistole)): In diesem Repository sind 3D-Modelle sowieso Anleitungen enthalten, die den Druck und den Zusammenbau einer Nachbildung einer echten Lackierpistole ermöglichen.