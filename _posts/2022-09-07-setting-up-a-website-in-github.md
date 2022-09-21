---
layout: post
title: "Setting up a website with Github"
subtitle: ""
date: 2022-09-08
background: '/PATH_TO_IMAGE'
---
**Github** : *is a code hosting platfrom for version control and collaboration*


Go to Github website and make an account is will keep your your website running


**Terminal**: *is a simple text based interface to the computer,in terminalyou can type commands, manipulate files, execute programs etc*


via terminal you will be coding everything from the next steps and on


**Jekyll**: *is a static site generator with build in support for github pages*


Download Jekyll and follow the instruction from the website below


**Ruby**: *is a scripting language designed for front- and back-end development*


Download ruby via terminal or their website, attention to download a version higher that 2.5.0


**Ruby installer**: *provides developers working windows systems a quick and easy way to begin developig ruby*


Download ruby installer if you afre working on windows here it ask you to add extra gems you can all add them via terminal again


**webrick**: *is a library providing simple HTTP web server*


downloading webrick gem will help you eventually for your site configurations you can add it with the command: bundle add webrick


**MSYS2**: *developent tool machine: is a Software Distribution and Building Platform for Windows*



**Gitbash**: *is an application for Windows enviroments that provides an emulation layer for Git command line experience*


**Github desktop**: *enables you to intercat with Github using GUI instead of a web browser*


Download github desktop to code in remote areas and not having to enter agin in the website

**Visual Studio Code**: *source code editor that can use different coding languages*


Finally, download VSC to do change on your selected template and run your website



**PROBLEMS SOLVING**


Visual studio code starting up


Templates problems


URL problems encounters:

Encoutered few troubleshooting problem and the source was the url my website wasn't uploading the theme only the text. Following the instruction in that website I've changed the "url" to simple url and 
#comment out the base url.


https://mademistakes.com/mastering-jekyll/site-url-baseurl/#markdown-links


permalink:


Permalinks are the output path for your pages, posts, or collections. They allow you to structure the directories of your source code different from the directories in your output.

markdowns:


markdowns and posts generally follow standard naming conventions of YYYY-MM-DD-filename.md inside of a _posts directory, like this you'll be alble to track down your file, then every file should start as follows


---
layout: post
title: "file title"
subtitle: ""
date: 2022-09-08
background: '/PATH_TO_IMAGE'
---


https://www.markdownguide.org/cheat-sheet


helpfull coding commands:


gem install jekyll bundler//jekyll new myblog//cd myblog//bundle exec jekyll serve//jekyll trace//git add .//git commit -u//git commit -a//git push//

code --help
