# Krisha's Portfolio

A personal portfolio site built with Jekyll and hosted free on GitHub Pages.

## How to update the site

Everything is edited right here on GitHub — click a file, click the pencil
(edit) icon, make changes, then "Commit changes" to save. The site rebuilds
itself within a minute or two.

### Where things live
| What you want to change                       | File / folder            |
|-----------------------------------------------|--------------------------|
| Site title, description                       | `_config.yml`            |
| Your name, menu, project list, social links   | `_data/settings.yml`     |
| Individual project pages                      | `projects/`              |
| Project tile images (named `thumbnail.jpg`)   | `assets/img/projects/`   |
| About / Contact pages                         | `pages/`                 |
| Blog posts                                    | `_posts/`                |
| Browser-tab icon                              | `favicon.ico`            |

### Copy-and-fill templates
Ready-made starter files (with instructions inside) are in the `_templates/`
folder. The underscore means they stay in the repo but never appear on the
live site. To use one, open it, copy the contents, create a new file in the
right folder, and paste.

### Two-step rule (the thing people forget)
- A **blog post** appears automatically once added to `_posts/`.
- A **project** or **menu page** needs its file AND a matching line added to
  `_data/settings.yml`. The `url` there must match the filename without `.md`.

### Project thumbnails
For a project whose `url` is `example-project`, its tile image must be at
`assets/img/projects/example-project/thumbnail.jpg` — the folder name matches
the project url, and the file must be named `thumbnail.jpg`.
