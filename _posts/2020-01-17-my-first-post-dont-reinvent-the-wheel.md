---
toc: true
layout: post
title: My First Post
description: Don't reinvent the wheel.
categories: [awesome-list, fastpages]
image: images/reinvent-the-wheel.jpg

---
# My First Post: Setting tone for this blog

![]({{ site.baseurl }}/images/reinvent-the-wheel.jpg "Credit: JohnHartStudio.com")

## There's always an awesome list for X.

`Don't reinvent the wheel` is something you'll hear a lot in the field of technology. That means, whenever possible, try to use existing tools out there instead of building from scratch. If you use GitHub long enough, you probably already know this: for almost everything you'd like to learn, there's an awesome list for that, which collects all sorts of awesome resources, including tools and tutorials. All you need to do is search for `awesome X` on GitHub. Or better yet, there's even a meta list of awesome lists on various topics, like [sindresorhus/awesome](https://github.com/sindresorhus/awesome). Included in it is an awesome list for linguistics, [theimpossibleastronaut/awesome-linguistics](https://github.com/theimpossibleastronaut/awesome-linguistics), which is a good place to start learning about natural language processing (NLP) if you are a humanities major who knows nothing about programming, as I was about one year ago. To take one more example, I wish I had discovered [keon/awesome-nlp](https://github.com/keon/awesome-nlp) much earlier, which could've saved me lots of time when I was still fumbling around and trying to wrap my head around how a tool, say `gensim`, fits into the broader picture of NLP. But sometimes the name of an awesome list doesn't have the keyword `awesome` in it, such as this gem [ivan-bilan/The-NLP-Pandect](https://github.com/ivan-bilan/The-NLP-Pandect). In my opinion, although an awesome list by any other name would be as awesome, the The-NLP-Pandect repo would have got much more stars if `awesome` were in its name.     

## But the hardest part is to get the ball rolling.

However, awesome as they are, awesome lists can be quite intimidating to go through and easy to get lost in. And even when you are lucky enough to finally come across an awesome tool that you wanna try out, it sometimes takes lots of trials and errors to figure out the right way to get the ball rolling, especially when you are a fresh programmer. So on this blog, I plan to add my personal touch to various tools, documenting not only what I did right to get the ball rolling, but also what I did wrong to save you (or even future me) from abysmal frustration. For almost every tool, there is already a wide specturum of instructional documents available online, ranging from hardcore official documentations to professional posts on platforms like Medium. And this blog is meant to be a friendly complement to those. I'll be writing in plain language because I was not trained for computer science or programming anyway. 

## The fast stack

I'd like to start with a series of tools that I dub `the fast stack`, including `fastpages`, `fast.ai`, `fastText`, and `fastAPI`. Designed by the fast.ai team, `fastpages` is basically a  template for creating a blog (like this one!) and does lots of awesome things for you hehind the scenes. Features that I like about it include:

- automatically converts `.md` and `.ipynb` files on GitHub to posts on your website
- automatically adds links to Colab and GitHub
- shows interactive visualizations of the output of codes
- supports comments 
- is free from end to end

Truth be told that I actually failed twice before I successfully set up this blog. The lesson learned is this: **do exactly what's said on the [instructions](https://github.com/fastai/fastpages)!** Humanities majors like me are often taught to be creative, but be sure to leave your creativity at the door when you set up computer programs. This then concludes my first repo. Nothing is super technical here since it's just a warm-up. I'll save other tools in the fast stack for another day. 

{% include info.html text="I was clueless when I read PR in the instructions. It turns out to mean 'pull requests'. Click on the tab that says 'pull requests' when you are done forking the original repo. Then you're good to go by following the instructions there." %}
