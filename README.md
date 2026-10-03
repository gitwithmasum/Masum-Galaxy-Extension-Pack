<p align="center">
  <img src="images/marketplace-hero.jpg" alt="Masum Galaxy Extension Pack — complete futuristic VS Code experience" width="100%">
</p>

# Masum Galaxy // Extension Pack

The complete **Masum Galaxy VS Code experience** by **Masum Billah** — futuristic color themes, Galaxy file icons, and custom product icons in one install.

**Version 1.0.0 · Free · MIT**

## Included extensions

| Extension | What it adds |
| --- | --- |
| **Masum Galaxy // Future Code** | Futuristic Galaxy, Cyber City, AI Core, Black Hole, Quantum Grid, Mars Colony, Deep Ocean, Aurora, Mecha Core, Orbital Station and Solar Flare color themes, plus optional animated workbench effects |
| **Masum Galaxy // File Icons** | Galaxy-inspired file and folder icons for web, full-stack, AI/ML, database and DevOps workflows |
| **Masum Galaxy // Product Icons** | Premium Galaxy VS Code UI/product icons with optional Aurora hover effects |

### Extension IDs

```text
gitwithmasum.masum-galaxy-future-code
gitwithmasum.masum-galaxy-file-icons
gitwithmasum.masum-galaxy-product-icons
```

## Why use the pack?

Install one extension pack instead of installing the three Masum Galaxy extensions separately. Each included extension remains independently configurable, so you can choose the color theme, file icon theme and product icon theme you want.

## Branding

- Marketplace icon: `images/icon.png`
- Hero banner: `images/marketplace-hero.jpg`

## Local development

```powershell
git clone https://github.com/gitwithmasum/Masum-Galaxy-Extension-Pack.git
cd Masum-Galaxy-Extension-Pack

npm.cmd install
npx.cmd vsce package
```

This creates:

```text
masum-galaxy-extension-pack-1.0.0.vsix
```

Install the local VSIX with:

```powershell
code --install-extension .\masum-galaxy-extension-pack-1.0.0.vsix --force
```

## Recommended setup

After installation, open the Command Palette with `Ctrl + Shift + P` and choose your preferred:

```text
Preferences: Color Theme
Preferences: File Icon Theme
Preferences: Product Icon Theme
```

For the full Galaxy look, use **Masum Galaxy // Future Code**, **Masum Galaxy // File Icons**, and **Masum Galaxy // Product Icons** together.

## Included projects

- [Masum Galaxy // Future Code](https://github.com/gitwithmasum/Galaxy-VS-Code-Themes)
- [Masum Galaxy // File Icons](https://github.com/gitwithmasum/Galaxy-VS-Code-File-Icon)
- [Masum Galaxy // Product Icons](https://github.com/gitwithmasum/Galaxy-VS-Code-Product-Icon)

## License

MIT
