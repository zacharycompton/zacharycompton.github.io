---
permalink: /markdown/
title: "Markdown"
author_profile: false
redirect_from: 
  - /md/
  - /markdown.html
---

## Tips
- If you're copying pages, creating new pages, ensure that your front matter code doesn't have overlaping permalinks, otherwise the page that gets batched last (alphabetically) will take the permalink.
	
- Markdown tables can be very touchy.  Make sure you have space between them and other content, and you don't have odd symbols like colons preceding them, or they might not build properly.

- Don't forget to put a space in your headers and other modifiers, # Title, not #Title.

- Visit the 'actions' tab of the repository on github to watch the gitpages batching process.  If you send two quick pushes before the first can batch, it will cancel the first batch, and restart it as one big update. Here is a direct link: <a href="https://github.com/zacharycompton/zacharycompton.github.io/actions" target="_blank">Github Actions</a>


## Editing the Site
I suggest cloning the site into a dropbox folder and editing the site with <a href="https://notepad-plus-plus.org/downloads/" target="_blank">Notepad++</a>

## Use GIT Shell for pushing
Establish your current directory of the clone first

```
git status
```

```
git add -A
git commit -m "Casual Update"
git push

```
Include the extra blank line at the bottom to have it run fully without hitting enter at the end

## Using inline HTML will help give you added formating and functionality in the .md files
To comment in your markdown use:
```
<!-- Comment -->
```
To be able to better control padding and spaces between text and objects use:
```
<br>
```
To add a light grey horizonal line to the page use:
```
<hr>
```
To add a hyperlink that will open in a new tab use(Helpful if you are visiting an external site):
```
<a href="url" target="_blank">link text</a>
```
To make an anchor on your pages content use:
```
<a name="anchor1"></a>
```
Reference that anchor with a pound sign:
```
http://www.site.com/page#anchor1
```
HTML to embed a youtube video (just change the url):
```
<center><iframe width="560" height="315" src="https://www.youtube.com/embed/E-YlcBZgJRY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>
```

## Steps to add a knited html, from RStudio
1. Create your RMD.
2. Name the file with the following naming format:
	- ```
	  YYYY-MM-DD-TITLE.rmd
	  ```
3. Knit it to HTML and place that HTML in the _Posts Website Folder. (highly recommended you use dropbox .../zacharycompton.github.io/_posts)
3. Open the knitted html document in notepad++.
4. Add the following front matter to the beginning of the document:
```
---
layout: post
title: Tutorial 1 Knit
permalink: /tutorial1knit/
redirect_from:
	- /tutorial1knit.html
---
```
5. Change the title, permalink, and redirect to reflect the new document and Save.
7. GIT push the changes to github using GIT Shell.
```
git add -A
git commit -m "Casual Update"
git push

	```
8. This url would be https://zacharycompton.github.io/tutorial1knit
9. Use this inline HTML to reference the file, and open it in a new tab when clicked:
	- <a href="https://zacharycompton.github.io/tutorial1knit" target="_blank">Tutorial 1 Knitted HTML</a>

## Using Font-Awesome specialized fonts
<a href="https://fontawesome.com/v5/cheatsheet" target="_blank">Font-Awesome V5 Cheatsheet</a>
```
<i class="fas fa-fw fa-chart-area">
```
Or
```
<i class="fa fa-terminal" aria-hidden="true"></i>
```


## Locations of key files/directories

* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

## Tips and hints

* Name a file ".md" to have it render in markdown, name it ".html" to render in HTML.
* Go to the [commit list](https://github.com/academicpages/academicpages.github.io/commits/master) (on your repo) to find the last version Github built with Jekyll. 
  * Green check: successful build
  * Orange circle: building
  * Red X: error
  * No icon: not built

## Resources
 * [Liquid syntax guide](https://shopify.github.io/liquid/tags/control-flow/)

## Markdown guide

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.

## Tables

### Table 1

| Entry            | Item   |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | 2016   | Description of the item in the list                          |
| [Jane Doe](#)    | 2019   | Description of the item in the list                          |
| [Doe Doe](#)     | 2022   | Description of the item in the list                          |

### Table 2

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com "Github").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.
