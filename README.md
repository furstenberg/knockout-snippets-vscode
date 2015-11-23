# Knockout.js Snippets for VS Code

This extension for Visual Studio Code adds snippets for Knockout.js.

## Installation

1. Install Visual Studio Code 0.10.1 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code

## Snippets

Below is a list of available snippets and the triggers for them. The **⇥** means the `TAB` key.

### Bindings

#### Controlling text and appearance
| Trigger  | Content |
| -------: | ------- |
| `kodbv→`   | The visible binding	`data-bind="visible: "`|
| `kodbt→`   | The text binding 	`data-bind="text: "` |
| `kodbh→`   | The html binding 	`data-bind="html: "` |
| `kodbc→`   | The css binding 		`data-bind="css: "` |
| `kodbs→`   | The style binding 	`data-bind="style: "` |
| `kodba→`   | The attr binding 	`data-bind="attr: "` |

### Observables

| Trigger  | Content |
| -------: | ------- |
| `koo→`   | Observable |
| `kooa→`   | Observable Arrays  |
| `koco→`   | Computed Observables |
| `kopc→`   | Pure computed observables |

You can press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

### Credits

Initially based upon [Knockout.JS TextMate bundle](https://github.com/napcs/knockout-tmbundle) by Brian Hogan.