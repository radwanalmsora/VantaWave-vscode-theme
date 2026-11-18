# VantaWave — Visual Studio Code Theme

A polished dual-theme extension for Visual Studio Code, built around calm deep-ink surfaces, a distinctive cyan signature accent, and readable syntax colors.

## Included
- **VantaWave Dark** — deep navy editor, restrained contrast, vivid but balanced syntax.
- **VantaWave Light** — cool near-white canvas with coordinated teal accents.
- Custom activity/status bars, tabs, panels, terminal ANSI palette, Git decorations, diagnostics, and editor widgets.
- Brand icon exported at 16, 24, 32, 48, 64, 96, 128, 256, 512, and 1024 px.

## Preview / install locally
1. Open this folder in VS Code.
2. Press `F5` to launch an Extension Development Host.
3. Open **Preferences: Color Theme** and choose **VantaWave Dark** or **VantaWave Light**.

## Build VSIX with GitHub Actions
1. Create a GitHub repository and upload the contents of this ZIP to its root.
2. Edit `package.json` and replace `your-publisher-id` with your Marketplace publisher ID (or a valid identifier you control).
3. Push to the `main` branch, or run the **Build VSIX** workflow manually from the Actions tab.
4. Download the generated `VantaWave-VSIX` artifact from the completed workflow run.

The workflow packages the extension with `@vscode/vsce`; it does not publish it to the Marketplace.

## Package locally
```bash
npm install
npx @vscode/vsce package
```

## License
MIT — see `LICENSE`.
