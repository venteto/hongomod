# Venteto Hugo Congo Module
Reusable bits for my Hugo sites

## Usage
After updating this repo, be sure to also update any sites using this module, so that they pick up the changes:
```bash
hugo mod get -u
```

## Features
This module adds the following:
- Enables a second footer menu only visible in non-production environments, for links you may only want to see during development, e.g., the link to your live site, any git repos, any host's dashboard, any analytics dashboards, et al.
- Provides a reusable third footer menu only visible in non-production environments, which displays links to your robots.txt file and a favicon generator site.
- An attribution for this module in the normal Hugo and Congo attribution footer
- Custom `fig` shortcode, which can make use of a `figbase` frontmatter parameter, for base paths to any image included in the figure (if figbase is omitted, the path defaults to including images as page bundle files)