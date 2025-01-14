# B760_DS3H_AX BIOS Deutsch

• Die in diesem Abschnitt beschriebenen BIOS Einrichtungsmenüs können von den genauen Einstellungen Ihres Motherboards abweichen.Die tatsächlichen BIOS Einrichtungsmenüoptionen, die Sie sehen, hängen von den Spezifikationen des Motherboards und der BIOS Version ab.
• Einige BIOS Einstellungen sind nur verfügbar, wenn der verwendete Chipsatz des Motherboards und die CPU/der Speicher diese Funktion unterstützen.Weitere Informationen zu den einzigartigen Funktionen von Intel® CPUs finden Sie auf der Intel Website.

BIOS (Basic Input and Output System) speichert Hardware Parameter des Systems im CMOS auf dem Motherboard.Zu seinen Hauptfunktionen gehören die Durchführung des Power On Self Test (POST) beim Systemstart, das Speichern von Systemparametern und das Laden des Betriebssystems usw.BIOS enthält ein BIOS Einrichtungsprogramm, das es dem Benutzer ermöglicht, grundlegende Systemeinstellungen zu ändern oder bestimmte Systemfunktionen zu aktivieren.

Wenn der Strom ausgeschaltet ist, liefert die Batterie auf dem Motherboard die notwendige Energie, um die Konfigurationswerte im CMOS zu halten.

Um das BIOS Einrichtungsprogramm aufzurufen, drücken Sie während des POST beim Einschalten die Taste (Entf) (Delete).

Zum Aktualisieren des BIOS verwenden Sie entweder das GIGABYTE Q Flash  oder Q Flash Plus Dienstprogramm.

• Q Flash ermöglicht es dem Benutzer, das BIOS schnell und einfach zu aktualisieren oder zu sichern, ohne das Betriebssystem zu betreten.
• Q Flash Plus ermöglicht es Ihnen, das BIOS zu aktualisieren, wenn Ihr System ausgeschaltet ist (S5 Abschaltzustand).Speichern Sie das neueste BIOS auf einem USB Stick und stecken Sie ihn in den dafür vorgesehenen Anschluss.Sie können dann das BIOS automatisch durch einfaches Drücken der Q Flash Plus Taste flashen.

Anweisungen zur Verwendung der Q Flash  und Q Flash Plus Dienstprogramme finden Sie auf der Seite "Einzigartige Funktionen" der GIGABYTE Website und suchen Sie nach "BIOS Update Utilities".

• Da das Flashen des BIOS potenziell riskant ist, wird empfohlen, das BIOS nicht zu flashen, wenn Sie keine Probleme mit der aktuellen Version des BIOS haben.Wenn Sie das BIOS flashen, tun Sie dies mit Vorsicht.Unzureichendes BIOS Flashen kann zu Fehlfunktionen des Systems führen.
• Es wird empfohlen, die Standardeinstellungen nicht zu ändern (es sei denn, dies ist notwendig), um Systeminstabilität oder andere unerwartete Ergebnisse zu vermeiden.Das unzureichende Ändern der Einstellungen kann dazu führen, dass das System nicht startet.Wenn dies auftritt, versuchen Sie, die CMOS Werte zu löschen und das Board auf die Standardwerte zurückzusetzen.
• Informationen zum Löschen der CMOS Werte und zum Zurücksetzen des Boards auf die Standardwerte finden Sie in der Bedienungsanleitung zum Batterie /CMOS Jumper oder zur Schaltfläche oder im Abschnitt "Optimierte Standardeinstellungen laden".

## BIOS Setup

### Startbildschirm

Der folgende Startbildschirm mit dem Logo erscheint, wenn der Computer hochfährt.(Der Bildschirm kann je nach Motherboard variieren.)
Funktionstasten:

* (DEL): BIOS SETUP\Q FLASH
Drücken Sie die (Entf) Taste, um das BIOS Setup aufzurufen oder um das Q Flash Dienstprogramm im BIOS Setup aufzurufen.

* (F12): BOOT MENÜ
Das Boot Menü ermöglicht es Ihnen, das erste Boot Gerät ohne den Aufruf des BIOS Setup einzustellen.Verwenden Sie im Boot Menü die Pfeiltasten (h) oder (i), um das erste Boot Gerät auszuwählen, und drücken Sie dann

* (Enter), um zu bestätigen.Das System startet sofort von diesem Gerät.
Hinweis: Die Einstellung im Boot Menü ist nur einmalig wirksam.Nach dem Neustart des Systems basiert die Gerätebootreihenfolge weiterhin auf den BIOS Setup Einstellungen.

* (END): Q FLASH
Drücken Sie die (Ende) Taste, um direkt auf das Q Flash Dienstprogramm zuzugreifen, ohne zuerst das BIOS Setup aufzurufen.

## Funktionstasten

* Das Hauptmenü

* Erweiterter Modus

Der erweiterte Modus bietet detaillierte BIOS Einstellungen.Sie können die Pfeiltasten auf Ihrer Tastatur verwenden, um zwischen den Punkten zu wechseln, und drücken Sie (Enter), um zu bestätigen oder ein Untermenü aufzurufen.Oder Sie können Ihre Maus verwenden, um den gewünschten Punkt auszuwählen.

* Hardware Informationen

* Optionen Beschreibung Aktuelle Einstellungen

* Einrichtungsmenüs

* Konfigurationselemente

* Systemzeit

Die Schnellzugriffsleiste ermöglicht es Ihnen, schnell zu den Bildschirmen Allgemeine Hilfe, Einfache Modus, Smart Fan 6 oder Q Flash zu wechseln.

## Erweiterter Modus Funktionstasten

* (f)(g) Bewegen Sie die Auswahlleiste, um ein Einrichtungsmenü auszuwählen.
* (h)(i) Bewegen Sie die Auswahlleiste, um ein Konfigurationselement in einem Menü auszuwählen.
* (Enter)/Doppelklick Befehl ausführen oder Menü aufrufen
* (+)/(Seite hoch) Erhöhen Sie den numerischen Wert oder ändern Sie ihn.
* ( )/(Seite runter) Verringern Sie den numerischen Wert oder ändern Sie ihn.
* (F1) Zeigt Beschreibungen der Funktionstasten an.
* (F2) Wechseln zum einfachen Modus.
* (F3) Speichern Sie die aktuellen BIOS Einstellungen in einem Profil.
* (F4) Laden Sie die BIOS Einstellungen aus einem zuvor erstellten Profil.
* (F5) Stellen Sie die vorherigen BIOS Einstellungen für die aktuellen Untermenüs wieder her.
* (F6) Zeigt den Smart Fan 6 Bildschirm an.
* (F7) Laden Sie die optimierten BIOS Standardwerte für die aktuellen Untermenüs.
* (F8) Zugriff auf das Q Flash Dienstprogramm.
* (F10) Speichern Sie alle Änderungen und beenden Sie das BIOS Setup Programm.
* (F11) Wechseln Sie zum Favoriten Untermenü.
* (F12) Erfassen Sie den aktuellen Bildschirm als Bild und speichern Sie es auf Ihrem USB Laufwerk.
* (Einf) Fügen Sie eine Favoritenoption hinzu oder entfernen Sie sie.
* (Strg)+(S) Zeigt Informationen zum installierten Speicher an.
* (Esc) Hauptmenü: Beenden Sie das BIOS Setup Programm.

Untermenüs: Beenden Sie das aktuelle Untermenü.

* (Alt)+(F) Geben Sie Schlüsselwörter ein, um das gesuchte BIOS Konfigurationselement zu finden.

## Einfache Modus

Der einfache Modus ermöglicht es Benutzern, schnell ihre aktuellen Systeminformationen anzuzeigen oder Anpassungen für optimale Leistung vorzunehmen.Im einfachen Modus können Sie Ihre Maus verwenden, um durch die Konfigurationselemente zu navigieren, oder drücken Sie (F2), um zum erweiterten Modus zu wechseln.

Verwenden Sie die (F6) Funktionstaste, um schnell zu diesem Bildschirm zu wechseln.Dieser Bildschirm ermöglicht es Ihnen, Lüftergeschwindigkeitseinstellungen für jeden Lüfteranschluss zu konfigurieren oder Ihre System /CPU Temperatur zu überwachen.

### ALLE ABSTIMMEN

Ermöglicht es Ihnen, die aktuellen Einstellungen auf alle Lüfteranschlüsse anzuwenden.

### Temperatur

Zeigt die aktuelle Temperatur des ausgewählten Zielbereichs an.

### Lüftergeschwindigkeit

