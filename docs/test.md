<!-- Space: OC -->
<!-- Parent: Testing Mark -->
<!-- Title: Test -->

<!-- Include: ../templates/disclaimer.md -->


# Testing Mark

This is the page for testing the markdown to confluence features of Mark

## Overview

Mark reads your markdown file, creates a Confluence page if it's not found by its name, uploads attachments, translates Markdown into HTML and updates the contents of the page via REST API. It's like you don't even need to create sections/pages in your Confluence anymore, just use them in your Markdown documentation.

## Check out what it can do

### Mermaid diagrams!
Mark can render Mermaid charts via [mermaid.go](https://github.com/dreampuf/mermaid.go)  

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
### Info Panels!
> Info
> 
> Standard Markdown block quotes are converted to Confluence Info/Warn/Note box by Mark when the following conditions are met:

1. The BlockQuote is on the root level of the document (not nested).
2. The first line of the BlockQuote contains one of the following patterns Info/Warn/Note.

In any other case the default behaviour will be resumed and html <blockquote> tag will be used


### Code blocks!

```bash
command-to-run
```

