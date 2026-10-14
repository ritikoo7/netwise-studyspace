# 🌐 NetWise | Computer Networks Studyspace

> A lightweight, interactive study dashboard for learning and revising Computer Networks in one place.

NetWise is a standalone web project built to help students organize their Computer Networks syllabus, track study progress, revise important topics, and manage their study sessions. It runs directly in a browser, with no installation or backend required.

## ✨ Features

- **Dashboard:** View study progress and a quick overview of your learning activity.
- **Syllabus tracker:** Organize topics across five modules and mark your progress.
- **Revision tracker:** Keep track of topics that need another review.
- **Topic video search:** Find YouTube explanations for selected topics.
- **Tasks and calendar:** Plan study sessions, deadlines, and revision.
- **Notes:** Save your own topic notes.
- **Flashcards:** Practice concepts with quick revision cards.
- **Focus timer:** Run focused study sessions.
- **AI Study Buddy prompt helper:** Prepare a study prompt to use with an AI assistant. This is a prompt-building prototype, not an embedded AI service.
- **Dark mode:** Switch the interface to a darker theme.
- **Backup and restore:** Export or import your saved study data.
- **Responsive layout:** Designed to work across common desktop and mobile screen sizes.

## 📚 Modules Covered

1. Data Link Layer
2. Network Layer & Routing
3. Transport Layer
4. Application Layer
5. Security & Other Network Technologies

The project contains 52 topics across these modules.

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage` for saving data locally

No Node.js, npm, database, server, or API key is required.

## 🚀 Run Locally

1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html`, or open it in your browser.
4. Start tracking your syllabus and study tasks.

### Clone with Git

```bash
git clone https://github.com/ritikoo7/netwise.git
cd netwise
```

If your repository uses a different name, replace `netwise` in the commands with your repository name.

## 🌍 Publish with GitHub Pages

1. Create a GitHub repository named `netwise` (or your preferred project name).
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site.

For the repository `ritikoo7/netwise`, the expected project URL is:

`https://ritikoo7.github.io/netwise/`

The link will work after GitHub Pages has been enabled and deployment has completed.

## 📁 Project Structure

```text
netwise/
├── index.html    # Complete website: HTML, CSS, and JavaScript
└── README.md     # Project overview and setup instructions
```

This is intentionally a single-file website, so you do not need `package.json`, a build tool, or a backend.

## 💾 Data and Privacy

- Study information is stored in your browser using `localStorage`.
- Your saved data may not appear in another browser or device automatically.
- Clearing browser site data can remove saved progress. Use the built-in export/backup feature regularly if you want a copy.
- The website does not require an account or a server to run.

## 🔮 Possible Future Improvements

- Add topic-wise practice quizzes and mock tests.
- Add a downloadable progress report.
- Add more visual summaries for syllabus completion.
- Split the single HTML file into separate HTML, CSS, and JavaScript files.
- Add optional cloud sync in a future version.

## 🤝 Contributing

Suggestions and improvements are welcome. You can fork the repository, make a change on a separate branch, and open a pull request describing what you changed.

## 📄 License

No license is included by default. If you want others to reuse, modify, and distribute this project, add a license file such as the MIT License after deciding how you want the project to be shared.

---

**Made for focused Computer Networks learning.** 🌐
