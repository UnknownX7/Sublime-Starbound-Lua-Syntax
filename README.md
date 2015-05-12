# Starbound Lua

This plugin enables syntax highlighting and autocompletion for Starbound Lua in [Sublime Text 2](http://www.sublimetext.com/2) or [Sublime Text 3](http://www.sublimetext.com/3). (Sublime Text 3 is HIGHLY recommended!)

To install this, it is recommended that you use [Package Control](https://packagecontrol.io/installation) to automatically receive the latest updates and make the entire process much simpler. This will ensure that you do not need to check this page for updates every time an update is released for Starbound as the API is constantly changing and being added to.

### Package Control Installation:
1. Open Sublime Text and press <kbd>Shift+Ctrl+P</kbd>.
2. Type `install` and press enter.
3. Another text box should appear, type `Starbound` and you should see this plugin highlighted. Press <kbd>Enter</kbd> to install it.

#### Sublime Text 3 (and possibly 2)
1. Once you have it installed you may need to disable the default Lua syntax (Sublime will probably try to suggest functions from default Lua). Press <kbd>Shift+Ctrl+P</kbd> again.
2. Type `disable` and press enter.
3. Type `lua` and press enter.

### Manual Installation:
1. Download this Git Repository's master branch as a `.zip` file. (Or you can download the latest [release](https://github.com/UnknownX7/Sublime-Starbound-Lua-Syntax/releases).)
2. Navigate to `Preferences > Browse Packages...`.
3. Put the folder from the `.zip` into the location that was opened.
4. Restart Sublime.

#### Sublime Text 3 (and possibly 2)
1. Once you have it installed you may need to disable the default Lua syntax (Sublime will probably try to suggest functions from default Lua). Navigate to `Preferences > Settings - User`.
2. Add the following text:
```
{
	"ignored_packages":
	[
		"ASP",
		"Vintage",
		"Lua"
	]
}
```

### Usage
Navigate to `View > Syntax > Starbound Lua` to apply the syntax to the current file and any newly opened files.

There are also custom templates for groups of specific lua hooks with documentation available. To use them, type `TEMPLATE` and use the arrow keys to select the correct template for your `.lua` file, then press <kbd>Tab</kbd> or <kbd>Enter</kbd>. These are intended for blank files and will immediately paste all known lua hooks for the selected category. You may press <kbd>Tab</kbd> again multiple times to highlight a predetermined order of text blocks for ease of editing. Moving your text cursor outside of the range of one of these text blocks will end the use of <kbd>Tab</kbd> selecting for all code snippets. These snippets will use hook information from the developers when available. Otherwise it is information gathered by trial and error.

#### If you have other custom Lua syntaxes...

#### Suggestions
Open an issue if you would like to suggest anything. Or you can find me on the #starbound and ##starbound-modding IRC channels as `UnknownX`. (or the forums)

#### Nightly Branch
This branch is for upcoming changes to the Lua API. This will not be merged with the master branch until a stable update is released and changes are verified.