# Notes on Static Rendering

There are a lot of fancy static site generators like [Gatsby](https://www.gatsbyjs.org/), [Jekyll](https://jekyllrb.com/), etc and you can pair them with [Netlify](https://www.netlify.com/) to do some pretty slick CI/CD hosting of documentation.

However, I think Github's default [rendering system](https://github.com/github/markup), especially since it supports [relative linking](https://blog.github.com/2013-01-31-relative-links-in-markup-files/) is slick enough without introducing lots of extra overhead.

I wonder whether just using a prettier version of the Github rendering addresses most use cases for documentation.

Github Pages I think does a pretty good job in a default way, and you can add [custom themes](https://help.github.com/articles/adding-a-jekyll-theme-to-your-github-pages-site/) and custom domains as well. [Check it out for this repo](https://geetduggal.github.io/notes/). If something like Gatsby can be configured to work like Github pages in a reasonably headache-free way that would be great for its slickness in rendering.