Zeigt aktuelle Lüfter /Pumpengeschwindigkeiten an.

### Durchflussrate

Zeigt die Durchflussrate Ihres Wasserkühlungssystems an.Drücken Sie (Enter) auf Lüftergeschwindigkeit, um zu dieser Funktion zu wechseln.

### Lüftergeschwindigkeitsregelung

Ermöglicht es Ihnen, zu bestimmen, ob die Lüftergeschwindigkeitsregelung aktiviert werden soll und die Lüftergeschwindigkeit anzupassen.
*Normal Ermöglicht es dem Lüfter, bei unterschiedlichen Geschwindigkeiten je nach Temperatur zu laufen.Sie können die Lüftergeschwindigkeit auf der FAN Control Seite des GIGABYTE Control Center basierend auf Ihren Systemanforderungen einstellen.
*Leise Ermöglicht es dem Lüfter, mit langsamen Geschwindigkeiten zu laufen.
*Manuell Ermöglicht es Ihnen, die Kurvenknoten zu ziehen, um die Lüftergeschwindigkeit anzupassen.Oder Sie können die EZ Tuning Funktion verwenden.Nach dem Anpassen der Knotenposition drücken Sie Anwenden, um die Neigung der Kurve automatisch zu berechnen.
*Volle Geschwindigkeit Ermöglicht es dem Lüfter, mit voller Geschwindigkeit zu laufen.

### Lüfterregelung Temperatur Eingabe verwenden

Ermöglicht es Ihnen, die Referenztemperatur für die Lüftergeschwindigkeitsregelung auszuwählen.

### Temperaturintervall

Ermöglicht es Ihnen, das Temperaturintervall für die Lüftergeschwindigkeitsänderung auszuwählen.

### FAN/PUMP Control Mode

*Auto Lässt das BIOS den Typ des installierten Lüfters automatisch erkennen und den optimalen Steuerungsmodus festlegen.
*Spannung Der Spannungsmodus wird für einen 3 Pin Lüfter/Pumpe empfohlen.
*PWM Der PWM Modus wird für einen 4 Pin Lüfter/Pumpe empfohlen.

### FAN/PUMP Stop

Aktiviert oder deaktiviert die Lüfter /Pumpen Stoppfunktion.Sie können das Temperaturlimit mithilfe der Temperaturkurve festlegen.Der Lüfter oder die Pumpe stoppt den Betrieb, wenn die Temperatur unter das Limit fällt.

### FAN/PUMP Modus

Ermöglicht es Ihnen, den Betriebsmodus für den Lüfter festzulegen.

### Slope

Passt die Lüftergeschwindigkeit linear basierend auf der Temperatur an.

### Stair

Passt die Lüftergeschwindigkeit stufenweise basierend auf der Temperatur an.

### FAN/PUMP Fehlerwarnung

Ermöglicht es dem System, einen Warnton auszugeben, wenn der Lüfter/die Pumpe nicht angeschlossen ist oder ausfällt.Überprüfen Sie den Zustand des Lüfters/der Pumpe oder die Verbindung des Lüfters/der Pumpe, wenn dies auftritt.

### Lüfterprofil speichern

Diese Funktion ermöglicht es Ihnen, die aktuellen Einstellungen in einem Profil zu speichern.Sie können das Profil im BIOS speichern oder die Option "Datei auswählen in HDD/FDD/USB" wählen, um das Profil auf Ihrem Speichermedium zu speichern.

### Lüfterprofil laden

Diese Funktion ermöglicht es Ihnen, ein zuvor gespeichertes BIOS Profil zu laden, ohne die BIOS Einstellungen neu konfigurieren zu müssen.Oder Sie können die Option "Datei auswählen in HDD/FDD/USB" wählen, um ein Profil von Ihrem Speichermedium zu laden.

### Favoriten (F11)

Legen Sie Ihre häufig verwendeten Optionen als Favoriten fest und verwenden Sie die (F11) Taste, um schnell zu der Seite zu wechseln, auf der sich alle Ihre Favoriten befinden.Um eine Favoritenoption hinzuzufügen oder zu entfernen, gehen Sie zur ursprünglichen Seite und drücken Sie (Einfügen) auf der Option.Die Option wird mit einem Sternsymbol markiert, wenn sie als "Favorit" festgelegt ist.

## Tweaker

### CPU Upgrade

Ermöglicht es Ihnen, die CPU Frequenz festzulegen.Das endgültige Ergebnis kann je nach verwendeter CPU variieren.Die Optionen sind: Standard, Gaming Profil, Erweiterte Profil.

### CPU Basistakt

Ermöglicht es Ihnen, den CPU Basistakt manuell in Schritten von 0,01 MHz einzustellen.
Wichtig: Es wird dringend empfohlen, die CPU Frequenz entsprechend den Spezifikationen der CPU einzustellen.

### PCIe/DMI/PEG Taktfrequenz

Ermöglicht es Ihnen, die PCIe/DMI/PEG Taktfrequenz manuell in Schritten von 0,01 MHz einzustellen.

### Verbesserte Multi Core Leistung

Ermöglicht es Ihnen festzulegen, ob das höchste Turboverhältnis auf alle CPU Kerne angewendet werden soll.

### Leistungs CPU Taktverhältnis

Ermöglicht es Ihnen, das Taktverhältnis für die installierte Leistungs CPU zu ändern.Der einstellbare Bereich hängt von der installierten CPU ab.

### Effizienz CPU Taktverhältnis

Ermöglicht es Ihnen, das Taktverhältnis für die installierte Effizienz CPU zu ändern.Der einstellbare Bereich hängt von der installierten CPU ab.

### Maximales Ringverhältnis

Ermöglicht es Ihnen, das maximale CPU Uncore Verhältnis festzulegen.Der einstellbare Bereich hängt von der verwendeten CPU ab.

### Minimales Ringverhältnis

Ermöglicht es Ihnen, das minimale CPU Uncore Verhältnis festzulegen.Der einstellbare Bereich hängt von der verwendeten CPU ab.

### IGP Verhältnis

Ermöglicht es Ihnen, das Grafikverhältnis festzulegen.
Ob das System stabil mit den von Ihnen vorgenommenen Overclock /Überspannungseinstellungen funktioniert, hängt von Ihren gesamten Systemkonfigurationen ab.Falsches Overclocking/Überspannung kann zu Schäden an CPU, Chipsatz oder Speicher führen und die Lebensdauer dieser Komponenten verkürzen.Diese Seite ist nur für fortgeschrittene Benutzer und wir empfehlen, die Standardeinstellungen nicht zu ändern, um Systeminstabilität oder andere unerwartete Ergebnisse zu vermeiden.(Unzureichendes Ändern der Einstellungen kann dazu führen, dass das System nicht startet.Wenn dies auftritt, löschen Sie die CMOS Werte und setzen Sie das Board auf die Standardwerte zurück.)

Einige BIOS Einstellungen sind nur verfügbar, wenn der verwendete Chipsatz des Motherboards und die CPU/der Speicher diese Funktion unterstützen.Weitere Informationen zu den einzigartigen Funktionen von Intel® CPUs finden Sie auf der Intel Website.

### PVD Ratio Threshold Override

Ermöglicht es Ihnen festzulegen, ob die Leistung bei extremem BCLK Overclocking durch Reduzierung eines "PLL Banding" Zustands verbessert werden soll, der teilweise durch eine sehr hohe DCO Frequenz verursacht wird.

### CPU Übertemperaturschutz

Ermöglicht es Ihnen, den TJ Max Offset Wert fein abzustimmen.

### Hyper Threading Technologie

Ermöglicht es Ihnen festzulegen, ob die Multi Threading Technologie bei Verwendung einer Intel® CPU aktiviert werden soll, die diese Funktion unterstützt.Diese Funktion funktioniert nur für Betriebssysteme, die den Multi Prozessor Modus unterstützen.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Intel(R) Speed Shift Technology (Intel® Speed Shift Technology)

Aktiviert oder deaktiviert die Intel® Speed Shift Technology.Wenn diese Funktion aktiviert ist, kann der Prozessor seine Betriebsfrequenz schneller erhöhen und verbessert die Systemreaktionsfähigkeit.

### CPU Thermal Monitor

Aktiviert oder deaktiviert die Intel® Thermal Monitor Funktion, eine CPU Überhitzungsschutzfunktion.Wenn diese Funktion aktiviert ist, werden die CPU Kernfrequenz und die Spannung reduziert, wenn die CPU überhitzt.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Ring zu Kern Offset (Down Bin)

