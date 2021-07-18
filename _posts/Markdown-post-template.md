---
toc: true
layout: post
description: A minimal example of using markdown with fastpages.
image: images/birds-of-a-feather.jpg
categories: [markdown]
title: An Example Markdown Post

---
![](https://github.com/howard-haowen/blog.ai/raw/master/images/birds-of-a-feather.jpg "Credit: blogs.lse.ac.uk")

# Example Markdown Post

## Basic setup

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-filename.md`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `filename` is whatever file name you choose, to remind yourself what this post is about. `.md` is the file extension for markdown files.

The first line of the file should start with a single hash character, then a space, then your title. This is how you create a "*level 1 heading*" in markdown. Then you can create level 2, 3, etc headings as you wish but repeating the hash character, such as you see in the line `## File names` above.

## Basic formatting

You can use *italics*, **bold**, `code font text`, and create [links](https://www.markdownguide.org/cheat-sheet/). Here's a footnote [^1]. Here's a horizontal rule:

---

## Lists

Here's a list:

- item 1
- item 2

And a numbered list:

1. item 1
1. item 2

## Boxes and stuff

> This is a quotation

{% include alert.html text="You can include alert boxes" %}

...and...

{% include info.html text="You can include info boxes" %}

## Images

![]({{ site.baseurl }}/images/logo.png "fast.ai's logo")

## Code

You can format text and code per usual 

General preformatted text:

    # Do a thing
    do_thing()

Python code and output:

```python
# Prints '2'
print(1+1)
```

    2

Formatting text as shell commands:

```shell
echo "hello world"
./some_script.sh --option "value"
wget https://example.com/cat_photo1.png
```

Formatting text as YAML:

```yaml
key: value
- another_key: "another value"
```


## Tables

| Column 1 | Column 2 |
|:-:|--:|
| Row 1 | One thing |
| Row 2 | Another thing |

The second row is just metadata for the table that determines how the text will be vertically aligned. Each column can be aligned left, right, or center. The alignment is set by using a pattern of dashes and a colon separated by spaces and pipes.

-   To left-align a column, put a colon to the left of two dashes  `:--`.
    
    -   Three dashes  `---`  can also be used.
    
-   To right-align, put a colon to the right of two dashes  `--:`.

-   To center-align, surround a dash with two colons  `:-:`.

## Tweetcards

{% twitter https://twitter.com/jakevdp/status/1204765621767901185?s=20 %}


## Footnotes



[^1]: This is the footnote.


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NTQzMzA1MTgsMTUxNjI1MDU4MywxNj
kzMzE0NTM3XX0=
-->