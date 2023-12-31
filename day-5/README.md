# 30 Days of HTML - Day 5: Hyperlinks

## Introduction

Welcome to Day 5 of "30 Days of HTML." Today, we'll explore hyperlinks, an essential element for connecting webpages.

## Anchor Tags

In HTML, you use anchor tags, `<a>`, to create hyperlinks. An anchor tag is used to define both the source of the link and the text displayed on the webpage. Here's the basic structure of an anchor tag:

```html
<a href="goal">Link Text</a>
```
Goal: the page where the user should end.
If you want to go to a different site you need to add `https://` before the link (you dont need that if you link to another file on the same url)

Link text: the text that is displayed on the website

## Linkin to other parts of the page
You can link to other parts of the same page by adding a [id attribute](https://github.com/SusgUY446/30-days-of-html/blob/main/day-3/README.md) to the part of the page
```html
<a href="#section2">Jump to Section 2</a>

<h2 id="section2">Section 2</h2>
<p>This is the content of Section 2.</p>
```
## mailto:

With `mailto:` you can open a send mail window

Syntax:
```html
<a href="mailto:susguy446@gmail.com">Email SusgUY446</a>
```