Ermöglicht es Ihnen festzulegen, ob die automatische Reduzierungsfunktion des CPU Ring Verhältnisses deaktiviert werden soll.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### CPU EIST Funktion

Aktiviert oder deaktiviert die Enhanced Intel® Speed Step Technology (EIST).Je nach CPU Auslastung kann die Intel® EIST Technologie die CPU Spannung und  Kernfrequenz dynamisch und effektiv senken, um den durchschnittlichen Stromverbrauch und die Wärmeproduktion zu verringern.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Race To Halt (RTH) /Energy Efficient Turbo

Aktiviert oder deaktiviert die CPU Energiesparfunktionen.

### Intel(R) Turbo Boost Technology

Ermöglicht es Ihnen festzulegen, ob die Intel® CPU Turbo Boost Technologie aktiviert werden soll.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Intel(R) Turbo Boost Max Technology 3.0

Aktiviert oder deaktiviert die Intel® Turbo Boost Max Technology 3.0.Intel® Turbo Boost Max Technology 3.0 ermöglicht es dem System, den besten Leistungskern des Prozessors zu identifizieren und ermöglicht es Ihnen, die kritischsten Arbeitslasten manuell darauf zu richten.Sie können sogar die Frequenz jedes Kerns einzeln anpassen, um die Leistung zu optimieren.

## Erweiterte CPU Einstellungen

### CPU Flex Ratio Override

Aktiviert oder deaktiviert das CPU Flex Ratio.

### CPU Flex Ratio Einstellungen

Ermöglicht es Ihnen, das CPU Flex Ratio festzulegen.Der einstellbare Bereich kann je nach CPU variieren.

### Frequency TVB

Ermöglicht es Ihnen, die automatische CPU Frequenzreduzierung, die durch Thermal Velocity Boost initiiert wird, zu aktivieren oder zu deaktivieren.

### Enhanced TVB

Aktiviert oder deaktiviert die erweiterte Thermal Velocity Boost (TVB) Funktion.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Voltage Reduction Initiated TVB

Ermöglicht es Ihnen, die automatische CPU Spannungsreduzierung, die durch Thermal Velocity Boost initiiert wird, zu aktivieren oder zu deaktivieren.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### IA CEP (Current Excursion Protection)

Ermöglicht es Ihnen, IA CEP zu aktivieren oder zu deaktivieren.

### GT CEP (Current Excursion Protection)

Ermöglicht es Ihnen, GT CEP zu aktivieren oder zu deaktivieren.

### Fll OC Mode

Ermöglicht es Ihnen, den FLL Modus auszuwählen.

### Legacy Game Compatibility Mode

Ermöglicht es Ihnen, den Legacy Game Compatibility Mode zu aktivieren, um die Funktionalität älterer Spiele zu verbessern.

### Core VR Fast Vmode

Aktiviert oder deaktiviert den Core Fast V Mode.

### Unterspannungsschutz

Aktiviert oder deaktiviert die Unterspannungsschutzfunktion.

## AVX Einstellungen

**Advanced Vector Extensions (AVX)** sind Erweiterungen der x86-Befehlssätze, die speziell entwickelt wurden, um die Leistung von Anwendungen zu verbessern, die intensive Rechenaufgaben ausführen. Dazu gehören wissenschaftliche Berechnungen, 3D-Modellierung, Video-Rendering und andere datenintensive Aufgaben. AVX ermöglicht es Prozessoren, gleichzeitig mit mehreren Datenpunkten zu arbeiten, was zu erheblichen Leistungssteigerungen führt.

### Konfiguration der AVX-Einstellungen im BIOS

Im BIOS können Sie AVX-bezogene Funktionen aktivieren oder deaktivieren. Wenn die AVX-Einstellungen aktiviert sind, konfiguriert das System diese automatisch gemäß den Spezifikationen Ihrer CPU. Dies stellt sicher, dass die AVX-Instruktionen von Ihrer CPU unterstützt und optimal genutzt werden.

### AVX

Diese Einstellung ermöglicht es Ihnen, die AVX-Befehlssätze auf einer CPU, die AVX unterstützt, zu deaktivieren. Beachten Sie, dass diese Option nur verfügbar ist, wenn die AVX-Einstellungen auf Benutzerdefiniert gesetzt sind.

### AVX Offset

Der AVX Offset ist eine Einstellung, die das CPU-Taktverhältnis reduziert, wenn der Prozessor AVX-Workloads ausführt. Zum Beispiel, wenn der Offset-Wert auf 3 gesetzt ist, wird das CPU-Taktverhältnis beim Ausführen von AVX-Befehlen um 3 reduziert. Dies kann hilfreich sein, um die thermische Belastung der CPU zu reduzieren und die Systemstabilität zu gewährleisten.

### AVX Optimum

Diese Einstellung ermöglicht es Ihnen, die AVX-Befehle zu optimieren. Dies bedeutet, dass die CPU-Performance für AVX-Workloads angepasst wird, um eine bessere Effizienz und Leistung zu erzielen.

### AVX Voltage Guardband Scale Factor

Diese Einstellung ermöglicht es Ihnen, die Standard-AVX-Spannung zu senken. Eine niedrigere Spannung kann dazu beitragen, die Leistungsaufnahme zu reduzieren und die thermische Belastung der CPU zu minimieren.

Mit diesen Einstellungen können Sie die Leistung und Effizienz Ihrer CPU für AVX-intensive Anwendungen optimieren und anpassen.

### Aktive Turbo Verhältnisse

Ermöglicht es Ihnen, die CPU Turbo Verhältnisse für verschiedene Anzahl aktiver Kerne festzulegen.Auto stellt die CPU Turbo Verhältnisse entsprechend den CPU Spezifikationen ein.Dieser Punkt ist nur konfigurierbar, wenn aktive Turbo Verhältnisse auf Manuell gesetzt ist.

### CPU Kerne Aktivierungsmodus

Ermöglicht es Ihnen, auszuwählen, wie CPU Kerne aktiviert werden sollen.

### Anzahl der aktivierten CPU P Kerne

Ermöglicht es Ihnen, die Anzahl der zu aktivierenden CPU P Kerne auszuwählen (die Anzahl der CPU Kerne kann je nach CPU variieren).Dieser Punkt ist nur konfigurierbar, wenn der CPU Kerne Aktivierungsmodus auf Zufallsmodus gesetzt ist.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Anzahl der aktivierten CPU E Kerne

Ermöglicht es Ihnen, die Anzahl der zu aktivierenden CPU E Kerne auszuwählen (die Anzahl der CPU Kerne kann je nach CPU variieren).Dieser Punkt ist nur konfigurierbar, wenn der CPU Kerne Aktivierungsmodus auf Zufallsmodus gesetzt ist.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Aktiver P Kern/E Kern

Ermöglicht es Ihnen, auszuwählen, welcher CPU Kern aktiviert werden soll.Die Anzahl der CPU Kerne kann je nach CPU variieren.Dieser Punkt ist nur konfigurierbar, wenn der CPU Kerne Aktivierungsmodus auf Selektionsmodus gesetzt ist.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Per Core HT Deaktivierungseinstellungen

Ermöglicht es Ihnen festzulegen, ob die HT Funktion für jeden CPU Kern deaktiviert werden soll.Dieser Punkt ist nur konfigurierbar, wenn die Per Core HT Deaktivierungseinstellungen auf Manuell gesetzt sind.

## C States Steuerung

C-States sind Energiesparmodi für die CPU, die darauf abzielen, den Energieverbrauch zu reduzieren, wenn die CPU nicht voll ausgelastet ist. Jeder C-State repräsentiert einen unterschiedlichen Grad an Energieeinsparung und Inaktivität. Die Aktivierung und Deaktivierung der C-States-Steuerung im BIOS ermöglicht es Ihnen, das Verhalten der CPU in Bezug auf Energieeinsparung und Leistung zu steuern.

### CPU Enhanced Halt (C1E)

Aktiviert oder deaktiviert die Intel® CPU Enhanced Halt (C1E) Funktion, eine CPU Energiesparfunktion im System Halt Zustand.Wenn aktiviert, werden die CPU Kernfrequenz und die Spannung im System Halt Zustand reduziert, um den Stromverbrauch zu senken.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist.

### C6/C7 Zustandsunterstützung

Ermöglicht es Ihnen festzulegen, ob die CPU im System Halt Zustand in den C6/C7 Modus wechseln soll.Wenn aktiviert, werden die CPU Kernfrequenz und die Spannung im System Halt Zustand reduziert, um den Stromverbrauch zu senken.Der C6/C7 Zustand ist ein weiter entwickelter Energiesparzustand als C3.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist.

