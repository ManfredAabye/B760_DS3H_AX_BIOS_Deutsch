# Gigabyte B760_DS3H_AX DDR5 BIOS Deutsch

**Achtung: Das Benutzen dieser Anleitung geschieht auf eigene Gefahr!!!!!**

• Die in diesem Abschnitt beschriebenen BIOS Einrichtungsmenüs können von den genauen Einstellungen Ihres Motherboards abweichen. </br>Die tatsächlichen BIOS Einrichtungsmenüoptionen, die Sie sehen, hängen von den Spezifikationen des Motherboards und der BIOS Version ab. </br>
• Einige BIOS Einstellungen sind nur verfügbar, wenn der verwendete Chipsatz des Motherboards und die CPU/der Speicher diese Funktion unterstützen. </br>Weitere Informationen zu den einzigartigen Funktionen von Intel® CPUs finden Sie auf der Intel Website. </br>

BIOS (Basic Input and Output System) speichert Hardware Parameter des Systems im CMOS auf dem Motherboard. </br>Zu seinen Hauptfunktionen gehören die Durchführung des Power On Self Test (POST) beim Systemstart, das Speichern von Systemparametern und das Laden des Betriebssystems usw. </br>BIOS enthält ein BIOS Einrichtungsprogramm, das es dem Benutzer ermöglicht, grundlegende Systemeinstellungen zu ändern oder bestimmte Systemfunktionen zu aktivieren. </br>

Wenn der Strom ausgeschaltet ist, liefert die Batterie auf dem Motherboard die notwendige Energie (meist eine CR2032 Knopfzelle), um die Konfigurationswerte im CMOS zu halten. </br>

Um das BIOS Einrichtungsprogramm aufzurufen, drücken Sie während des POST beim Einschalten die Taste (Entf) (Delete). </br>

Zum Aktualisieren des BIOS verwenden Sie entweder das GIGABYTE Q Flash  oder Q Flash Plus Dienstprogramm. </br>

• Q Flash ermöglicht es dem Benutzer, das BIOS schnell und einfach zu aktualisieren oder zu sichern, ohne das Betriebssystem zu betreten. </br>
• Q Flash Plus ermöglicht es Ihnen, das BIOS zu aktualisieren, wenn Ihr System ausgeschaltet ist (S5 Abschaltzustand). </br>Speichern Sie das neueste BIOS auf einem USB Stick und stecken Sie ihn in den dafür vorgesehenen Anschluss. </br>Sie können dann das BIOS automatisch durch einfaches Drücken der Q Flash Plus Taste flashen. </br>

Anweisungen zur Verwendung der Q Flash  und Q Flash Plus Dienstprogramme finden Sie auf der Seite "Einzigartige Funktionen" der GIGABYTE Website und suchen Sie nach "BIOS Update Utilities". </br>

• Da das Flashen des BIOS potenziell riskant ist, wird empfohlen, das BIOS nicht zu flashen, wenn Sie keine Probleme mit der aktuellen Version des BIOS haben. </br>Wenn Sie das BIOS flashen, tun Sie dies mit Vorsicht. </br>Unzureichendes BIOS Flashen kann zu Fehlfunktionen des Systems führen. </br>
• Es wird empfohlen, die Standardeinstellungen nicht zu ändern (es sei denn, dies ist notwendig), um Systeminstabilität oder andere unerwartete Ergebnisse zu vermeiden. </br>Das unzureichende Ändern der Einstellungen kann dazu führen, dass das System nicht startet. </br>Wenn dies auftritt, versuchen Sie, die CMOS Werte zu löschen und das Board auf die Standardwerte zurückzusetzen. </br>
• Informationen zum Löschen der CMOS Werte und zum Zurücksetzen des Boards auf die Standardwerte finden Sie in der Bedienungsanleitung zum Batterie /CMOS Jumper oder zur Schaltfläche oder im Abschnitt "Optimierte Standardeinstellungen laden". </br>

## BIOS Setup

### Startbildschirm

Der folgende Startbildschirm mit dem Logo erscheint, wenn der Computer hochfährt. </br>(Der Bildschirm kann je nach Motherboard variieren. )
Funktionstasten:

* (DEL): BIOS SETUP\Q FLASH
Drücken Sie die (Entf) Taste, um das BIOS Setup aufzurufen oder um das Q Flash Dienstprogramm im BIOS Setup aufzurufen. </br>

* (F12): BOOT MENÜ
Das Boot Menü ermöglicht es Ihnen, das erste Boot Gerät ohne den Aufruf des BIOS Setup einzustellen. </br>Verwenden Sie im Boot Menü die Pfeiltasten (h) oder (i), um das erste Boot Gerät auszuwählen, und drücken Sie dann

* (Enter), um zu bestätigen. </br>Das System startet sofort von diesem Gerät. </br>
Hinweis: Die Einstellung im Boot Menü ist nur einmalig wirksam. </br>Nach dem Neustart des Systems basiert die Gerätebootreihenfolge weiterhin auf den BIOS Setup Einstellungen. </br>

* (END): Q FLASH
Drücken Sie die (Ende) Taste, um direkt auf das Q Flash Dienstprogramm zuzugreifen, ohne zuerst das BIOS Setup aufzurufen. </br>

## Funktionstasten

### Hauptmenü

Das Hauptmenü ist der Einstiegsbereich des BIOS, von dem aus Sie verschiedene Konfigurationen und Einstellungen vornehmen können.

### Erweiterter Modus

Der erweiterte Modus bietet detaillierte BIOS-Einstellungen, die Ihnen erlauben, fortgeschrittene Konfigurationen vorzunehmen. Hier sind die Möglichkeiten, wie Sie den erweiterten Modus nutzen können:

**Pfeiltasten**: Verwenden Sie die Pfeiltasten auf Ihrer Tastatur, um zwischen den verschiedenen Punkten im erweiterten Modus zu navigieren. </br>
**Enter-Taste**: Drücken Sie die Enter-Taste, um eine Einstellung zu bestätigen oder ein Untermenü aufzurufen. </br>
**Maus**: Sie können auch Ihre Maus verwenden, um den gewünschten Punkt im erweiterten Modus auszuwählen. </br>

### Hardware Informationen

Dieser Bereich zeigt detaillierte Informationen über die Hardware Ihres Systems, wie z.B. die CPU, den RAM, die Grafikkarte und andere Komponenten. </br>

### Optionen Beschreibung Aktuelle Einstellungen

Hier finden Sie eine Liste der verfügbaren Optionen im erweiterten Modus, zusammen mit einer kurzen Beschreibung und den aktuellen Einstellungen. </br>

### Einrichtungsmenüs

Dieser Bereich enthält verschiedene Menüs, die spezifische Konfigurationen und Einstellungen ermöglichen. </br>

### Konfigurationselemente

Hier können Sie spezifische Hardware- und Systemeinstellungen konfigurieren, wie z.B. die Systemzeit, die CPU-Einstellungen und die Speicherparameter. </br>

### Systemzeit

Diese Einstellung ermöglicht es Ihnen, die Systemzeit und das Datum zu konfigurieren, die vom BIOS gespeichert und verwendet werden, um die Uhrzeit und das Datum im System korrekt anzuzeigen. </br>

Die Schnellzugriffsleiste ermöglicht es Ihnen, schnell zu den Bildschirmen Allgemeine Hilfe, Einfache Modus, Smart Fan 6 oder Q Flash zu wechseln. </br>

## Erweiterter Modus Funktionstasten

* (f)(g) Bewegen Sie die Auswahlleiste, um ein Einrichtungsmenü auszuwählen. </br>
* (h)(i) Bewegen Sie die Auswahlleiste, um ein Konfigurationselement in einem Menü auszuwählen. </br>
* (Enter)/Doppelklick Befehl ausführen oder Menü aufrufen
* (+)/(Seite hoch) Erhöhen Sie den numerischen Wert oder ändern Sie ihn. </br>
* ( )/(Seite runter) Verringern Sie den numerischen Wert oder ändern Sie ihn. </br>
* (F1) Zeigt Beschreibungen der Funktionstasten an. </br>
* (F2) Wechseln zum einfachen Modus. </br>
* (F3) Speichern Sie die aktuellen BIOS Einstellungen in einem Profil. </br>
* (F4) Laden Sie die BIOS Einstellungen aus einem zuvor erstellten Profil. </br>
* (F5) Stellen Sie die vorherigen BIOS Einstellungen für die aktuellen Untermenüs wieder her. </br>
* (F6) Zeigt den Smart Fan 6 Bildschirm an. </br>
* (F7) Laden Sie die optimierten BIOS Standardwerte für die aktuellen Untermenüs. </br>
* (F8) Zugriff auf das Q Flash Dienstprogramm. </br>
* (F10) Speichern Sie alle Änderungen und beenden Sie das BIOS Setup Programm. </br>
* (F11) Wechseln Sie zum Favoriten Untermenü. </br>
* (F12) Erfassen Sie den aktuellen Bildschirm als Bild und speichern Sie es auf Ihrem USB Laufwerk. </br>
* (Einf) Fügen Sie eine Favoritenoption hinzu oder entfernen Sie sie. </br>
* (Strg)+(S) Zeigt Informationen zum installierten Speicher an. </br>
* (Esc) Hauptmenü: Beenden Sie das BIOS Setup Programm. </br>

