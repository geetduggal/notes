# Notes on Static Rendering

There are a lot of fancy static site generators like [Gatsby](https://www.gatsbyjs.org/), [Jekyll](https://jekyllrb.com/), etc and you can pair them with [Netlify](https://www.netlify.com/) to do some pretty slick CI/CD hosting of documentation.

However, I think Github's default [rendering system](https://github.com/github/markup), especially since it supports [relative linking](https://blog.github.com/2013-01-31-relative-links-in-markup-files/) is slick enough without introducing lots of extra overhead.

I wonder whether just using a prettier version of the Github rendering addresses most use cases for documentation.