### C8 Zustandsunterstützung

Ermöglicht es Ihnen festzulegen, ob die CPU im System Halt Zustand in den C8 Modus wechseln soll.Wenn aktiviert, werden die CPU Kernfrequenz und die Spannung im System Halt Zustand reduziert, um den Stromverbrauch zu senken.Der C8 Zustand ist ein weiter entwickelter Energiesparzustand als C6/C7.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist.

### C10 Zustandsunterstützung

Ermöglicht es Ihnen festzulegen, ob die CPU im System Halt Zustand in den C10 Modus wechseln soll.Wenn aktiviert, werden die CPU Kernfrequenz und die Spannung im System Halt Zustand reduziert, um den Stromverbrauch zu senken.Der C10 Zustand ist ein weiter entwickelter Energiesparzustand als C8.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist.

### Paket C Zustandsgrenze

Ermöglicht es Ihnen, die C Zustandsgrenze für den Prozessor festzulegen.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.Dieser Punkt ist nur konfigurierbar, wenn die C States Steuerung auf aktiviert gesetzt ist.

### Turbo Leistungsgrenzen

Ermöglicht es Ihnen, eine Leistungsgrenze für den CPU Turbo Modus festzulegen.Wenn der CPU Stromverbrauch die festgelegte Leistungsgrenze überschreitet, reduziert die CPU automatisch die Kernfrequenz, um die Leistung zu senken.Auto setzt die aktuelle Grenze entsprechend den CPU Spezifikationen.

### Leistungsgrenze TDP (Watt) / Leistungszeit

Ermöglicht es Ihnen, die Leistungsgrenze für den CPU/Plattform/Speicher Turbo Modus festzulegen und wie lange es dauert, um bei der festgelegten Leistungsgrenze zu arbeiten.Auto setzt die Leistungsgrenze entsprechend den CPU Spezifikationen.Dieser Punkt ist nur konfigurierbar, wenn Turbo Leistungsgrenzen auf aktiviert gesetzt sind.

### Kernstromgrenze (Ampere)

Ermöglicht es Ihnen, eine Stromgrenze für den CPU Turbo Modus festzulegen.Wenn der CPU Strom die festgelegte Stromgrenze überschreitet, reduziert die CPU automatisch die Kernfrequenz, um den Strom zu senken.Auto setzt die Stromgrenze entsprechend den CPU Spezifikationen.Dieser Punkt ist nur konfigurierbar, wenn Turbo Leistungsgrenzen auf aktiviert gesetzt sind.

### Turbo Per Core Limit Control

Ermöglicht es Ihnen, die Grenze für jeden CPU Kern separat zu steuern.

### DDR5 Auto Booster

Aktiviert oder deaktiviert die DDR5 Dynamic Turbo Boost Funktion, die ein automatisches Umschalten zwischen Standardfrequenz und erhöhter Frequenz ermöglicht.
Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### DDR5 XMP Booster

Ermöglicht es Ihnen, zwischen Profilen zu wählen, die für bestimmte Speicher IC Hersteller erstellt wurden, um die Speicherleistung zu verbessern.

### Extreme Memory Profile (X.M.P.)

Ermöglicht es dem BIOS, die SPD Daten des installierten XMP Speichermoduls zu lesen, um die Speicherleistung zu verbessern, wenn aktiviert.

### Deaktiviert

Deaktiviert diese Funktion.

### Profil 1

Verwendet die Einstellungen von Profil 1.

### Profil 2

Verwendet die Einstellungen von Profil 2.(Nur verfügbar, wenn ein Speicher Modul installiert ist, das diese Funktion unterstützt.)

### System Memory Multiplier

Ermöglicht es Ihnen, den System Speicher Multiplikator festzulegen.Auto setzt den Speicher Multiplikator entsprechend den SPD Daten des Speichers.

### Memory Ref Clock

Ermöglicht es Ihnen, den Referenztakt des Speichers manuell anzupassen.

### Gear Mode

Ermöglicht es Ihnen, das maximale OC Frequenzpotenzial zu verbessern.

### Memory Boot Mode

Bietet Methoden zur Speichererkennung und  initialisierung.
  **Auto**: Lässt das BIOS diese Einstellung automatisch konfigurieren.
  **Normal**: Das BIOS führt die Speicherinitialisierung automatisch durch.Bitte beachten Sie, dass, wenn das System instabil wird oder nicht bootet, versuchen Sie, die CMOS Werte zu löschen und das Board auf die Standardeinstellungen zurückzusetzen.(Informationen zum Löschen der CMOS Werte finden Sie in Kapitel 2 des Benutzerhandbuchs bei den Anweisungen zum Batterie /CMOS Jumper/Schalter.)
  **Enable Fast Boot**: Überspringt die Speichererkennung und  initialisierung nach bestimmten Kriterien für einen schnelleren Speicherstart.
  **Disable Fast Boot**: Erkennen und initialisieren Sie den Speicher bei jedem Bootvorgang.

### SA GV

Aktiviert oder deaktiviert System Agent Geyserville (SAGV), wodurch das System Spannungen oder Frequenzen entsprechend den Arbeitslasten dynamisch ändern kann oder den Wert auf einen bestimmten Punkt festlegt.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Dynamic Memory Boost

Aktiviert oder deaktiviert die Dynamic Memory Boost Funktion, die ein automatisches Umschalten zwischen der Standard SPD Profilfrequenz und der ausgewählten XMP Profilfrequenz ermöglicht.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.Dieser Punkt ist nur konfigurierbar, wenn die Echtzeit Speicherfrequenz auf Deaktiviert gesetzt ist.

### Realtime Memory Frequency

Aktiviert oder deaktiviert die Echtzeit Speicherfrequenzfunktion, die ein manuelles Umschalten zwischen der Standard SPD Profilfrequenz und der ausgewählten XMP Profilfrequenz ermöglicht.Dieser Punkt ist nur konfigurierbar, wenn Dynamic Memory Boost auf Deaktiviert gesetzt ist.

### Realtime Memory Timing

Ermöglicht es Ihnen, die Speichertimings nach der BIOS Phase fein abzustimmen.

### Memory Enhancement Settings

Ermöglicht es dem System, auf drei verschiedenen Leistungsniveaus zu arbeiten.
  **Erweiterte Speichereinstellungen**

### Memory Channel Detection Message

Ermöglicht es Ihnen, festzulegen, ob eine Warnmeldung angezeigt werden soll, wenn der Speicher nicht im optimalen Speicherslot installiert ist.

### Retry Loop Count

Ermöglicht es Ihnen, die Anzahl der Wiederholungen für den Speicher Selbsttest festzulegen, wenn das Speicher Overclocking fehlschlägt.

### SPD Info

Zeigt Informationen über den installierten Speicher an.

### SPD Setup

Ermöglicht es Ihnen, Speicherparameter für den installierten Speicher zu konfigurieren oder die Einstellungen als Profil zu speichern.

### Memory Channels Timings

Ermöglicht es Ihnen, die Speichertimings für verschiedene Kanäle einzustellen.
  **Standard Timing Control der Kanäle**
  **Erweiterte Timing Control der Kanäle**
  **Sonstige Timing Control der Kanäle**

Diese Abschnitte bieten Speichertimingeinstellungen.Hinweis: Ihr System kann instabil werden oder nicht starten, nachdem Sie die Speichertimings geändert haben.Wenn dies auftritt, setzen Sie das Board auf die Standardeinstellungen zurück, indem Sie optimierte Standardeinstellungen laden oder die CMOS Werte löschen.

### Memory Training Settings

Ermöglicht es Ihnen, die Speicherinitialisierungseinstellungen anzupassen.

### CPU/PCH Voltage Control/DRAM Voltage Control

Diese Punkte ermöglichen es Ihnen, die Spannungen von CPU, Chipsatz und Speicher anzupassen.Die angezeigten Punkte und Werte können je nach Chipsatz des Motherboards und der verwendeten CPU variieren.

### Erweiterte Spannungseinstellungen

Dieses Untermenü ermöglicht es Ihnen, den Load Line Kalibrierungsgrad, die Überspannungsschutzstufe und die Überstromschutzstufe zu konfigurieren.

### DDR5 Voltage Control

Diese Punkte ermöglichen es Ihnen, die Spannungen des DDR5 Speichers anzupassen.Dieses Untermenü ist nur auf Modellen vorhanden, die DDR5 Speicher unterstützen.

