# Nutzungsplanung_BE_V2 (ENTWURF)

## Einleitung
Dieser inoffizielle Modellentwurf ist für die Testphase von ePlan und die involvierte Testgruppe bestimmt. Änderungen während der Testphase lassen sich nicht ausschliessen und können Anpassungen an den Datensätzen oder Systemen zur Folge haben.

## Zuständigkeiten
Während der Testphase sind die Testgemeinden zuständig für die Arbeit mit dem `Hauptmodell`:
- Nutzungsplanung_BE_V2_0.ili (DE) oder PlansDAffectation_BE_V2_0.ili (FR)
- Nutzungsplanung_BE_V2_0_Catalogues.ili
- Nutzungsplanung_BE_V2_0_Catalogues.xml

Bei Bedarf stehen fiktive `Demo-Datensätze` zur Verfügung:
- Nutzungsplanung_BE_V2_0_DEMO_Ausgangslage.xtf
- Nutzungsplanung_BE_V2_0_DEMO_Aenderung.xtf
- PlansDAffectation_BE_V2_0_DEMO.xtf

Parallel dazu arbeitet der Kanton an einem `Teilmodell für Metainformationen`:
- Nutzungsplanung_BE_V2_0_Metainfo.ili
- Nutzungsplanung_BE_V2_0_Metainfo_DEMO_Delta.xtf
- Nutzungsplanung_BE_V2_0_Metainfo_DEMO_Dossier.xtf

Das Teilmodell für Metainformationen befindet sich derzeit im Aufbau und ist für die Testgemeinden vorläufig nicht relevant. Später kann es für interessierte Gemeinden allenfalls von informativer Bedeutung sein. 

## Modellnamen
Um sicherzustellen, dass alle Beteiligten mit der richtigen Modellversion arbeiten, wird der Modellname bei jeder funktionalen Änderung an den Topics "Nutzungsplanung" und "Catalogues" (Hauptmodell) sowie beim Abschluss der Testphase geändert.<br>
Bei Änderungen an den Topics "Dossier" und "DeltaObjects" (Meta-Modell) wird fallweise entschieden, ob eine Umbenennung Sinn macht.

Erste Testversion: Nutzungsplanung_`BE_V2_Test01`<br>
Zweite Testversion: Nutzungsplanung_`BE_V2_Test02`<br>
Dritte Testversion: Nutzungsplanung_`BE_V2_Test03`<br>
...<br>
Erste offizielle Modellversion: Nutzungsplanung_`BE_V2_0`

Jede Änderung am Modellnamen kann Anpassungen an den Datensätzen oder Systemen zur Folge haben. Die markierten Suffixe können dabei relativ einfach mit einer Suchen/Ersetzen-Funktion ausgetauscht werden. In Notepad++ lässt sich diese Funktion mit `Ctrl + H` aufrufen. Im Reiter "In Dateien suchen" lässt sich diese Funktion mit gebotener Vorsicht sogar auf alle Dateien im anzugebenden Verzeichnis anwenden.

## Dateinamen
Anders als der Modellname spielen die Dateinamen bei der Modellvalidierung keine Rolle. Um unnötige Aufwände zu vermeiden und damit GitHub vorgenommene Änderungen an einer Datei aufzeigen kann, bleiben die Dateinamen deshalb vorläufig stabil und stimmen nicht zwangsläufig mit dem Modellnamen überein.
