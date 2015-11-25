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
| `kovi→`   | The visible binding	`data-bind="visible: "`|
| `kote→`   | The text binding 	`data-bind="text: "` |
| `koht→`   | The html binding 	`data-bind="html: "` |
| `kocs→`   | The css binding 		`data-bind="css: "` |
| `kost→`   | The style binding 	`data-bind="style: "` |
| `koat→`   | The attr binding 	`data-bind="attr: "` |

#### Control flow
| Trigger  | Content |
| -------: | ------- |
| `kofe→`   | The foreach binding `data-bind="foreach: "`|
| `koif→`   | The if binding  `data-bind="if: "` |
| `koin→`   | The ifnot binding `data-bind="ifnot: "` |
| `kowi→`   | The with binding  `data-bind="with: "` |
| `koco→`   | The component binding `data-bind="component: "` |

#### Working with form fields
| Trigger  | Content |
| -------: | ------- |
| `kocl→`   | The click binding `data-bind="click: "`|
| `koev→`   | The event binding  `data-bind="event: "` |
| `kosu→`   | The submit binding `data-bind="submit: "` |
| `koen→`   | The enable binding `data-bind="enable: "` |
| `kodi→`   | The disable binding `data-bind="disable: "` |
| `kova→`   | The value binding `data-bind="value: "`|
| `koti→`   | The textInput binding  `data-bind="textInput: "` |
| `kohf→`   | The hasFocus binding `data-bind="hasFocus: "` |
| `koch→`   | The checked binding `data-bind="checked: "` |
| `koop→`   | The options binding `data-bind="options: "` |
| `koso→`   | The selectedOptions binding `data-bind="selectedOptions: "` |
| `koun→`   | The uniqueName binding `data-bind="uniqueName: "` |

#### Rendering templates
| Trigger  | Content |
| -------: | ------- |
| `kotm→`   | The template binding `data-bind="template: "`|

### Observables

| Trigger  | Content |
| -------: | ------- |
| `koob→`   | Observable |
| `kooa→`   | Observable Arrays  |
| `koco→`   | Computed Observables |
| `kopc→`   | Pure computed observables |

You can press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

### Credits

Initially based upon [Knockout.JS TextMate bundle](https://github.com/napcs/knockout-tmbundle) by Brian Hogan.

Logo by [Boyan Mihaylov](http://boyan.in)