---
layout: post
title: Cинтаксис Markdown
description: "Для роботи з сервісами, що я пропоную використовувати як інструменти колективної роботи над проектами з оптимізації урравління виробнисими ррцесами, необхідним є оозуміння мови розмітки документів Markdown."
modified: 2014-12-24
comments: true
tags: [sample post]
image:
  path: /images/abstract-3.jpg
  feature: abstract-3.jpg
  credit: Ukrainian
  creditlink: https://vokov.treba.tk/syntaksys-markdown/
---

In short, markdown is a simple markup language that allows you to create a virtually complete web publication at the same time as the writing of the material. "Decorated" means with hyperlinks highlighting the text in the right places (bold or italic), quotes and lists. In most cases, this is enough, and for hardcore bloggers there is also an extended version of markdown with support for tables and other tricky pieces. But here we need a special software such functionality and need powerful professionals faster than"mere mortals". In such a jungle of climb will not.

File format-plain text, AKA TXT. Some more extension Editors assign" MD", but this is only for convenience and Association of such content with a certain application to OS x (Windows, perhaps, too, but in this OS I had no deal with MD-editors, so I will not guess). For example, does so the writer I., inside a tricky file with the extension ".TD " all the same the usual unformatted text.

The same markdown Idea is to set simple notation commands or, the MD Converter will be able to convert to standard HTML code. A simple example of this designation is the selection of text with asterisks :

` *italic* ` Converter converts text be in italics*
'**bold**, ' and this text will change in * * bold**

And here is how it looks in HTML format, then what markdown-Converter turns. It is in this form that the material is added to the admin panel (in HTML-editor mode, of course, forget about the visual editor - it lives its own special life):

'<EM > text < / EM> < Strong>to text< / strong>to`

Thus, in markdown can be written in principle in any text editor, even in the simplest, the same program TextEdit. Ale in specialized is still more convenient for a number of reasons, ranging from the built-in mode Converter and preview of the result and ending with the automation of entering the necessary commands.



#### Header:

`
# Heading 1
## Heading 2  
### Heading 3 
`

Result:

# Heading 1
## Heading 2
### Heading 3

Before heading to put the gate, then a space, and then by analogy.

#### List:

`
* Markdown is good 
* Markdown is very cool 
* Markdown need to know 
`

Result:

* Markdown is good
* Markdown is very cool
* Markdown need to know

There is an important nuance-the Converter to understand the command correctly, there should be an empty line above the list, and a space after the asterisk. You can also create numbered lists, but then put a semicolon instead of an asterisk, followed by a space. In order to create a nested list inside the main list, you need to insert an empty line under the desired item, then one click on the" tab " and then by analogy - an asterisk→space→list item.

#### Quotes

` 
> Quote 

>> A nested quote 
 `

Result:

> Quote

>> A nested quote

Inside the quotes you can add headings, lists, etc. In HTML-adding citations team, ` <blockquote> `, it turns put before the text character ">»

You can also add images, build tables

#### Tables

`
| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1 | cell2 | cell3 |
| cell4 | cell5 | cell6 |
|----
| cell1 | cell2 | cell3 |
| cell4 | cell5 | cell6 |
| = = = = =  
| Foot1 | Foot2 | Foot3
{: rules= " groups"}
`

Result:

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1 | cell2 | cell3 |
| cell4 | cell5 | cell6 |
|----
| cell1 | cell2 | cell3 |
| cell4 | cell5 | cell6 |
| = = = = =  
| Foot1 | Foot2 | Foot3
{: rules= " groups"}

#### Insert program code

With illuminated operators:

"'css
#container {
  float: left;
  margin: 0 x 240 pixels, 0 0;
  width: 100%;
}
`


"'css
#container {
  float: left;
  margin: 0 x 240 pixels, 0 0;
  width: 100%;
}
`

and without such:

    <div id= "amazing">
        < P > that's great, isn't it?< / p>
    </div element>