Untermenüs: Beenden Sie das aktuelle Untermenü. </br>

* (Alt)+(F) Geben Sie Schlüsselwörter ein, um das gesuchte BIOS Konfigurationselement zu finden. </br>

## Einfache Modus

Der einfache Modus ermöglicht es Benutzern, schnell ihre aktuellen Systeminformationen anzuzeigen oder Anpassungen für optimale Leistung vorzunehmen. </br>Im einfachen Modus können Sie Ihre Maus verwenden, um durch die Konfigurationselemente zu navigieren, oder drücken Sie (F2), um zum erweiterten Modus zu wechseln. </br>

Verwenden Sie die (F6) Funktionstaste, um schnell zu diesem Bildschirm zu wechseln. </br>Dieser Bildschirm ermöglicht es Ihnen, Lüftergeschwindigkeitseinstellungen für jeden Lüfteranschluss zu konfigurieren oder Ihre System /CPU Temperatur zu überwachen. </br>

### ALLE ABSTIMMEN

Ermöglicht es Ihnen, die aktuellen Einstellungen auf alle Lüfteranschlüsse anzuwenden. </br>

### Temperatur

Zeigt die aktuelle Temperatur des ausgewählten Zielbereichs an. </br>

### Lüftergeschwindigkeit

Zeigt aktuelle Lüfter /Pumpengeschwindigkeiten an. </br>

### Durchflussrate

Zeigt die Durchflussrate Ihres Wasserkühlungssystems an. </br>Drücken Sie (Enter) auf Lüftergeschwindigkeit, um zu dieser Funktion zu wechseln. </br>

### Lüftergeschwindigkeitsregelung

Ermöglicht es Ihnen, zu bestimmen, ob die Lüftergeschwindigkeitsregelung aktiviert werden soll und die Lüftergeschwindigkeit anzupassen. </br>
*Normal Ermöglicht es dem Lüfter, bei unterschiedlichen Geschwindigkeiten je nach Temperatur zu laufen. </br>Sie können die Lüftergeschwindigkeit auf der FAN Control Seite des GIGABYTE Control Center basierend auf Ihren Systemanforderungen einstellen. </br>
*Leise Ermöglicht es dem Lüfter, mit langsamen Geschwindigkeiten zu laufen. </br>
*Manuell Ermöglicht es Ihnen, die Kurvenknoten zu ziehen, um die Lüftergeschwindigkeit anzupassen. </br>Oder Sie können die EZ Tuning Funktion verwenden. </br>Nach dem Anpassen der Knotenposition drücken Sie Anwenden, um die Neigung der Kurve automatisch zu berechnen. </br>
*Volle Geschwindigkeit Ermöglicht es dem Lüfter, mit voller Geschwindigkeit zu laufen. </br>

### Lüfterregelung Temperatur Eingabe verwenden

Ermöglicht es Ihnen, die Referenztemperatur für die Lüftergeschwindigkeitsregelung auszuwählen. </br>

### Temperaturintervall

Ermöglicht es Ihnen, das Temperaturintervall für die Lüftergeschwindigkeitsänderung auszuwählen. </br>

### FAN/PUMP Control Mode

*Auto Lässt das BIOS den Typ des installierten Lüfters automatisch erkennen und den optimalen Steuerungsmodus festlegen. </br>
*Spannung Der Spannungsmodus wird für einen 3 Pin Lüfter/Pumpe empfohlen. </br>
*PWM Der PWM Modus wird für einen 4 Pin Lüfter/Pumpe empfohlen. </br>

### FAN/PUMP Stop

Aktiviert oder deaktiviert die Lüfter /Pumpen Stoppfunktion. </br>Sie können das Temperaturlimit mithilfe der Temperaturkurve festlegen. </br>Der Lüfter oder die Pumpe stoppt den Betrieb, wenn die Temperatur unter das Limit fällt. </br>

### FAN/PUMP Modus

Ermöglicht es Ihnen, den Betriebsmodus für den Lüfter festzulegen. </br>

### Slope

Passt die Lüftergeschwindigkeit linear basierend auf der Temperatur an. </br>

### Stair

Passt die Lüftergeschwindigkeit stufenweise basierend auf der Temperatur an. </br>

### FAN/PUMP Fehlerwarnung

Ermöglicht es dem System, einen Warnton auszugeben, wenn der Lüfter/die Pumpe nicht angeschlossen ist oder ausfällt. </br>Überprüfen Sie den Zustand des Lüfters/der Pumpe oder die Verbindung des Lüfters/der Pumpe, wenn dies auftritt. </br>

### Lüfterprofil speichern

Diese Funktion ermöglicht es Ihnen, die aktuellen Einstellungen in einem Profil zu speichern. </br>Sie können das Profil im BIOS speichern oder die Option "Datei auswählen in HDD/FDD/USB" wählen, um das Profil auf Ihrem Speichermedium zu speichern. </br>

### Lüfterprofil laden

Diese Funktion ermöglicht es Ihnen, ein zuvor gespeichertes BIOS Profil zu laden, ohne die BIOS Einstellungen neu konfigurieren zu müssen. </br>Oder Sie können die Option "Datei auswählen in HDD/FDD/USB" wählen, um ein Profil von Ihrem Speichermedium zu laden. </br>

### Favoriten (F11)

Legen Sie Ihre häufig verwendeten Optionen als Favoriten fest und verwenden Sie die (F11) Taste, um schnell zu der Seite zu wechseln, auf der sich alle Ihre Favoriten befinden. </br>Um eine Favoritenoption hinzuzufügen oder zu entfernen, gehen Sie zur ursprünglichen Seite und drücken Sie (Einfügen) auf der Option. </br>Die Option wird mit einem Sternsymbol markiert, wenn sie als "Favorit" festgelegt ist. </br>

## Tweaker

### CPU Upgrade

Ermöglicht es Ihnen, die CPU Frequenz festzulegen. </br>Das endgültige Ergebnis kann je nach verwendeter CPU variieren. </br>Die Optionen sind: Standard, Gaming Profil, Erweiterte Profil. </br>

### CPU Basistakt

Ermöglicht es Ihnen, den CPU Basistakt manuell in Schritten von 0,01 MHz einzustellen. </br>
Wichtig: Es wird dringend empfohlen, die CPU Frequenz entsprechend den Spezifikationen der CPU einzustellen. </br>

### PCIe/DMI/PEG Taktfrequenz

Ermöglicht es Ihnen, die PCIe/DMI/PEG Taktfrequenz manuell in Schritten von 0,01 MHz einzustellen. </br>

### Verbesserte Multi Core Leistung

Ermöglicht es Ihnen festzulegen, ob das höchste Turboverhältnis auf alle CPU Kerne angewendet werden soll. </br>

### Leistungs CPU Taktverhältnis

Ermöglicht es Ihnen, das Taktverhältnis für die installierte Leistungs CPU zu ändern. </br>Der einstellbare Bereich hängt von der installierten CPU ab. </br>

### Effizienz CPU Taktverhältnis

Ermöglicht es Ihnen, das Taktverhältnis für die installierte Effizienz CPU zu ändern. </br>Der einstellbare Bereich hängt von der installierten CPU ab. </br>

### Maximales Ringverhältnis

Ermöglicht es Ihnen, das maximale CPU Uncore Verhältnis festzulegen. </br>Der einstellbare Bereich hängt von der verwendeten CPU ab. </br>

### Minimales Ringverhältnis

Ermöglicht es Ihnen, das minimale CPU Uncore Verhältnis festzulegen. </br>Der einstellbare Bereich hängt von der verwendeten CPU ab. </br>

### IGP Verhältnis

Ermöglicht es Ihnen, das Grafikverhältnis festzulegen. </br>
Ob das System stabil mit den von Ihnen vorgenommenen Overclock /Überspannungseinstellungen funktioniert, hängt von Ihren gesamten Systemkonfigurationen ab. </br>Falsches Overclocking/Überspannung kann zu Schäden an CPU, Chipsatz oder Speicher führen und die Lebensdauer dieser Komponenten verkürzen. </br>Diese Seite ist nur für fortgeschrittene Benutzer und wir empfehlen, die Standardeinstellungen nicht zu ändern, um Systeminstabilität oder andere unerwartete Ergebnisse zu vermeiden. </br>(Unzureichendes Ändern der Einstellungen kann dazu führen, dass das System nicht startet. </br>Wenn dies auftritt, löschen Sie die CMOS Werte und setzen Sie das Board auf die Standardwerte zurück. )

Einige BIOS Einstellungen sind nur verfügbar, wenn der verwendete Chipsatz des Motherboards und die CPU/der Speicher diese Funktion unterstützen. </br>Weitere Informationen zu den einzigartigen Funktionen von Intel® CPUs finden Sie auf der Intel Website. </br>

### PVD Ratio Threshold Override

Ermöglicht es Ihnen festzulegen, ob die Leistung bei extremem BCLK Overclocking durch Reduzierung eines "PLL Banding" Zustands verbessert werden soll, der teilweise durch eine sehr hohe DCO Frequenz verursacht wird. </br>

### CPU Übertemperaturschutz

