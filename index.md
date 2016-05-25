---
layout: post
title: Blogging Like a Hacker
---

Haddock User Guide
==================

#### Simon Marlow
#### David Waern

Copyright © 2010 Simon Marlow, David Waern

Abstract
--------

This document describes Haddock version 2.15.0, a Haskell documentation tool.

Table of Contents
-----------------

1. Introduction
    1. Obtaining Haddock
    1. License
    1. Contributors
    1. Acknowledgements
2. Invoking Haddock
    1. Using literate or pre-processed source
3. Documentation and Markup
    1. Documenting a top-level declaration
    2. Documenting parts of a declaration
        1. Class methods
        2. Constructors and record fields
        3. Function arguments
    3. The module description
    4. Controlling the documentation structure
        1. Re-exporting an entire module
        2. Omitting the export list
    5. Named chunks of documentation
    6. Hyperlinking and re-exported entities
    7. Module Attributes
    8. Markup
        1. Paragraphs
        2. Special characters
        3. Character references
        4. Code Blocks
        5. Examples
        6. Properties
        7. Hyperlinked Identifiers
        8. Emphasis, Bold and Monospaced text
        9. Linking to modules
        10. Itemized and Enumerated lists
        11. Definition lists
        12. URLs
        13. Images
        14. Anchors
        15. Headings
