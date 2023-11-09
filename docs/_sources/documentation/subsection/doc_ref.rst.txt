:orphan:

How to use cross-references with Sphinx
=======================================

When writing documentation you often need to link to other pages of your documentation,
other sections of the current page, or sections from other pages.

.. _target to paragraph:

An easy way is just to use the raw URL that Sphinx generates for each page/section.
This works, but it has some disadvantages:

- Links can change, so they are hard to maintain.
- Links can be verbose and hard to read, so it is unclear what page/section they are linking to.
- There is no easy way to link to specific sections like paragraphs, figures, or code blocks.
- URL links only work for the html version of your documentation.

Instead, Sphinx offers a powerful way to linking to the different elements of the document,
called *cross-references*.
Some advantages of using them:

- Use a human-readable name of your choice, instead of a URL.
- Portable between formats: html, PDF, ePub.
- Sphinx will warn you of invalid references.
- You can cross reference more than just pages and section headers.

This page describes some best-practices for cross-referencing with Sphinx
with two markup options: reStructuredText and MyST (Markdown).

.. contents:: Table of contents
   :local:
   :backlinks: none
   :depth: 3

Getting started
---------------
