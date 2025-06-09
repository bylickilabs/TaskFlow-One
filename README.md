|![HTML](https://img.shields.io/badge/html-5-E34F26?logo=html5&logoColor=white)|![CSS](https://img.shields.io/badge/css-3-1572B6?logo=css3&logoColor=white)|![JavaScript](https://img.shields.io/badge/javascript-es6-F7DF1E?logo=javascript&logoColor=black)|![Kanban](https://img.shields.io/badge/kanban-supported-33CC99?logo=trello&logoColor=white)|![Dependabot](https://img.shields.io/badge/dependabot-enabled-success?logo=dependabot)|[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-online-brightgreen?logo=github&logoColor=white&style=for-the-badge)](https://bylickilabs.github.io/TaskFlow-One/)|
|---|---|---|---|---|---|

|[![License](https://img.shields.io/github/license/bylickilabs/TaskFlow-One?style=for-the-badge)](https://github.com/bylickilabs/TaskFlow-One/blob/main/LICENSE)|[![Last Commit](https://img.shields.io/github/last-commit/bylickilabs/TaskFlow-One?style=for-the-badge)](https://github.com/bylickilabs/TaskFlow-One/commits/)|[![Issues](https://img.shields.io/github/issues/bylickilabs/TaskFlow-One?style=for-the-badge)](https://github.com/bylickilabs/TaskFlow-One/issues)|[![Security Policy](https://img.shields.io/badge/security-policy-blue?style=for-the-badge&logo=github)](https://github.com/bylickilabs/TaskFlow-One/blob/main/SECURITY.md)|
|---|---|---|---|

# 🚀 TaskFlow One
> Modernes, intuitives Kanban-Board für effektives Projektmanagement im inspirierenden Neon-Design.

|![TaskFlow-One](https://github.com/user-attachments/assets/df92f925-0bd3-4832-8423-e7de4096e8d8)|
|---|


<br>

---

<br>

## 📌 Inhaltsverzeichnis

1. [📝 Projektbeschreibung](#-projektbeschreibung)  
2. [✨ Features](#-features)  
3. [📸 Screenshots](#-screenshots)  
4. [⚙️ Installation](#️-installation)  
5. [🚧 Konfiguration](#-konfiguration)  
6. [📖 Nutzung](#-nutzung)  
7. [🔒 Sicherheit](#-sicherheit)  
8. [🔗 Social Media Integration](#-social-media-integration)  
9. [💡 Zukünftige Entwicklungen](#-zukünftige-entwicklungen)  
10. [📜 Lizenz](#-lizenz)  
11. [👥 Beitrag leisten](#-beitrag-leisten)  
12. [📌 GitHub Topics](#-github-topics)
13. [❤️ Vielen Dank](#%EF%B8%8F-vielen-dank)

<br>

---

<br>

## 📝 Projektbeschreibung

**TaskFlow Neon** ist ein visuell ansprechendes, benutzerfreundliches und flexibles Kanban-basiertes Tool zur effektiven Organisation deiner Projekte und Aufgaben.  
Das dynamische Neon-Design motiviert und inspiriert, während klare Strukturen deine Produktivität steigern.

<br>

---

<br>

## ✨ Features

- ✅ Übersichtliche Kanban-Struktur: „To Do“, „Doing“ und „Done“
- 📝 Markdown-Unterstützung für umfangreiche Aufgabenbeschreibungen
- 📑 Code-Vorschau in separatem Modal mit Markdown-Parsing
- ⚙️ Konfigurierbar über zentrale `config.js`
- 🌗 Tag-/Nachtmodus (umschaltbar)
- 🔗 Social-Media-Integration mit Iconleiste am rechten Bildschirmrand
- 🔒 Passwortschutz für sensible Aufgaben

<br>

---

<br>

## 📸 Screenshots

*(Hier Screenshots deines Projekts einfügen)*

<br>

---

<br>

## ⚙️ Installation

### 1. Repository klonen:

```yarn
git clone https://github.com/deinBenutzername/taskflow-neon.git
```

### 2. Projektverzeichnis aufrufen:

```yarn
cd taskflow-neon
```

### 3. Starten:
> Öffne die Datei index.html direkt in deinem Webbrowser.

<br>

---

<br>

## 🚧 Konfiguration
       - Alle Einstellungen befinden sich zentral in der Datei config.js.

> Beispiel:

```yarn
const CONFIG = {
  passwordProtectionEnabled: true,
  password: "deinSicheresPasswort",

  showGitHubRepos: true,
  githubRepos: [
    { username: "deinUser", repo: "repo1", displayName: "Repository 1" },
    { username: "deinUser", repo: "repo2", displayName: "Repository 2" }
  ],

  showSocialIcons: true,
  socialMediaLinks: {
    github: "https://github.com/deinUser",
    twitch: "https://twitch.tv/deinUser",
    website: "https://deinewebsite.de"
  }
};
```

<br>

---

<br>

## 📖 Nutzung
- Neue Aufgabe:
  - Klick auf „Neue Aufgabe +“ <p>
    
- Bearbeiten: 
  - Klick auf Stift-Icon oben rechts <p>

- Verschieben:
  - Per Drag-and-Drop <p>

- Code ansehen:
  - Klick auf „Code anzeigen“ <p>

- Löschen:
  - Klick auf „Löschen“ <p>

- Markdown:
  - Tabellen, Listen, Formatierungen möglich

<br>

---

<br>

## 🔒 Sicherheit
- Optionaler Passwortschutz für das Bearbeiten von Aufgaben
- Aktivierung und Passwort in config.js steuerbar

<br>

---

<br>

## 🔗 Social Media Integration
Unterstützte Plattformen:
GitHub, Twitch, Website, Facebook, Twitter, Instagram, Discord, YouTube, LinkedIn, etc.
Icons erscheinen fixiert am rechten Bildschirmrand – beim Klick wird ein neuer Tab geöffnet.

<br>

---

<br>

## 💡 Zukünftige Entwicklungen
- Benutzerverwaltung & Teams
  - Rechtemanagement

<br>

- Erweiterte Statistiken und Zeitverfolgung
  - Mobile App (iOS & Android)
 
<br>

---

<br>

## 📜 Lizenz
Dieses Projekt steht unter der [LICENSE](LICENSE).

<br>

---

<br>

## 👥 Beitrag leisten
> Beiträge sind willkommen!
  - Forke das Repo

<br>

> Erstelle einen Feature-Branch:

```yarn
git checkout -b feature/neues-feature
```

> Committe deine Änderungen:

```yarn
git commit -m "feat: neues Feature hinzugefügt"
```

> Pushe den Branch:

```yarn
git push origin feature/neues-feature
```

<br>

---

<br>

## 📌 GitHub Topics
> kanban
> task-manager
> project-management
> markdown
> neon-ui
> frontend
> javascript
> responsive
> drag-and-drop
> open-source

<br>

---

<br>

## ❤️ Vielen Dank
Vielen Dank, das du dieses Projekt Unterstützt!
