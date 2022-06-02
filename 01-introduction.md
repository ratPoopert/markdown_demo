# Markdown - An Introduction

## What is Markdown?

At its core, Markdown is a markup syntax for creating consistent and beautiful documents with plain text. Think of it like the HTML that displays the content of a webpage, but in a syntax that is clean and human readable.

## Why Should You Care?

### Future Proofing

Microsoft Word may go away someday. Or maybe you'll just get tired of paying for your Office 365 license. In any case, the XML markup that controls the styling and layout of your .docx files is a convoluted mess that requires proprietary software to read and edit.

Plain text is not going away. It powers the digital world. Keeping your documents in a plain-text format like Markdown means that even if your O365 license gets yanked, you will still be able to read your content in any plain text editor (even Notepad).

### Portability

An extension of the previous point, Markdown syntax is built to be converted into any document format. Want to turn your paper into a PDF? No problem! That potential employer wants to see your resume in Word? The world is your oyster!

Because Markdown is a simple markup syntax, you (or a CSS-savvy friend), can create stylesheets to quickly and consistently format your documents with a personal touch. This can be carried all the way to organizational branding like colorschemes and fonts.

### Simplicity

Because the syntax takes only a few minutes to learn, you can get right to the meat of writing content. No more getting derailed by bullet points that aren't aligning correctly or wonky numbering. The styling comes later. Now, we write.

## Basic Syntax

### Paragraphs

To write a paragraph, just write text as you normally would. Nothing fancy.

When you're ready to start a new paragraph, just add an extra line after the previous paragraph and get to typing.

### Inline Styling

In the middle of your plain jane paragraph, you can also:

* _italicize_ text with `_single underscores_`
* __bold__ text with `__double underscores__`
* add ~~strikethroughs~~ with `~~double squiggly tildes~~`
* Add nifty inline `monospaced code` with `` `the backtick` ``

Depending on the parser, underlines can be tricky. Luckily they are also commonly used with hyperlinks and should be avoided in regular use. But, if you need to <u>underline</u>, you can with HTML `<u>underline</u>` tags.

### Headings

You can also add a heading hierarchy with the # prefix:

```
# Heading Level 1
## Heading Level 2
### Heading Level 3
```

### Unordered Lists

Unordered lists are just as easy:

```
* Item 1
* Item 2
    * Sub-item 1
        * Sub-sub item 1
    * Sub-item 2
* Item 3
```

### Ordered Lists

Markdown keeps track of the numbering for you, so if you miss something the first time around, it'll still come out clean. Check this out:

```
1. Do this first
3. Do this second
2. Do this third
```

1. Do this first
3. Do this second
2. Do this third

No more fiddling with numbering when you're trying to get a thought onto the page!

### Links

Links use a `[bracket](parentheses)` syntax:

```
Buy your aptamers at [Aptagen](https://www.aptagen.com)!
```

Buy your aptamers at [Aptagen](https://www.aptagen.com)!

### Tables

Once again, the basic syntax doesn't care much about the spacing, so you can quickly put together a table like this to get the thought out:

```
|  | A | B | C |
|-|-|-|-|
| __1__ | A1 | B1 | C1 |
| __2__ | A2 | B2 | C2 |
| __3__ | A3 | B3 | C3 |
```

And the processor will give you a table so clean you can eat off it:

|  | A | B | C |
|-|-|-|-|
| __1__ | A1 | B1 | [C1](clickablelink.com) |
| __2__ | A2 | B2 | ![C2](https://cdn.iconscout.com/icon/premium/png-256-thumb/markdown-4-560096.png) |
| __3__ | A3 | B3 | C3 |

## Advanced Syntax

### Math

$y = mx + b$

$e = mc^2$

### Chemistry

$H_2O$

## Helpful Tools

### Text Editors

#### Notepad

#### Vim

#### VS Code

##### Markdown All-in-One

### Version Control
