# Awesome Open Source Hardware Projects

Dies ist eine kuratierte Sammlung von Open-Source-Hardware-Projekten oder für die Hardwareentwicklung relevante Open-Source-Software-Projekte.

Als Hardware sei jedes physische Ding verstanden werden, angefangen von elektronischen Schaltungen über Maschinen und Geräte hin zu Materialien.


[TOC]


## Kriterien

Die Projekte werden nach folgenden Kriterien ausgewählt:

- SPDX/FSF/OSI-konforme Lizenzierung
    - Keine "Non-Commercial"-Attribution
    - Lizenz muss beliebige Nutzung, Veränderung und **Weiterverbreitung** ermöglichen
- freier Zugang zu den Quelldateien, sofern diese existieren
    - alle in der Dokumentation ersichtlichen Komponenten sind min. in der dargestellten Form verfügbar
        - STL, STEP, etc sind keine Quellformate
        - SVG, z.B. für Schnittmuster, sofern diese nicht aus einem CAD-Modell abgeleitet wurden, ansonsten ist das CAD-Modell die Quelle
        - Bilder: JPG, PNG, ... bei Fotografien, Vektorgrafiken: SVG, o.a., ein Diagramm als JPG ist kein Quellformat
    - Quelldateien müssen gebündelt inkl. Lizenzdatei heruntergeladen werden können, i.F. eines Archivs oder als Repository vorliegen
        - ansonsten ist freie Nutzung und Weitergabe der Quelldateien nicht garantiert im Falle einer Lizenzänderung

optional:

- Konformität zur DIN-SPEC-3105
- verfügbar als Repository
- Dokumentation kann separat sein, z.B. als Wiki


## Projekte


### Elektronik


### Baukästen

