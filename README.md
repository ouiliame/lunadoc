# lunadoc

Documentation generator for software projects.

## Why?

There are many tools for documenting software, but they are fragmented and require a lot of manual work. For stellar documentation projects, you need:

1) consistency and maintainability provided by an automatic documentation generation tool

In addition, death by a thousand papercuts due to:

- preference for markdown but standard usage of some other standard like javadoc, doxygen, or ReST
- hard to customize 

## Structure

lunadoc is a suite of tools that work with its opinionated documentation generation pipeline to produce clean, cross-referenced docs that are easy to style and works for multiple languages.

Features:

- a static site generator
- custom components that are common for documenting and explaining code (cross-referenced parameter list, JSON view, UML diagrams, interactive state machine, algorithm visualization)
- multiple language backends utilizing language servers for static analysis / auto-documentation generation
- custom markdown syntax
- beautiful and easy to customize styles by default
- support for customization and layouts
