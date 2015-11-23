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
<!--
#### Control flow
| Trigger  | Content |
| -------: | ------- |
| `kofe→`   | The foreach binding `data-bind="visible: "`|
| `imd→`   | The if binding  `data-bind="text: "` |
| `ime→`   | The ifnot binding `import * as localAlias from 'fs';` |
| `ima→`   | The with binding `import { rename  as localRename } from 'fs';` |
| `enf→`   | The component binding `export const log = (parameter) => { console.log(parameter);};` |

#### Working with form fields
| Trigger  | Content |
| -------: | ------- |
| `imp→`   | The click binding `data-bind="visible: "`|
| `imd→`   | The event binding  `data-bind="text: "` |
| `ime→`   | The submit binding `import * as localAlias from 'fs';` |
| `ima→`   | The enable binding `import { rename  as localRename } from 'fs';` |
| `enf→`   | The disable binding `export const log = (parameter) => { console.log(parameter);};` |
| `imp→`   | The value binding `data-bind="visible: "`|
| `imd→`   | The textInput binding  `data-bind="text: "` |
| `ime→`   | The hasFocus binding `import * as localAlias from 'fs';` |
| `ima→`   | The checked binding `import { rename  as localRename } from 'fs';` |
| `enf→`   | The options binding `export const log = (parameter) => { console.log(parameter);};` |
| `ima→`   | The selectedOptions binding `import { rename  as localRename } from 'fs';` |
| `enf→`   | The uniqueName binding `export const log = (parameter) => { console.log(parameter);};` |

#### Rendering templates
| Trigger  | Content |
| -------: | ------- |
| `imp→`   | The template binding `data-bind="visible: "`|

-->
### Observables

| Trigger  | Content |
| -------: | ------- |
| `koo→`   | Observable |
| `kooa→`   | Observable Arrays  |
| `koco→`   | Computed Observables `import * as localAlias from 'fs';` |
| `kopc→`   | Pure computed observables `import { rename  as localRename } from 'fs';` |

You can press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

### Credits

Initially based upon [Knockout.JS TextMate bundle](https://github.com/napcs/knockout-tmbundle) by Brian Hogan.