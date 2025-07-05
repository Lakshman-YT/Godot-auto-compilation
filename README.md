# 🚀 Godot Export Templates Builder (AES-256 Secured) 🔐

This GitHub Actions workflow automatically builds **Linux** and **Windows export templates** from the **latest stable version of Godot Engine**, with added security using an **AES-256 script** for protecting your game scripts.

## 🎯 Features

- ✅ Clones latest **Godot Engine** source
- 🔐 Integrates AES-256 encryption script for secure builds
- ⚙️ Builds export templates for:
  - 🐧 Linux
  - 🪟 Windows
- 💾 Uses SCons with LTO optimizations
- 📦 Uploads `.zip` export templates as artifacts
- ☁️ Caches build output to speed up rebuilds

---

## 📦 Build Artifacts

| Platform | Artifact |
|----------|----------|
| 🐧 Linux  | `export_templates_linux.zip` |
| 🪟 Windows| `export_templates_windows.zip` |

➡️ Download them from the **GitHub Actions run artifacts** once the workflow completes.

---

## 🧪 Run It Manually

Trigger this workflow using the **"Run workflow"** button under  
`Actions > Build Export Templates`.

---

## 📸 Follow Me & Stay Updated

- 🌐 GitHub: [github.com/Lakshman-YT](https://github.com/Lakshman-YT)  
- 📸 Instagram: [@lakshman_choudhary01](https://instagram.com/lakshman_choudhary01)  
- 📺 YouTube: [GW TUTS on YouTube](https://www.youtube.com/@gwtuts4061)  
- 🎮 itch.io: [gw tuts.itch.io](https://)

---

## 📽️ Watch the Tutorial

📹 I made a full tutorial video explaining how this workflow works and how to customize it!

👉 [Watch Now on YouTube](https://youtube.com/)

---

## 🧠 Requirements

- Set a GitHub secret called: `SCRIPT_AES256_ENCRYPTION_KEY`  
  → Go to `Settings > Secrets and variables > Actions`

---

## 🤝 Contributions

Open to improvements! Fork it, extend it, or create a PR! 🚀

---

## 🛡️ License

MIT License — use freely, contribute kindly.

---

Made with ❤️ by [@Lakshman-YT](https://github.com/Lakshman-YT)
