# ⚡ Aether

An interactive, **dark-themed educational site** for students to explore physics concepts with animations and visualizations.
Currently starting with **Kinematics** 🚀

---

## 🗂️ Project Structure

```
frontend/
├── index.html              # Landing page
├── topics/
│   └── kinematics.html     # (Work in progress)
├── assets/
│   ├── css/
│   │   └── base.css        # Dark theme base styles
│   ├── js/
│   │   └── main.js         # Global site logic (future)
│   └── img/                # Icons / images
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/a78738825/aether.git
cd aether
```

### 2. Run locally

Since it’s static HTML/CSS/JS, you can just open `index.html` in a browser.
Or run a simple local server (recommended):

```bash
# Python 3
python -m http.server 8000
```

Then visit 👉 [http://localhost:8000](http://localhost:8000)

### 3. Deployment

We’re using **Vercel** for hosting. Every push to `main` auto-deploys.

---

## 🤝 Contributing

We welcome contributions! Some ideas to start with:

* 🎨 Improve **dark theme design** (typography, layout, responsiveness).
* 📚 Add more **topics/pages** (Dynamics, Work-Energy, etc.).
* 🎬 Implement **animations** (Canvas, p5.js, or Three.js).
* 🧪 Add interactive **quizzes/notes** alongside animations.

**How to contribute:**

1. Fork the repo 🍴
2. Create a new branch: `git checkout -b feature/my-feature`
3. Commit changes: `git commit -m "Add my feature"`
4. Push: `git push origin feature/my-feature`
5. Open a Pull Request ✅

---

## 📌 Roadmap

* [ ] Kinematics animations (projectile motion, uniform acceleration, vectors).
* [ ] Responsive design for mobile/tablet.
* [ ] User settings (dark/light toggle, theme customization).
* [ ] Possible backend (FastAPI) for saving progress in the future.

---

## 📄 License

MIT License – feel free to use, modify, and share ✨
