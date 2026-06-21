# 🌌 Protoss Theme for [Obsidian.md](http://Obsidian.md)

> *A sleek, futuristic Obsidian theme inspired by the StarCraft Protoss race. Optimized for focus, readability, and a touch of sci-fi elegance.*

Protoss Theme Preview *(Replace with actual screenshot later!)*

---

## ⚡ Features

- **Protoss Aesthetic**: Deep space blues, neon cyans, and golden highlights inspired by the Protoss race.
- **Optimized Performance**: Refactored CSS for minimal runtime overhead (e.g., `contain: paint`, GPU-accelerated animations).
- **Custom Typography**: Uses [Jura](https://fonts.google.com/specimen/Jura), [Orbitron](https://fonts.google.com/specimen/Orbitron), and [Oxanium](https://fonts.google.com/specimen/Oxanium) for a futuristic feel.
- **Dynamic Effects**:
  - Glowing callouts with animated sweep highlights.
  - Starfield background for sidebars.
  - Hover effects for tables, tasks, and navigation.
- **Dark Theme**: Designed for low-light environments with high contrast.

---

## 🛠️ Installation

### Manual Install

1. Navigate to your Obsidian vault’s `.obsidian/themes/` folder.
2. Clone this repository or download the `protoss-theme.css` file.
3. Enable the theme in Obsidian:
  - **Settings → Appearance → Themes → Protoss Theme**.

### (Future) Community Plugins

> *Planned: Publish to Obsidian’s official theme store once stable.*

---

## 🎨 Customization

### Design Tokens

All colors and effects are defined as CSS variables in `:root` for easy theming. Override them in a custom CSS snippet:

```css
:root {
  --protoss-background-color: #061727;
  --protoss-cyan-color: #4adede;
  --protoss-yellow-color: #c9a03c;
  /* ... */
}
```

### Supported Components

- Callouts (Terran/Protoss/Zerg variants)
- Tables (gradient headers, hover glow)
- Task lists (checkbox glow, nested list borders)
- Sidebars (starfield background)
- Scrollbars (gradient thumb)
- Metadata properties
- (Planned) Graph view styling

---

## 🚀 Development

### Project Status

- **Current Version**: `0.1.0` (Alpha)
- **Last Updated**: June 21, 2026
- **License**: [MIT](LICENSE)

### Roadmap


| Priority | Feature                      | Status |
| -------- | ---------------------------- | ------ |
| High     | Fix sidebar background color | ✅      |
| High     | Add screenshots              | ⬜      |
| Medium   | Graph view styling           | ⬜      |
| Low      | Light theme variant          | ⬜      |


### Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-idea`).
3. Commit your changes (`git commit -m "Add: Your feature"`).
4. Push to the branch (`git push origin feature/your-idea`).
5. Open a Pull Request!

---

## 📜 Inspiration

> *"The Protoss are a highly advanced alien race with a deep connection to the Khala (their psychic network). This theme channels their technological prowess and mystical aesthetic into a productivity tool."*

- **StarCraft Universe**: Colors and design language inspired by Protoss structures (e.g., [Khaydarin Crystals](https://starcraft.fandom.com/wiki/Khaydarin_crystal)).
- **Obsidian.md**: Built for compatibility with Obsidian’s latest updates.

---

## 📥 Assets

- **Fonts**: [Google Fonts (Jura, Orbitron, Oxanium)](https://fonts.google.com/)
- **Icons**: Obsidian’s default icon set (compatible with custom icon plugins).

---

## 💬 Feedback

Found a bug or have a suggestion? Open an [issue](https://github.com/gokayburuc/protoss-obsidian-theme/issues) or start a [discussion](https://github.com/gokayburuc/protoss-obsidian-theme/discussions).

---

## 📄 License

This project is licensed under the **MIT License** – see [LICENSE](LICENSE) for details.

---

Made with ❤️ for the **Protoss** and **Obsidian** communities.
