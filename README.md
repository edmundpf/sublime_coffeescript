# Sublime Coffee
> Adds Text Highlighting and Keyboard shortcuts for Coffeescript to Sublime Text 3 ☕

## Installation/Usage
* Clone the Repository
	``` bash
	git@github.com:edmundpf/sublime_coffeescript.git
	```
* Open Sublime Text User Packages Folder
	* In the Sublime Text menu: `Preferences > Browse Packages...`
	* Navigate into *User* folder
* Copy Files
	* Copy the *custom_coffee.sublime-syntax* and *custom_coffee_comments.tmPreferences* files to the *Packages/User* folder you opened
* **DONE!!!**
## New Features
* Adds highlighting for Coffeescript template/interpolated strings
* Functions are highlighted with use of parentheses ()
* Node.js/Babel keyword highlighting (export, import, module.exports, etc..)
* Coffeescript style function highlighting
## To-Do/Incomplete minor issues
* Feel free to help tackle these issues/problems I've ran into with the syntax highlighting, just put in a pull request!
* **Add proper regex highlighting**
* **Proper function highlighting when function continues on next-line**
* **Proper formatting of booleans and types in functions** - i.e. *true, false, null* etc. should be shown as purple, not orange
## Contributing
* Just put in a pull request with enhancements/fixes/new features and I'll review it then merge the changes, I plan to keep this repository active, thanks!