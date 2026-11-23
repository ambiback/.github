# AmbiBack

**Open-source DIY ambient backlighting for TVs and monitors.** AmbiBack combines ESP32 firmware, camera and LED control, a bridge from DreamScreen to Philips Hue, Android apps and a Windows client.

[Project website](https://www.ambiback.de/) · [Deutsch](#deutsch)

> **Status:** AmbiBack devices have not been on sale for around five years. This is a DIY and open-source project, with no product support. The code was migrated to this organization in November 2026. The migrated state has not been tested with real hardware, and the firmware has not been compiled since the migration changes.

## Projects

| Repository | What it is | Current state |
| --- | --- | --- |
| [ambiback-firmware](https://github.com/ambiback/ambiback-firmware) | ESP32 firmware for LEDs, camera, DreamScreen, Hue and network clients | Not compiled since the migration |
| [ambiback-ui](https://github.com/ambiback/ambiback-ui) | React web interface for the device API | [Published on GitHub Pages](https://ambiback.github.io/ambiback-ui/), not tested against a real device |
| [ambiback-manager](https://github.com/ambiback/ambiback-manager) | Android app for device setup and control | Build and unit tests pass, not tested on a real device |
| [ambiback-pc](https://github.com/ambiback/ambiback-pc) | Windows client that captures the screen and sends colors | Release build passes, full app not run |
| [ambiback-tv-legacy](https://github.com/ambiback/ambiback-tv-legacy) | Former Android TV app | Archived, not rebuilt |

## History

AmbiBack began in 2019/2020 as an independent development. DreamScreen had previously been distributed and supported in Germany, until that came to an abrupt end in late 2019. This led to the idea of a camera-based system, which was built from 2020 to 2021. Oliver Kohlgraf of Tele-Kohlgraf provided major support and contributed ideas. The entire implementation is by Andre Lorbach.

The AmbiBack Bridge was sold for a short time as an interim solution for DreamScreen owners. The camera and PC versions remained prototypes.

## License

The projects are licensed under the GNU GPL v3. Third-party code keeps its own license, as noted in each repository.

Philips Hue and DreamScreen are trademarks of their respective owners. This project is not affiliated with them.

---

## Deutsch

**Open-Source-Ambilight zum Selberbauen für Fernseher und Monitore.** AmbiBack verbindet ESP32-Firmware, Kamera- und LED-Steuerung, eine Bridge von DreamScreen zu Philips Hue, Android-Apps und einen Windows-Client.

> **Status:** AmbiBack-Geräte werden seit rund fünf Jahren nicht mehr verkauft. AmbiBack ist heute ein DIY- und Open-Source-Projekt ohne Produktsupport. Der Code wurde im November 2026 in diese Organisation migriert. Der migrierte Stand wurde nicht mit echter Hardware getestet, und die Firmware wurde seit den Migrationsänderungen nicht kompiliert.

### Projekte

| Repository | Was es ist | Aktueller Stand |
| --- | --- | --- |
| [ambiback-firmware](https://github.com/ambiback/ambiback-firmware) | ESP32-Firmware für LEDs, Kamera, DreamScreen, Hue und Netzwerk-Clients | Seit der Migration nicht kompiliert |
| [ambiback-ui](https://github.com/ambiback/ambiback-ui) | React-Weboberfläche für die Geräte-API | [Auf GitHub Pages veröffentlicht](https://ambiback.github.io/ambiback-ui/), nicht mit echtem Gerät getestet |
| [ambiback-manager](https://github.com/ambiback/ambiback-manager) | Android-App zum Einrichten und Steuern | Build und Unit-Tests erfolgreich, nicht auf echtem Gerät getestet |
| [ambiback-pc](https://github.com/ambiback/ambiback-pc) | Windows-Client, der den Bildschirm erfasst und Farben sendet | Release-Build erfolgreich, Gesamt-App nicht gestartet |
| [ambiback-tv-legacy](https://github.com/ambiback/ambiback-tv-legacy) | Frühere Android-TV-App | Archiviert, nicht neu gebaut |

### Geschichte

AmbiBack begann 2019/2020 als eigene Entwicklung. Zuvor wurde DreamScreen in Deutschland vertrieben und betreut, bis das Ende 2019 abrupt endete. Daraus entstand die Idee eines kamerabetriebenen Systems, das von 2020 bis 2021 umgesetzt wurde. Oliver Kohlgraf von Tele-Kohlgraf hat das Projekt maßgeblich unterstützt und war an den Ideen beteiligt. Die gesamte Umsetzung stammt von Andre Lorbach.

Die AmbiBack Bridge wurde kurze Zeit als Zwischenlösung für DreamScreen-Besitzer verkauft. Die Kamera- und die PC-Version blieben Prototypen.

### Lizenz

Die Projekte stehen unter der GNU GPL v3. Drittcode behält seine eigene Lizenz, siehe die einzelnen Repositories.

Philips Hue und DreamScreen sind Marken ihrer jeweiligen Inhaber. Dieses Projekt steht in keiner Verbindung zu ihnen.
