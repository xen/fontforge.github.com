---
published: true
layout: default
title: Edit This Website
---

Like FontForge itself, this website is developed as a [collaborative  project](/en-US/about/project/index.html) where everyone is invited to contribute. The collaboration is organized through the [GitHub](http://github.com) website, so to contribute you'll need an account there. 

### Making Contribution Easy

Contributing to this website should be as easy as possible, like Wikipedia.

We've added a couple of little links to the 'Edit This Page' roundel in the footer of each page. Once you are logged into GitHub, the little 'github' link will work for you. There is also a link to [prose](http://prose.io), a more elegant UI for editing files on GitHub.

### Diving Into The Design

To contribute to the site beyond simply editing the text, such as to adjust the HTML, CSS, JS, or other aspects of the design, follow the typical GitHub process: forking the site, starting a branch to label the overall set of changes, making the changes you want, committing each change, and then making a pull request to have your branch merged with the live site.

If that sounds unfamiliar, GitHub has excellent [bootcamp tutorials](https://help.github.com/categories/54/articles) (that really are excellent) to get you going. Here's the project link on GitHub:

> [https://github.com/fontforge/fontforge.github.com](https://github.com/fontforge/fontforge.github.com)

<a id="translations"></a>
### Translations

The website is under active development in US English. 

If you'd like to start translating it, make a copy of the `/en-US` directory
and rename it with your language code, and start translating. When you think
the site is ready, make a pull request :-)

When a translation is ready, we'll have to make a modification to the language dropdown in `_includes/nav-main.html` so
that it will work to switch the URL (with the JS library `jurlp`)

(If you're interested in translating FontForge itself, please refer to the [FontForge User Interface Translations](/documentation/customizing/translations.html) page.)

## Contributors

Massive thanks to those kind souls who have contributed to this website:

1. __George Williams__, primary author of all of FontForge and most of the site's contents
2. __Bevan Stephens__, primary visual designer of this website
3. __Brian Zick__, helped with the information architecture of the new site and scripts to convert the old content to markdown
4. __Dave Crossland__, initiated the new site project, implemented Bevan's mockups as Jekyll, wrote some of new website content 
5. __Vera Lobatcheva__, helped migrate the old content to the new site
6. Your name here? :-)