Ermöglicht es Ihnen, den TJ Max Offset Wert fein abzustimmen. </br>

### Hyper Threading Technologie

Ermöglicht es Ihnen festzulegen, ob die Multi Threading Technologie bei Verwendung einer Intel® CPU aktiviert werden soll, die diese Funktion unterstützt. </br>Diese Funktion funktioniert nur für Betriebssysteme, die den Multi Prozessor Modus unterstützen. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Intel(R) Speed Shift Technology (Intel® Speed Shift Technology)

Aktiviert oder deaktiviert die Intel® Speed Shift Technology. </br>Wenn diese Funktion aktiviert ist, kann der Prozessor seine Betriebsfrequenz schneller erhöhen und verbessert die Systemreaktionsfähigkeit. </br>

### CPU Thermal Monitor

Aktiviert oder deaktiviert die Intel® Thermal Monitor Funktion, eine CPU Überhitzungsschutzfunktion. </br>Wenn diese Funktion aktiviert ist, werden die CPU Kernfrequenz und die Spannung reduziert, wenn die CPU überhitzt. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Ring zu Kern Offset (Down Bin)

Ermöglicht es Ihnen festzulegen, ob die automatische Reduzierungsfunktion des CPU Ring Verhältnisses deaktiviert werden soll. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### CPU EIST Funktion

Aktiviert oder deaktiviert die Enhanced Intel® Speed Step Technology (EIST). </br>Je nach CPU Auslastung kann die Intel® EIST Technologie die CPU Spannung und  Kernfrequenz dynamisch und effektiv senken, um den durchschnittlichen Stromverbrauch und die Wärmeproduktion zu verringern. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Race To Halt (RTH) /Energy Efficient Turbo

Aktiviert oder deaktiviert die CPU Energiesparfunktionen. </br>

### Intel(R) Turbo Boost Technology

Ermöglicht es Ihnen festzulegen, ob die Intel® CPU Turbo Boost Technologie aktiviert werden soll. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Intel(R) Turbo Boost Max Technology 3. </br>0

Aktiviert oder deaktiviert die Intel® Turbo Boost Max Technology 3. </br>0. </br>Intel® Turbo Boost Max Technology 3. </br>0 ermöglicht es dem System, den besten Leistungskern des Prozessors zu identifizieren und ermöglicht es Ihnen, die kritischsten Arbeitslasten manuell darauf zu richten. </br>Sie können sogar die Frequenz jedes Kerns einzeln anpassen, um die Leistung zu optimieren. </br>

## Erweiterte CPU Einstellungen

### CPU Flex Ratio Override

Aktiviert oder deaktiviert das CPU Flex Ratio. </br>

### CPU Flex Ratio Einstellungen

Ermöglicht es Ihnen, das CPU Flex Ratio festzulegen. </br>Der einstellbare Bereich kann je nach CPU variieren. </br>

### Frequency TVB

Ermöglicht es Ihnen, die automatische CPU Frequenzreduzierung, die durch Thermal Velocity Boost initiiert wird, zu aktivieren oder zu deaktivieren. </br>

### Enhanced TVB

Aktiviert oder deaktiviert die erweiterte Thermal Velocity Boost (TVB) Funktion. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Voltage Reduction Initiated TVB

Ermöglicht es Ihnen, die automatische CPU Spannungsreduzierung, die durch Thermal Velocity Boost initiiert wird, zu aktivieren oder zu deaktivieren. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### IA CEP (Current Excursion Protection)

Ermöglicht es Ihnen, IA CEP zu aktivieren oder zu deaktivieren. </br>

### GT CEP (Current Excursion Protection)

Ermöglicht es Ihnen, GT CEP zu aktivieren oder zu deaktivieren. </br>

### Fll OC Mode

Ermöglicht es Ihnen, den FLL Modus auszuwählen. </br>

### Legacy Game Compatibility Mode

Ermöglicht es Ihnen, den Legacy Game Compatibility Mode zu aktivieren, um die Funktionalität älterer Spiele zu verbessern. </br>

### Core VR Fast Vmode

Aktiviert oder deaktiviert den Core Fast V Mode. </br>

### Unterspannungsschutz

Aktiviert oder deaktiviert die Unterspannungsschutzfunktion. </br>

## AVX Einstellungen

**Advanced Vector Extensions (AVX)** sind Erweiterungen der x86-Befehlssätze, die speziell entwickelt wurden, um die Leistung von Anwendungen zu verbessern, die intensive Rechenaufgaben ausführen. </br> Dazu gehören wissenschaftliche Berechnungen, 3D-Modellierung, Video-Rendering und andere datenintensive Aufgaben. </br> AVX ermöglicht es Prozessoren, gleichzeitig mit mehreren Datenpunkten zu arbeiten, was zu erheblichen Leistungssteigerungen führt. </br>

### Konfiguration der AVX-Einstellungen im BIOS

Im BIOS können Sie AVX-bezogene Funktionen aktivieren oder deaktivieren. </br> Wenn die AVX-Einstellungen aktiviert sind, konfiguriert das System diese automatisch gemäß den Spezifikationen Ihrer CPU. </br> Dies stellt sicher, dass die AVX-Instruktionen von Ihrer CPU unterstützt und optimal genutzt werden. </br>

### AVX

Diese Einstellung ermöglicht es Ihnen, die AVX-Befehlssätze auf einer CPU, die AVX unterstützt, zu deaktivieren. </br> Beachten Sie, dass diese Option nur verfügbar ist, wenn die AVX-Einstellungen auf Benutzerdefiniert gesetzt sind. </br>

### AVX Offset

Der AVX Offset ist eine Einstellung, die das CPU-Taktverhältnis reduziert, wenn der Prozessor AVX-Workloads ausführt. </br> Zum Beispiel, wenn der Offset-Wert auf 3 gesetzt ist, wird das CPU-Taktverhältnis beim Ausführen von AVX-Befehlen um 3 reduziert. </br> Dies kann hilfreich sein, um die thermische Belastung der CPU zu reduzieren und die Systemstabilität zu gewährleisten. </br>

### AVX Optimum

Diese Einstellung ermöglicht es Ihnen, die AVX-Befehle zu optimieren. </br> Dies bedeutet, dass die CPU-Performance für AVX-Workloads angepasst wird, um eine bessere Effizienz und Leistung zu erzielen. </br>

### AVX Voltage Guardband Scale Factor

Diese Einstellung ermöglicht es Ihnen, die Standard-AVX-Spannung zu senken. </br> Eine niedrigere Spannung kann dazu beitragen, die Leistungsaufnahme zu reduzieren und die thermische Belastung der CPU zu minimieren. </br>

Mit diesen Einstellungen können Sie die Leistung und Effizienz Ihrer CPU für AVX-intensive Anwendungen optimieren und anpassen. </br>

### Aktive Turbo Verhältnisse

Ermöglicht es Ihnen, die CPU Turbo Verhältnisse für verschiedene Anzahl aktiver Kerne festzulegen. </br>Auto stellt die CPU Turbo Verhältnisse entsprechend den CPU Spezifikationen ein. </br>Dieser Punkt ist nur konfigurierbar, wenn aktive Turbo Verhältnisse auf Manuell gesetzt ist. </br>

### CPU Kerne Aktivierungsmodus

Ermöglicht es Ihnen, auszuwählen, wie CPU Kerne aktiviert werden sollen. </br>

### Anzahl der aktivierten CPU P Kerne

Ermöglicht es Ihnen, die Anzahl der zu aktivierenden CPU P Kerne auszuwählen (die Anzahl der CPU Kerne kann je nach CPU variieren). </br>Dieser Punkt ist nur konfigurierbar, wenn der CPU Kerne Aktivierungsmodus auf Zufallsmodus gesetzt ist. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Anzahl der aktivierten CPU E Kerne

Ermöglicht es Ihnen, die Anzahl der zu aktivierenden CPU E Kerne auszuwählen (die Anzahl der CPU Kerne kann je nach CPU variieren). </br>Dieser Punkt ist nur konfigurierbar, wenn der CPU Kerne Aktivierungsmodus auf Zufallsmodus gesetzt ist. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Aktiver P Kern/E Kern

Ermöglicht es Ihnen, auszuwählen, welcher CPU Kern aktiviert werden soll. </br>Die Anzahl der CPU Kerne kann je nach CPU variieren. </br>Dieser Punkt ist nur konfigurierbar, wenn der CPU Kerne Aktivierungsmodus auf Selektionsmodus gesetzt ist. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Per Core HT Deaktivierungseinstellungen

Ermöglicht es Ihnen festzulegen, ob die HT Funktion für jeden CPU Kern deaktiviert werden soll. </br>Dieser Punkt ist nur konfigurierbar, wenn die Per Core HT Deaktivierungseinstellungen auf Manuell gesetzt sind. </br>

## C States Steuerung

C-States sind Energiesparmodi für die CPU, die darauf abzielen, den Energieverbrauch zu reduzieren, wenn die CPU nicht voll ausgelastet ist. </br> Jeder C-State repräsentiert einen unterschiedlichen Grad an Energieeinsparung und Inaktivität. </br> Die Aktivierung und Deaktivierung der C-States-Steuerung im BIOS ermöglicht es Ihnen, das Verhalten der CPU in Bezug auf Energieeinsparung und Leistung zu steuern. </br>

