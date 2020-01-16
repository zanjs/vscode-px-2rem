# px to rem

This is an extension for Visual Studio Code that allows you to convert px to rem, and vice versa.

## Usage

### Keybindings

- `Alt+Z` Px to rem, and rem to px. Converts selected text from px to rem, and rem to px.

![](./imgs/alt_z.gif)

### Commands

- Px to rem, and rem to px. Converts selected text from px to rem, and rem to px.
- Px to rem. Converts selected text from px to rem
- Rem to px. Converts selected text from rem to px

## Extension Settings

This extension contributes the following settings:

- `px-2rem.px-per-rem`: number of pixels per rem. Default is `75px`.
- `px-2rem.number-of-decimals-digits`: maximum number of decimals digits a px or rem can have
- `px-2rem.only-change-first-ocurrence`: set to change all or only the first selected ocurrence of px/rem
- `px-2rem.notify-if-no-changes`: enable/disable notification that alerts the users if no conversion could be made

## Known Issues

- If you select a value with multiple cursors it will get converted, but following cursors may change place after the conversion.
- '_Edits from command extension.pxToRemAndRemToPx were not applied_' message appears in debug console.

## Release Notes

### 1.2.8

- Default is `75px`

### 1.2.7

- Fixed bug, minimum number of decimal was 1, not 0

### 1.2.6

- Added gif for `alt + z` keybinding

### 1.2.5

- Fixed bug where text was being selected after conversion.

### 1.2.4

- There's no need to select a value to modify it. Now you only have to have the curso next to the value.

### 1.2.2 & 1.2.3

- Modified readme

### 1.2.1

- Fixed bug, The program was not finding all the px and rems in the selections

### 1.2.0

- Introduced an option to set the maximum number of decimals digits a rem and px can have

### 1.1.0

- Keybinding added
- Improved Readme, and fixed some typos
- New command that allows you to covert rem and px back and forward

### 1.0.0

Initial release

---

**Enjoy!**
