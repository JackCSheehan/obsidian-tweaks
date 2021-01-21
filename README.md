## Obsidian Tweaks
A collection of small CSS snippets for Obsidian.

Obsidian is a markdown editor designed to act as a personal knowledge base and note-taking software. Obsidian is great, but it has a few quirks that make using certain features of it (the slideshow plugin, for example) a bit frustrating. Luckily, Obsidian has native support for adding custom CSS to any part of the program. This repository is as a collection for CSS files that I've written to enhance my Obsidian experience.

You can check out Obsidian [here](https://obsidian.md/).


Feel free to contribute to this repository if you'd like.

Below is an explanation of each stylesheet and why I find them useful.

#### Scrollable Slides
---
Obsidian has a core plugin that will automatically create slideshows from your notes, using the `---` symbol as a delimiter for the slides. One issue this plugin has, however, is that the slides are not responsive. If you put too much content on slide, it simply overflows and content is hidden beneath the slide's container div. The scrollable slides stylesheet automatically adds a scrollbar to overflowing sides so that content is not simply lost from overflowing.

#### Slide Image Margins
---
Occasionally, the slideshow plugin places images in such a way that the bottom portion of them are cut off. This stylesheet sets the margins of images in slideshows to 0 so that they display fully on the slide. This stylesheet is not needed if you're using the Scrollable Slides snippet.