### CPU Enhanced Halt (C1E)

Aktiviert oder deaktiviert die Intel® CPU Enhanced Halt (C1E) Funktion, eine CPU Energiesparfunktion im System Halt Zustand. </br>Wenn aktiviert, werden die CPU Kernfrequenz und die Spannung im System Halt Zustand reduziert, um den Stromverbrauch zu senken. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist. </br>

### C6/C7 Zustandsunterstützung

Ermöglicht es Ihnen festzulegen, ob die CPU im System Halt Zustand in den C6/C7 Modus wechseln soll. </br>Wenn aktiviert, werden die CPU Kernfrequenz und die Spannung im System Halt Zustand reduziert, um den Stromverbrauch zu senken. </br>Der C6/C7 Zustand ist ein weiter entwickelter Energiesparzustand als C3. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist. </br>

### C8 Zustandsunterstützung

Ermöglicht es Ihnen festzulegen, ob die CPU im System Halt Zustand in den C8 Modus wechseln soll. </br>Wenn aktiviert, werden die CPU Kernfrequenz und die Spannung im System Halt Zustand reduziert, um den Stromverbrauch zu senken. </br>Der C8 Zustand ist ein weiter entwickelter Energiesparzustand als C6/C7. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist. </br>

### C10 Zustandsunterstützung

Ermöglicht es Ihnen festzulegen, ob die CPU im System Halt Zustand in den C10 Modus wechseln soll. </br>Wenn aktiviert, werden die CPU Kernfrequenz und die Spannung im System Halt Zustand reduziert, um den Stromverbrauch zu senken. </br>Der C10 Zustand ist ein weiter entwickelter Energiesparzustand als C8. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist. </br>

### Paket C Zustandsgrenze

Ermöglicht es Ihnen, die C Zustandsgrenze für den Prozessor festzulegen. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist. </br>

### Turbo Leistungsgrenzen

Ermöglicht es Ihnen, eine Leistungsgrenze für den CPU Turbo Modus festzulegen. </br>Wenn der CPU Stromverbrauch die festgelegte Leistungsgrenze überschreitet, reduziert die CPU automatisch die Kernfrequenz, um die Leistung zu senken. </br>Auto setzt die aktuelle Grenze entsprechend den CPU Spezifikationen. </br>

### Leistungsgrenze TDP (Watt) / Leistungszeit

Ermöglicht es Ihnen, die Leistungsgrenze für den CPU/Plattform/Speicher Turbo Modus festzulegen und wie lange es dauert, um bei der festgelegten Leistungsgrenze zu arbeiten. </br>Auto setzt die Leistungsgrenze entsprechend den CPU Spezifikationen. </br>Dieser Punkt ist nur konfigurierbar, wenn Turbo Leistungsgrenzen auf aktiviert gesetzt sind. </br>

### Kernstromgrenze (Ampere)

Ermöglicht es Ihnen, eine Stromgrenze für den CPU Turbo Modus festzulegen. </br>Wenn der CPU Strom die festgelegte Stromgrenze überschreitet, reduziert die CPU automatisch die Kernfrequenz, um den Strom zu senken. </br>Auto setzt die Stromgrenze entsprechend den CPU Spezifikationen. </br>Dieser Punkt ist nur konfigurierbar, wenn Turbo Leistungsgrenzen auf aktiviert gesetzt sind. </br>

### Turbo Per Core Limit Control

Ermöglicht es Ihnen, die Grenze für jeden CPU Kern separat zu steuern. </br>

### DDR5 Auto Booster

Aktiviert oder deaktiviert die DDR5 Dynamic Turbo Boost Funktion, die ein automatisches Umschalten zwischen Standardfrequenz und erhöhter Frequenz ermöglicht. </br>
Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### DDR5 XMP Booster

Ermöglicht es Ihnen, zwischen Profilen zu wählen, die für bestimmte Speicher IC Hersteller erstellt wurden, um die Speicherleistung zu verbessern. </br>

### Extreme Memory Profile (X.M.P.)

Ermöglicht es dem BIOS, die SPD Daten des installierten XMP Speichermoduls zu lesen, um die Speicherleistung zu verbessern, wenn aktiviert. </br>

### Deaktiviert

Deaktiviert diese Funktion. </br>

### Profil 1

Verwendet die Einstellungen von Profil 1. </br>

### Profil 2

Verwendet die Einstellungen von Profil 2. </br>(Nur verfügbar, wenn ein Speicher Modul installiert ist, das diese Funktion unterstützt. )

### System Memory Multiplier

Ermöglicht es Ihnen, den System Speicher Multiplikator festzulegen. </br>Auto setzt den Speicher Multiplikator entsprechend den SPD Daten des Speichers. </br>

### Memory Ref Clock

Ermöglicht es Ihnen, den Referenztakt des Speichers manuell anzupassen. </br>

### Gear Mode

Ermöglicht es Ihnen, das maximale OC Frequenzpotenzial zu verbessern. </br>

### Memory Boot Mode

Bietet Methoden zur Speichererkennung und  initialisierung. </br>
  **Auto**: Lässt das BIOS diese Einstellung automatisch konfigurieren. </br>
  **Normal**: Das BIOS führt die Speicherinitialisierung automatisch durch. </br>Bitte beachten Sie, dass, wenn das System instabil wird oder nicht bootet, versuchen Sie, die CMOS Werte zu löschen und das Board auf die Standardeinstellungen zurückzusetzen. </br>(Informationen zum Löschen der CMOS Werte finden Sie in Kapitel 2 des Benutzerhandbuchs bei den Anweisungen zum Batterie /CMOS Jumper/Schalter. )
  **Enable Fast Boot**: Überspringt die Speichererkennung und  initialisierung nach bestimmten Kriterien für einen schnelleren Speicherstart. </br>
  **Disable Fast Boot**: Erkennen und initialisieren Sie den Speicher bei jedem Bootvorgang. </br>

### SA GV

Aktiviert oder deaktiviert System Agent Geyserville (SAGV), wodurch das System Spannungen oder Frequenzen entsprechend den Arbeitslasten dynamisch ändern kann oder den Wert auf einen bestimmten Punkt festlegt. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Dynamic Memory Boost

Aktiviert oder deaktiviert die Dynamic Memory Boost Funktion, die ein automatisches Umschalten zwischen der Standard SPD Profilfrequenz und der ausgewählten XMP Profilfrequenz ermöglicht. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>Dieser Punkt ist nur konfigurierbar, wenn die Echtzeit Speicherfrequenz auf Deaktiviert gesetzt ist. </br>

### Realtime Memory Frequency

Aktiviert oder deaktiviert die Echtzeit Speicherfrequenzfunktion, die ein manuelles Umschalten zwischen der Standard SPD Profilfrequenz und der ausgewählten XMP Profilfrequenz ermöglicht. </br>Dieser Punkt ist nur konfigurierbar, wenn Dynamic Memory Boost auf Deaktiviert gesetzt ist. </br>

### Realtime Memory Timing

Ermöglicht es Ihnen, die Speichertimings nach der BIOS Phase fein abzustimmen. </br>

### Memory Enhancement Settings

Ermöglicht es dem System, auf drei verschiedenen Leistungsniveaus zu arbeiten. </br>
  **Erweiterte Speichereinstellungen**

### Memory Channel Detection Message

Ermöglicht es Ihnen, festzulegen, ob eine Warnmeldung angezeigt werden soll, wenn der Speicher nicht im optimalen Speicherslot installiert ist. </br>

### Retry Loop Count

Ermöglicht es Ihnen, die Anzahl der Wiederholungen für den Speicher Selbsttest festzulegen, wenn das Speicher Overclocking fehlschlägt. </br>

### SPD Info

Zeigt Informationen über den installierten Speicher an. </br>

### SPD Setup

Ermöglicht es Ihnen, Speicherparameter für den installierten Speicher zu konfigurieren oder die Einstellungen als Profil zu speichern. </br>

### Memory Channels Timings

Ermöglicht es Ihnen, die Speichertimings für verschiedene Kanäle einzustellen. </br>
  **Standard Timing Control der Kanäle**
  **Erweiterte Timing Control der Kanäle**
  **Sonstige Timing Control der Kanäle**

Diese Abschnitte bieten Speichertimingeinstellungen. </br>Hinweis: Ihr System kann instabil werden oder nicht starten, nachdem Sie die Speichertimings geändert haben. </br>Wenn dies auftritt, setzen Sie das Board auf die Standardeinstellungen zurück, indem Sie optimierte Standardeinstellungen laden oder die CMOS Werte löschen. </br>

### Memory Training Settings

Ermöglicht es Ihnen, die Speicherinitialisierungseinstellungen anzupassen. </br>

### CPU/PCH Voltage Control/DRAM Voltage Control

Diese Punkte ermöglichen es Ihnen, die Spannungen von CPU, Chipsatz und Speicher anzupassen. </br>Die angezeigten Punkte und Werte können je nach Chipsatz des Motherboards und der verwendeten CPU variieren. </br>

### Erweiterte Spannungseinstellungen

