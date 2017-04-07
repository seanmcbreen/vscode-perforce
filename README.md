# vscode-perforce

[![GitHub issues](https://img.shields.io/github/issues/stef-levesque/vscode-perforce.svg)](https://github.com/stef-levesque/vscode-perforce/issues)
[![Dependency Status](https://img.shields.io/david/stef-levesque/vscode-perforce.svg)](https://david-dm.org/stef-levesque/vscode-perforce#info=dependencies)  
[![Dev Dependency Status](https://img.shields.io/david/dev/stef-levesque/vscode-perforce.svg)](https://david-dm.org/stef-levesque/vscode-perforce#info=devDependencies)  
[![GitHub license button](https://img.shields.io/github/license/stef-levesque/vscode-perforce.svg)](https://github.com/stef-levesque/vscode-perforce/blob/master/LICENSE.md)
[![VS Code marketplace button](http://vsmarketplacebadge.apphb.com/installs/slevesque.perforce.svg)](https://marketplace.visualstudio.com/items/slevesque.perforce)
[![Gitter chat button](https://img.shields.io/gitter/room/stef-levesque/vscode-perforce.svg)](https://gitter.im/stef-levesque/vscode-perforce)

Perforce integration for Visual Studio Code.  Now using the SCM Provider API - resulting in a more integrated experience for Perforce in VS Code.

## Commands

* `add` - Open a new file to add it to the depot
* `edit` - Open an existing file for edit
* `revert` - Discard changes from an opened file
* `diff` - Display diff of client file with depot file
* `diff revision` - Display diff of client file with depot file at a specific revision
* `info` - Display client/server information
* `login`, `logout` - Login operations

## Status bar icons

* ![check](https://cdn.rawgit.com/github/octicons/master/lib/svg/check.svg) opened in add or edit
* ![file-text](https://cdn.rawgit.com/github/octicons/master/lib/svg/file-text.svg) not opened on this client
* ![circle-slash](https://cdn.rawgit.com/github/octicons/master/lib/svg/circle-slash.svg) not under client's root

## Source Control in VS Code

![SCM Switch](images/scm-switch.png)  

Visual Studio Code now allow to choose which [Source Control Manager](https://code.visualstudio.com/docs/extensionAPI/api-scm) to use.  
* You can find `Switch SCM Provider` in the command palette, or in the Source Control section menu
* Use the input box to create new changelists
* Right-click on file and changelist for more commands

![SCM Perforce](images/scm-perforce.png)  
Keep in mind this is still in early beta! Explore and leave your comments on [GitHub](https://github.com/stef-levesque/vscode-hexdump/issues)

## Installation

1. Install *Visual Studio Code* (1.11.1 or higher)
2. Launch *Code*
3. From the command palette `ctrl+shift+p` (Windows, Linux) or `cmd+shift+p` (OS X)
4. Select `Install Extensions`
5. Choose the extension `Perforce for VS Code`
6. Reload *Visual Studio Code*

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Requirements

Visual Studio Code v1.11.1

## Credits

* [Visual Studio Code](https://code.visualstudio.com/)
* [vscode-docs on GitHub](https://github.com/Microsoft/vscode-docs)

## License

[MIT](LICENSE.md)
