# Artur Donis

AI Specialist bei [RUHR24](https://www.ruhr24.de) · Entwickler · Ruhrgebiet

Ich entwickle die internen Werkzeuge einer regionalen Nachrichtenredaktion und binde dafür auch KI in die täglichen Abläufe ein. Mich interessiert die Schnittstelle zwischen Redaktion, Produkt und Code: Wo verliert ein Team Zeit, und wie sieht ein Tool aus, das diese Zeit zurückgibt, ohne dass jemand eine Anleitung lesen muss?

Ich komme aus Mediendesign und UX. Deshalb sollen meine Tools auch für Leute funktionieren, die keine Entwickler sind.

---

## Arbeit bei RUHR24

### ContentOS

Ein internes Redaktionstool, das ich seit Dezember 2025 aufbaue (400+ Commits, 25+ Module). Es wird täglich von der Redaktion genutzt.

- **Erstellen:** KI-gestützter Artikel-Editor mit Prüfung vor dem CMS-Push, Bildeditor (React-Konva) mit Ebenen, Freisteller, Upscaling und Bildgenerierung, Artikelimport per Scraper
- **Analytics (ContentSignal):** Traffic-Dashboard auf Basis von Kilkaya und BigQuery, Google-Discover-Radar, KI-Bewertung von Überschriften und Titelbildern
- **Automatisierung:** Verbreitung von Artikeln per Push und Social mit einem Klick, Datawrapper-Anbindung, Generator für Artikel-Widgets
- **MCP-Server:** Artikel, Bilder, Bildarchiv und Quizfragen lassen sich direkt aus Claude heraus steuern (Streamable HTTP, OAuth)
- **Plattform:** Google-OAuth, API-Keys mit Berechtigungen, Rollen- und Tool-Rechte mit Admin-Oberfläche und Audit-Log, Nutzungsstatistik in BigQuery

### Weitere Projekte

- **R24 Language Tool:** LLM-Backend (Python/FastAPI) für Umschreiben, Überschriften und SEO-Metadaten, mit mehreren Modellanbietern. Übernommen und an ContentOS angebunden.
- **Widgets:** Interaktive PHP-Widgets und Quizze für Reader Engagement, auf einer eigenen Subdomain gehostet und per iframe in Artikel eingebunden
- **n8n-Workflows:** RSS-Aufnahme mit Deduplizierung, Teams-Benachrichtigungen, GraphQL- und MCP-Anbindungen
- **CMS-Anbindung:** Text-zu-XML-Pipeline für die automatische Übergabe von Artikeln ans CMS
- **Infrastruktur:** Google-Cloud-Verwaltung, Migration in EU-Regionen, CI/CD mit GitHub Actions

### Arbeitsweise

- Neue Tools gehen früh in Produktion, sind zunächst aber nur für Admins sichtbar. Die Redaktion bekommt sie nach der Abnahme.
- Fehler behebe ich an der Ursache. Wird ein Modul zu groß, teile ich es auf.
- Oberflächen verwenden Design-Tokens, Icons und eine klare Button-Hierarchie. In der UI stehen keine Fachbegriffe.
- Ich entwickle mit Claude Code und achte bei eingebauter KI auf die Kosten, unter anderem über das Prompt-Design.

---

## Eigenes Projekt: Schichtplaner

Ich habe schon Schichtplaner mit OptaPlanner gebaut und entwickle gerade einen neuen von Grund auf, als White-Label-SaaS auf Basis von Timefold. Geplant sind atomare Schichten statt fest verdrahteter Wochenmuster, Soft Constraints pro Mitarbeiter, saubere Modulgrenzen und später eine KI-Schicht, die Änderungen nur vorschlägt und nicht selbst entscheidet.

Ältere Version: [schichtplaner](https://github.com/Artur267/schichtplaner)

---

## Stack

- **Sprachen:** TypeScript, JavaScript, Java, Python, C++, SQL, PHP, Lua
- **Frontend:** React, Vite, React-Konva, Three.js
- **Backend:** Node.js, Express, FastAPI, Spring Boot
- **Monorepo und Tests:** Nx, Vitest
- **Cloud:** Google Cloud (Cloud Run, BigQuery, Firestore, Cloud Storage, Secret Manager), Docker, GitHub Actions, Hetzner
- **KI:** Claude, Gemini, Vertex AI, Model Context Protocol (MCP)
- **Automatisierung und Daten:** n8n, Kilkaya, Supabase, Google Sheets
- **Constraint-Solver:** Timefold, OptaPlanner

---

## Studium und Interessen

Neben der Arbeit studiere ich (IT-Management, Computergrafik, Mathematik). Privat beschäftige ich mich mit Low-Level-Rendering: OpenGL und C++, Scene Graphs, Z-Buffering, BSP und der Frage, wie GoldSrc und die PS1 ihre Grafik umgesetzt haben. Aus dem Interesse sind ein Breakout-Klon in C++/SFML und ein Three.js-Redesign meines Portfolios entstanden. Außerdem beschäftige ich mich seit längerem mit Web-Sicherheit (CORS, CSP, Absicherung eigener Widgets).

Abseits vom Rechner fahre ich seit rund 20 Jahren Mountainbike: Enduro, Gravel und Bikepark.

---

## Kontakt

- Website: [arturdonis.de](https://www.arturdonis.de)
- Mail: Artur.Donis@gmx.de