Dieses Untermenü ermöglicht es Ihnen, den Load Line Kalibrierungsgrad, die Überspannungsschutzstufe und die Überstromschutzstufe zu konfigurieren. </br>

### DDR5 Voltage Control

Diese Punkte ermöglichen es Ihnen, die Spannungen des DDR5 Speichers anzupassen. </br>Dieses Untermenü ist nur auf Modellen vorhanden, die DDR5 Speicher unterstützen. </br>

## Einstellungen

### **PEG ASPM**

  **PEG** steht für **PCI Express Graphics**. </br>
  **ASPM** steht für **Active State Power Management**. </br>
  Diese Funktion ermöglicht es Ihnen, den ASPM Modus für das Gerät zu konfigurieren, das mit dem CPU PEG Bus (der PCIe Bus, der direkt mit der CPU verbunden ist und normalerweise für die Grafikkarte verwendet wird) verbunden ist. </br>
  ASPM reduziert den Stromverbrauch, wenn das Gerät nicht aktiv ist, indem es die Leistung der Links dynamisch anpasst. </br>

### **PCH ASPM**

  **PCH** steht für **Platform Controller Hub**. </br>
  Diese Funktion ermöglicht es Ihnen, den ASPM Modus für das Gerät zu konfigurieren, das mit dem PCI Express Bus des Chipsatzes (PCH) verbunden ist. </br>
  Ähnlich wie PEG ASPM, zielt diese Einstellung darauf ab, den Stromverbrauch zu reduzieren, indem die Link Leistung basierend auf der Aktivität des Geräts verwaltet wird. </br>

### **DMI ASPM**

  **DMI** steht für **Direct Media Interface**. </br>
  Diese Funktion ermöglicht es Ihnen, den ASPM Modus sowohl für die CPU Seite als auch die Chipsatz Seite des DMI Links zu konfigurieren. </br>
  Der DMI Link verbindet die CPU mit dem Chipsatz und verwaltet den Datentransfer zwischen ihnen. </br>
  Das Aktivieren von ASPM für den DMI Link hilft, den Stromverbrauch zu senken, wenn der Link nicht stark beansprucht wird. </br>

### **S3 Save Mode**

  **S3** ist ein Energiesparmodus, der auch als **Suspend to RAM** oder **Standby** bekannt ist. </br>
  Diese Funktion ermöglicht es Ihnen festzulegen, ob das System im System S3 Zustand in den Energiesparmodus wechselt. </br>
  Im S3 Zustand wird der gesamte Systeminhalt im RAM gespeichert, und fast alle anderen Komponenten werden ausgeschaltet, was zu einem sehr niedrigen Stromverbrauch führt. </br>
  Das System kann jedoch schnell wieder aktiviert werden, wenn es wieder benötigt wird. </br>

### **Die ErP Funktion**

(Energy related Products) ist eine Einstellung im BIOS, die sicherstellt, dass das System im S5 Zustand (kompletter Ausschaltzustand) den geringstmöglichen Stromverbrauch hat. </br>

  Diese Einstellung entspricht den Anforderungen der EU Richtlinie zur umweltgerechten Gestaltung energieverbrauchsrelevanter Produkte. </br>
  Bestimmt, ob das System im S5 (Herunterfahren) Zustand am wenigsten Strom verbraucht. </br>Hinweis: Wenn dieser Punkt aktiviert ist, wird die Funktion "Wiederaufnahme durch Alarm" deaktiviert. </br>
  
### **Soft Off by PWR BTTN**

    Konfiguriert die Möglichkeit, den Computer im MS DOS Modus mit der Einschalttaste auszuschalten. </br>
    **Sofort Aus**: Drücken Sie die Einschalttaste und das System wird sofort ausgeschaltet. </br>
    **Verzögerung 4 Sekunden**: Drücken und halten Sie die Einschalttaste 4 Sekunden lang, um das System auszuschalten. </br>Wenn die Einschalttaste weniger als 4 Sekunden gedrückt wird, wechselt das System in den Suspend Modus. </br>
  
## Detaillierte Erklärung

  **S5 Zustand (Soft Off)**:
    Dies ist der Zustand, in dem der Computer vollständig ausgeschaltet ist, aber immer noch eine minimale Menge an Strom verbraucht, um bestimmte Funktionen wie Wake on LAN oder den Erhalt der CMOS Einstellungen aufrechtzuerhalten. </br>

  **ErP aktivieren**:
    Wenn diese Funktion aktiviert ist, reduziert das System den Stromverbrauch im S5 Zustand auf das gesetzlich vorgeschriebene Minimum. </br>Dies kann bedeuten, dass bestimmte Funktionen, die normalerweise im ausgeschalteten Zustand Strom verbrauchen, deaktiviert werden. </br>

  **Auswirkung auf "Wiederaufnahme durch Alarm"**:
    Wenn **ErP** aktiviert ist, wird die Funktion "Wiederaufnahme durch Alarm" (Wake up by Alarm) deaktiviert. </br>Dies bedeutet, dass das System nicht mehr zu einer bestimmten Zeit automatisch eingeschaltet werden kann, da diese Funktion Strom benötigt, um im ausgeschalteten Zustand funktionsfähig zu bleiben. </br>

Zusammengefasst bedeutet die Aktivierung der **ErP** Funktion, dass der Stromverbrauch im ausgeschalteten Zustand minimiert wird, was jedoch die Deaktivierung bestimmter stromverbrauchender Funktionen zur Folge hat. </br>

## Plattformleistung

### Resume by Alarm

Bestimmt, ob das System zu einer gewünschten Zeit eingeschaltet werden soll. </br>Wenn aktiviert, stellen Sie das Datum und die Uhrzeit wie folgt ein:
  **Wecktag**: Schalten Sie das System zu einer bestimmten Zeit an jedem Tag oder an einem bestimmten Tag im Monat ein. </br>
  **Weckstunde/Minute/Sekunde**: Stellen Sie die Uhrzeit ein, zu der das System automatisch eingeschaltet wird. </br>
Hinweis: Wenn Sie diese Funktion verwenden, vermeiden Sie einen unzureichenden Shutdown vom Betriebssystem oder das Entfernen der Netzspannung, da die Einstellungen sonst nicht wirksam sein könnten. </br>

### Native ASPM

Ermöglicht es Ihnen, zwischen BIOS gesteuertem oder betriebssystemgesteuertem ASPM zu wählen. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### Power Loading

Aktiviert oder deaktiviert die Dummy Last. </br>Wenn die Stromversorgung bei geringer Last ist, wird ein Selbstschutz aktiviert, der zum Abschalten oder Ausfall führt. </br>Wenn dies auftritt, setzen Sie diese Einstellung auf Aktiviert. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### RC6 (Render Standby)

Ermöglicht es Ihnen festzulegen, ob die integrierte Grafik in den Standby Modus wechselt, um den Stromverbrauch zu senken. </br>

### AC BACK

Bestimmt den Zustand des Systems nach der Wiederkehr der Stromversorgung nach einem Stromausfall. </br>
  **Memory**: Das System kehrt nach der Rückkehr der Netzspannung in den letzten bekannten Wachzustand zurück. </br>
  **Always On**: Das System wird nach der Rückkehr der Netzspannung eingeschaltet. </br>
  **Always Off**: Das System bleibt nach der Rückkehr der Netzspannung ausgeschaltet. </br>

### Initial Display Output

Legt fest, welche Grafikkarte das Monitor Display zuerst ansteuert, entweder die installierte PCI Express Grafikkarte oder die integrierte Grafikeinheit. </br>
  **IGFX**: Setzt die integrierte Grafikeinheit als erstes Display. </br>
  **PCIe 1 Slot**: Setzt die Grafikkarte im PCIEX16 Slot als erstes Display. </br>
  **PCIe 2 Slot**: Setzt die Grafikkarte im PCIEX8 Slot als erstes Display. </br>
  **PCIe 3 Slot**: Setzt die Grafikkarte im PCIEX4 Slot als erstes Display. </br>

### Internal Graphics

Aktiviert oder deaktiviert die integrierte Grafikfunktion. </br>

### DVMT Pre Allocated

Ermöglicht es Ihnen, die Speichermenge der integrierten Grafikeinheit festzulegen. </br>

### Aperture Size

Ermöglicht es Ihnen, die maximale Menge an Systemspeicher festzulegen, die der Grafikkarte zugewiesen werden kann. </br>Optionen sind: 128MB, 256MB, 512MB, 1024MB und 1024MB. </br>

### PCIE Bifurcation Support

Ermöglicht es Ihnen festzulegen, wie die Bandbreite des PCIEX16 Slots aufgeteilt wird. </br>

### OnBoard LAN Controller

Aktiviert oder deaktiviert die Onboard LAN Funktion. </br>Wenn Sie stattdessen eine Netzwerkkarte eines Drittanbieters installieren möchten, setzen Sie diesen Punkt auf Deaktiviert. </br>

### OnBoard LAN Controller#2

Aktiviert oder deaktiviert die Onboard LAN Funktion. </br>Wenn Sie stattdessen eine Netzwerkkarte eines Drittanbieters installieren möchten, setzen Sie diesen Punkt auf Deaktiviert. </br>

### Audio Controller