## Einstellungen

### **PEG ASPM**

  **PEG** steht für **PCI Express Graphics**.
  **ASPM** steht für **Active State Power Management**.
  Diese Funktion ermöglicht es Ihnen, den ASPM Modus für das Gerät zu konfigurieren, das mit dem CPU PEG Bus (der PCIe Bus, der direkt mit der CPU verbunden ist und normalerweise für die Grafikkarte verwendet wird) verbunden ist.
  ASPM reduziert den Stromverbrauch, wenn das Gerät nicht aktiv ist, indem es die Leistung der Links dynamisch anpasst.

### **PCH ASPM**

  **PCH** steht für **Platform Controller Hub**.
  Diese Funktion ermöglicht es Ihnen, den ASPM Modus für das Gerät zu konfigurieren, das mit dem PCI Express Bus des Chipsatzes (PCH) verbunden ist.
  Ähnlich wie PEG ASPM, zielt diese Einstellung darauf ab, den Stromverbrauch zu reduzieren, indem die Link Leistung basierend auf der Aktivität des Geräts verwaltet wird.

### **DMI ASPM**

  **DMI** steht für **Direct Media Interface**.
  Diese Funktion ermöglicht es Ihnen, den ASPM Modus sowohl für die CPU Seite als auch die Chipsatz Seite des DMI Links zu konfigurieren.
  Der DMI Link verbindet die CPU mit dem Chipsatz und verwaltet den Datentransfer zwischen ihnen.
  Das Aktivieren von ASPM für den DMI Link hilft, den Stromverbrauch zu senken, wenn der Link nicht stark beansprucht wird.

### **S3 Save Mode**

  **S3** ist ein Energiesparmodus, der auch als **Suspend to RAM** oder **Standby** bekannt ist.
  Diese Funktion ermöglicht es Ihnen festzulegen, ob das System im System S3 Zustand in den Energiesparmodus wechselt.
  Im S3 Zustand wird der gesamte Systeminhalt im RAM gespeichert, und fast alle anderen Komponenten werden ausgeschaltet, was zu einem sehr niedrigen Stromverbrauch führt.
  Das System kann jedoch schnell wieder aktiviert werden, wenn es wieder benötigt wird.

### **Die ErP Funktion**

(Energy related Products) ist eine Einstellung im BIOS, die sicherstellt, dass das System im S5 Zustand (kompletter Ausschaltzustand) den geringstmöglichen Stromverbrauch hat.

  Diese Einstellung entspricht den Anforderungen der EU Richtlinie zur umweltgerechten Gestaltung energieverbrauchsrelevanter Produkte.
  Bestimmt, ob das System im S5 (Herunterfahren) Zustand am wenigsten Strom verbraucht.Hinweis: Wenn dieser Punkt aktiviert ist, wird die Funktion "Wiederaufnahme durch Alarm" deaktiviert.
  
### **Soft Off by PWR BTTN**

    Konfiguriert die Möglichkeit, den Computer im MS DOS Modus mit der Einschalttaste auszuschalten.
    **Sofort Aus**: Drücken Sie die Einschalttaste und das System wird sofort ausgeschaltet.
    **Verzögerung 4 Sekunden**: Drücken und halten Sie die Einschalttaste 4 Sekunden lang, um das System auszuschalten.Wenn die Einschalttaste weniger als 4 Sekunden gedrückt wird, wechselt das System in den Suspend Modus.
  
## Detaillierte Erklärung

  **S5 Zustand (Soft Off)**:
    Dies ist der Zustand, in dem der Computer vollständig ausgeschaltet ist, aber immer noch eine minimale Menge an Strom verbraucht, um bestimmte Funktionen wie Wake on LAN oder den Erhalt der CMOS Einstellungen aufrechtzuerhalten.

  **ErP aktivieren**:
    Wenn diese Funktion aktiviert ist, reduziert das System den Stromverbrauch im S5 Zustand auf das gesetzlich vorgeschriebene Minimum.Dies kann bedeuten, dass bestimmte Funktionen, die normalerweise im ausgeschalteten Zustand Strom verbrauchen, deaktiviert werden.

  **Auswirkung auf "Wiederaufnahme durch Alarm"**:
    Wenn **ErP** aktiviert ist, wird die Funktion "Wiederaufnahme durch Alarm" (Wake up by Alarm) deaktiviert.Dies bedeutet, dass das System nicht mehr zu einer bestimmten Zeit automatisch eingeschaltet werden kann, da diese Funktion Strom benötigt, um im ausgeschalteten Zustand funktionsfähig zu bleiben.

Zusammengefasst bedeutet die Aktivierung der **ErP** Funktion, dass der Stromverbrauch im ausgeschalteten Zustand minimiert wird, was jedoch die Deaktivierung bestimmter stromverbrauchender Funktionen zur Folge hat.

## Plattformleistung

### Resume by Alarm

Bestimmt, ob das System zu einer gewünschten Zeit eingeschaltet werden soll.Wenn aktiviert, stellen Sie das Datum und die Uhrzeit wie folgt ein:
  **Wecktag**: Schalten Sie das System zu einer bestimmten Zeit an jedem Tag oder an einem bestimmten Tag im Monat ein.
  **Weckstunde/Minute/Sekunde**: Stellen Sie die Uhrzeit ein, zu der das System automatisch eingeschaltet wird.
Hinweis: Wenn Sie diese Funktion verwenden, vermeiden Sie einen unzureichenden Shutdown vom Betriebssystem oder das Entfernen der Netzspannung, da die Einstellungen sonst nicht wirksam sein könnten.

### Native ASPM

Ermöglicht es Ihnen, zwischen BIOS gesteuertem oder betriebssystemgesteuertem ASPM zu wählen.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### Power Loading

Aktiviert oder deaktiviert die Dummy Last.Wenn die Stromversorgung bei geringer Last ist, wird ein Selbstschutz aktiviert, der zum Abschalten oder Ausfall führt.Wenn dies auftritt, setzen Sie diese Einstellung auf Aktiviert.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### RC6 (Render Standby)

Ermöglicht es Ihnen festzulegen, ob die integrierte Grafik in den Standby Modus wechselt, um den Stromverbrauch zu senken.

### AC BACK

Bestimmt den Zustand des Systems nach der Wiederkehr der Stromversorgung nach einem Stromausfall.
  **Memory**: Das System kehrt nach der Rückkehr der Netzspannung in den letzten bekannten Wachzustand zurück.
  **Always On**: Das System wird nach der Rückkehr der Netzspannung eingeschaltet.
  **Always Off**: Das System bleibt nach der Rückkehr der Netzspannung ausgeschaltet.

### Initial Display Output

Legt fest, welche Grafikkarte das Monitor Display zuerst ansteuert, entweder die installierte PCI Express Grafikkarte oder die integrierte Grafikeinheit.
  **IGFX**: Setzt die integrierte Grafikeinheit als erstes Display.
  **PCIe 1 Slot**: Setzt die Grafikkarte im PCIEX16 Slot als erstes Display.
  **PCIe 2 Slot**: Setzt die Grafikkarte im PCIEX8 Slot als erstes Display.
  **PCIe 3 Slot**: Setzt die Grafikkarte im PCIEX4 Slot als erstes Display.

### Internal Graphics

Aktiviert oder deaktiviert die integrierte Grafikfunktion.

### DVMT Pre Allocated

Ermöglicht es Ihnen, die Speichermenge der integrierten Grafikeinheit festzulegen.

### Aperture Size

Ermöglicht es Ihnen, die maximale Menge an Systemspeicher festzulegen, die der Grafikkarte zugewiesen werden kann.Optionen sind: 128MB, 256MB, 512MB, 1024MB und 1024MB.

### PCIE Bifurcation Support

Ermöglicht es Ihnen festzulegen, wie die Bandbreite des PCIEX16 Slots aufgeteilt wird.

### OnBoard LAN Controller

Aktiviert oder deaktiviert die Onboard LAN Funktion.Wenn Sie stattdessen eine Netzwerkkarte eines Drittanbieters installieren möchten, setzen Sie diesen Punkt auf Deaktiviert.

### OnBoard LAN Controller#2

Aktiviert oder deaktiviert die Onboard LAN Funktion.Wenn Sie stattdessen eine Netzwerkkarte eines Drittanbieters installieren möchten, setzen Sie diesen Punkt auf Deaktiviert.

### Audio Controller

Aktiviert oder deaktiviert die Onboard Audio Funktion.Wenn Sie stattdessen eine Audiokarte eines Drittanbieters installieren möchten, setzen Sie diesen Punkt auf Deaktiviert.

