# Cascara Retro Themes

![](https://sandydunlop.github.io/assets/vscode-retro-preview.png)

For:

- Visual Studio Code
- Ghostty
- iTerm2

---

## Building From Source

The Cascara Retro Themes collection is written in CT - a language designed to builing themes.

The build process uses two Gradle plugins:

1. cascara-gradle-plugins.ct
2. cascara-gradle-plugins.vsix

To build the VSIX package:

```bash
./gradlew build
```

To install the VSIX package:

```bash
./gradlew installVsix
```

To reinstall the VSIX package:

```bash
./gradlew reinstallVsix
```

To remove the VSIX package:

```bash
./gradlew uninstallVsix
```

## Installation

### Visual Studio Code

1. Open **Visual Studio Code**
2. Launch the Extension Marketplace (`Ctrl+Shift+X` or `Cmd+Shift+X`)
3. Search for `Cascara Retro Theme`
4. Click **Install**
5. Select one of the Cascara retro themes as your Color Theme

## License

Cascara Theme is released under the MIT license, which grants the following permissions:

- Commercial use
- Distribution
- Modification
- Private use

For more convoluted language, see the LICENSE.

---

