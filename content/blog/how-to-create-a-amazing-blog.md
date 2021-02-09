---
title: Hi Chekol!!
description: Until now, trying to style an article, document, or blog post with
  Tailwind has been a tedious task that required a keen eye for typography and a
  lot of complex custom CSS.
tag: blog
date: 2021-01-22T18:15:03.780Z
thumbnail: /img/mvo-gravitar1.jpeg
start: February 8, 2021 2:54 PM
---
<p className="lead">
  Until now, trying to style an article, document, or blog post with Tailwind has been a tedious
  task that required a keen eye for typography and a lot of complex custom CSS.
</p>

By default, Tailwind removes all of the default browser styling from paragraphs, headings, lists and more. This ends up being really useful for building application UIs because you spend less time undoing user-agent styles, but when you *really arjklasdfhkljsadhklh*

We get lots of complaints about it actually, with people regularly asking us things like:

> Why is Tailwind removing the default styles on my `h1` elements? How do I disable this? What do you mean I lose all the other base styles too?

We hear you, but we're not convinced that simply disabling our base styles is what you really want. You don't want to have to remove annoying margins every time you use a `p` element in a piece of your dashboard UI. And I doubt you really want your blog posts to use the user-agent styles either — you want them to look *awesome*, not awful.

The `@tailwindcss/typography` plugin is our attempt to give you what you *actually* want, without any of the downsides of doing something stupid like disabling our base styles.

It adds a new `prose` class that you can slap on any block of vanilla HTML content and turn it into a beautiful, well-formatted document: