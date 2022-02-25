# Word to Markdown

Follow these instructions to convert a Word document to a Markdown file using Pandoc.

## Table of Contents

1. [Table of Contents](#toc)
2. [Prerequisites](#prerequisites)
3. [Success Conditions](#success-conditions)
4. [Steps](#steps)
5. [Home](WordToMarkdownGuide.md)

## Prerequisites

- Pandoc should now be installed.

- A Word document to convert to a Markdown file.

## Success Conditions

- You should have a Markdown file that is pretty similar to your Word document.

## Steps

- First go to your terminal and use `cd` to go to the directory with your Word document.

- In your terminernal enter the command `pandoc -s yourFile.docx -t markdown -o yourFile.md` where `yourFile` is the name of your file.

- **Warning: if you haven't already installed pandoc, your operating system will not recognize the command. If this happens follow [these](Download-and-Instillation.md) instrusctions to install pandoc and return to the last step.**

- You should now have a file called `yourFile.md` in your directory. It should look something like this:

![Directory Image](/yourFile.PNG)

[Home](WordToMarkdownGuide.md)