## Project setup and Gulp installation
FastShell utilises open source components running on the Terminal/command-line for it's workflow, you'll need to install Node and Gulp. Here's a walkthrough of how to get a project up and running in minutes. Once Node and Gulp are installed all future projects running Gulp are instant.

1. Install [Node.js](http://nodejs.org/download), [Sass](http://sass-lang.com/tutorial.html) and [Git](http://git-scm.com) on your machine. If you're a Windows user you'll also need to install [Ruby](http://rubyinstaller.org/downloads).
2. [Install Gulp](http://Gulpjs.com/) using `npm install -g gulp`. You may need to use `sudo` in front of the Gulp install command to give it permissions.
3. Fork/Clone/Download the FastShell repository into your machine, you should hopefully see all the files and folders.
4. Open Terminal and install FastShell's dependencies to `node_modules` directory in your project directory using `npm install`. You don't need `sudo` to do this.
5. The `npm install` you did in previous step should install all the dependencies, which you can confirm by visiting the `node_modules` in your project directory. Then use `gulp` (again in your project directory) to run the commands associated with FastShell and to automatically open a new FastShell project running on `localhost:3002`.
6. From now on, just run `gulp` in your project directory to automatically run FastShell's Gulp tasks.

# FastShell
[![Build Status](https://travis-ci.org/HosseinKarami/fastshell.png?branch=master)](https://travis-ci.org/HosseinKarami/fastshell)

inspired by [FireShell](http://getfireshell.com)
Fiercely quick front-end boilerplate and workflows.

The opinionated FastShell framework. Built for the modern developer. For teams and the individual, encouraging a better workflow. JavaScript task running, build processes, autominification and file concatenation, wrapped with an enhanced HTML5 boilerplated framework.

* Source: [github.com/HosseinKarami/fastshell](http://github.com/HosseinKarami/fastshell)
* Documentation: [DOCS.md](https://github.com/HosseinKarami/fastshell/blob/master/DOCS.md)
* HomePage: [Fastshell](https://HosseinKarami.github.io/fastshell)


## License

#### The MIT License (MIT)

Copyright (c) FastShell

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