- UniProKit
        ![UniProKit Tool Box](https://codeberg.org/case06/upklib_v2/raw/branch/master/toolbox/images/set_all.jpg)
    - Beschreibung:
        - Das Universal Prototyping Kit ist ein offenes Baukastensystem für Hardware mit bestimmten Designprinzipien sowie als FreeCAD-Bibliothek verfügbar
    - Lizenz: CC-BY-SA-4.0
    - Repository: [Codeberg](https://codeberg.org/case06/upklib_v2)



### Maschinen und Geräte


#### Fräsen

- Open Lab Starter Kit (OLSK)
    - OLSK Large CNC
            ![OLSK Large CNC V3](https://github.com/Open-Lab-Starter-Kit/OLSK-Large-CNC/raw/main/media/OLSK_Large_CNC_V2_1.jpg)
        - Beschreibung:
            - Großformat 3-Achs-CNC-Fräse mit 2500 x 1250 mm Arbeitsraum und automatischem Werkzeugwechselsystem
        - Lizenz:
            - Hardware (CAD, PCB, BOM, ...): CERN-OHL-W-2.0
            - Dokumentation (Anleitungen, Bilder, Videos, Präsentationen, Beschreibungen): CC-BY-SA-4.0
        - Repository: [GitHub](https://github.com/Open-Lab-Starter-Kit/OLSK-Large-CNC)
    - OLSK Small CNC
            ![OLSK Small CNC V3](https://github.com/Open-Lab-Starter-Kit/OLSK-Small-CNC/raw/main/media/OLSK_SmallCNC_V3_1.png)
        - Beschreibung:
            - Desktop 3-Achs-CNC-Fräse mit 400mm x 600mm x 150mm Arbeitsraum und automatischem Werkzeugwechselsystem
        - Lizenz:
            - Hardware (CAD, PCB, BOM, ...): CERN-OHL-W-2.0
            - Dokumentation (Anleitungen, Bilder, Videos, Präsentationen, Beschreibungen): CC-BY-SA-4.0
        - Repository: [GitHub](https://github.com/Open-Lab-Starter-Kit/OLSK-Small-CNC)
- MakersMill
        ![MakersMill](https://codeberg.org/case06/MakersMill/raw/branch/main/cadfiles/images/makersmill_v1.png)
    - Beschreibung:
        - Kleine Desktop 3-Achs-CNC-Fräse auf Basis des UniProKits
    - Lizenz: CC-BY-SA-4.0
    - Repository: [Codeberg](https://codeberg.org/case06/MakersMill)







#### 3D-Drucker

- Open Lab Starter Kit (OLSK)
    - OLSK Large 3D Printer
            ![OLSK Large 3D Printer V3](https://github.com/Open-Lab-Starter-Kit/OLSK-Large-3D-Printer/raw/main/media/OLSK_Large3DPrinter_V2_1.png)
        - Beschreibung:
            - Großformat 3D-Drucker mit 1000 x 1000 x 1300 mm Arbeitsraum
        - Lizenz:
            - Hardware (CAD, PCB, BOM, ...): CERN-OHL-W-2.0
            - Dokumentation (Anleitungen, Bilder, Videos, Präsentationen, Beschreibungen): CC-BY-SA-4.0
        - Repository: [GitHub](https://github.com/Open-Lab-Starter-Kit/OLSK-Large-3D-Printer)
    - OLSK Small 3D Printer
            ![OLSK Small 3D Printer V3](https://github.com/Open-Lab-Starter-Kit/OLSK-Small-3D-Printer/raw/main/media/OLSK_Small_3DPrinter_V3_1.png)
        - Beschreibung:
            - Desktop 3D-Drucker mit 235 x 235 x 235mm Arbeitsraum
        - Lizenz:
            - Hardware (CAD, PCB, BOM, ...): CERN-OHL-W-2.0
            - Dokumentation (Anleitungen, Bilder, Videos, Präsentationen, Beschreibungen): CC-BY-SA-4.0
        - Repository: [GitHub](https://github.com/Open-Lab-Starter-Kit/OLSK-Small-3D-Printer)
- MakersFriend
        ![MakersFriend](https://codeberg.org/case06/MakersFriend/raw/branch/main/doc/bom_src/images/rawimages/IMG_20210419_174207.jpg)
    - Beschreibung:
        - Desktop 3D-Drucker auf Basis des UniProKits
    - Lizenz: CC-BY-SA-4.0
    - Repository: [Codeberg](https://codeberg.org/case06/MakersFriend)


#### Lasercutter

- Open Lab Starter Kit (OLSK)
    - OLSK Large Laser
            ![OLSK Large Laser V3](https://github.com/Open-Lab-Starter-Kit/OLSK-Large-Laser/raw/main/media/OLSK_Large_Laser_V2_2.png)
        - Beschreibung:
            - Großformat Lasercutter mit 1000mm x 700mm Arbeitsraum und Werkzeugwechselsystem
        - Lizenz:
            - Hardware (CAD, PCB, BOM, ...): CERN-OHL-W-2.0
            - Dokumentation (Anleitungen, Bilder, Videos, Präsentationen, Beschreibungen): CC-BY-SA-4.0
        - Repository: [GitHub](https://github.com/Open-Lab-Starter-Kit/OLSK-Large-Laser)
    - OLSK Small Laser
            ![OLSK Small Laser V2](https://github.com/Open-Lab-Starter-Kit/OLSK-Small-Laser/raw/main/media/OLSK_Small_Laser_v2_Intro.jpg)
        - Beschreibung:
            - Lasercutter mit 600x400mm Arbeitsraum
        - Lizenz:
            - Hardware (CAD, PCB, BOM, ...): CERN-OHL-W-2.0
            - Dokumentation (Anleitungen, Bilder, Videos, Präsentationen, Beschreibungen): CC-BY-SA-4.0
        - Repository: [GitHub](https://github.com/Open-Lab-Starter-Kit/OLSK-Small-Laser)


#### Vinylcutter

- Open Lab Starter Kit (OLSK)
    - OLSK Vinyl Cutter
        ![OLSK Vinyl Cutter V3](https://github.com/Open-Lab-Starter-Kit/OLSK-Vinyl-Cutter/raw/main/media/OLSK_Vinyl_Cutter_V3_1.png)
        - Beschreibung:
            - Vinylcutter mit 300 mm Schneidbreite
        - Lizenz:
            - Hardware (CAD, PCB, BOM, ...): CERN-OHL-W-2.0
            - Dokumentation (Anleitungen, Bilder, Videos, Präsentationen, Beschreibungen): CC-BY-SA-4.0
        - Repository: [GitHub](https://github.com/Open-Lab-Starter-Kit/OLSK-Vinyl-Cutter)


#### 3D-Scanner

- Open Lab Starter Kit (OLSK)
    - OLSK 3D Scanner
        ![OLSK 3D Scanner V3](https://github.com/Open-Lab-Starter-Kit/OLSK-3D-Scanner/raw/main/media/OLSK_3DScanner_v3_1.png)
        - Beschreibung:
            - 3D Scanner mit Drehtisch und einer beweglichen Kamera
        - Lizenz:
            - Hardware (CAD, PCB, BOM, ...): CERN-OHL-W-2.0
            - Dokumentation (Anleitungen, Bilder, Videos, Präsentationen, Beschreibungen): CC-BY-SA-4.0
        - Repository: [GitHub](https://github.com/Open-Lab-Starter-Kit/OLSK-3D-Scanner)
- Ciclop
        ![Ciclop](https://github.com/bqlabs/ciclop/raw/master/doc/images/ciclop.jpg)
    - Beschreibung:
        - Kleiner 3D Scanner
    - Lizenz: CC-BY-SA-4.0
    - Repository: [GitHub](https://github.com/LibreScanner/ciclop)







### Materialien





### Software



## Projekte, die die Kriterien nicht vollständig erfüllen

### 3D-Scanner

- scAnt
        ![scAnt](https://github.com/evo-biomech/scAnt/raw/master/images/scanner_3D_comp.png)
    - Beschreibung:
        - 3D Scanner zur digitalisierung von Insekten
    - Lizenz: 
        - Software: MIT
        - Hardware: CC-BY-SA-4.0
    - Links: [GitHub](https://github.com/evo-biomech/scAnt), [Thingiverse](https://www.thingiverse.com/thing:4694713)
    - Probleme:
        - Strukturteile nur einzeln auf thingiverse ohne Lizenzdatei verfügbar
        - erfordert Snapshot der Seite zur Dokumentation