Title: Figuring_Out_a_Workflow    
Date: 2015-10-11 22:47    
Tags: Pelican, Work-flow, Python, Github    
Category: Geekery    
Slug: Figuring_Out_a_Workflow    
Author: wdougwatson    
Summary: In this post I try to detail where I'm at with using Pelican as my cms.    

# Groping for My Ass With Both Hands

I managed to make my [first post]( http://wdougwatson.github.io/Welcome%20to%20My%20Brain%20Dump.html "Welcome to My Brain Dump") using [Pelican](http://blog.getpelican.com/ "Pelican") and while it wasn't overly complicated the sheer number of steps involved has left me confused. I'm sure that I'll memorize all the steps eventually but right now I'm constantly checking one browser window or another to find what I need.   

This isn't all due to Pelican, rather, I'm to blame. Most of my life I've been a tinkerer. Ive never stuck with anything long enough to really learn it thoroughly. This is all compounded by the fact that for a couple of years now I've done nothing but watch TV and read comic books. Back when I was running a self hosted Wordpress blog I got pretty good at hacking out solutions on my own install but that was about eight years ago.    

## Why Am I Putting Myself Through All This?
There are really two answers to that question. The first answer is that I miss blogging. I could blog on [Wordpress.com](http://wordpress.com "Wordpress") or [blogger](https://www.blogger.com "blogger") but honestly neither of those solutions appeals to me. They just don't allow enough control over my site. Also blogger is just complete shit. I could opt to self host a wordpress site but in my home server testing I just find wordpress too damned bloated. Using Pelican and Github I have total control of site design with a local backup. I can write in MarkDown and produce static pages that are bloat free. The second answer is that I need to learn stuff. Doing things this way will force me to actually learn MarkDown instead of just pecking around with it.  **Before yesterday I didn't know shit about Git**. Now I have a working knowledge. I am by no means a master but I can manage my local repos.    

##  Where I AM So Far
I'm currently following several tutorials until I get a flow going. For Git I've kept three tabs open in Chrome - [Git Magic](http://www-cs-students.stanford.edu/~blynn/gitmagic/ch02.html#_saving_state "Git Magic"), [this page on the Github documentation site](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/ "Github docs"), and [a question on Stack Overflow](http://stackoverflow.com/questions/6373277/git-sync-local-repo-with-remote-one "Stack Overflow"). There are three because tather than read each of the documents in its entirety I use Google kinda like a table of contents for the internet (I'm still a tinkerer).  I have also have three tabs open concerning Pelican - [migrating to github pages using pelican](http://mathamy.com/migrating-to-github-pages-using-pelican.html "migrating to github pages using pelican"), [a page from the pelican docs](http://docs.getpelican.com/en/3.1.1/getting_started.html#installing-pelican "pelican docs"), and [how to setup github user page with pelican](http://ntanjerome.org/blog/how-to-setup-github-user-page-with-pelican/ "how to setup a github user page with pelican"). Each of these does the same job in a slightly different way. The [first](http://mathamy.com/migrating-to-github-pages-using-pelican.html "migrating to github pages using pelican") has you make your git repo in the content folder. I had already initiated my repo however and didn't want to go this route. The [docs](http://docs.getpelican.com/en/3.1.1/getting_started.html#installing-pelican "how to setup github user page with pelican") page is important because it discusses the meta information you need to put at the start of your .md files. [How to setup github user page with pelican](http://ntanjerome.org/blog/how-to-setup-github-user-page-with-pelican/ "how to setup a github user page with pelican") uses [ghp-import](https://pypi.python.org/pypi/ghp-import "ghp-import") to create your actual page.
## Problems

Other than just not having the whole process down pat I have one serious issue. The actual generation of my site has wiped my source files. The site files are there and having a website is the point but this means I have to repeat many steps each time I do a post. To me this seems silly. I'm sure there is something I'm missing and I'll do some more lookingbut for now the process seems rather unintuitive.
## The Actual Writing

Any text editor could be used to write the MarkDown files. For my first post I used [Joe](http://joe-editor.sourceforge.net/ "THE BEST CONSOLE BASED TEXT EDITOR!") because it is without a doubt my favorite command line text editor. However, I wanted an editor with MarkDown preview. For this reason I'm using [Atom](https://atom.io/ "Pretty cool editor")   
## Conclusion
There simply isn't one right now. As I said, Im confused. But I will tinker on. Hopefully this time my tinkering will result in some concrete knowledge.
