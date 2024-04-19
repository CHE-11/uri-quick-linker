# URI Quick Linker
URI Quick Linker is a fast way to copy and paste URI links in your project. This makes it easy to make a way to link to a specific page in your project from a different page.

https://github.com/CHE-11/uri-quick-linker/assets/57516026/c086b7c7-dbc0-40bc-be0e-68a306ec9416

## Usage
The extension gives you two options on the right click context menu: 
- Copy URI and Line Number
- Paste Commented URI
- Format Commented URI's
  - Sometimes the extension glitches and doesn't turn the URI into a link. This option will format the URI into a link.

## Config
There are three settings that can be changed: 
- uriQuickLinker.useVSCodeInsiders : boolean - Set to true if you use a vscode insider build
- uriQuickLinker.fileTypes : object - Set different prefix and suffixs for different file types

## Development
To work on the extension, simple clone the repo, and run ```yarn install``` to install the dependencies. Then run the VS Code command ```Start Debugging``` to start the extension in a new window.

## Acknowlegements

My extension is heavily based off [Elliot Betancourt's Extension - hipdot-vs-code-url-scheme-grabber](https://github.com/ebetancourt/hipdot-vs-code-url-scheme-grabber/tree/main?tab=readme-ov-file) which is heavily based off the hardwork of [Nisanth Chunduru's Extension - vscode-copy-filepath-with-line-number](https://github.com/nisanthchunduru/vscode-copy-filepath-with-line-number).

Big thanks to both!

