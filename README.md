# Copper Jekyll theme - [DEMO](https://mpgn.github.io/copper-jekyll-theme)

## Feature
	
- Markdown blogging 
- Syntax highlighting  
- Fully responsive
- Three differents categories handle
- Two themes
- Latex syntax
- RSS feed
- Twitter button share
- Google+ or Disqus comment
- Fontawesome Icons

## Two themes

You can choose the use the left bar : 

![img1](https://mpgn.github.io/copper-jekyll-theme/assets/images/1.png)

Or remove the left bar in the file `_config.yml` by setting `left_bar` to false !

![img1](https://mpgn.github.io/copper-jekyll-theme/assets/images/2.png)


## Instruction

1. fork this reposotory
2. change the `_config.yml` file with your values
3. create your blogging post

```
---
layout: post
title: yout title
category: your category (see below how to create category)
lang: GB
description: description for twitter
github: github url if you have (a small github icon will appear with the project)
sticky: true -> if you want a star icon -this is not real sticky)
---
```

4. create categories : 

Add a file at the same level as `index.html`
Then add this header into the file
```
---
layout: category
title: Category name page
permalink: /category-name/
category: Category-name
---
```

And leave the rest of the file empty.

Check the [demo](https://mpgn.github.io/copper-jekyll-theme) for example 

5. push to Github and active Github page on the repo settings
6. Enjoy ;)

## In the box

- [Bootstrap 3](http://getbootstrap.com/) SASS framework 
- [Jekyll](https://github.com/jekyll/jekyll) - Thanks to its creators, contributors and maintainers.
- [Jekyll Now](https://github.com/barryclark/jekyll-now) as a starting base. Many thanks to [Barry Clark](http://www.barryclark.co/) for creating this amazing base 
- [FontAwesome](http://fontawesome.io/) icons

## Licence

Copper theme is under MIT licence ! 