### Above 4G Decoding

Aktiviert oder deaktiviert die Dekodierung von 64 Bit fähigen Geräten im Adressraum über 4 GB (nur wenn Ihr System 64 Bit PCI Dekodierung unterstützt).Setzen Sie diesen Punkt auf Aktiviert, wenn mehr als eine fortgeschrittene Grafikkarte installiert ist und deren Treiber beim Starten des Betriebssystems nicht geladen werden können (aufgrund des begrenzten 4 GB Speicheradressraums).

### Re Size BAR Support

Aktiviert oder deaktiviert die Unterstützung für Resizable BAR.

## IO Ports

### IOAPIC 24 119 Entries

Aktiviert oder deaktiviert diese Funktion.

### Super IO Configuration

### Serial Port

Aktiviert oder deaktiviert den Onboard Seriellen Port.

### Parallel Port

Aktiviert oder deaktiviert den Onboard Parallelen Port.

## Gigabyte Utilities Downloader Configuration

Ermöglicht es Ihnen festzulegen, ob das GIGABYTE Control Center nach dem Start des Betriebssystems automatisch heruntergeladen und installiert werden soll.Stellen Sie vor der Installation sicher, dass das System mit dem Internet verbunden ist.

### Thunderbolt(TM) Configuration

Dieses Untermenü bietet Thunderbolt bezogene Konfigurationsoptionen.Dieses Untermenü erscheint nur auf Motherboards, die über einen integrierten Intel® Thunderbolt™ Controller verfügen oder auf denen eine GIGABYTE Thunderbolt™ Erweiterungskarte installiert ist.

### PCIE Tunneling over USB4

Aktiviert oder deaktiviert PCIe Tunneling über USB4.

### Wake up from Thunderbolt(TM) Devices

Ermöglicht es dem System, von Thunderbolt™ Geräten aufgeweckt zu werden.

## USB Configuration

### Legacy USB Support

Ermöglicht die Verwendung von USB Tastatur/Maus in MS DOS.

### XHCI Hand off

Bestimmt, ob die XHCI Hand off Funktion für ein Betriebssystem ohne XHCI Hand off Unterstützung aktiviert werden soll.

### USB Mass Storage Driver Support

Aktiviert oder deaktiviert die Unterstützung für USB Speichergeräte.

### Port 60/64 Emulation

Aktiviert oder deaktiviert die Unterstützung für USB Speichergeräte.

### Mass Storage Devices

Zeigt eine Liste der angeschlossenen USB Speichergeräte an.Dieser Punkt erscheint nur, wenn ein USB Speichergerät installiert ist.

## Network Stack Configuration

### Network Stack

Deaktiviert oder aktiviert das Booten vom Netzwerk, um ein GPT Format Betriebssystem zu installieren, wie z.B.die Installation des Betriebssystems vom Windows Deployment Services Server.

### IPv4 PXE Support

Aktiviert oder deaktiviert IPv4 PXE Unterstützung.Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist.

### IPv4 HTTP Support

Aktiviert oder deaktiviert HTTP Boot Unterstützung für IPv4.Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist.

### IPv6 PXE Support

Aktiviert oder deaktiviert IPv6 PXE Unterstützung.Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist.

### IPv6 HTTP Support

Aktiviert oder deaktiviert HTTP Boot Unterstützung für IPv6.Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist.

### PXE boot wait time

Ermöglicht es Ihnen festzulegen, wie lange Sie warten müssen, bevor Sie (Esc) drücken können, um den PXE Bootvorgang abzubrechen.Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist.

### Media detect count

Ermöglicht es Ihnen, die Anzahl der Überprüfungen des Vorhandenseins von Medien festzulegen.Dieser Punkt ist nur konfigurierbar, wenn der Netzwerk Stack aktiviert ist.

### NVMe Configuration

Zeigt Informationen über Ihre installierte M.2 NVMe PCIe SSD an.

## SATA Configuration

Aktiviert oder deaktiviert die integrierten SATA Controller.

### Aggressive LPM Support

Aktiviert oder deaktiviert die Energiesparfunktion, ALPM (Aggressive Link Power Management), für die Chipsatz SATA Controller.

### Port

Aktiviert oder deaktiviert jeden SATA Port.

### SATA Port DevSlp

Ermöglicht es Ihnen festzulegen, ob das angeschlossene SATA Gerät in den Schlafmodus wechseln soll.

### Hot plug

Aktiviert oder deaktiviert die Hot Plug Funktion für jeden SATA Port.

### Configured as eSATA

Aktiviert oder deaktiviert die Unterstützung für externe SATA Geräte.

### VMD setup menu

Ermöglicht es Ihnen, die VMD Controller zu konfigurieren.Um RAID Konfigurationen zu erstellen, setzen Sie den VMD Controller auf Aktiviert und setzen Sie die globale VMD Zuordnung auf Deaktiviert.Je nach verwendeten SATA/M.2 Anschlüssen setzen Sie den entsprechenden Punkt "Diesen Root Port unter VMD zuordnen" auf Aktiviert.Bitte navigieren Sie zur Seite "Erstellen eines RAID Sets" auf der GIGABYTE Website für Anweisungen zur Konfiguration eines RAID Arrays.

### Ethernet Controller / PCIe GBE Family Controller

Dieses Untermenü bietet Informationen zur LAN Konfiguration und zugehörigen Konfigurationsoptionen.

### LEDs im eingeschalteten Zustand des Systems

Ermöglicht es Ihnen, die LED Beleuchtung des Motherboards zu aktivieren oder zu deaktivieren, wenn das System eingeschaltet ist.
  **Aus**: Deaktiviert den ausgewählten Beleuchtungsmodus, wenn das System eingeschaltet ist.
  **Ein**: Aktiviert den ausgewählten Beleuchtungsmodus, wenn das System eingeschaltet ist.

### LEDs im Schlaf , Ruhezustand und Soft Off Zustand

Ermöglicht es Ihnen, den Beleuchtungsmodus der Motherboard LEDs im Systemzustand S3/S4/S5 festzulegen.Dieser Punkt ist konfigurierbar, wenn LEDs im eingeschalteten Zustand des Systems auf Ein gesetzt sind.
  **Aus**: Deaktiviert den ausgewählten Beleuchtungsmodus, wenn das System in den S3/S4/S5 Zustand wechselt.
  **Ein**: Aktiviert den ausgewählten Beleuchtungsmodus, wenn das System in den S3/S4/S5 Zustand wechselt.

### RST_SW (MULTIKEY) (Funktion der RST_SW Taste)

  **Taste auf HW Reset setzen**: Verwenden Sie die Taste, um Ihr System zurückzusetzen.
  **Taste zum Ein /Ausschalten der LEDs verwenden**: Verwenden Sie die Taste, um die LEDs des Motherboards ein  oder auszuschalten.
  **Taste zum Aufrufen des BIOS Setups verwenden**: Verwenden Sie die Taste, um das BIOS Setup aufzurufen.
  **Taste zum Starten im abgesicherten Modus verwenden**: Verwenden Sie die Taste, um das System im abgesicherten Modus zu starten.

### GEN5 Redriver SIPO Mode

Aktiviert oder deaktiviert den GEN5 Redriver SIPO Mode.

### GEN5 Equalization

Ermöglicht es Ihnen, den GEN5 Equalizer Wert anzupassen.

### GEN5 DC Gain

Ermöglicht es Ihnen, den GEN5 DC Verstärkungswert anzupassen.

### Onboard DB Port LED

Ermöglicht es Ihnen, die LED Beleuchtung der Debug LEDs des Motherboards zu aktivieren oder zu deaktivieren, wenn das System eingeschaltet ist.

### Intel Platform Trust Technology (PTT)

Aktiviert oder deaktiviert die Intel® PTT Technologie.

### 3DMark01 Enhancement

Ermöglicht es Ihnen festzulegen, ob einige ältere Benchmark Leistungen verbessert werden sollen.

### CPU PCIe Link Speed

Ermöglicht es Ihnen, den Betriebsmodus der CPU gesteuerten PCI Express Slots festzulegen.Der tatsächliche Betriebsmodus hängt von den Hardwarespezifikationen jedes Slots ab.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

## Verschiedenes

### PCH PCIe Link Speed

Ermöglicht es Ihnen, den Betriebsmodus der Chipsatz gesteuerten PCI Express Slots festzulegen.Der tatsächliche Betriebsmodus hängt von den Hardwarespezifikationen jedes Slots ab.Auto lässt das BIOS diese Einstellung automatisch konfigurieren.

