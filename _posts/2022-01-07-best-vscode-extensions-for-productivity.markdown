---
layout: single
title:  "Best vscode extensions for productivity"
date:   2022-01-07 10:40:22 +0200
categories: vscode software
comments: true
toc: true
toc_label: "Table of content"
toc_icon: "cog"
header:
    overlay_filter: "0.6"
    overlay_image: "assets/images/board.jpg"
    show_overlay_excerpt: false
---

# Introduction
I have been using [vscode](https://code.visualstudio.com/) for over 2 years now and i'm in love. 
It's been a long time since I was so happy about microsoft products and vscode is killing it. If you have yet to discover this tool, 
it's an open-source IDE with marketplace, intended to be a lightweight (yet powerful) version of visual studio with the goal in mind
to be able to support all languages.

It's pretty simple to install, it's free for all uses and it is compilable with windows, mac, and linux.
You can download it [here](https://code.visualstudio.com/#alt-downloads).

So as mentioned earlier, vscode derives most of it's powerful features from other open source extensions built by community members. 
I will list all of the extensions that I regularly use and point out the main features that I like about them the most. 
Please feel free to PM and show me other extensions to add to this list. 
I will add a simple code snippet to easily install all the extension list in 1 simple command. 

Let's start. 

# Extensions

## [Github copilot](https://copilot.github.com/)

Ok, wow. Github copilot is on closed beta phase that anyone can register. I have registered 2 month ago and got my access a couple weeks ago. This is crazy good. Github copilot uses github NLP engine to assist programmers with their work. In it's simplest form, you write the function declaratio, and BOOM you get the function content. I am using it all the time. If you are into ML, try for example to declare
 ```
 def get_mnist_dataset():
 ```
 And then you can even try to do:

 ```
 def train_on_mnist():
 ```
Prepare to be amazed. Registration is [here](https://github.com/features/copilot/signup)

## [Remote development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

This extension blew my mind when I started to heavily work with multiple remote SSH clients. With this extension, one can connect to remote 
ssh clients and code inside the vscode while working on remote files seamlessly. This also works seamlessly with dockers too!

![remote development demo](/assets/gifs/ssh-readme.gif)

## [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)

This one is linearly related to the last one. Now that you have remote development set up, and you work on several machines at ones. All of those windows might get a bit confusing. This is where Peacock gets in. One can easily give is of his machine a distinctive color to the IDE to differentiate and avoid making fatal errors where you should'nt. 

![peacock showcase](/assets/gifs/peacock.png)

## [Git graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)

Sweet visual extension for viewing you git graph with all of his branches checkouts stashes etc. You can even checkout straight from the
graph and easily go over commits from previous checkouts.

![git graph demo](/assets/gifs/git-graph-demo.gif)

## [Markdown All in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

I'm using markdown a lot! Readmes, documentation... heck, even this post is written with markdown! So an helper extension for markdown, for me
is mandatory. This extension let's you do
-  an automatic table of content
-  font types (bold, italic, ...) with keyboard shortcuts, 
-  GitHub flavored markdown
-  Math with latex
-  autocompletion
-  pasting a link into a word.

And much more. I'll let you explore it by yourself. 

## [Material icon theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

This one is simple and elegant. By changing the visuals of the icons in the navigation menu, one can easily navigate and find
what he searches for. 

## [Python docstring generator](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)

Documentation is important but hard to be consistent about. So an extension that ease your life and make it's easier is a treat. Python docstring generator generates with a click a template with desired format (can be configured to google, numpy, w/e) with placeholders for the deduced variables and outputs. Very cool. 

![python docstring demo](/assets/gifs/docstring-demo.gif)

## [Python indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent)

Another cool and simple extension that helps you keep your indentation right!

![python indent](/assets/gifs/python-indent.gif)

## [Code time](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode)

As a data freak, I fell in love with Code time. This extensions tracks your activity and monitor your productive hours, along the active coding time, idle time and other interesting metrics that are fun to watch and analyze at the end of the week. 

![codetime demo](/assets/gifs/codetime.png)


<!-- ## Github pull request and Issues

## Cmake

## Code stream -->

<!-- {% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->
