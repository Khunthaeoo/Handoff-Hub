# Handoff Hub 📦

**Every file. Every note. Every next step.**

Handoff Hub is a student project handoff web app that helps university students and project teams organize files, track deliverables, and prepare project handoffs.

It provides a simple way to manage project information, check required items, and package files and notes for the next team member.

## ✨ Features

- **Project Management** — Create, edit, and organize projects.
- **File Management** — Upload, view, download, and remove project attachments.
- **Handoff Checklist** — Track required deliverables and completion progress.
- **Project Notes** — Record project versions, known issues, and next steps.
- **JSON Import & Export** — Transfer project information between compatible app instances.
- **ZIP Handoff Packages** — Package project files and a manifest for delivery, if ZIP export is enabled.
- **Local Data Storage** — Save project information in your browser.
- **Responsive Design** — Use the application on desktop, tablet, and mobile devices.

## 🎯 Why Handoff Hub?

During university assignments, group projects, and hackathons, important files and instructions can become scattered across chat applications and folders.

Handoff Hub helps teams prepare a more complete handoff by organizing project files, documenting unfinished work, and checking whether important deliverables are ready.

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript
- Browser APIs for file handling and local storage
- IndexedDB, where implemented, for storing file contents
- GitHub Pages for static hosting

## 🚀 Getting Started

### Run Locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Create a project and add checklist items.
4. Upload project files and prepare a handoff package.

No installation or build process is required if the application is implemented as a standalone HTML file.

### Deploy with GitHub Pages

1. Upload `index.html`, `README.md`, and `LICENSE` to your GitHub repository.
2. Open the repository's **Settings**.
3. Select **Pages**.
4. Under the build and deployment settings, choose deployment from a branch.
5. Select your main branch and the root folder.
6. Save and open the published website URL after deployment finishes.

## 📁 Project Structure

```text
handoff-hub/
├── index.html
├── README.md
└── LICENSE
```

The application code is contained in `index.html`, including its embedded CSS and JavaScript.

## 💾 Data and Privacy

Handoff Hub is designed to process selected files in the browser and save project information locally.

- Data saved in browser storage is not automatically synchronized between devices.
- Clearing browser site data may remove locally saved information.
- Export important project data and files as backups.
- A JSON manifest contains project information and file metadata; it does not necessarily contain the actual file contents.
- ZIP export, when available, packages actual attached files with a manifest.

GitHub Pages hosts the application itself. It does not provide a writable file-upload server or automatic cloud synchronization.

## ⚠️ Limitations

- The application is designed primarily for individual, local use.
- Real-time collaboration and remote file sharing require an additional backend or storage service.
- Available browser storage depends on the browser and device.
- File previews depend on the file type and browser capabilities.

## 🔮 Future Improvements

- Cloud storage integration.
- Shareable project handoff links.
- User accounts and access permissions.
- File version history.
- Improved file previews and project activity logs.

## 👨‍💻 Author

Developed as a student web application project to explore front-end development, file handling, browser storage, data validation, and user interface design.


