<p align="center">
  <img src="./images/logo.png" alt="StackMint Theme Logo" width="160" />
</p>

<h1 align="center">StackMint Theme</h1>

<p align="center">
  A clean, vibrant, and modern <b>Visual Studio Code color theme</b> designed to provide a comfortable and enjoyable coding experience with balanced syntax highlighting and high contrast visual clarity.
</p>

<p align="center">
  <a href="https://open-vsx.org/extension/smcolorthemesohagsheik/stackmint-theme"><img src="https://img.shields.io/open-vsx/v/smcolorthemesohagsheik/stackmint-theme?label=Open%20VSX" alt="Open VSX" /></a>
  <a href="https://open-vsx.org/extension/smcolorthemesohagsheik/stackmint-theme"><img src="https://img.shields.io/open-vsx/dt/smcolorthemesohagsheik/stackmint-theme?label=Downloads" alt="Downloads" /></a>
  <a href="https://github.com/smsohag32/stackmint-theme"><img src="https://img.shields.io/github/stars/smsohag32/stackmint-theme?style=social" alt="GitHub Stars" /></a>
</p>

---

## ✨ Theme Collection

| Theme | Style | Highlights |
| :--- | :--- | :--- |
| 🌿 **StackMint Eye Comfort** | **Eye Comfort / Soft Dark** | Gentle on the eyes, reduces fatigue during long sessions. Soothing background (`#161c22`) with vivid, colorful syntax highlighting that makes code pop with effortless readability. |
| ⚡ **StackMint Pro** | **Professional Classic Dark** | Balanced Material-slate background (`#263238`), crisp contrast, and iconic radiant mint accents for everyday professional development. |
| 🌙 **StackMint Midnight** | **Deep Midnight Dark** | Ultra-deep nocturnal navy background (`#0B1220`) with vibrant electric cyan, amber, and coral accents for maximum contrast. |

---

## ✨ Features

- 🌿 **Eye Comfort Engineering**: Optimized color luminance, soft background, and balanced contrast designed to reduce eye strain during extended 8+ hour coding sessions.
- 🎨 **Colorful & Easy to Read**: Every syntactic token (keywords, functions, strings, numbers, types, variables, parameters) has a distinct, vibrant, accessible color.
- 🪟 **Comprehensive Workbench UI**: Fully harmonized editor, activity bar, sidebar, tabs, status bar, breadcrumbs, command palette, integrated terminal, and git diffs.
- 💻 **Multi-Language Perfection**: Fine-tuned for JavaScript, TypeScript, React JSX/TSX, Python, HTML, CSS/SCSS, C/C++, Go, Rust, PHP, JSON, YAML, SQL, and Markdown.
- 🧩 **VS Code & Compatible Editors**: Works seamlessly with Visual Studio Code, VSCodium, Cursor, and Open VSX compatible editors.

---

## 📦 Download Versions (.vsix Releases)

All packaged extension versions are organized inside the [`releases/`](./releases/) directory. You can download and install any version directly:

| Version | Release Package | Download Link | Notes |
| :--- | :--- | :--- | :--- |
| **`v1.1.0`** *(Latest)* | `stackmint-theme-1.1.0.vsix` | ⬇️ **[Download v1.1.0](./releases/stackmint-theme-1.1.0.vsix)** | Added **StackMint Eye Comfort**, rebranded **StackMint Pro** & **StackMint Midnight** with full UI styling |
| `v1.0.0` | `stackmint-theme-1.0.0.vsix` | ⬇️ **[Download v1.0.0](./releases/stackmint-theme-1.0.0.vsix)** | Initial 1.0.0 release |
| `v0.0.3` | `stackmint-theme-0.0.3.vsix` | ⬇️ **[Download v0.0.3](./releases/stackmint-theme-0.0.3.vsix)** | Pre-release version 0.0.3 |
| `v0.0.2` | `stackmint-theme-0.0.2.vsix` | ⬇️ **[Download v0.0.2](./releases/stackmint-theme-0.0.2.vsix)** | Pre-release version 0.0.2 |

### 🛠️ Installing from a `.vsix` File

1. Download the desired `.vsix` file from the table above (or browse the [`releases/`](./releases/) folder).
2. Open **Visual Studio Code**.
3. Open the **Extensions** panel:
   - **Windows / Linux:** `Ctrl + Shift + X`
   - **macOS:** `Cmd + Shift + X`
4. Click the **`...` (More Actions)** menu at the top-right corner of the Extensions view.
5. Click **Install from VSIX...**
6. Select the downloaded `.vsix` file (e.g. `stackmint-theme-1.1.0.vsix`).

---

## 📸 Preview

```md
![StackMint Theme Preview](./images/preview.png)
```

---

## 🎨 Activating the Theme

After installation:

1. Open the Command Palette:
   - **Windows / Linux:** `Ctrl + Shift + P`
   - **macOS:** `Cmd + Shift + P`
2. Type and select **Preferences: Color Theme**.
3. Choose your favorite variant:
   - **StackMint Eye Comfort** *(Recommended for long coding sessions)*
   - **StackMint Pro**
   - **StackMint Midnight**
4. Press **Enter**.

---

## 🛠️ Development

Clone the repository:

```bash
git clone https://github.com/smsohag32/stackmint-theme.git
cd stackmint-theme
```

Open in VS Code:

```bash
code .
```

To build a new `.vsix` package into the `releases/` directory:

```bash
npx @vscode/vsce package --out releases/
```

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

1. Fork this repository.
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push to branch: `git push origin feature/my-feature`
5. Open a Pull Request.

---

## ⭐ Support

If you enjoy using **StackMint Theme**, please consider giving the [repository](https://github.com/smsohag32/stackmint-theme) a ⭐ on GitHub!

Made with ❤️ for developers.
