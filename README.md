# Markdown Cheat Sheet

A cheat sheet to refer to when creating README files in GitHub repositories and other markdown files. It also includes a more in-depth description of syntax where relevant, such as best practices. 

## Cheat Sheet

| Element  | Markdown Syntax | Preview |
| :------- | :-------------- | :------ |
| [Headings](#headings) | `# Heading 1` <br> `## Heading 2` <br> `### Heading 3` <br> `#### Heading 4` <br> `##### Heading 5` <br> `###### Heading 6` | <h1> Heading 1 </h1> <h2> Heading 2 </h2> <h3> Heading 3 </h3> <h4> Heading 4 </h4> <h5> Heading 5 </h5> <h6> Heading 6 </h6> |
| [Paragraph](#paragraphs) | `This is a paragraph. Just type text as normal.` | This is a paragraph. Just type text as normal. |
| [Bold Text](#bold-text) | `**This text is bold**` | **This text is bold** |
| [Italicised Text](#italicised-text) | `*This text is italicised*` | *This text is italicised* |
| [Line Break](#line-breaks) | `<two or more spaces> <return character>` | |
| [Blockquote](#blockquotes) | `> This is a blockquote` | ... |
| [List](#lists) | `1. This is the first item.` <br> `2. This is the second item` | <ol> <li>This is the first item.</li> <li>This is the second item.</li> </ol> |
| [Code](#code) | <code>\`This is some code...`</code> | `This is some code...` |
| [Horizontal Rule](#horizontal-rules) | `---` | ____________________________ |

## More Information

### Headings

Headings are created by adding one or multiple hashtags (#) infront of the text, word, or phrase to be made into a heading. The number of hashtags which prepend the intended heading reflects the heading level.

For example, a to create a heading with a level 3, prepend the text, word, or phrase with three hashtags.

It is good practice to leave a space between the prepending hastags and the text, word, or phrase to be made into a heading as not all markdown applications agree on how to handle a missing space between the hashtag and phrase. For compatibility, you should also practive putting blank lines before and after headings. 

### Paragraphs

To create paragraphs in your markdown files, you type normally, leaving a blank line between paragraphs ro lines of text you want separated. 

Unless the paragraph is part of a list, don't indent the paragraph with tabs or spaces. If you need to indent a paragraph, it is best to use an editor which supports tabs to indent a paragraph. If your markdown editor supports HTML, you can use teh HTML entity for non-breaking space (`&nbsp`).

### Emphasis

There are multiple ways one can emphasise text, through making it bold and making it italic. 

#### Bold Text

To make text **bold**, as illustrated in the cheat sheet table, add two astericks before and after the word, text, or phrase you want to emphasise. If you wanted to make specific characters of a word bold, simply add the astericks before and after the character with no spaces. 

It is also possible to make text bold by using underscores instead of astericks. The same way you use astericks, you can use two underscores on either side of the word, text, or phrase you wish to emphasise. However, it is best to practice emphasising text using astericks for compatibility reasons. 

#### Italicised Text

To present text in *italics*, as illustratied in the cheat sheet table, add a single asterick before and after the word, text, or phrase you want to emphasise. If you wanted to make a specific character within a word italic, simply add the asterick before and after the character with no spaces. 

It is also possible to make text italic by using underscores instead of astericks. The same way you use a single asterick on each side of the text you want empahsised, you can use an underscore on each side of the word, text, or phrase you wish to emphasise. However, it is best to proactice emphasising text using astericks for compatibility reasons. 

### Line Breaks

### Blockquotes

### Lists

### Code

### Horizontal Rules

### Links

### Images

### Escaping Characters

### HTML

### Tables

### Footnotes

### Task Lists

### Emojis

## Other Notes
Most markdown files support the original basic syntax which was outlined in the original *Markdown Design Document*. There can be minor variations and differences between the range of [Markdown Processors](https://github.com/markdown/markdown.github.com/wiki/Implementations), this cheat sheet will attempt to stick to the most generic markdown syntax possible (particulary those which will work with GitHub repositories). 

### References
This program makes use of information and websites referenced below:
 - [markdownguide.org](https://www.markdownguide.org/)
