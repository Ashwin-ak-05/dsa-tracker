# 📘 DSA Problem Tracker (Forkable & GitHub-Synced)

> A no-backend, zero-installation DSA tracker built with just HTML + JS. Save your notes & code directly to your own GitHub repo using the GitHub API.

![DSA Tracker Screenshot](screenshot.png) <!-- Add your screenshot -->

---

## 🚀 Features

- ✅ Load predefined sheets like **Neetcode 150**, **GFG Top 160**, or create your own
- ✍️ Add **personal notes** and save per problem
- 💻 Add **multi-language code** (C++, Java, Python)
- 💾 Save data directly to your **own GitHub repo** via GitHub API
- 🌐 Works on **GitHub Pages**, no installation or backend required
- 🔐 Each user keeps their own GitHub token locally (never shared)

---

## 📁 Folder Structure (in your GitHub Repo)

```
📁 sheets/
   └── neetcode-150.json
📁 problems/
   └── 1-Two Sum/
       ├── notes.md
       └── code/
           ├── cpp.cpp
           ├── java.java
           └── py.py
```

---

## ⚙️ How to Use

### 1. 🍴 Fork this repository

Go to [GitHub repo](#) and click **Fork** to make your own copy.

### 2. 🧑‍💻 Enable GitHub Pages

In your forked repo:
- Go to **Settings > Pages**
- Set source to `main` branch, `/ (root)` folder
- Click **Save** → your app is live!

### 3. 🔑 Generate GitHub Token

- Visit [https://github.com/settings/tokens](https://github.com/settings/tokens)
- Click **"Generate new token (classic)"**
- Enable these scopes:
  - ✅ `repo` → `contents` access is enough
- Copy the token and keep it safe (you only need it once)

### 4. 💻 Use the App

- Open the app URL (from GitHub Pages)
- Enter your GitHub Token, username, repo name
- Select a sheet (e.g. Neetcode 150)
- Click 📝 to add notes or 💻 to save code
- Code and notes are saved directly into your own GitHub repo!

---

## 🧪 Sample JSON File Format

```json
[
  {
    "id": 1,
    "name": "Two Sum",
    "link": "https://leetcode.com/problems/two-sum",
    "level": "Easy"
  },
  {
    "id": 2,
    "name": "Group Anagrams",
    "link": "https://leetcode.com/problems/group-anagrams",
    "level": "Medium"
  }
]
```
Place this in `sheets/neetcode-150.json` and commit it.

---

## 💡 Why This Project is Unique

- 🧩 No `npm`, no `yarn`, no backend
- 🗂 Fork-and-go: others can use it by just forking
- 🔐 Secure: users store their token locally and own their GitHub data
- 📦 GitHub Pages powered: works entirely in browser
- ✨ Clean UI, expandable architecture

This is the **most lightweight, GitHub-native DSA tracker** you’ll find.

---

## 🛠️ Roadmap Ideas (PRs welcome!)

- [ ] Add solved checkbox per problem
- [ ] Filter by difficulty/topic
- [ ] Markdown rendering for notes
- [ ] Progress export (CSV)
- [ ] Search bar

---

## 🤝 Contributing

1. Fork the project
2. Create your branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push and open a PR!

---

## 🙌 Credits

Built by **Ashwin** — with simplicity, self-learning, and open-source spirit 🌱

> Feel free to share, fork, and use — just plug in your token and go! 🔐

---

## 📬 License

MIT License. Use freely and responsibly.
