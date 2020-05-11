# So you want to be a programmer

Most of us start programming in a single language. Yet, we quickly learn a program rarely lives in a single format or in a single environment. For the sake of it being useful, it must be adaptable, accessible to others and extensible.

This guide is an effort to introduce prospective programmers (some of them family members) into the tools that make for good programming. And to give strategies for busting through programming roadblocks. It is *not* to teach more about a specific substantive computer language or to create a web developer.

Below is a list of terms and tasks to make you a better user of available tools.  The have proven invaluable to me, although I've often discovered them in the agony of frustration and on accident.  Becoming better acquainted with the tools of the coding trade will help you be a better and more efficient programmer regardless of language. And besides, you have to do something when you're quarantined at home!

(WARNING:  I'm on a mac!)

# github (1 hour)

Go where the programmers are and use version control.

- register for account
- public vs. private accounts
- install github on computer
- create repo for programming
- create README.md
- place code into gist
- search for languages of interest
- delete repo

# stackoverflow (20 min.)

Your question was already asked--so don't bother someone else without looking for it first.

- register for account
- find "about" page for language of your choice
- search for questions with tag "[language]"

# atom (2 hours)

Even with an IDE, you need a good text editor.

- register for atom account
- install packages
- syntax highlighter
- linter
- indentation settings
- sublime functionality
- markdown writer
- markdown preview
- markdown cheatsheet
- code folding
- commenting
- bracket matching
- beautify

# terminal (2 hours + as much as you can stand)

Quit avoiding the terminal.  You're trying to be a programmer for Pete's sake.

- How to access it.
- What is a shell? How many are there?
- Can you customize?
- Top commands:
- "ls" "pwd" "cd" "mv" "rm" "touch" "mkdir"
- flags
- man-help
- "/"--root
- "~"--home
- what is tag on SO?
- is there an "about" page?
- hidden files/dot files
- environmental variables (printenv)
- great [article](https://www.twilio.com/blog/2017/01/how-to-set-environment-variables.html) on environmental variables
- `printenv` and `echo $PATH`
- Define "relative path".
- Define "absolute path".
- sudo
- try customizing if on a mac.  (oh-my-zosh)

# webpages (30 min.)

You creation isn't helpful unless someone can find it.  Some knowledge of webpages is necessary.

- What is a web browser?
- Name in descending order browser popularity
- Find page source code in your browser
- save [washington post](https://www.washingtonpost.com) to the desktop
- open the page in atom
- `beautify` the code
- collapse irrelevant sections
- open page in browser debugger
- how many lines of code are in the `<head>`?
- how long did it take for the page to load in the browser?
- open graph tags / twitter cards / debugger


# development (20 min.)

Know the lingo.

- what is "mobile-first"?
- what is "responsive web design"?
- define breakpoints
- packages
- libraries
- bundlers
- package manager

# linters (20 min)

Get some help when debugging.

- [geojson](http://geojson.io/#map=2/20.0/-0.2)
- [html & others](https://www.freeformatter.com/html-validator.html)
- [C# linting article](https://medium.com/@michaelparkerdev/linting-c-in-2019-stylecop-sonar-resharper-and-roslyn-73e88af57ebd)
- [Article on Linting](https://medium.com/loodos/whats-the-lint-er-7c21057f4088)

# APIs (1 hour)

You are going to use them a lot so know something about them.

- what are they?
- what is http?
- Know what a [curl](https://en.wikipedia.org/wiki/CURL) request is.
- [Curl tutorials](https://ec.haxx.se)
- JSON is the primary way data is transported via internet.
- go to the terminal and enter `curl -i https://api.github.com/users/octocat/orgs`
-  what is status code 200?
- see [dogs](https://httpstatusdogs.com)
- see [cats](https://http.cat)
- authentication--OAuth

# cheatsheets (20 min.)

Can be really useful, especially when getting started.

- [Regular expression syntax cheatsheet](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet)
- [R studio Cheatsheets](https://rstudio.com/resources/cheatsheets/)
- [C#](https://hackr.io/blog/c-sharp-cheat-sheet)
- [bootstrap](https://hackerthemes.com/bootstrap-cheatsheet/)

# regex

- [W3](https://www.w3schools.com/jsref/jsref_obj_regexp.asp)
- [About page on stackoverflow](https://stackoverflow.com/tags/regex/info)
- `[regex]` tag can be used on stackoverflow
- Friedl is widely regarded for his [book](http://shop.oreilly.com/product/9780596528126.do).
- practice regex wth [regexone](https://regexone.com)


# W3schools (2-3 hours)

- [W3](https://www.w3schools.com) teaches via minimal working examples.
- Complete lessons in this order:  html, css, bootstrap, js, jquery

# Project 01 (20 min.)

- create folder `myWebpage01`
- cd into `myWebpage01`
- touch `index.html`
- open atom add `myWebpage01` as project in sidebar
- go to [html shell](http://htmlshell.com) & copy html into `index.html`
- include `<img>` from [unsplash](https://unsplash.com).
- install bootstrap from [here](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
- serve `index.html` to local 127.0.0.1:3000
- open page in browser debugger
- find & fix warnings and error messages
- create & push project to github repo
- include .gitignore, README.md, & MIT license
- create website via project setting in github
- add project tags

# Project 02 (30 minutes)


- create folder `myWebpage02`
- cd into `myWebpage02`
- touch `index.html`
- open atom add `myWebpage02` as project in sidebar
- install bootstrap from [here](https://getbootstrap.com/docs/4.4/getting-started/introduction/) using CDN.
- What does "CDN" mean?
- include `<img>` from [unsplash](https://unsplash.com).
- serve `index.html` to local 127.0.0.1:3000
- open page in browser debugger
- find & fix warnings and error messages
- create & push project to github repo
- include .gitignore, README.md, & MIT license
- create website via project setting in github
- add project tags

# Project 03 (1 hour)

- create folder `myWebpage03`
- cd into `myWebpage03`
- touch `index.html`
- open atom add `myWebpage03` as project in sidebar
- follow W3 [tutorial](https://www.w3schools.com/howto/howto_website_bootstrap4.asp).
- include `<img>` from [unsplash](https://unsplash.com).
- serve `index.html` to local 127.0.0.1:3000
- open page in browser debugger
- find & fix warnings and error messages
- create & push project to github repo
- include .gitignore, README.md, & MIT license
- create website via project setting in github
- add project tags

# Cross-Programming Expertise

You'll run into these three topics no matter where you go.  If you know them well, you'll thrive.

- APIs & CURL
- regex
- dates