### VT d

Aktiviert oder deaktiviert die Intel® Virtualization Technology für Directed I/O.

### Trusted Computing

Aktiviert oder deaktiviert das Trusted Platform Module (TPM).

### Option Search (Hot Key: Alt F)

Dieser Bildschirm ermöglicht es Ihnen, Stichwörter (nur Englisch) einzugeben, um die gesuchte BIOS Option zu finden.Drücken Sie (Alt) und (F), um den Optionssuchbildschirm aufzurufen.Geben Sie die Stichwörter in das Suchfeld ein und drücken Sie (Enter) oder klicken Sie auf Suchen.

### Reset Case Open Status

  **Deaktiviert**: Behält oder löscht den Eintrag des vorherigen Gehäuseeinbruchstatus.
  **Aktiviert**: Löscht den Eintrag des vorherigen Gehäuseeinbruchstatus und das Feld "Case Open" zeigt beim nächsten Start "No" an.

### Case Open

Zeigt den Erkennungsstatus des am CI Anschluss des Motherboards angeschlossenen Gehäuseeinbrucherkennungsgeräts an.Wenn die Gehäuseabdeckung des Systems entfernt wird, zeigt dieses Feld "Yes" an, andernfalls "No".Um den Gehäuseeinbruchstatus zu löschen, setzen Sie "Reset Case Open Status" auf Aktiviert, speichern Sie die Einstellungen im CMOS und starten Sie dann Ihr System neu.

### CPU Vcore/CPU VCCIN AUX/CPU VCCSA/VDD2 CPU/PCH1.8V/+3.3V/+5V/PCH 0.82V/+12V/CPU VAXG

Zeigt die aktuellen Systemspannungen an.Die angezeigten Punkte und Werte können je nach Chipsatz des Motherboards und der verwendeten CPU variieren.

## PC Gesundheitsstatus

### Systeminformationen

Dieser Abschnitt bietet Informationen über Ihr Motherboard Modell und die BIOS Version.Sie können auch die Standardsprache des BIOS auswählen und die Systemzeit manuell einstellen.

### Access Level

Zeigt den aktuellen Zugriffsebenenstatus an, abhängig von der verwendeten Passwortschutzart.(Wenn kein Passwort festgelegt ist, wird standardmäßig Administrator angezeigt.) Die Administrator Ebene ermöglicht es Ihnen, Änderungen an allen BIOS Einstellungen vorzunehmen; die Benutzerebene erlaubt nur Änderungen an bestimmten BIOS Einstellungen.

### System Language

Wählt die Standardsprache, die vom BIOS verwendet wird.

### System Date

Stellt das Systemdatum ein.Das Datumsformat ist Woche (schreibgeschützt), Monat, Datum und Jahr.Verwenden Sie (Enter), um zwischen den Feldern Monat, Datum und Jahr zu wechseln und verwenden Sie die (Page Up) oder (Page Down) Taste, um den gewünschten Wert einzustellen.

### System Time

Stellt die Systemzeit ein.Das Zeitformat ist Stunde, Minute und Sekunde.Zum Beispiel, 13:00:00 für 1 Uhr nachmittags.Verwenden Sie (Enter), um zwischen den Feldern Stunde, Minute und Sekunde zu wechseln und verwenden Sie die (Page Up) oder (Page Down) Taste, um den gewünschten Wert einzustellen.

### Plug in Devices Info

Zeigt Informationen über Ihre installierten PCI Express  und M.2 Geräte an.

### Q Flash

Ermöglicht den Zugriff auf das Q Flash Dienstprogramm, um das BIOS zu aktualisieren oder die aktuelle BIOS Konfiguration zu sichern.

## Boot

### Bootup NumLock State

Aktiviert oder deaktiviert die Numlock Funktion auf dem numerischen Tastenfeld der Tastatur nach dem POST.

### CFG Lock

Aktiviert oder deaktiviert die MSR 0xE2 Funktion.

### Security Option

Legt fest, ob bei jedem Systemstart ein Passwort erforderlich ist oder nur beim Aufrufen des BIOS Setups.Nach dem Konfigurieren dieses Punktes setzen Sie das/die Passwort(e) unter Administrator Passwort/Benutzer Passwort.
  **Setup**: Ein Passwort ist nur zum Aufrufen des BIOS Setup Programms erforderlich.
  **System**: Ein Passwort ist für den Systemstart und das Aufrufen des BIOS Setup Programms erforderlich.

### Full Screen LOGO Show

Ermöglicht es Ihnen festzulegen, ob das GIGABYTE Logo beim Systemstart angezeigt wird.Deaktiviert überspringt das GIGABYTE Logo beim Systemstart.

### Boot Option Priorities

Legt die allgemeine Startreihenfolge der verfügbaren Geräte fest.Wechselmedien, die das GPT Format unterstützen, werden in der Startgeräteliste mit dem Präfix "UEFI:" angezeigt.Um von einem Betriebssystem zu starten, das die GPT Partitionierung unterstützt, wählen Sie das Gerät mit dem Präfix "UEFI:".
Oder wenn Sie ein Betriebssystem installieren möchten, das die GPT Partitionierung unterstützt, wie Windows 11 64 Bit, wählen Sie das optische Laufwerk, das die Windows 11 64 Bit Installationsdiskette enthält und das Präfix "UEFI:" hat.

### Fast Boot

Aktiviert oder deaktiviert das schnelle Booten, um den Betriebssystem Startvorgang zu verkürzen.Ultra Fast bietet die schnellste Startgeschwindigkeit.

### SATA Support

  **Letzter Boot SATA Devices Only**: Außer dem vorherigen Boot Laufwerk sind alle SATA Geräte deaktiviert, bevor der OS Bootvorgang abgeschlossen ist.
  **Alle SATA Devices**: Alle SATA Geräte sind im Betriebssystem und während des POST funktionsfähig.Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf aktiviert oder Ultra Fast gesetzt ist.

### VGA Unterstützung

Ermöglicht es Ihnen auszuwählen, welches Betriebssystem gestartet werden soll.
  **Auto**: Aktiviert nur das Legacy Option ROM.
  **EFI Treiber**: Aktiviert das EFI Option ROM.
Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf Aktiviert oder Ultra Fast gesetzt ist.

### USB Unterstützung

  **Disable Link**: Alle USB Geräte sind deaktiviert, bevor der OS Startvorgang abgeschlossen ist.
  **Full Initial**: Alle USB Geräte sind im Betriebssystem und während des POST funktionsfähig.
  **Partial Initial**: Einige USB Geräte sind deaktiviert, bevor der OS Startvorgang abgeschlossen ist.
Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf Aktiviert oder Ultra Fast gesetzt ist.Diese Funktion ist deaktiviert, wenn Fast Boot auf Ultra Fast gesetzt ist.

### Netzwerk Stack Treiberunterstützung

  **Disable Link**: Deaktiviert das Booten vom Netzwerk.
  **Enabled**: Aktiviert das Booten vom Netzwerk.
Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf Aktiviert oder Ultra Fast gesetzt ist.

### Nächster Start nach AC Stromausfall

  **Normal Boot**: Aktiviert den normalen Start beim Zurückkehren der Netzspannung.
  **Fast Boot**: Beibehaltung der Fast Boot Einstellungen beim Zurückkehren der Netzspannung.
Dieser Punkt ist nur konfigurierbar, wenn Fast Boot auf Aktiviert oder Ultra Fast gesetzt ist.

### Mausgeschwindigkeit

Ermöglicht es Ihnen, die Bewegungsgeschwindigkeit des Mauszeigers festzulegen.

### Windows 10 Funktionen

Ermöglicht es Ihnen, das zu installierende Betriebssystem auszuwählen.

### CSM Unterstützung

Aktiviert oder deaktiviert das UEFI CSM (Compatibility Support Module), um einen Legacy PC Boot Vorgang zu unterstützen.
  **Disabled**: Deaktiviert das UEFI CSM und unterstützt nur den UEFI BIOS Boot Vorgang.
  **Enabled**: Aktiviert das UEFI CSM.

### LAN PXE Boot Option ROM

Ermöglicht es Ihnen auszuwählen, ob das Legacy Option ROM für den LAN Controller aktiviert werden soll.
Dieser Punkt ist nur konfigurierbar, wenn die CSM Unterstützung auf Enabled gesetzt ist.

### Speicher Boot Optionen Steuerung

