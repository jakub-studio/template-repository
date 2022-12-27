# TypeScript template repository
A quick minimal template aimed to get you going without fumbling over small repeated configs.

**This template is geared primarily towards [JavaScript](https://en.wikipedia.org/wiki/JavaScript)/[TypeScript](https://www.typescriptlang.org/) projects and editing with [Visual Studio Code](https://code.visualstudio.com/). If your project/workspace is something different, it is advised you go over the template contents and configure it for your needs.**

## Template preferences
This template is opinionated, which means that it's configured for the following:
- All line endings are `\n` (LF) instead of `\r\n` (CRLF).
- Visual Studio Code should use the typescript version located in `node_modules` (if installed)

## Features
- `.gitignore` - [Git Ignore File]() 
	- The included `.gitignore` is the [`Node.gitignore`](https://github.com/github/gitignore/blob/main/Node.gitignore) from the [`github/gitignore`](https://github.com/github/gitignore) repository
- `.gitattributes` - [Git Attributes File](https://git-scm.com/docs/gitattributes)
	- Configured to ensure all text files are not treated as binaries.
	- Code files are formatted with LF line endings
- `.vscode/settings.json` - [Workspace settings for Visual Studio Code](https://code.visualstudio.com/docs/getstarted/settings#_workspace-settings)
	- Treat all code files to end with LF line endings.
	- Use `node_modules/typescript` version if installed (this ensures consistent Type Checking across development environments which may have different Visual Studio Code versions installed)

## How to use it
<img width="1012" alt="GitHub page of jakub-studio/template-repository showing the 'Use this template' feature" src="https://user-images.githubusercontent.com/34782021/209727530-448aa11d-537d-42af-9304-65dac837f907.png">
Click `Use this template` on the top right of this repository on GitHub web and then click either:

1. Create a new repository
2. Create a new codespace

_Option 1 is recommended for most users unless you are specifically using [GitHub codespaces](https://github.com/features/codespaces) for your project_

### Next steps
After you have created a new repository from this template, it is advised to do the following:
- [ ] Update the `README.md` file to reflect your project
- [ ] Update the `LICENSE` file to reflect your project
	- The template uses [The Unlicense](https://unlicense.org/). It is important that you change this to a license of your choosing unless you wish to use The Unlicense. If you are unfamiliar with open source licensing, I suggest you give [this website](https://opensource.org/licenses) a visit.
- [ ] Run `npm init` within the project folder
- [ ] Run `npm i typescript` (if using)

After that, you are good to go! Happy coding!

Any issues or suggestions? Feel free to open an issue or a pull request!