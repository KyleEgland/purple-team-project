# Purple Team Project

Something bigger than us all(?).

## Getting Started

This project is a static-site served by Github Pages using Jekyll. This site can be viewed by navigating to the Pages [url](https://kyleegland.info/purple-team-project/) or by cloning the project, setting up a ruby environment, and invoking the dev server:

`$ bundle exec jekyll serve`

...then navigating to the "baseurl" (specified in `_config.yml`) at the dev server specified location. Normally, the server runs on http://127.0.0.1:4000, however, I'm serving this off of my "main" page so it has a "baseurl" specified and http://127.0.0.1:4000/purple-team-project/ is the url that is needed in order to see the page (see issue [here](https://github.com/jekyll/jekyll/issues/1629)). http://localhost:4000 *should* also work but I was unsuccessful.

## Credits and Resources

Please see `credits-and-resources.md` in `~/Docs`
