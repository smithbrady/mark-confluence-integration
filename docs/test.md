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
Mark can render Mermaid charts via [mermaid go](https://github.com/dreampuf/mermaid.go) 

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

### Code blocks!

```bash
command-to-run
```
### Info Panels!

