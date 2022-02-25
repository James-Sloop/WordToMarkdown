# Markdown to Word

Follow these instructions to convert a Markdown file to a word document using Pandoc.

## Table of Contents

1. [Table of Contents](#toc)
2. [Prerequisites](#prerequisites)
3. [Success Conditions](#success-conditions)
4. [Steps](#steps)
5. [Home](index.md)

## Prerequisites

- Pandoc should now be installed.

- A Markdown file to convert to a Word document.

## Success Conditions

- You should have a Word document that is pretty similar to your Markdown file.

## Steps

- First go to your terminal and use `cd` to go to the directory with your Markdown file.

- In your terminernal enter the command `pandoc -s yourFile.md -o yourFile.docx` where `yourFile` is the name of your file.

- **Warning:** if you haven't already installed pandoc, your operating system will not recognize the command. If this happens follow [these](Download-and-Instillation.md) instrusctions to install pandoc and return to the last step.

- You should now have a file called `yourFile.docx` in your directory. It should look something like this:

![Directory Image](yourFile.png)

[Home](index.md)
