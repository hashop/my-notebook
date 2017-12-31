MARKDOWN NOTES
==============

## Table of Contents
1. [Headings](#headings)
2. [Paragraphs](#paragraphs)
3. [Line Breaks](#line-breaks)
4. [Horizonal Rule](#horizonal-rule)
5. [Text-attributes](#text-attributes)
6. [Lists](#lists)
7. [Images](#images)

## Headings
Create headings using the following

```md
# This is an h1 tag
## This is an h2 tag
### This is an h3 tag
#### This is an h4 tag
##### This is an h5 tag
###### This is an h6 tag

<!-- Alt. h1 -->
Heading h1
==========
<!-- Alt. h2 -->
Heading h2
----------
```

## Paragraphs
Create paragraphs by using blank lines.

This is a paragraph.

```md
## Heading 2

This is a paragraph following heading 2.
```

## Line breaks
Create line breaks by using two spaces at end of a line.

This is a sentence with  
a line break.

```md
This is a sentence with  
a line break.
```

## Horizonal rule
Create a horizonal rule by dashes.

---

```md
---
```

## Text attributes
Make text bold, italic, or monospace.

This paragraph contains _italic-text_, **bold-text**, and `monospace-text`.

```md
This paragraph contains _italic-text_, **bold-text**, and `monospace-text`.

Note: Use the following without the quotes to add code. 
Change or omit language as needed.
"```python 
def example_funct():
	return 1;
```"
```

## Lists

#### Numbered list
Autoformatted using numbers.
1. Uno
2. Dos
```md
1. Uno
2. Dos
```

#### Bulleted list
Autoformatted using a dash(-) or asterisk(*).
- Apples
- Bananas
* Chicken
* Beef
```md
- Apples
- Bananas
* Chicken
* Beef
```


## Hyperlinks
Use the format to create hyperlinks that mimic the a tag.

Click [here](https://github.com/hashop).
```md
Click [here](https://github.com/hashop).
```

## Images
Use the format to create images that mimic the img tag with alt-text.

![alt-text](http://via.placeholder.com/350x150)
```md
![alt-text](http://via.placeholder.com/350x150)
```

## TODO:

* Tables
* Blockquotes
* HTML/ Definition list
* Strikethroughs
* Split up code highlighting