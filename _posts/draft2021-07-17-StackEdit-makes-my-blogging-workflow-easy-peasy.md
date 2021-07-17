---
toc: true
layout: post
description: This post describes my blogging workflow.
image: images/simplified-blogging.jpg
categories: [blogging, markdown, stackedit, colab]
title: StackEdit makes my blogging workflow easy-peasy

---

![](https://github.com/howard-haowen/blog.ai/raw/master/images/simplified-blogging.jpg "Credit: John Atkinson")

# StackEdit makes my blogging workflow easy-peasy

**FastPages** supports blog posts in three file formats, including `.ipynb` for Jupyter, `.md` for Markdown and `.docx` for Microsoft Word. Each type of formats is supposed to be saved in a dedicated folder, respectively named `_notebooks`, `_posts`, and `_word` by **FastPages**. I've been using **Colab** to write posts in `.ipynb` because publishing them is as easy as saving them to **GitHub**. This can be done on **Colab** by doing:

> File >  Save a copy in GitHub

Then all you need to do is select your **FastPages** repo and the `_notebooks` folder. But as for posts in `.md`, the workflow was not as smooth. 


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoidGl0bGU6IFN0YWNrRWRpdC10ZW1wbG
F0ZVxuZGF0ZTogMjAyMS0wNy0wMTdcbiIsImhpc3RvcnkiOlst
MTgzNTIyODQzMiwxNTg2OTE2MjkxXX0=
-->