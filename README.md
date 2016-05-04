# UnusedCssFinder-Sublime
> Only supports **Sublime Text 3**.

Sublime plugin to find unused css names

Author: Jannis Harder: jannisharder@hotmail.de

Last modified: 4 May 2016

Plugin to find unused css names in current active css file. Searches for all id and class names inside current open project or file directory if no project is currently open. All css names that do not occur once in any other .php, .html, .xhtml or .js file is highlighted.

Might run slow on big projects, do not hesitate to send me improvement recommendations as this is my first sublime plugin.

#### Usage
Recommended:
Go to `Package Settings` `->` `Key Bindings - User` and add:

{ "keys": ["ctrl+u", "ctrl+f"], "command": "unused_css_finder"}

Then open any *.css fileand press `ctrl` + `u` + `f` to search for unused css ids and classes. The package searches for occurences in your currently open project or in the files location if no project is open at the moment. All unused css names will be highlighted in the search and you can remove that highlighting with pressing the same key-shortcut again.