Aktiviert oder deaktiviert die Onboard Audio Funktion. </br>Wenn Sie stattdessen eine Audiokarte eines Drittanbieters installieren möchten, setzen Sie diesen Punkt auf Deaktiviert. </br>

### Above 4G Decoding

Aktiviert oder deaktiviert die Dekodierung von 64 Bit fähigen Geräten im Adressraum über 4 GB (nur wenn Ihr System 64 Bit PCI Dekodierung unterstützt). </br>Setzen Sie diesen Punkt auf Aktiviert, wenn mehr als eine fortgeschrittene Grafikkarte installiert ist und deren Treiber beim Starten des Betriebssystems nicht geladen werden können (aufgrund des begrenzten 4 GB Speicheradressraums). </br>

### Re Size BAR Support

Aktiviert oder deaktiviert die Unterstützung für Resizable BAR. </br>

## IO Ports

### IOAPIC 24 119 Entries

Aktiviert oder deaktiviert diese Funktion. </br>

### Super IO Configuration

### Serial Port

Aktiviert oder deaktiviert den Onboard Seriellen Port. </br>

### Parallel Port

Aktiviert oder deaktiviert den Onboard Parallelen Port. </br>

## Gigabyte Utilities Downloader Configuration

Ermöglicht es Ihnen festzulegen, ob das GIGABYTE Control Center nach dem Start des Betriebssystems automatisch heruntergeladen und installiert werden soll. </br>Stellen Sie vor der Installation sicher, dass das System mit dem Internet verbunden ist. </br>

### Thunderbolt(TM) Configuration

Dieses Untermenü bietet Thunderbolt bezogene Konfigurationsoptionen. </br>Dieses Untermenü erscheint nur auf Motherboards, die über einen integrierten Intel® Thunderbolt™ Controller verfügen oder auf denen eine GIGABYTE Thunderbolt™ Erweiterungskarte installiert ist. </br>

### PCIE Tunneling over USB4

Aktiviert oder deaktiviert PCIe Tunneling über USB4. </br>

### Wake up from Thunderbolt(TM) Devices

Ermöglicht es dem System, von Thunderbolt™ Geräten aufgeweckt zu werden. </br>

## USB Configuration

### Legacy USB Support

Ermöglicht die Verwendung von USB Tastatur/Maus in MS DOS. </br>

### XHCI Hand off

Bestimmt, ob die XHCI Hand off Funktion für ein Betriebssystem ohne XHCI Hand off Unterstützung aktiviert werden soll. </br>

### USB Mass Storage Driver Support

Aktiviert oder deaktiviert die Unterstützung für USB Speichergeräte. </br>

### Port 60/64 Emulation

Aktiviert oder deaktiviert die Unterstützung für USB Speichergeräte. </br>

### Mass Storage Devices

Zeigt eine Liste der angeschlossenen USB Speichergeräte an. </br>Dieser Punkt erscheint nur, wenn ein USB Speichergerät installiert ist. </br>

## Network Stack Configuration

### Network Stack

Deaktiviert oder aktiviert das Booten vom Netzwerk, um ein GPT Format Betriebssystem zu installieren, wie z. </br>B. </br>die Installation des Betriebssystems vom Windows Deployment Services Server. </br>

### IPv4 PXE Support

Aktiviert oder deaktiviert IPv4 PXE Unterstützung. </br>Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist. </br>

### IPv4 HTTP Support

Aktiviert oder deaktiviert HTTP Boot Unterstützung für IPv4. </br>Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist. </br>

### IPv6 PXE Support

Aktiviert oder deaktiviert IPv6 PXE Unterstützung. </br>Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist. </br>

### IPv6 HTTP Support

Aktiviert oder deaktiviert HTTP Boot Unterstützung für IPv6. </br>Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist. </br>

### PXE boot wait time

Ermöglicht es Ihnen festzulegen, wie lange Sie warten müssen, bevor Sie (Esc) drücken können, um den PXE Bootvorgang abzubrechen. </br>Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist. </br>

### Media detect count

Ermöglicht es Ihnen, die Anzahl der Überprüfungen des Vorhandenseins von Medien festzulegen. </br>Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist. </br>

### NVMe Configuration

Zeigt Informationen über Ihre installierte M. </br>2 NVMe PCIe SSD an. </br>

## SATA Configuration

Aktiviert oder deaktiviert die integrierten SATA Controller. </br>

### Aggressive LPM Support

Aktiviert oder deaktiviert die Energiesparfunktion, ALPM (Aggressive Link Power Management), für die Chipsatz SATA Controller. </br>

### Port

Aktiviert oder deaktiviert jeden SATA Port. </br>

### SATA Port DevSlp

Ermöglicht es Ihnen festzulegen, ob das angeschlossene SATA Gerät in den Schlafmodus wechseln soll. </br>

### Hot plug

Aktiviert oder deaktiviert die Hot Plug Funktion für jeden SATA Port. </br>

### Configured as eSATA

Aktiviert oder deaktiviert die Unterstützung für externe SATA Geräte. </br>

### VMD setup menu

Ermöglicht es Ihnen, die VMD Controller zu konfigurieren. </br>Um RAID Konfigurationen zu erstellen, setzen Sie den VMD Controller auf Aktiviert und setzen Sie die globale VMD Zuordnung auf Deaktiviert. </br>Je nach verwendeten SATA/M. </br>2 Anschlüssen setzen Sie den entsprechenden Punkt "Diesen Root Port unter VMD zuordnen" auf Aktiviert. </br>Bitte navigieren Sie zur Seite "Erstellen eines RAID Sets" auf der GIGABYTE Website für Anweisungen zur Konfiguration eines RAID Arrays. </br>

### Ethernet Controller / PCIe GBE Family Controller

Dieses Untermenü bietet Informationen zur LAN Konfiguration und zugehörigen Konfigurationsoptionen. </br>

### LEDs im eingeschalteten Zustand des Systems

Ermöglicht es Ihnen, die LED Beleuchtung des Motherboards zu aktivieren oder zu deaktivieren, wenn das System eingeschaltet ist. </br>
  **Aus**: Deaktiviert den ausgewählten Beleuchtungsmodus, wenn das System eingeschaltet ist. </br>
  **Ein**: Aktiviert den ausgewählten Beleuchtungsmodus, wenn das System eingeschaltet ist. </br>

### LEDs im Schlaf , Ruhezustand und Soft Off Zustand

Ermöglicht es Ihnen, den Beleuchtungsmodus der Motherboard LEDs im Systemzustand S3/S4/S5 festzulegen. </br>Dieser Punkt ist konfigurierbar, wenn LEDs im eingeschalteten Zustand des Systems auf Ein gesetzt sind. </br>
  **Aus**: Deaktiviert den ausgewählten Beleuchtungsmodus, wenn das System in den S3/S4/S5 Zustand wechselt. </br>
  **Ein**: Aktiviert den ausgewählten Beleuchtungsmodus, wenn das System in den S3/S4/S5 Zustand wechselt. </br>

### RST_SW (MULTIKEY) (Funktion der RST_SW Taste)

  **Taste auf HW Reset setzen**: Verwenden Sie die Taste, um Ihr System zurückzusetzen. </br>
  **Taste zum Ein /Ausschalten der LEDs verwenden**: Verwenden Sie die Taste, um die LEDs des Motherboards ein  oder auszuschalten. </br>
  **Taste zum Aufrufen des BIOS Setups verwenden**: Verwenden Sie die Taste, um das BIOS Setup aufzurufen. </br>
  **Taste zum Starten im abgesicherten Modus verwenden**: Verwenden Sie die Taste, um das System im abgesicherten Modus zu starten. </br>

### GEN5 Redriver SIPO Mode

Aktiviert oder deaktiviert den GEN5 Redriver SIPO Mode. </br>

### GEN5 Equalization

Ermöglicht es Ihnen, den GEN5 Equalizer Wert anzupassen. </br>

### GEN5 DC Gain

Ermöglicht es Ihnen, den GEN5 DC Verstärkungswert anzupassen. </br>

### Onboard DB Port LED

Ermöglicht es Ihnen, die LED Beleuchtung der Debug LEDs des Motherboards zu aktivieren oder zu deaktivieren, wenn das System eingeschaltet ist. </br>

### Intel Platform Trust Technology (PTT)

Aktiviert oder deaktiviert die Intel® PTT Technologie. </br>

### 3DMark01 Enhancement

Ermöglicht es Ihnen festzulegen, ob einige ältere Benchmark Leistungen verbessert werden sollen. </br>

### CPU PCIe Link Speed

Ermöglicht es Ihnen, den Betriebsmodus der CPU gesteuerten PCI Express Slots festzulegen. </br>Der tatsächliche Betriebsmodus hängt von den Hardwarespezifikationen jedes Slots ab. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

## Verschiedenes

### PCH PCIe Link Speed

Ermöglicht es Ihnen, den Betriebsmodus der Chipsatz gesteuerten PCI Express Slots festzulegen. </br>Der tatsächliche Betriebsmodus hängt von den Hardwarespezifikationen jedes Slots ab. </br>Auto lässt das BIOS diese Einstellung automatisch konfigurieren. </br>

### VT d

Aktiviert oder deaktiviert die Intel® Virtualization Technology für Directed I/O. </br>

