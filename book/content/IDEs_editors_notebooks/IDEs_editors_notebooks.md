# IDEs, Editors, and Notebooks
<!--
NATALIE's TO-DO list:
- Open GitHub issue for Debugging Chapter.


NATALIE's Questions:
- How do I link to other bits of the Turing Way?


-->

## Prerequisites / recommended skill level

<!-- add pre-requisites here -->
<!--
| Prerequisite | Importance | Notes |
| -------------|----------|------|
| Chapter/topic | How important it is | Any notes |
-->

## Table of contents

<!-- table of contents here -->

<a name="Summary"></a>
## Summary
This chapter is about which software you use to write and edit your code. There are three broad categories (text editors, IDEs, and notebooks) and within those categories there are many specific pieces of software (for example vim, sublime text, RStudio, jupyter notebooks). The Turing Way won't tell you which IDE or editor to use, but it will highlight some things that you might want to consider when you're making your choice.

## How this will help you/ why this is useful
<!-- why we think you should read the whole thing -->
The IDE or editor that you choose to program in will contribute to:
* how quick and enjoyable it is to program (and the slope of the learning curve involved)
* how easy it is to share your code with different people
* how easy it is to [debug](#Debugging), or use version control or virtual environments.

## What's the difference: IDEs, editors, and notebooks?

### IDEs
IDEs (Integrated Development Environments) integrate many [features](#features-to-know-about) that programmers find useful into one place. Rather than being only the place that you write your code, IDEs can also manage virtual environments, streamline using version control, or help you to conform to style conventions. While they can provide a lot of useful tools, they require more computational resources (which can make them slow), and additional skills to make the most of them. Some IDEs may provide features that you know you won't need (e.g. for managing)
Examples of IDEs: RStudio, PyCharm, Visual Studio

<!-- TODO: Maybe put an image of an IDE here, with some different panes labelled -->

### Text editors
Text editors offer a bare-bones code-writing environment. The only feature that they will definitely have is allowing you to write the text, although most will also allow you to run it from the editor. They therefore take up less space on your machine, and can sometimes be faster to write in. Text editors are often customisable, allowing you to add new [features](#features-to-know-about) over time as they become useful to you. 
Examples of Text editors: Sublime Text, Visual Studio Code

<!-- TODO: Maybe put an image of an editor here, with the fact that there is only the editor pane labelled -->

### Notebooks
Notebooks can be both a file format and a type of editor. 

As a file format, notebooks (such as Jupyter Notebooks, or RMarkdown Notebooks) allow you to write your code alongside notes about what you are doing. The output of your code (such as graphs and data) is also displayed in the same place. This helps you to create a document of your work (like a lab notebook), which is good for sharing your process and results. 

RMarkdown Notebooks are written inside RStudio (which is an IDE), but Jupyter Notebook documents are written inside a Jupyter Notebook environment.

#### Note on notebooks
In notebooks, code is divided into small chunks (called cells or blocks). These can be run independently from the rest of the notebook. 
<!-- Hints/tips for using Jupyter notebooks that are useful -->

## Literate programming
<!-- Does this comes up somewhere else in the Turing Way?? - link it?) -->

## Features to know about

### Debuggers
<!-- TODO: This should be a chapter with stuff like: print statements, assert statements, how to use debuggers, etc.-->
Debuggers lets you find mistakes in your code more easily<!--LINK TO THE DEBUGGING CHAPTER-->. You can step through code a line at a time (or at specific "breakpoints") and check the contents of variables to find where your code is doing something different than you were expecting.

Many IDEs contain visual debuggers - the debugger is part of the graphical user interface of the editor, so you can see how breakpoints and the current position of the debugger in the code relates to the code you are writing. For example, you can click to place breakpoints next to the code you have written. Visual debuggers aren't the only option for debugging, there interactive text-based debuggers, too (for example in the form of Python modules), which allow you to do the same thing by writing code instead of visually.

### Integrated version control

### Auto-complete

### Syntax and style highlighting

### Virtual environments
<!-- Presumably this comes up somewhere else in the Turing Way - link it?) -->

## How to choose?
- Ask your friends and colleagues what they would recommend. Knowing who you can ask questions to can be helpful when you're getting used to a new environment. 
- Decide which features you care about and choose an editor, IDE, or notebook that has those features.
- Try one out, you might cycle through a few until you find one you like.
- Consider interoperability with other tools which you might want to use (e.g. BinderHub)
<!-- Mention Open Source? -->
<!-- TODO: Maybe some stories other than mine-->

> "My ideal editor has changed over time. When I started my PhD, I tried PyCharm (a pretty substantial IDE for Python) and hated it at first. It had too many features I didn't need or want. Instead, I happily used a much more basic editor for many years (Sublime Text). Recently, I tried PyCharm again and now I absolutely love it!" - Natalie Thurlby



<!--
## Checklist
> this can be done at the end or maybe as a separate checklist exercise, but please do note things down here as you go
-->

<!--
## What to learn next
> recommended next chapters that are a good next step up
-->

<!--
## Further reading
> top 3/5 resources to read on this topic (if they weren't licensed so we could include them above already) at the top, maybe in their own box/in bold.
> less relevant/favourite resources in case someone wants to dig into this in detail
-->

<!--
## Definitions/glossary
> Link to the glossary here or copy in key concepts/definitions that readers should be aware of to get the most out of this chapter
-->

<!--
## Bibliography
> Credit/urls for any materials that form part of the chapter's text.
-->