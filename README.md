# Markdown Tutorial 
:wave: Hello, this is a quick tutorial / reference for Markdown, specifially [GitHub Flavored Markdown](https://github.github.com/gfm/).

### Index
- [Introduction](#:apple:-introduction-to-markdown)
- [Text Basics](#text-basics-with-markdown)
- [Lists](#lists-in-markdown)
- [Tables](#tables-in-markdown)
- [Images](#images-in-markdown)
- [Math and Science](#math-and-science-in-markdown)
- [Emojis](#emojis-in-markdown)

###### :calendar:Created February 2023

***

## :apple: Introduction to Markdown

- Markdown is a lightweight markup language created in 2004 and used to format digital content.
- Markdown is converted to HTML in order to be displayed in the browser or other applications. 
- There are different flavors of Markdown such as [GitHub Flavored Markdown](https://github.github.com/gfm/), [Reddit Flavored Markdown](https://www.reddit.com/wiki/markdown/), [Markua](http://markua.com/#the-magical-typewriter-m-) and [more](https://en.wikipedia.org/wiki/Markdown#Variants). This tutorial will focus on [GitHub Flavored Markdown](https://github.github.com/gfm/).
- To create a Markdown file you can use notepad and save the file with the `.md` extension. Open it with your browser to view it. You could also just create a repo on GitHub and practice your GFM (GitHub Flavored Markdown) in a `README.md`.
- HTML can be embedded within Markdown.

***

## Text Basics with Markdown

Markup languages use symbols and specific syntax rules to format content. You can think of it as adding marks or 'marking up' 
text to modify how it is displayed after conversion.
 
Here is a reference for marking up text...

| Markdown | Output | HTML Equivalent |
|:--------:|:------:|:---------------:|
| `normal text` | normal text | `normal text` |
| `# Header One` | <h1>Header One</h1> | `<h1>Header One</h1>`|
| `## Header Two` | <h2>Header Two</h2> | `<h2>Header Two</h2>`|
| `### Header Three` | <h3> Header Three </h3> | `<h3>Header Three</h3>`|
| `#### Header Four` | <h4> Header Four </h4> | `<h4>Header Four</h4>` |
| `##### Header Five` | <h4> Header Five </h5> | `<h5>Header Five</h5>`|
| `###### Header Six` | <h6> Header Six</h6> | `<h6>Header Six</h6>`|
| `*italic text*` | *italic text* | `<em>Italic Text</em>`
| `**bold text**` | **bold text** | `<strong>bold text</strong>`|
| `***bolid italic text***` | ***bold italic text*** | `<strong><em>bold italic text</strong></em>`|
| `>blockquote text` | <blockquote>blockquote text</blockquote> | `<blockquote>blockquote text</blockquote>`|
| `~~strikethrough~~` | <s>strikethrough</s> | `<s>strikethrough</s>`|

<table>
 <tr>
  <td>&#10071;</td>
  <td>
   </br>
   Some Markdown elements such as <code># headers</code> are required to be the first characters on the lines which they appear. 
   </br></br>
   &nbsp;&#10060;<code>text # header text</code>
   </br>
   </br>
   This is because headers are known as <a href ="https://www.w3schools.com/html/html_blocks.asp"> block elements </a> in both HTML and Markdown. 
   </br>
   </br>
  </td>
 </tr>
</table>

***

## Lists in Markdown
Here we will go over three types of lists. Please note that there is a space between the text and list item marker for every example.
### Unordered Lists
Unordered lists have each list item demarcated by a bullet point.
#### Markdown :arrow_right:
```
- item one
- item two 
- item three
```
#### Output :arrow_right:
- item one
- item two 
- item three
#### HTML equivalent :arrow_right:
```html
<ul>
 <li>item one</li>
 <li>item two</li>
 <li>item three</li>
</ul>
```
### Ordered Lists
#### Markdown :arrow_right:
```
1. item one
2. item two
3. item three
```
#### Output :arrow_right:
1. item one
2. item two
3. item three
### Task List
#### Markdown :arrow_right:
```
- [x] item one
- [ ] item two
- [ ] item three
```
#### Output :arrow_right:
- [x] item one
- [ ] item two 
- [ ] item three 

***
## Tables in Markdown
***
## Images in Markdown
***
## Math and Science in Markdown
***
## Emojis in Markdown
***
