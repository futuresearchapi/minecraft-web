# mcbrow.netlify.app

A self-hosted, browser-based Minecraft client using the Minecraft Web Client.

---

## 🚀 Features

- Runs Minecraft directly in the browser  
- Self-hostable on static sites (Netlify, GitHub Pages, etc.)  
- Easily configurable with a `dist/config.json` file  
- Lightweight, no backend needed

---

## 🧱 Getting Started

1. Download and extract `self-host.zip` into this project, excluding `dist/config.json`  
2. Configure your Minecraft server settings in `dist/config.json`  
3. Deploy the `dist/` folder to your static host

---

## 🚧 Auto-Update Workflow

We use GitHub Actions to:
- Fetch the latest client files  
- Extract them without overriding `dist/config.json`  
- Commit and push changes back to the repo  
- Remove the zip before committing

---

## Contributing

Feel free to fork the repo and submit pull requests.  
Please follow standard GitHub contribution practices.

---

## 📜 License

Licensed under the **MIT License**.
