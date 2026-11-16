# OsdagBridge – FOSSEE IIT Bombay Internship

### Software Development | Python | PySide6 | Open Source

**Summer Internship Project – July 2026**

This repository showcases my technical contributions to **OsdagBridge**, an open-source desktop application developed under the FOSSEE project at IIT Bombay.

During my internship, I worked on improving the application's user interface, CAD visualisation, dynamic rendering and application robustness.

## Project Overview

OsdagBridge is a PySide6-based desktop module of the Osdag platform, designed for steel and composite bridge design, analysis and visualisation.

## My Key Contributions

### 1. Custom Vehicle Load Diagrams
- Developed three custom diagram widgets using PySide6 and QPainter.
- Implemented tracked/bogie vehicle diagrams, wheeled axle diagrams and clear carriageway width diagrams.
- Replaced static placeholders with dynamically rendered diagrams.
- Integrated the widgets into the Custom Vehicle dialog.

### 2. Dynamic Girder Highlighting
- Implemented real-time girder highlighting in cross-section CAD views.
- Synchronised selected girder information across three visualisation views.
- Improved visual clarity through dynamic highlighting.

### 3. CAD Rendering Improvements
- Fixed a blank CAD view issue occurring when the Member Properties dialog was first opened.
- Improved viewport initialisation and rendering behaviour.

### 4. Application Robustness
- Introduced guarded imports for optional dependencies.
- Improved application behaviour when packages such as OpenSeesPy, OSPGrillage, pythonocc-core and NavCube are unavailable.
- Added graceful fallback behaviour for unavailable 3D CAD functionality.

## Technology Stack

- **Programming:** Python
- **GUI Development:** PySide6, Qt
- **Graphics:** QPainter, QPen, QBrush, QPolygonF
- **Visualisation:** Matplotlib
- **Version Control:** Git, GitHub

## Contributions and Pull Requests

- [PR #52 – Custom Vehicle Diagrams and UI Enhancements](https://github.com/Aditya-Donde/OsdagBridge/pull/52)
- [PR #66 – Dynamic Girder Highlighting and Robustness Fixes](https://github.com/Aditya-Donde/OsdagBridge/pull/66)

## Original Project

[OsdagBridge – GitHub Repository](https://github.com/Aditya-Donde/OsdagBridge)

[Osdag Project Website](https://osdag.fossee.in/)

## Internship Documentation

The complete internship report is available in this repository as `Internship-Report.pdf`.

It documents the problem statements, implementation approaches, technical decisions, screenshots, code snippets and outcomes of my contributions.

---

**Anushka Pareek**  
B.Tech Computer Science and Engineering | VIT Bhopal University  
FOSSEE Summer Intern | IIT Bombay
