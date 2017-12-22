# resources 
In case they're helpful. Find the topic below or use Ctrl/Cmd + F to find what you're looking for quickly. 

## *Topics*  
* [Code Editors/IDEs](#code-editors)
* [Code Environments](#code-environments)
* [CSS](#css)
* [Debugging](#debugging)
* [Design](#design)
* [Express](#express)
* [Git](#git)
* [HTML](#html)
* [Hosting](#hosting)
* [JavaScript](#javascript)
* [Pay to learn](#pay-to-learn)
* [Massive](#massive)
* [Markdown](#markdown)  
* [Node](#node)
* [React](#react) 
* [Redux](#redux)
* [Regex](#regex)
* [SVG](#svg)
* [SQL](#sql)
* [Terminal](#terminal)
* [Tools](#tools)

### Code Editors
#### [VS Code](https://code.visualstudio.com/)
* [JavaScript in VS Code](https://code.visualstudio.com/docs/languages/javascript#_automatic-type-acquisition)
* [Chrome Debugger for VS Code](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)

##### Jump to variable definition
Hold command (⌘) on Mac or control on Windows before clicking on a reference to a variable to jump to that variable's definition.

##### Display Preview of Markdown
To switch between views, press ⇧⌘V in the editor. You can view the preview side-by-side (⌘KV). ([Source](https://code.visualstudio.com/docs/languages/markdown#_markdown-preview))

##### Open New Terminal With Keyboard
`Ctrl` + `Shift` + `~`

##### Time Savers
###### Macs
* `Cmd ⌘` + `Shift ⇧ ` + `p` shows keyboard shortcuts.
* Hold down option and arrow key to move an entire line up or down.  
* Hold down option and click in multiple places to create multiple cursors.  

### Code Environments
https://repl.it (Online REPL, compiler, and IDE)  
http://www.pythontutor.com/visualize.html (Includes languages other than Python, including JavaScript. Allows you to visualize code execution and see the control flow.)  
https://www.getpostman.com/

### CSS  
#### Flexbox
http://geddski.teachable.com/p/flexbox-zombies  
http://flexbox.help/

#### Fonts
https://fonts.google.com/  
https://kyleschaeffer.com/development/css-font-size-em-vs-px-vs-pt-vs/  
#### Parallax
http://scrollmagic.io/  

#### Shapes
https://css-tricks.com/examples/ShapesOfCSS/

### Debugging
https://developers.google.com/web/tools/chrome-devtools/  
https://developers.google.com/web/tools/chrome-devtools/javascript/  

### Design
#### Getting inspiration/ideas
https://www.awwwards.com/

#### Colors
https://color.adobe.com/  
https://coolors.co/

### [Express](https://expressjs.com/)

### HTML
#### Color code helps
https://html-color-codes.info/  
https://html-color-codes.info/colors-from-image/ - Upload an image and get a color code by clicking on any part of it.

### Git
#### Commands
##### Change URL of remote 
<pre>git remote set url <em>https://url-of-repo</em></pre>
##### When git opens Vim and asks for a commit message (and you want to exit)
`:q!`  
The `:` tells Vim to enter command mode, the `q` tells Vim to quit, and the `!` means you really mean it.

### Hosting
https://zeit.co/docs  
https://surge.sh/ - For front-end development

### JavaScript
#### Reference
Mozilla Developer Network (MDN) - https://developer.mozilla.org/en-US/docs/Web/JavaScript
#### Practice Problems
[Codewars](https://codewars.com/) - "Achieve code mastery through challenge"  
[CodeFights](https://codefights.com/) - Interview Practice, Challenges, Arcade, Head-to-Head, Company Bots, Tournaments

#### 'this' in JavaScript
http://yehudakatz.com/2011/08/11/understanding-javascript-function-invocation-and-this/

### Pay to learn
Resources that cost money (but may sometimes make content available for free). Sometimes paid courses are significantly higher quality than what's available for free. (Sometimes not.)  
* https://egghead.io/

### Markdown  
https://www.markdowntutorial.com/   
http://en.wikipedia.org/wiki/Markdown#Example  
http://spec.commonmark.org/dingus/  
http://johnmacfarlane.net/babelmark2/faq.html  
http://idratherbewriting.com/2013/06/04/exploring-markdown-in-collaborative-authoring-to-publishing-workflows/  
https://www.markdownguide.org

### [Massive](https://dmfay.github.io/massive-js/)

### [Node](https://nodejs.org/en/)
[Anatomy of an HTTP Transaction](https://nodejs.org/en/docs/guides/anatomy-of-an-http-transaction/#anatomy-of-an-http-transaction)


### [React](https://reactjs.org/docs/hello-world.html)
#### Development Environment
##### Find what process is running the dev server at a specific port:
If the dev server is running on port 3000:
```
lsof -i :3000
```
This will produce some information like this: 
```
COMMAND    PID         USER   FD   TYPE  SIZE/OFF NODE NAME
Google    7257 jamescarlson   93u  IPv4       0t0  TCP localhost:55054->localhost:hbci (ESTABLISHED)
node      9614 jamescarlson   14u  IPv4       0t0  TCP *:hbci (LISTEN)
node      9614 jamescarlson   31u  IPv4       0t0  TCP localhost:hbci->localhost:55054 (ESTABLISHED)
```
Find the process ID in the PID column for COMMAND of "node". To kill that process, type `kill -9` and then the PID (in the example above, `9614`). 

<pre>
kill -9 <i>PID</i>
</pre>

### [Redux](https://redux.js.org/)
[Redux for Dummies (article)](https://hackernoon.com/redux-for-dummies-867f7aff7a2f)  
[React-Redux-Review (repo)](https://github.com/james-carlson/react-redux-review)  
[DevMountain Redux Drills](https://github.com/DevMountain/redux-drills)  
[A Dummy's Guide to Redux and Thunk in React](https://medium.com/@stowball/a-dummys-guide-to-redux-and-thunk-in-react-d8904a7005d3)
### Regex
http://regexr.com/
### SVG
http://svgpocketguide.com/book/
### SQL
https://www.sqlteaching.com/  
https://sqlbolt.com/
### Terminal 
http://osxdaily.com/2013/02/05/improve-terminal-appearance-mac-os-x/
### Tools
https://caniuse.com/ - provides up-to-date browser support tables for support of front-end web technologies on desktop and mobile web browsers.
