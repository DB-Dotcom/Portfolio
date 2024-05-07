# Portfolio
# Portfolio-Projekt

Dieses Portfolio ist als Single-Page-Application (SPA) mit React und Vite implementiert, um meine Projekte, Fähigkeiten und beruflichen Erfahrungen interaktiv darzustellen.

## Technologien

- **React**: Eine JavaScript-Bibliothek für den Bau von Benutzeroberflächen, insbesondere Single-Page-Applications.
- **Vite**: Ein moderner Frontend-Build-Tool, der extrem schnelles Hot-Module-Replacement (HMR) bietet.
- **CSS Module**: Für stylespezifische Komponenten, die Konflikte im globalen CSS-Raum vermeiden.
- **Dracula Theme**: Ein beliebtes dunkles Farbschema, das in diesem Projekt global über CSS-Variablen implementiert wird.

## Aufbau der Seite

Das Portfolio ist in verschiedene Sektionen gegliedert, die jeweils über ein responsive Navigationselement zugänglich sind:

- **Über mich**: Einleitender Abschnitt, der eine Kurzvorstellung meiner Person und beruflichen Hintergrund bietet.
- **Projekte**: Eine Sammlung meiner Arbeiten, dargestellt in Form von Karten, die jeweils ein Bild und Buttons zu den Projektdetails, GitHub-Repositories und Live-Demos enthalten.
- **Fähigkeiten (Skills)**: Eine Übersicht meiner technischen und beruflichen Fähigkeiten.
- **Footer**: Enthält Kontaktinformationen und soziale Medien-Links.

### Navigation

Die Navigation verwendet `react-scroll` für das sanfte Scrollen zwischen den Sektionen auf der Seite und schaltet um zwischen einer Standardansicht und einem Hamburger-Menü auf mobilen Geräten.

## Installation

```bash
git clone https://github.com/deinUsername/portfolio.git
cd portfolio
npm install
npm run dev