### Trusted Computing

Aktiviert oder deaktiviert das Trusted Platform Module (TPM). </br>

### Option Search (Hot Key: Alt F)

Dieser Bildschirm ermöglicht es Ihnen, Stichwörter (nur Englisch) einzugeben, um die gesuchte BIOS Option zu finden. </br>Drücken Sie (Alt) und (F), um den Optionssuchbildschirm aufzurufen. </br>Geben Sie die Stichwörter in das Suchfeld ein und drücken Sie (Enter) oder klicken Sie auf Suchen. </br>

### Reset Case Open Status

  **Deaktiviert**: Behält oder löscht den Eintrag des vorherigen Gehäuseeinbruchstatus. </br>
  **Aktiviert**: Löscht den Eintrag des vorherigen Gehäuseeinbruchstatus und das Feld "Case Open" zeigt beim nächsten Start "No" an. </br>

### Case Open

Zeigt den Erkennungsstatus des am CI Anschluss des Motherboards angeschlossenen Gehäuseeinbrucherkennungsgeräts an. </br>Wenn die Gehäuseabdeckung des Systems entfernt wird, zeigt dieses Feld "Yes" an, andernfalls "No". </br>Um den Gehäuseeinbruchstatus zu löschen, setzen Sie "Reset Case Open Status" auf Aktiviert, speichern Sie die Einstellungen im CMOS und starten Sie dann Ihr System neu. </br>

### CPU Vcore/CPU VCCIN AUX/CPU VCCSA/VDD2 CPU/PCH1. </br>8V/+3. </br>3V/+5V/PCH 0. </br>82V/+12V/CPU VAXG

Zeigt die aktuellen Systemspannungen an. </br>Die angezeigten Punkte und Werte können je nach Chipsatz des Motherboards und der verwendeten CPU variieren. </br>

## PC Gesundheitsstatus

### Systeminformationen

Dieser Abschnitt bietet Informationen über Ihr Motherboard Modell und die BIOS Version. </br>Sie können auch die Standardsprache des BIOS auswählen und die Systemzeit manuell einstellen. </br>

### Access Level

Zeigt den aktuellen Zugriffsebenenstatus an, abhängig von der verwendeten Passwortschutzart. </br>(Wenn kein Passwort festgelegt ist, wird standardmäßig Administrator angezeigt. ) Die Administrator Ebene ermöglicht es Ihnen, Änderungen an allen BIOS Einstellungen vorzunehmen; die Benutzerebene erlaubt nur Änderungen an bestimmten BIOS Einstellungen. </br>

### System Language

Wählt die Standardsprache, die vom BIOS verwendet wird. </br>

### System Date

Stellt das Systemdatum ein. </br>Das Datumsformat ist Woche (schreibgeschützt), Monat, Datum und Jahr. </br>Verwenden Sie (Enter), um zwischen den Feldern Monat, Datum und Jahr zu wechseln und verwenden Sie die (Page Up) oder (Page Down) Taste, um den gewünschten Wert einzustellen. </br>

### System Time

Stellt die Systemzeit ein. </br>Das Zeitformat ist Stunde, Minute und Sekunde. </br>Zum Beispiel, 13:00:00 für 1 Uhr nachmittags. </br>Verwenden Sie (Enter), um zwischen den Feldern Stunde, Minute und Sekunde zu wechseln und verwenden Sie die (Page Up) oder (Page Down) Taste, um den gewünschten Wert einzustellen. </br>

### Plug in Devices Info

Zeigt Informationen über Ihre installierten PCI Express  und M. </br>2 Geräte an. </br>

### Q Flash

Ermöglicht den Zugriff auf das Q Flash Dienstprogramm, um das BIOS zu aktualisieren oder die aktuelle BIOS Konfiguration zu sichern. </br>

## Boot

### Bootup NumLock State

Aktiviert oder deaktiviert die Numlock Funktion auf dem numerischen Tastenfeld der Tastatur nach dem POST. </br>

### CFG Lock

Aktiviert oder deaktiviert die MSR 0xE2 Funktion. </br>

### Security Option

Legt fest, ob bei jedem Systemstart ein Passwort erforderlich ist oder nur beim Aufrufen des BIOS Setups. </br>Nach dem Konfigurieren dieses Punktes setzen Sie das/die Passwort(e) unter Administrator Passwort/Benutzer Passwort. </br>
  **Setup**: Ein Passwort ist nur zum Aufrufen des BIOS Setup Programms erforderlich. </br>
  **System**: Ein Passwort ist für den Systemstart und das Aufrufen des BIOS Setup Programms erforderlich. </br>

### Full Screen LOGO Show

Ermöglicht es Ihnen festzulegen, ob das GIGABYTE Logo beim Systemstart angezeigt wird. </br>Deaktiviert überspringt das GIGABYTE Logo beim Systemstart. </br>

### Boot Option Priorities

Legt die allgemeine Startreihenfolge der verfügbaren Geräte fest. </br>Wechselmedien, die das GPT Format unterstützen, werden in der Startgeräteliste mit dem Präfix "UEFI:" angezeigt. </br>Um von einem Betriebssystem zu starten, das die GPT Partitionierung unterstützt, wählen Sie das Gerät mit dem Präfix "UEFI:". </br>
Oder wenn Sie ein Betriebssystem installieren möchten, das die GPT Partitionierung unterstützt, wie Windows 11 64 Bit, wählen Sie das optische Laufwerk, das die Windows 11 64 Bit Installationsdiskette enthält und das Präfix "UEFI:" hat. </br>

### Fast Boot

Aktiviert oder deaktiviert das schnelle Booten, um den Betriebssystem Startvorgang zu verkürzen. </br>Ultra Fast bietet die schnellste Startgeschwindigkeit. </br>

### SATA Support

  **Letzter Boot SATA Devices Only**: Außer dem vorherigen Boot Laufwerk sind alle SATA Geräte deaktiviert, bevor der OS Bootvorgang abgeschlossen ist. </br>
  **Alle SATA Devices**: Alle SATA Geräte sind im Betriebssystem und während des POST funktionsfähig. </br>Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf aktiviert oder Ultra Fast gesetzt ist. </br>

### VGA Unterstützung

Ermöglicht es Ihnen auszuwählen, welches Betriebssystem gestartet werden soll. </br>
  **Auto**: Aktiviert nur das Legacy Option ROM. </br>
  **EFI Treiber**: Aktiviert das EFI Option ROM. </br>
Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf Aktiviert oder Ultra Fast gesetzt ist. </br>

### USB Unterstützung

  **Disable Link**: Alle USB Geräte sind deaktiviert, bevor der OS Startvorgang abgeschlossen ist. </br>
  **Full Initial**: Alle USB Geräte sind im Betriebssystem und während des POST funktionsfähig. </br>
  **Partial Initial**: Einige USB Geräte sind deaktiviert, bevor der OS Startvorgang abgeschlossen ist. </br>
Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf Aktiviert oder Ultra Fast gesetzt ist. </br>Diese Funktion ist deaktiviert, wenn Fast Boot auf Ultra Fast gesetzt ist. </br>

### Netzwerk Stack Treiberunterstützung

  **Disable Link**: Deaktiviert das Booten vom Netzwerk. </br>
  **Enabled**: Aktiviert das Booten vom Netzwerk. </br>
Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf Aktiviert oder Ultra Fast gesetzt ist. </br>

### Nächster Start nach AC Stromausfall

  **Normal Boot**: Aktiviert den normalen Start beim Zurückkehren der Netzspannung. </br>
  **Fast Boot**: Beibehaltung der Fast Boot Einstellungen beim Zurückkehren der Netzspannung. </br>
Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf Aktiviert oder Ultra Fast gesetzt ist. </br>

### Mausgeschwindigkeit

Ermöglicht es Ihnen, die Bewegungsgeschwindigkeit des Mauszeigers festzulegen. </br>

### Windows 10 Funktionen

Ermöglicht es Ihnen, das zu installierende Betriebssystem auszuwählen. </br>

### CSM Unterstützung

Aktiviert oder deaktiviert das UEFI CSM (Compatibility Support Module), um einen Legacy PC Boot Vorgang zu unterstützen. </br>
  **Disabled**: Deaktiviert das UEFI CSM und unterstützt nur den UEFI BIOS Boot Vorgang. </br>
  **Enabled**: Aktiviert das UEFI CSM. </br>

### LAN PXE Boot Option ROM

Ermöglicht es Ihnen auszuwählen, ob das Legacy Option ROM für den LAN Controller aktiviert werden soll. </br>
Dieser Punkt ist nur konfigurierbar, wenn die CSM Unterstützung auf Enabled gesetzt ist. </br>

### Speicher Boot Optionen Steuerung

Ermöglicht es Ihnen auszuwählen, ob das UEFI  oder Legacy Option ROM für den Speichergeräte Controller aktiviert werden soll. </br>
  **Do not launch**: Deaktiviert das Option ROM. </br>
  **UEFI**: Aktiviert nur das UEFI Option ROM. </br>
  **Legacy**: Aktiviert nur das Legacy Option ROM. </br>
Dieser Punkt ist nur konfigurierbar, wenn die CSM Unterstützung auf Enabled gesetzt ist. </br>

