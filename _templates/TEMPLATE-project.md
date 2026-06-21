---
# ============================================================
#  PROJECT TEMPLATE
#  Where this file goes:  projects/
#  How to name the file:  a short-name.md  (no date needed)
#       example:          science-fair.md
#
#  IMPORTANT — TWO STEPS to make a project show up:
#    1. Save this file in the projects/ folder.
#    2. Add ONE line to  _data/settings.yml  under "Projects Section":
#         - {name: 'Science Fair', url: 'science-fair'}
#       The 'url' must match this file's name WITHOUT the .md
#       (so science-fair.md  ->  url: 'science-fair')
#
#  If you skip step 2, the project won't appear on the home page.
# ============================================================

# Leave this line exactly as-is:
layout: post

# Change this to your project's name (keep the quotes):
title: 'My Project Name'
---

<!-- Below is your project write-up in plain markdown.
     Delete these comment lines before publishing. -->

A short paragraph explaining what this project is, what you made or did,
and why it was interesting. Two or three sentences is plenty.

## What I used
- Skill, tool, or material one
- Skill, tool, or material two

## Links
- [See it live](https://example.com)
- [Source / more info](https://example.com)

<!-- PROJECT THUMBNAIL (the image shown on the home page):
     Create a folder that matches this project's url, e.g.
        assets/img/projects/science-fair/
     and put an image named exactly  thumbnail.jpg  inside it.

     EXTRA IMAGES inside the write-up: put them in that same folder
     and add them with the line below (change the path to yours). -->

{% include image.html image="projects/science-fair/photo.jpg" %}
