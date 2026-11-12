# Quiet Ember Sand High Contrast

Quiet Ember Sand High Contrast is a dark Visual Studio Code theme using the exact workbench, syntax, and semantic color values from the installed Vira Sand High Contrast theme. The extension keeps its own name and packaging while matching that palette.

This is an independent community extension and is not affiliated with or endorsed by Vira.

## Included

- A complete dark workbench palette for the editor, sidebar, tabs, terminal, panels, inputs, and common extension views.
- Syntax colors for TextMate scopes and semantic tokens.
- A coordinated terminal ANSI palette.

## Install the development version

1. Open this folder in VS Code.
2. Press `F5` to launch an Extension Development Host.
3. Open **Preferences: Color Theme** and choose **Quiet Ember Sand High Contrast**.

## Build an installable VSIX

1. Install Node.js if it is not already installed.
2. In this folder, run `npm install`.
3. Run `npm run package` to create `quiet-ember-theme-0.1.0.vsix`.

Anyone can install that VSIX in VS Code from **Extensions: Install from VSIX...** in the Extensions view's `...` menu. You can also share the VSIX file directly.

## Publish to the Visual Studio Marketplace

1. Create a publisher at <https://marketplace.visualstudio.com/manage> and choose a unique publisher ID.
2. Change the `publisher` value in `package.json` to that ID. The current value, `quietember`, is only a proposed ID and must match a publisher account you control.
3. Increase `version` in `package.json` for each release.
4. Run `npm install` and `npm run package` again.
5. On the publisher management page, create a **New Extension** for **Visual Studio Code**, then upload the generated VSIX and submit it for validation.

After Marketplace approval, people can find and install the theme by its name from the Extensions view (`Ctrl+Shift+X`).

See Microsoft's [publishing guide](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) for publisher setup and the [VSIX installation guide](https://code.visualstudio.com/docs/configure/extensions/extension-marketplace#_install-from-a-vsix) for the manual install route.

## Palette

| Role | Color |
| --- | --- |
| Editor surface | `#131210` |
| Main foreground | `#DFD9D0` |
| Cursor accent | `#FFCC00` |
| Syntax rules | 81 matched scopes |
| Palette source | Vira Sand High Contrast |

## Customize

Override any workbench color in your VS Code `settings.json` under `workbench.colorCustomizations`, or syntax colors under `editor.tokenColorCustomizations`.

## License

MIT.