### Andere PCI Geräte

Ermöglicht es Ihnen auszuwählen, ob das UEFI  oder Legacy Option ROM für den PCI Geräte Controller außer LAN, Speichergerät und Grafikkarten Controller aktiviert werden soll. </br>
  **Do not launch**: Deaktiviert das Option ROM. </br>
  **UEFI**: Aktiviert nur das UEFI Option ROM. </br>
  **Legacy**: Aktiviert nur das Legacy Option ROM. </br>
Dieser Punkt ist nur konfigurierbar, wenn die CSM Unterstützung auf Enabled gesetzt ist. </br>

### Administrator Passwort

Ermöglicht es Ihnen, ein Administrator Passwort zu konfigurieren. </br>Drücken Sie (Enter) auf diesem Punkt, geben Sie das Passwort ein und drücken Sie dann (Enter). </br>Sie werden aufgefordert, das Passwort zu bestätigen. </br>Geben Sie das Passwort erneut ein und drücken Sie (Enter). </br>Sie müssen das Administrator Passwort (oder das Benutzer Passwort) beim Systemstart und beim Aufrufen des BIOS Setups eingeben. </br>Das Administrator Passwort ermöglicht Ihnen im Gegensatz zum Benutzer Passwort, Änderungen an allen BIOS Einstellungen vorzunehmen. </br>Passwort entfernen altes Administrator Passwort eingeben und neues leer lassen. </br>

### Benutzer Passwort

Ermöglicht es Ihnen, ein Benutzer Passwort zu konfigurieren. </br>Drücken Sie (Enter) auf diesem Punkt, geben Sie das Passwort ein und drücken Sie dann (Enter). </br>Sie werden aufgefordert, das Passwort zu bestätigen. </br>Geben Sie das Passwort erneut ein und drücken Sie (Enter). </br>Sie müssen das Administrator Passwort (oder das Benutzer Passwort) beim Systemstart und beim Aufrufen des BIOS Setups eingeben. </br>Das Benutzer Passwort ermöglicht jedoch nur Änderungen an bestimmten BIOS Einstellungen, nicht an allen. </br>Um das Passwort zu löschen, drücken Sie (Enter) auf dem Passwortfeld und geben das korrekte Passwort ein, wenn Sie dazu aufgefordert werden. </br>Wenn Sie zur Eingabe eines neuen Passworts aufgefordert werden, drücken Sie (Enter), ohne ein Passwort einzugeben. </br>Drücken Sie erneut (Enter), um zu bestätigen. </br>
Hinweis: Stellen Sie sicher, dass das Administrator Passwort zuerst festgelegt wird, bevor Sie das Benutzer Passwort festlegen. </br>Passwort entfernen altes Benutzer Passwort eingeben und neues leer lassen. </br>

### Secure Boot

Ermöglicht es Ihnen, Secure Boot zu aktivieren oder zu deaktivieren und verwandte Einstellungen zu konfigurieren. </br>Dieser Punkt ist nur konfigurierbar, wenn die CSM Unterstützung auf Disabled gesetzt ist. </br>

### Bevorzugter Betriebsmodus

Ermöglicht es Ihnen auszuwählen, ob Sie den einfachen Modus oder den erweiterten Modus nach dem Aufrufen des BIOS Setups betreten. </br>Auto wechselt zu dem Modus, der zuletzt verwendet wurde. </br>

### Speichern # Beenden

  **Save # Exit Setup**: Drücken Sie (Enter) auf diesem Punkt und wählen Sie Ja. </br>Dadurch werden die Änderungen im CMOS gespeichert und das BIOS Setup Programm verlassen. </br>Wählen Sie Nein oder drücken Sie (Esc), um zum Hauptmenü des BIOS Setups zurückzukehren. </br>
  **Exit Without Saving**: Drücken Sie (Enter) auf diesem Punkt und wählen Sie Ja. </br>Dadurch wird das BIOS Setup Programm ohne Speichern der vorgenommenen Änderungen im CMOS verlassen. </br>Wählen Sie Nein oder drücken Sie (Esc), um zum Hauptmenü des BIOS Setups zurückzukehren. </br>
  **Load Optimized Defaults**: Drücken Sie (Enter) auf diesem Punkt und wählen Sie Ja, um die optimalen BIOS Standardeinstellungen zu laden. </br>Die BIOS Standardeinstellungen helfen dem System, im optimalen Zustand zu arbeiten. </br>Laden Sie immer die optimierten Standardeinstellungen nach dem Aktualisieren des BIOS oder nach dem Löschen der CMOS Werte. </br>
  **Boot Override**: Ermöglicht es Ihnen, ein Gerät auszuwählen, von dem sofort gebootet werden soll. </br>Drücken Sie (Enter) auf dem ausgewählten Gerät und wählen Sie Ja zur Bestätigung. </br>Ihr System wird automatisch neu gestartet und von diesem Gerät gebootet. </br>
  **Save Profiles**: Diese Funktion ermöglicht es Ihnen, die aktuellen BIOS Einstellungen in einem Profil zu speichern. </br>Sie können bis zu 8 Profile erstellen und als Setup Profil 1 bis Setup Profil 8 speichern. </br>Drücken Sie (Enter), um abzuschließen. </br>Oder Sie können "Datei auswählen in HDD/FDD/USB" auswählen, um das Profil auf Ihrem Speichermedium zu speichern. </br>
  **Load Profiles**: Wenn Ihr System instabil wird und Sie die BIOS Standardeinstellungen geladen haben, können Sie diese Funktion verwenden, um die BIOS Einstellungen aus einem zuvor erstellten Profil zu laden, ohne die BIOS Einstellungen erneut konfigurieren zu müssen. </br>Wählen Sie zuerst das Profil aus, das Sie laden möchten, und drücken Sie dann (Enter), um abzuschließen. </br>Sie können "Datei auswählen in HDD/FDD/USB" wählen, um das zuvor erstellte Profil von Ihrem Speichermedium zu laden oder das Profil automatisch zu laden, das von dem BIOS erstellt wurde, z. </br>B. </br>das Zurücksetzen der BIOS Einstellungen auf die letzten Einstellungen, die ordnungsgemäß funktioniert haben (bekanntermaßen guter Zustand). </br>

## Diverse Windows Funktionen

* Festplatten von gpt oder mbr ändern. </br>

Bei der Installation von Windows 11 die Festplatten ändern. </br>
Nach starten der Installations DVD die Umschalttaste und F10 drücken. </br>
Es öffnet sich eine Konsole
diskpart   startet Festplattentool
list disk   listet Festplatten auf. </br>
select disc 0 oder 1   je nachdem welche Festplatte ausgewählt werden soll. </br>
clean   für löschen. </br>
convert gpt oder mbr   je nachdem was benötigt wird. </br>
// Dies muss für alle Festplatten einzeln gemacht werden, die geändert werden sollen oder müssen. </br>//
exit   Ende und Konsolenfenster schließen. </br>
Dann normal die Installation weitermachen. </br>

## Prozessorlast Verteilung einstellen

* Folgendes ist Windows ab 8. </br>1 geprüft
* Windows Taste und R dann nacheinander eingeben
cmd
ab win 10 hier weiter machen
msconfig
* Im nächsten Fenster auswählen
Start
erweiterte Optionen
* dann die ferfügbaren Core (Prozessorkerne) einstellen. </br>

---

Windows 10:
Einstellungen
System
Netzbetrieb und Energiesparen
Zusätzliche Energieeinstellungen
Hinter Ausbalanciert "Energiesparplaneinstellungen ändern" auswählen
Erweiterte Energieeinstellungen ändern
Prozessorenenergieverwaltung
"Minimaler Leistungszustand des Prozessors" auf "70%" stellen

---

Windows 11:
Suche nach:
Energiesparplan bearbeiten

Dort suchen nach:
Erweiterte Energieeinstellungen

Prozessorenenergieverwaltung
"Minimaler Leistungszustand des Prozessors" auf "70%" stellen mindestens aber 51% um flüssig arbeiten zu können. </br>

## Passwort abschalten

Drücken Sie auf Ihrer Tastatur gleichzeitig die Windows Taste und R. </br>
netplwiz eingeben
Benutzer müssen Benutzernamen und Kennwort eingeben: dort den Haken weg machen

Das funktioniert bei Windows 11 nicht. </br>

## Windows ab 8 ohne Datenverlust reparieren

* Windows Konsole starten als Administrator mit Win + X  - Eingabeaufforderung Administrator. </br>
* Fehler suchen und Reparieren
    sfc /scannow
* Nur Fehler suchen
    sfc /ferifyonly

## Image auf Komponentenspeicherbeschädigungen durchsuchen und Reparieren

* Windows Konsole starten als Administrator mit Win + X  - Eingabeaufforderung Administrator. </br>

## auf Komponentenspeicherbeschädigungen durchsuchen

Dism /Online /Cleanup Image /ScanHealth

## Image reparieren

Dism /Online /Cleanup Image / RestoreHealth

## Record Image Recimg Befehlsübersicht mit

recimg /?

## Image erstellen

recimg  /createimage d:\Refresh ; (Anstatt d:\Refresh kann auch anderer Ordnername gewählt werden)
