# Landing Page Jekyll theme

Jekyll theme based on [landing-page bootstrap theme ](http://startbootstrap.com/templates/landing-page/)

## How to serve locally with Ruby 3.2.2 and rbenv

To preview your site locally, use rbenv to set the Ruby version and Jekyll to serve the site. You do not need a Gemfile for basic usage.

1. Set the local Ruby version for this project:
   ```sh
   rbenv local 3.2.2
   ```
   This will create a `.ruby-version` file in your project directory.
2. Install Jekyll (if not already installed):
   ```sh
   gem install jekyll
   ```
3. Serve the site locally:
   ```sh
   jekyll serve
   ```
4. Open [http://localhost:4000](http://localhost:4000) in your browser to view the site.

## How to update posts and content

1. Make your changes (such as adding or editing posts in `_posts/` or images in `img/`) on the `main` branch.
2. Commit and push your changes to GitHub:
   ```sh
   git add .
   git commit -m "Update posts or content"
   git push origin main
   ```
3. GitHub Actions will automatically build and deploy your site to the `gh-pages` branch. No manual deployment is needed.

### Creating a new post

Create a new file in the `_posts/` directory. Use the following as an example:

```markdown
---
layout: default
img: ipad.png
category: Services
title: The service title
---

The description of this service
```

## Demo

View this jekyll theme in action [here](https://swcool.github.io/landing-page-theme)

## Screenshot

![screenshot](https://raw.githubusercontent.com/swcool/landing-page-theme/master/img/screenshot.png)

===

For more Jekyll details, read [documentation](http://jekyllrb.com/).
This Jekyll theme used [Freelancer Jekyll theme](https://github.com/jeromelachaud/freelancer-theme/) as reference.

## License

The contents of this repository are licensed under the [Apache
2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

## Version

1.0.1
