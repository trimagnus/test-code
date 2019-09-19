# test-code Cheat Sheet
A place to stash my learning experiences.
There will be no rhyme or reason here. Be warned ;)

[Markdown Cheatsheet](https://help.ghost.org/article/4-markdown-guide)

### Crouton/Linux Dev Notes
To copy into Nano from clipboard: `ctrl+shift+v`

Open terminal: `ctrl+alt+T`

... then `shell`

Single app window: `sudo enter-chroot xiwi [-T|-F] <appname>`

*Note: May require preventing forking for some apps*

Also note: `sudo enter-chroot -b xiwi <appname>` runs in background process. To fully close this window, use `ctrl+alt+shift+esc`.
  
Full Desktop: `sudo startxfce4`

Desktop in tab: `sudo startxfce4 -n <chroot-name> -X xiwi-tab`

Use Chomebook browser as default in xfce:
1. Go to Applications->Settings->Preferred Applications from the main XFCE menu
2. On the Web Browser drop-down list, click the down arrow to the right, then pick "Other"
3. From the resulting **Choose a custom Web Browser** dialog, paste in `croutonurlhandler "%s"`, then click on the Ok and then Close buttons.

### Useful Linux utilities
* Nano
* Git
* Node
* Visual Studio Code (yes, it's great)
** Bracket pair colorizer, live-server, ES6 Code Snippets

### Node/JS notes
`npm init` -> `nano .gitignore` -> *In .gitignore* `/node_modules`
## Array methods with examples
* Find
* Filter
* Map
* Reduce
* ForEach

## Misc JS
`'use strict';`
`this`
Promises | `async / await`
DOM manipulation

## Technologies to learn
* node.js
* [express](http://expressjs.com/)
* React
* Webpack
* Mocha
* [sass](https://sass-lang.com/)
* [grunt](https://gruntjs.com/) / [gulp](https://gulpjs.com/)
* [MongoDB](https://www.mongodb.com/) (or other database?)
* [pm2](http://pm2.keymetrics.io/)
