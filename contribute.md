---
layout: page
title: Contribute
permalink: /contribute/
---

## How to Contribute Content

Thank you for your interest in contributing! Follow these simple steps to create blog content using Markdown. Below are some key Markdown elements and how to use custom classes for styling.

## Headings
You can create headings by using the `#` symbol followed by a space:

- `# Heading 1` → # Heading 1
- `## Heading 2` → ## Heading 2
- `### Heading 3` → ### Heading 3

## Lists
Create unordered lists using `-` or `*`:
- Item 1
- Item 2
  - Subitem

Create ordered lists using numbers:
1. First item
2. Second item

## Links
To add a hyperlink, use this format:
```markdown
[Link Text](URL)
```

Example:
[Visit our site](https://example.com) → Visit our site

## Images
To add an image, use this format:

```
![Alt text](image_url)
```

In the image_url put the url of image you get after uploading the image to any image hosting service like cloudinary or imgur [https://img.doerig.dev/](https://img.doerig.dev/)


## Text Formatting
```
Bold: **text** 
Italic: *text* 
Strikethrough: ~~text~~  
```

## Blockquotes
To add a blockquote, use > before the text:

```
> This is a quote.
```

> This is a quote.

## Horizontal Rule
To create a horizontal rule, use three dashes (---):
```
---
```

## Custom Classes for Quran Ayah, Highlighting and Notes
Highlight Text: To highlight specific text, use the .hl class within a span tag like this:

```
<span class="hl">Highlighted text</span>
```
<span class="hl">Highlighted text</span>

Note Styling: To add a note, wrap the text in a span or p tag with the .note class:

```
<span class="note">This is an important note.</span>
```
<span class="note">This is an important note.</span>

```
<p class="note">This paragraph is styled as a note.</p>
```
<p class="note">This paragraph is styled as a note.</p>


Make sure to wrap the Ayah in a `<span> or <p>` tag with the `.q` class to apply custom styling.
```
<p class="q">
54:17
وَلَقَدْ يَسَّرْنَا ٱلْقُرْءَانَ لِلذِّكْرِ فَهَلْ مِن مُّدَّكِرٍۢ ١٧

</p>
```
<p class="q">
54:17
وَلَقَدْ يَسَّرْنَا ٱلْقُرْءَانَ لِلذِّكْرِ فَهَلْ مِن مُّدَّكِرٍۢ ١٧

</p>




## Make sure to add this on top in file :
```
---
layout: post
title:  "How to use arabic dictionary for sarf study and meaning ?"
date:   2024-09-12 4:30:18 +0530
categories: sarf 
author: Huzaifa Qureshi
img: https://res.cloudinary.com/ddymelpa3/image/upload/f_auto,q_auto/v1/arabic%20blogs/sarf%20part%201/gi2vwptyqgtyrxx2tiov
---
```
here update the details of the blog


### Save the text file as "yyyy-mm-dd-blog-title.md"
eg : 2024-09-24-How-To-Contribute.md

and Email the file to : [developerhuzaifa@gmail.com](mailto:developerhuzaifa@gmail.com) 