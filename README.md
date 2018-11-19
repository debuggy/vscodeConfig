# vscodeConfig

[![CircleCI](https://circleci.com/gh/debuggy/vscodeConfig.svg?style=svg)](https://circleci.com/gh/debuggy/vscodeConfig)

User settings for VSCode

A get started guide for quick warming up when newly installed vscode.

## Recommandations
- **Python**

  Official [python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) of vscode.
  
- **Vim**

  Edit in [vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) pattern.

- **vscode-icons**
  
  Change [icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) in file explorer.

  
- **EditorConfig for VS Code**

  [EditorConfig](https://editorconfig.org/) for VSCode. It will override user/workspace settings with settings found in .editorconfig files. The extension is really useful for cooperative developing!
  
- **StandardJS for VS Code**

  [StandardJS](https://github.com/standard/standard) is a javascript linter which make developing simple and standard. Recommend if you use javascript.

## Options
- ~~**Prettify JSON**~~

  ~~Format json files.~~ VScode now have internal format support, no need for this extension in general.

- ~~**XML Tools**~~

  ~~Format XML files.~~ VScode now have internal format support, no need for this extension in general. Generally you should consider json or yaml as config file instead of XML.

- **One Dark Pro**

  The most popular color scheme in vscode. (Although I have changed the color scheme to default dark+)

- **Swagger Viewer**
  
  View swagger file in vscode when designing REST API.

- **SVG Viewer**

  View SVG file in vscode. The simplest way to view SVG file if you didn't install any software to view SVG file.

- **hexdump for VSCode**

  Display a specified file in hexadecimal. Useful when you want to check the file encoding.


- **GitLens**

  A better git tool for VSCode. Actually I seldom used this extension even though it does have powerful functions. I prefer use git cli commands instead.

- **TSLint**

  Typescript code style checking. **Note**: there is an alternative plugin [tslint-language-service](https://github.com/angelozerr/tslint-language-service) for tslint. If you use the plugin, you should better NOT install this extension.


- To be added

## User setting file
  The [User settings config](./User_Settings.json) file could enable user to quickly warm up with a new vscode.

  Currently it mainly contains the editing config for vim extension and will be included more configs further.