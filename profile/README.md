# AmbiBack

**Open-source DIY ambient backlighting for TVs and monitors.** AmbiBack combines ESP32 firmware, camera and LED control, a bridge from DreamScreen to Philips Hue, Android apps, a Windows client and USB flashers for Windows and the browser.

[Project website](https://www.ambiback.de/) · [Deutsch](#deutsch)

> **Status:** AmbiBack devices have not been on sale for around five years. This is a DIY and open-source project, with no product support. The code was migrated to this organization in November 2026. The migrated state has not been tested with real hardware. All 13 firmware device types compile with the public Arduino ESP32 core 3.3.6.

## Projects

### Firmware and device

| Repository | What it is | Current state |
| --- | --- | --- |
| [ambiback-firmware](https://github.com/ambiback/ambiback-firmware) | ESP32 firmware for LEDs, camera, DreamScreen, Hue and network clients | All 13 device types compile with core 3.3.6, not tested on hardware |
| [ambiback-ui](https://github.com/ambiback/ambiback-ui) | React web interface for the device API | [Published on GitHub Pages](https://ambiback.github.io/ambiback-ui/), not tested against a real device |

### Install firmware

| Repository | What it is | Current state |
| --- | --- | --- |
| [ambiback-web-flasher](https://github.com/ambiback/ambiback-web-flasher) | **New:** browser-based USB flasher, serial monitor and crash decoder for AmbiBack ESP32 devices (Chrome, Edge or Opera) | In progress, [first version under review](https://github.com/ambiback/ambiback-web-flasher/pull/1); will be at [ambiback.github.io/ambiback-web-flasher](https://ambiback.github.io/ambiback-web-flasher/), not tested with hardware |
| [ambiback-flasher](https://github.com/ambiback/ambiback-flasher) | Windows tool to build, flash and upload firmware and control a device over USB | [Release v1.0.0](https://github.com/ambiback/ambiback-flasher/releases/tag/v1.0.0) with installer and [user guide](https://github.com/ambiback/ambiback-flasher/blob/main/docs/user-guide.md), not tested with hardware |

### Apps

| Repository | What it is | Current state |
| --- | --- | --- |
| [ambiback-manager](https://github.com/ambiback/ambiback-manager) | Android app for device setup and control | Build and unit tests pass, not tested on a real device |
| [ambiback-pc](https://github.com/ambiback/ambiback-pc) | Windows client that captures the screen and sends colors to AmbiBack and Philips Hue | Release build passes, new [user guide](https://github.com/ambiback/ambiback-pc/blob/main/docs/user-guide.md) in English and German, full app not tested with hardware |

### Hardware and legacy

| Repository | What it is | Current state |
| --- | --- | --- |
| [ambiback-hardware](https://github.com/ambiback/ambiback-hardware) | KiCad and Gerber files for the LED controller PCB | Prototype, not tested with the current firmware |
| [ambiback-tv-legacy](https://github.com/ambiback/ambiback-tv-legacy) | Former Android TV app | Archived, not rebuilt |

## Hardware

The v0r1 LED controller PCB for the M5Stack Atom Lite was designed by [Andreas "Andy" Hofmann](https://github.com/ezcGman). It is a prototype, so review the design before ordering boards. The KiCad project, Gerber files and renderings are in [ambiback-hardware](https://github.com/ambiback/ambiback-hardware) under CC BY-NC-SA 4.0.

## History

AmbiBack began in 2019/2020 as an independent development. DreamScreen had previously been distributed and supported in Germany, until that came to an abrupt end in late 2019. This led to the idea of a camera-based system, which was built from 2020 to 2021. Oliver Kohlgraf of Tele-Kohlgraf provided major support and contributed ideas. The entire implementation is by Andre Lorbach.

The AmbiBack Bridge was sold for a short time as an interim solution for DreamScreen owners. The camera and PC versions remained prototypes.

## License

The software projects are licensed under the GNU GPL v3. The PCB data in ambiback-hardware is licensed under CC BY-NC-SA 4.0. Third-party code keeps its own license, as noted in each repository.

Philips Hue and DreamScreen are trademarks of their respective owners. This project is not affiliated with them.

---

## Deutsch

**Open-Source-Hintergrundbeleuchtung zum Selberbauen für Fernseher und Monitore.** AmbiBack verbindet ESP32-Firmware, Kamera- und LED-Steuerung, eine Bridge von DreamScreen zu Philips Hue, Android-Apps, einen Windows-Client und USB-Flasher für Windows und den Browser.

> **Status:** AmbiBack-Geräte werden seit rund fünf Jahren nicht mehr verkauft. AmbiBack ist heute ein DIY- und Open-Source-Projekt ohne Produktsupport. Der Code wurde im November 2026 in diese Organisation migriert. Der migrierte Stand wurde nicht mit echter Hardware getestet. Alle 13 Gerätetypen der Firmware bauen mit dem öffentlichen Arduino-ESP32-Core 3.3.6.

### Projekte

#### Firmware und Gerät

| Repository | Was es ist | Aktueller Stand |
| --- | --- | --- |
| [ambiback-firmware](https://github.com/ambiback/ambiback-firmware) | ESP32-Firmware für LEDs, Kamera, DreamScreen, Hue und Netzwerk-Clients | Alle 13 Gerätetypen bauen mit Core 3.3.6, nicht auf Hardware getestet |
| [ambiback-ui](https://github.com/ambiback/ambiback-ui) | React-Weboberfläche für die Geräte-API | [Auf GitHub Pages veröffentlicht](https://ambiback.github.io/ambiback-ui/), nicht mit echtem Gerät getestet |

#### Firmware installieren

| Repository | Was es ist | Aktueller Stand |
| --- | --- | --- |
| [ambiback-web-flasher](https://github.com/ambiback/ambiback-web-flasher) | **Neu:** USB-Flasher im Browser mit seriellem Monitor und Absturz-Decoder für AmbiBack-ESP32-Geräte (Chrome, Edge oder Opera) | In Arbeit, [erste Version im Review](https://github.com/ambiback/ambiback-web-flasher/pull/1); künftig unter [ambiback.github.io/ambiback-web-flasher](https://ambiback.github.io/ambiback-web-flasher/), nicht mit Hardware getestet |
| [ambiback-flasher](https://github.com/ambiback/ambiback-flasher) | Windows-Tool zum Bauen, Flashen und Hochladen der Firmware und zur Gerätesteuerung über USB | [Release v1.0.0](https://github.com/ambiback/ambiback-flasher/releases/tag/v1.0.0) mit Installer und [Benutzerhandbuch](https://github.com/ambiback/ambiback-flasher/blob/main/docs/user-guide.de.md), nicht mit Hardware getestet |

#### Apps

| Repository | Was es ist | Aktueller Stand |
| --- | --- | --- |
| [ambiback-manager](https://github.com/ambiback/ambiback-manager) | Android-App zum Einrichten und Steuern | Build und Unit-Tests erfolgreich, nicht auf echtem Gerät getestet |
| [ambiback-pc](https://github.com/ambiback/ambiback-pc) | Windows-Client, der den Bildschirm erfasst und Farben an AmbiBack und Philips Hue sendet | Release-Build erfolgreich, neues [Benutzerhandbuch](https://github.com/ambiback/ambiback-pc/blob/main/docs/benutzerhandbuch.md) auf Deutsch und Englisch, Gesamt-App nicht mit Hardware getestet |

#### Hardware und Altbestand

| Repository | Was es ist | Aktueller Stand |
| --- | --- | --- |
| [ambiback-hardware](https://github.com/ambiback/ambiback-hardware) | KiCad- und Gerber-Dateien der LED-Controller-Platine | Prototyp, nicht mit aktueller Firmware getestet |
| [ambiback-tv-legacy](https://github.com/ambiback/ambiback-tv-legacy) | Frühere Android-TV-App | Archiviert, nicht neu gebaut |

### Hardware

Die Platine v0r1 für den LED-Controller mit M5Stack Atom Lite stammt von [Andreas „Andy“ Hofmann](https://github.com/ezcGman). Sie ist ein Prototyp, prüfe den Entwurf daher, bevor du Platinen bestellst. KiCad-Projekt, Gerber-Dateien und Renderings liegen in [ambiback-hardware](https://github.com/ambiback/ambiback-hardware) unter CC BY-NC-SA 4.0.

### Geschichte

AmbiBack begann 2019/2020 als eigene Entwicklung. Zuvor wurde DreamScreen in Deutschland vertrieben und betreut, bis das Ende 2019 abrupt endete. Daraus entstand die Idee eines kamerabetriebenen Systems, das von 2020 bis 2021 umgesetzt wurde. Oliver Kohlgraf von Tele-Kohlgraf hat das Projekt maßgeblich unterstützt und war an den Ideen beteiligt. Die gesamte Umsetzung stammt von Andre Lorbach.

Die AmbiBack Bridge wurde kurze Zeit als Zwischenlösung für DreamScreen-Besitzer verkauft. Die Kamera- und die PC-Version blieben Prototypen.

### Lizenz

Die Softwareprojekte stehen unter der GNU GPL v3. Die Platinendaten in ambiback-hardware stehen unter CC BY-NC-SA 4.0. Drittcode behält seine eigene Lizenz, siehe die einzelnen Repositories.

Philips Hue und DreamScreen sind Marken ihrer jeweiligen Inhaber. Dieses Projekt steht in keiner Verbindung zu ihnen.