Ermöglicht es Ihnen auszuwählen, ob das UEFI  oder Legacy Option ROM für den Speichergeräte Controller aktiviert werden soll.
  **Do not launch**: Deaktiviert das Option ROM.
  **UEFI**: Aktiviert nur das UEFI Option ROM.
  **Legacy**: Aktiviert nur das Legacy Option ROM.
Dieser Punkt ist nur konfigurierbar, wenn die CSM Unterstützung auf Enabled gesetzt ist.

### Andere PCI Geräte

Ermöglicht es Ihnen auszuwählen, ob das UEFI  oder Legacy Option ROM für den PCI Geräte Controller außer LAN, Speichergerät und Grafikkarten Controller aktiviert werden soll.
  **Do not launch**: Deaktiviert das Option ROM.
  **UEFI**: Aktiviert nur das UEFI Option ROM.
  **Legacy**: Aktiviert nur das Legacy Option ROM.
Dieser Punkt ist nur konfigurierbar, wenn die CSM Unterstützung auf Enabled gesetzt ist.

### Administrator Passwort

Ermöglicht es Ihnen, ein Administrator Passwort zu konfigurieren.Drücken Sie (Enter) auf diesem Punkt, geben Sie das Passwort ein und drücken Sie dann (Enter).Sie werden aufgefordert, das Passwort zu bestätigen.Geben Sie das Passwort erneut ein und drücken Sie (Enter).Sie müssen das Administrator Passwort (oder das Benutzer Passwort) beim Systemstart und beim Aufrufen des BIOS Setups eingeben.Das Administrator Passwort ermöglicht Ihnen im Gegensatz zum Benutzer Passwort, Änderungen an allen BIOS Einstellungen vorzunehmen.Passwort entfernen altes Administrator Passwort eingeben und neues leer lassen.

### Benutzer Passwort

Ermöglicht es Ihnen, ein Benutzer Passwort zu konfigurieren.Drücken Sie (Enter) auf diesem Punkt, geben Sie das Passwort ein und drücken Sie dann (Enter).Sie werden aufgefordert, das Passwort zu bestätigen.Geben Sie das Passwort erneut ein und drücken Sie (Enter).Sie müssen das Administrator Passwort (oder das Benutzer Passwort) beim Systemstart und beim Aufrufen des BIOS Setups eingeben.Das Benutzer Passwort ermöglicht jedoch nur Änderungen an bestimmten BIOS Einstellungen, nicht an allen.Um das Passwort zu löschen, drücken Sie (Enter) auf dem Passwortfeld und geben das korrekte Passwort ein, wenn Sie dazu aufgefordert werden.Wenn Sie zur Eingabe eines neuen Passworts aufgefordert werden, drücken Sie (Enter), ohne ein Passwort einzugeben.Drücken Sie erneut (Enter), um zu bestätigen.
Hinweis: Stellen Sie sicher, dass das Administrator Passwort zuerst festgelegt wird, bevor Sie das Benutzer Passwort festlegen.Passwort entfernen altes Benutzer Passwort eingeben und neues leer lassen.

### Secure Boot

Ermöglicht es Ihnen, Secure Boot zu aktivieren oder zu deaktivieren und verwandte Einstellungen zu konfigurieren.Dieser Punkt ist nur konfigurierbar, wenn die CSM Unterstützung auf Disabled gesetzt ist.

### Bevorzugter Betriebsmodus

Ermöglicht es Ihnen auszuwählen, ob Sie den einfachen Modus oder den erweiterten Modus nach dem Aufrufen des BIOS Setups betreten.Auto wechselt zu dem Modus, der zuletzt verwendet wurde.

### Speichern # Beenden

  **Save # Exit Setup**: Drücken Sie (Enter) auf diesem Punkt und wählen Sie Ja.Dadurch werden die Änderungen im CMOS gespeichert und das BIOS Setup Programm verlassen.Wählen Sie Nein oder drücken Sie (Esc), um zum Hauptmenü des BIOS Setups zurückzukehren.
  **Exit Without Saving**: Drücken Sie (Enter) auf diesem Punkt und wählen Sie Ja.Dadurch wird das BIOS Setup Programm ohne Speichern der vorgenommenen Änderungen im CMOS verlassen.Wählen Sie Nein oder drücken Sie (Esc), um zum Hauptmenü des BIOS Setups zurückzukehren.
  **Load Optimized Defaults**: Drücken Sie (Enter) auf diesem Punkt und wählen Sie Ja, um die optimalen BIOS Standardeinstellungen zu laden.Die BIOS Standardeinstellungen helfen dem System, im optimalen Zustand zu arbeiten.Laden Sie immer die optimierten Standardeinstellungen nach dem Aktualisieren des BIOS oder nach dem Löschen der CMOS Werte.
  **Boot Override**: Ermöglicht es Ihnen, ein Gerät auszuwählen, von dem sofort gebootet werden soll.Drücken Sie (Enter) auf dem ausgewählten Gerät und wählen Sie Ja zur Bestätigung.Ihr System wird automatisch neu gestartet und von diesem Gerät gebootet.
  **Save Profiles**: Diese Funktion ermöglicht es Ihnen, die aktuellen BIOS Einstellungen in einem Profil zu speichern.Sie können bis zu 8 Profile erstellen und als Setup Profil 1 bis Setup Profil 8 speichern.Drücken Sie (Enter), um abzuschließen.Oder Sie können "Datei auswählen in HDD/FDD/USB" auswählen, um das Profil auf Ihrem Speichermedium zu speichern.
  **Load Profiles**: Wenn Ihr System instabil wird und Sie die BIOS Standardeinstellungen geladen haben, können Sie diese Funktion verwenden, um die BIOS Einstellungen aus einem zuvor erstellten Profil zu laden, ohne die BIOS Einstellungen erneut konfigurieren zu müssen.Wählen Sie zuerst das Profil aus, das Sie laden möchten, und drücken Sie dann (Enter), um abzuschließen.Sie können "Datei auswählen in HDD/FDD/USB" wählen, um das zuvor erstellte Profil von Ihrem Speichermedium zu laden oder das Profil automatisch zu laden, das von dem BIOS erstellt wurde, z.B.das Zurücksetzen der BIOS Einstellungen auf die letzten Einstellungen, die ordnungsgemäß funktioniert haben (bekanntermaßen guter Zustand).

## Diverse Windows Funktionen

* Festplatten von gpt oder mbr ändern.

Bei der Installation von Windows 11 die Festplatten ändern.
Nach starten der Installations DVD die Umschalttaste und F10 drücken.
Es öffnet sich eine Konsole
diskpart   startet Festplattentool
list disk   listet Festplatten auf.
select disc 0 oder 1   je nachdem welche Festplatte ausgewählt werden soll.
clean   für löschen.
convert gpt oder mbr   je nachdem was benötigt wird.
// Dies muss für alle Festplatten einzeln gemacht werden, die geändert werden sollen oder müssen.//
exit   Ende und Konsolenfenster schließen.
Dann normal die Installation weitermachen.

## Prozessorlast Verteilung einstellen

* Folgendes ist Windows ab 8.1 geprüft
* Windows Taste und R dann nacheinander eingeben
cmd
ab win 10 hier weiter machen
msconfig
* Im nächsten Fenster auswählen
Start
erweiterte Optionen
* dann die ferfügbaren Core (Prozessorkerne) einstellen.

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
"Minimaler Leistungszustand des Prozessors" auf "70%" stellen mindestens aber 51% um flüssig arbeiten zu können.

## Passwort abschalten

Drücken Sie auf Ihrer Tastatur gleichzeitig die Windows Taste und R.
netplwiz eingeben
Benutzer müssen Benutzernamen und Kennwort eingeben: dort den Haken weg machen

Das funktioniert bei Windows 11 nicht.

## Windows ab 8 ohne Datenverlust reparieren

* Windows Konsole starten als Administrator mit Win + X  - Eingabeaufforderung Administrator.
* Fehler suchen und Reparieren
    sfc /scannow
* Nur Fehler suchen
    sfc /ferifyonly

## Image auf Komponentenspeicherbeschädigungen durchsuchen und Reparieren

* Windows Konsole starten als Administrator mit Win + X  - Eingabeaufforderung Administrator.

## auf Komponentenspeicherbeschädigungen durchsuchen

Dism /Online /Cleanup Image /ScanHealth

## Image reparieren

Dism /Online /Cleanup Image / RestoreHealth

## Record Image Recimg Befehlsübersicht mit

recimg /?

## Image erstellen

recimg  /createimage d:\Refresh ; (Anstatt d:\Refresh kann auch anderer Ordnername gewählt werden)
