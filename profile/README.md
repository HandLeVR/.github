![](Images/HandLeVR_BMBF.jpg)

**For an english version see below.**

Virtual-Reality-(VR) und Augmented-Reality-(AR-)Technologien bieten das Potenzial, das praxis- und arbeitsplatznahe Lernen in der beruflichen Aus- und Weiterbildung deutlich zu verbessern. Zusätzlich weiten sich mit der technischen Weiterentwicklung und den sinkenden Anschaffungskosten der Endgeräte die Einsatzmöglichkeiten von VR und AR derzeit rasant aus.

Im Sinne der Kompetenzorientierung ist es notwendig, handlungsorientierte Lerneinheiten mit Lernfortschrittskontrollen in der Berufsbildung zu implementieren. Diese Entwicklung beruflicher Handlungskompetenz wird auch im Rahmenlehrplan des Ausbildungsberufes Fahrzeuglackierer/Fahrzeuglackiererin gefordert – aber bisher nur unzureichend bzw. ineffizient in Bezug auf die genutzten Ressourcen umgesetzt.

Zentrales Ziel dieses Projekts ist daher der ergänzende Einsatz von VR-Technologien, mit denen Auszubildende beim handlungsorientierten Erlernen von verschiedenen Techniken zum Anbringen einzelner Lackschichten auf Kfz-Werkstücken gefördert werden sollen. Dazu wurde zunächst grundlegend untersucht, welchen Beitrag VR-Technologien leisten können, um handlungsorientiertes Lernen in der Berufsausbildung zu ermöglichen, bzw. wie diese Technologien didaktisiert werden können, um entsprechende Lernerfolge sicherzustellen.

Dabei wird der rein explorative Zugang einem stärker didaktisierten Zugang gegenübergestellt und die motivationalen, (meta-)kognitiven und sozialen Effekte werden differenziert erfasst. Für die gezielte Optimierung der Lern- und Trainingseffekte lässt sich das Simulationssetting anpassen. Den Überlegungen des 4C/ID-Modells folgend setzt das didaktische Konzept vor allem auf die Parametrisierung der VR-Lehr-/Lernszenarien. Dementsprechend kann die Trainingssituation in der VR-Lackierwerkstatt durch Variation einer definierten Anzahl von Parametern – wie etwa die physikalischen Eigenschaften der gewählten Lackart –, die für das berufliche Handlungsfeld relevant sind, modifiziert werden.

Zentrales Werkzeug für dieses Vorhaben ist eine dreidimensionale VR-Lernumgebung: die VR-Lackierwerkstatt. Sie besteht aus einem Autorenwerkzeug für Lehrende sowie einer VR-Trainingsanwendung und einer Reflexionsanwendung für Auszubildende. 

Das Projekt wird durch einen Verbund aus ausgewiesenen Expertinnen und Experten in den Bereichen der Entwicklung von VR-Anwendungen (Universität Potsdam), der digital ausgerichteten Didaktik (Learning Lab der Universität Duisburg-Essen) sowie der beruflichen Qualifizierung und Weiterbildung im Handwerk (ZWH e. V.) getragen. Anwendungspartnerin im Rahmen des Projekts ist die Mercedes-Benz Ludwigsfelde GmbH mit einem Schwerpunkt in der Ausbildung von Fahrzeuglackierern/Fahrzeuglackiererinnen.

HandLeVR wird gefördert vom Bundesministerium für Bildung und Forschung (BMBF), Förderkennzeichen: 01PV18002A, Laufzeit: 01.01.2019 - 31.12.2021

Das Projekt steht unter der MIT-Lizenz und kann als Open Educational Ressource eingesetzt werden.


# Struktur

Die Projektergebnisse sind in folgende Repositories unterteilt:

**Autorenwerkzeug** ([https://github.com/HandLeVR/autorenwerkzeug](https://github.com/HandLeVR/autorenwerkzeug)): Das Autorenwerkzeug ermöglicht das Erstellen, Bearbeiten und Löschen von Nutzer/innen, Gruppen, Aufgaben, Aufgabensammlungen, Medien, Lacken und Aufnahmen, sowie das Zuweisen von Aufgaben, die dann in der Trainingsanwendung durchgeführt werden können. Aufgaben können verschiedene Teilschritte enthalten, wie z.B. Multiple-Choice-Fragen, Schätzaufgaben, eine Spritzprobe oder einen Farbauftrag. Das Autorenwerkzeug wurde mit Unity 2019.4.21f1 entwickelt.

**Trainingsanwendung/Reflektionswerkzeug** ([https://github.com/HandLeVR/trainingsanwendung](https://github.com/HandLeVR/trainingsanwendung)): In der Trainingsanwendung können zugewiesene Aufgaben in VR durchgeführt werden. Es ist auch möglich einen Propiermodus zu nutzen, in dem verschiedene Werkstücke mit verschiedenen Lacken lackiert werden können. Während des Lackierens stehen verschiedene Hilfsmittel zur Verfügung, wie ein Distanzstrahl, Distanzmarker oder ein Winkelstrahl. Im Propiermodus ist es außerdem möglich eine Aufnahme von einem Farbauftrag zu erstellen, die dann in einer Aufgabe eingebunden werden kann. Die Trainingsanwendung wurde mit Unity 2019.4.21f1 entwickelt. Das Reflekionswerkzeug ist in der Trainingsanwendung enthalten, da die Anwendungen sich viele Funktionalitäten teilen. Das Reflekionswerkzeug ermöglicht es Farbauftrage, die bei der Durchführung von Aufgaben entstanden sind, am PC anzuschauen und mit Hilfe verschiedener Erfolgskriterien zu reflektieren.

**Shared Library** ([https://github.com/HandLeVR/shared-library](https://github.com/HandLeVR/shared-library)): Die Shared Library enthält Skripte, Prefabs und Ressourcen, die sowohl im Autorenwerkzeug als auch in der Trainingsanwendung bzw. im Reflektionswerkzeug verwendet werden. Die Bibliothek wird automatisch von den beiden Unity-Projekten geladen.

**Server** ([https://github.com/HandLeVR/server](https://github.com/HandLeVR/server)): Der Server stellt REST-Webservices zur Verfügung über die Daten gespeichert und geladen werden können. Er wurde mit Java und Spring Boot umgesetzt. Es ist möglich einen dedizierten Server einzurichten oder den Server lokal auf dem gleichen System wie die Anwendungen laufen zu lassen.

**Begleitmaterialien** ([https://github.com/HandLeVR/begleitmaterialien](https://github.com/HandLeVR/begleitmaterialien)): Dieses Repository enthält Materialien, um die Nutzung der VR-Lackierwerkstatt und die Umsetzung neuer Lernaufgaben zu unterstützen.

**Materialien Lackierpistole** ([https://github.com/HandLeVR/lackierpistole](https://github.com/HandLeVR/lackierpistole)): In diesem Repository sind 3D-Modelle sowie Anleitungen enthalten, die den Druck und den Zusammenbau einer Nachbildung einer echten Lackierpistole ermöglichen.

# Voraussetzungen
- Windows 10+
- ein VR-System (momentan werden HTC Vive (Pro), Windows Mixed Reality und Quest (2) + Link unterstützt)
- [SteamVR](https://store.steampowered.com/app/250820/SteamVR)
- Java 13+ (nur wenn ein lokaler Server verwendet werden soll)
- GPU mit DirectX 11/12 und Shader Model 5.0  Unterstützung (wird benötigt, um die herunterlaufende Farbe darzustellen)


# Download
Unter [Releases](https://github.com/HandLeVR/autorenwerkzeug/releases) kann ein Archiv mit den aktuellen Anwendungen heruntergeladen werden. Damit kann die Anwendung lokal auf einem Rechner genutzt werden. Der Server muss zuerst über die Datei `server.bat` gestartet werde. Nun kann entweder das Autorenwerkzeug (`Autorenwerkzeug.exe`) oder die Trainingsanwendung bzw. das Reflektionswerkzeug (`Trainingsanwendung/Trainingsanwendung.exe`) gestartet werden. Beim ersten Start der Anwendung kann sich mit folgenden Daten angemeldet werden:

- **Nutzername:** Ausbildungsmeister
- **Passwort:** passwort

Das Passwort muss anschließend geändert werden. Weitere Konfigurationsmöglichkeiten für die Anwendungen finden sie in der [README](https://github.com/HandLeVR/autorenwerkzeug/blob/master/README.md) des Autorenwerkzeugs. Die nötigen Schritte zur Nutzung eines dedizierten Servers sind in der [README](https://github.com/HandLeVR/server/blob/master/README.md) des Servers beschrieben.

## Dateistruktur

`config`: Enthält alle Konfigurationsdateien des Servers. Die nötigen Konfigurationsschritte für einen dedizierten Server sind in der [README](https://github.com/HandLeVR/server/blob/master/README.md) des Servers beschrieben.

`Files`: Durch den lokalen Server verwaltete Dateien.

`Trainingsanwendung`: Kompilierte Dateien der Trainingsanwendung.

`Trainingsanwendung/Trainingsanwendung.exe`: Startet die Trainingsanwendung. Ermöglicht es nach der Anmeldung zum Autorenwerkzeug oder zum Reflektionswerkzeug zu wechseln.

`Autorenwerkzeug.exe`: Startet die Autorenwerkzeug. Ermöglicht es nach der Anmeldung zur Trainingsanwendung oder zum Reflektionswerkzeug zu wechseln.

`server.jar`: Eine ausführbare Jar zum Starten des Servers. Diese wird in der `server.bat` genutzt.

`server.bat`: Startet den Server.

# Anwendungen kompilieren
Im Folgenden werden die Schritte zum Kompilieren der Anwendungen beschrieben.

## Voraussetzungen
- [Unity 2019.4.21f1](https://unity.com)
- Java JDK 13+
- Maven

## Schritte

1. [Autorenwerkzeug](https://github.com/HandLeVR/autorenwerkzeug) mit Unity 2019.4.21f1+ [bauen](https://docs.unity3d.com/Manual/BuildSettings.html)  (PC, Mac & Linux Standalone).
2. [Trainingsanwendung](https://github.com/HandLeVR/trainingsanwendung) mit Unity 2019.4.21f1+ [bauen](https://docs.unity3d.com/Manual/BuildSettings.html) (PC, Mac & Linux Standalone).
3. Die kompilierten Dateien der Trainingsanwendung in den Unterordner `Trainingsanwendung` im Ordner mit den kompilierten Dateien des Autorenwerkzeugs kopieren.
4. Den Server [bauen](https://github.com/HandLeVR/server/blob/master/README.md#kompilieren).
5. Die resultierende Jar in `server.jar` umbenennen.
6. Die Jar und den Ordner [Files](https://github.com/HandLeVR/server/tree/master/Files) in den gewünschten Zielordner für den Server kopieren. Das Verzeichnis `Files` muss im gleichen Ordner wie die `server.jar` liegen.
7. Ein Ordner mit Namen `config` im Ordner, in dem die `server.jar` liegt, erstellen und die `application.properties` in den Ordner `config` kopieren.
8. Den Server (siehe [Serverkonfiguration](https://github.com/HandLeVR/server/blob/master/README.md#konfiguration)) and Anwendungen (siehe [Konfiguration Autorenwerkzeug](https://github.com/HandLeVR/autorenwerkzeug/blob/master/README.md)) konfigurieren, wenn nötig.



---
Virtual reality (VR) and augmented reality (AR) technologies offer the potential to significantly improve hands-on and workplace learning in vocational education and training. In addition, with the technical advancement and decreasing acquisition costs of the end devices, the application possibilities of VR and AR are currently expanding rapidly.

In terms of competence orientation, it is necessary to implement action-oriented learning units with learning progress checks in vocational training. This development of vocational action competence is also required in the curriculum of vehicle painters - but has so far been implemented only insufficiently or inefficiently in terms of the resources used.

The central objective of this project is therefore the supplementary use of VR technologies to support trainees in the action-oriented learning of various techniques for applying individual layers of paint to automotive workpieces. For this purpose, the contribution VR technologies can make to enable action-oriented learning in vocational training was researched and we investigated how these technologies can be didacticized in order to ensure corresponding learning successes.

In this context, the purely explorative approach is contrasted with a more didactic approach and the motivational, (meta-)cognitive and social effects are recorded in a differentiated manner. For the targeted optimization of learning and training effects, the simulation setting can be adapted. Following the considerations of the 4C/ID model, the didactic concept mainly relies on the parameterization of the VR teaching/learning scenarios. Accordingly, the training situation in the VR paint shop can be modified by varying a defined number of parameters - such as the physical properties of the selected paint type - that are relevant to the professional field of action.

The central tool for this project is a three-dimensional VR learning environment: the VR paint shop. It consists of an authoring tool for teachers as well as a VR training application and a reflection application for trainees.

The project is supported by a network of proven experts in the fields of VR application development (University of Potsdam), digitally oriented didactics (Learning Lab of the University of Duisburg-Essen) and vocational qualification and further training in the skilled trades (ZWH e. V.). The project's application partner is Mercedes-Benz Ludwigsfelde GmbH, which focuses on training vehicle painters.

HandLeVR is funded by the German Federal Ministry of Education and Research (BMBF), funding code: 01PV18002A, duration: 01.01.2019 - 31.12.2021

The project is licensed under the MIT license and can be used as an Open Educational Resource.

# Structure

The project results are divided into the following repositories:

**Authoring Tool** ([https://github.com/HandLeVR/autorenwerkzeug](https://github.com/HandLeVR/autorenwerkzeug)): The authoring tool allows teachers to create, edit and delete users, user groups, tasks, task collections, coats, and media. It also allows to assign task and task collection to users which then can be executed in the training application. Tasks can contain different sub tasks like multiple choice questions, estimation tasks, a spray tests or the application of the coat. The authoring tool is developed with Unity 2019.4.21f1.

**Training Application/Reflection Tool** ([https://github.com/HandLeVR/trainingsanwendung](https://github.com/HandLeVR/trainingsanwendung)): The training application is a VR application where the user can execute tasks created with the help of the authoring tool. It is also possible to use the sample mode where different coats can be used on different car workpieces. During painting different support tools can be used like the distance ray, the distance marker, or the angle ray. In the sample mode it is also possible to create record a coat application which can then be used in the authoring tool when creating task. The training application is developed with Unity 2019.4.21f1. The reflection tool is included in the training application as they share a lot of functionalities. The reflection tool allows to view records of paint applications done in tasks, to reflect the performance with the help of different criteria. 

**Shared Library** ([https://github.com/HandLeVR/shared-library](https://github.com/HandLeVR/shared-library)): The shared library contains scripts, prefabs and resources used in the authoring tool and the training application. The library is automatically loaded in the unity projects.

**Server** ([https://github.com/HandLeVR/server](https://github.com/HandLeVR/server)): The server is responsible for saving and sending data when requested. It is developed with Java and Spring Boot and provides different REST Webservices to request and save data. It is possible to use a dedicated server or a local instance.

**Support Materials** ([https://github.com/HandLeVR/begleitmaterialien](https://github.com/HandLeVR/begleitmaterialien)): This repository contains materials to support the use of the VR paint shop and the implementation of new learning tasks.

**Spray Gun Materials** ([https://github.com/HandLeVR/lackierpistole](https://github.com/HandLeVR/lackierpistole)): Included in this repository are 3D models as well as instructions for printing and assembling a replica of a real paint gun.

# Requirements
- Windows 10+
- a HMD (currently HTC Vive (Pro), Windows Mixed Reality and Quest (2) + Link are supported)
- [SteamVR](https://store.steampowered.com/app/250820/SteamVR)
- Java 13+ (only if the server is used locally)
- GPU supporting DirectX 11/12 and Shader Model 5.0 (needed to calculate the running paint)

# Download

Under [Releases](https://github.com/HandLeVR/autorenwerkzeug/releases) an archive with the current versions of the applications can be downloaded. This allows the application to be used locally on a computer. The server must first be started via the `server.bat` file. Now either the authoring tool (`Autorenwerkzeug.exe`) or the training application or the reflection tool (`Trainingsanwendung/Trainingsanwendung.exe`) can be started. When starting the application for the first time, you can log in with the following data:

- **Username:** Ausbildungsmeister
- **Password:** passwort

The password must be changed afterwards. Further configuration options for the applications can be found in the [README](https://github.com/HandLeVR/autorenwerkzeug/blob/master/README.md) of the authoring tool. The necessary steps for using a dedicated server are described in the [README](https://github.com/HandLeVR/server/blob/master/README.md) of the server.

## File Structure

`config`: Contains the configuration files for the server. See the [README](https://github.com/HandLeVR/server/blob/master/README.md#configuration) of the server for the needed configuration steps.

`Files`: Files managed by the local server.

`Trainingsanwendung`: Build files of the training application.

`Trainingsanwendung/Trainingsanwendung.exe`: Starts the training application. Allows to switch to the authoring tool or reflection tool after logging in.

`Autorenwerkzeug.exe`: Starts the authoring tool. Allows to switch to the training application or reflection tool after logging in.

`server.jar`: An executable jar containing the server. Is used by the `server.bat`.

`server.bat`: Starts the server.

# Build
In the following we describe the steps needed to build all applications.

## Requirements
- [Unity 2019.4.21f1](https://unity.com)
- Java JDK 13+
- Maven

## Steps
1. [Build](https://docs.unity3d.com/Manual/BuildSettings.html) the [authoring tool]((https://github.com/HandLeVR/autorenwerkzeug)) with Unity 2019.4.21f1+ (PC, Mac & Linux Standalone).
2. [Build](https://docs.unity3d.com/Manual/BuildSettings.html) the [training application]((https://github.com/HandLeVR/trainingsanwendung)) with Unity 2019.4.21f1+ (PC, Mac & Linux Standalone).
3. Copy the resulting files of the training application build into the sub folder `Trainingsanwendung` in the build folder of the authoring tool.
4. [Build](https://github.com/HandLeVR/server/blob/master/README.md#build) the server.
5. Rename the resulting Jar to `server.jar`.
6. Copy the Jar and the [Files](https://github.com/HandLeVR/server/tree/master/Files) directory into the desired folder. The `Files` directory needs to be placed in the same folder as the Jar.
7. Create a `config` directory in the folder where the Jar is located and copy the `application.properties` into the `config` folder.
8. Configure the server (see [server configuration](https://github.com/HandLeVR/server/blob/master/README.md#configuration)) and the applications (see [configuration authoring tool]((https://github.com/HandLeVR/autorenwerkzeug/blob/master/README.md))) if needed.