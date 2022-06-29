---
toc: true
layout: post
description: This post describes my blogging workflow.
image: images/simplified-blogging.jpg
categories: [blogging, markdown, stackedit, colab]
title: StackEdit makes blogging in Markdown easy-peasy

---

![](https://github.com/howard-haowen/blog.ai/raw/master/images/simplified-blogging.jpg "Credit: John Atkinson")

## Intro

[**FastPages**](https://github.com/fastai/fastpages) supports blog posts in three file formats, including `.ipynb` for Jupyter, `.md` for Markdown and `.docx` for Microsoft Word. Each type of formats is supposed to be saved in a dedicated folder, respectively named `_notebooks`, `_posts`, and `_word` by **FastPages**. I've been using **Colab** to write posts in `.ipynb` because publishing them is as easy as saving them to **GitHub**. This can be done on **Colab** by doing:

> File >  Save a copy in GitHub

Then all you need to do is select your **FastPages** repo on **GitHub** and the `_notebooks` folder. 

But as for posts in `.md`, my workflow was not as smooth until I discovered [**StackEdit**](https://stackedit.io), which is an *in-browser Markdown editor*.  So this post shows how **StackEdit** makes blogging in Markdown easy-peasy.


## Adding a workspace

Once you're on **StackEdit**, clicking on **START WRITING** is all that needs to be done to, umm..., start writing in Markdown. But what comes next is not that straightforward. It took me a while to figure it out. To sync a **StackEdit** browser instance with a folder on **GitHub**, you first need to add a workspace. This is done by clicking on the hashtag icon at the upper right corner. Then you do:

> Workspaces > Add a GitHub workspace 

Then enter your **FastPages** repo URL and the `_posts` folder path (or any other **GitHub** folder). Now if you click on the folder icon at the upper left corner, you'll see all your `.md` files in the the `_posts` folder like this:

![StackEdit-snapshot.png](https://github.com/howard-haowen/blog.ai/raw/master/images/StackEdit-snapshot.png "StackEdit-snapshot.png")

Now you can enjoy writing on **StackEdit**, and rest assured that all your local `.md` files (saved in the browser storage) will be synced with your **GitHub** folder.  

By the way, I found a trick of quickly embedding an image on **StackEdit**. Suppose you have an image file stored on **GitHub**, you can just copy that file name in the `tree` view on **GitHub** and paste it on **StackEdit**. Take the image above for example, this is what you'll see: 

`[StackEdit-snapshot.png](https://github.com/howard-haowen/blog.ai/blob/master/images/StackEdit-snapshot.png "StackEdit-snapshot.png")`

Then to display the image, you just need to add an exclamation mark at the beginning and replace `blob` with `raw`, like this:

`![StackEdit-snapshot.png](https://github.com/howard-haowen/blog.ai/raw/master/images/StackEdit-snapshot.png "StackEdit-snapshot.png")`

This trick saves you the trouble of typing out the embedding syntax. 

## Testing Markdown extensions

In addition to default Markdown syntax, **StackEdit** also supports some additional extensions, including `SmartyPants`,  `KaTeX`, and `UML diagrams`. To test if these extensions will be properly rendered by **FastPages**, I simply copied and pasted examples from **StackEdit** down below:

---

### SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


### KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoidGl0bGU6IFN0YWNrRWRpdC10ZW1wbG
F0ZVxuZGF0ZTogMjAyMS0wNy0wMTdcbiIsImhpc3RvcnkiOls4
NzE4OTk5ODMsLTM1ODY2OTU2NSwtMTU2NjQyNjA2NCwtMTUxMD
M5MjgwNl19
-->
