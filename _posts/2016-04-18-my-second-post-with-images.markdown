---
layout: post
title:  "My second post with images!"
date:   2016-04-18 10:28:06 +0530
categories: jekyll update
---

#### Including images

Here's an example of including an image in a post:

<<<<<<< HEAD
<<<<<<< 7eacf2c1e5fe64b6130abf73b4bff355e2d652ac
<<<<<<< 7110ddd0ca1c9064c1a984921664e782186395ba
![Astrix]({{ site.url }}/dablog/assets/astrix.jpg)
=======
![astrix]({{ site.url }}assets/astrix.jpg)
>>>>>>> Removed \ before the file path to see if the image displays
=======
![astrix]({{ site.url }}/assets/astrix.jpg)
>>>>>>> Update 2016-04-18-my-second-post-with-images.markdown
=======
![astrix]({{ site.url }}/assets/astrix.jpg)
>>>>>>> gh-pages

![Chimi]({{ site.url }}/dablog/assets/chimi.jpg)
Chances are, at some point, you’ll want to include images, downloads, or other digital assets along with your text content. While the syntax for linking to these resources differs between Markdown and Textile, the problem of working out where to store these files in your site is something everyone will face.

Because of Jekyll’s flexibility, there are many solutions to how to do this. One common solution is to create a folder in the root of the project directory called something like assets or downloads, into which any images, downloads or other resources are placed. Then, from within any post, they can be linked to using the site’s root as the path for the asset to include. Again, this will depend on the way your site’s (sub)domain and path are configured, but here are some examples (in Markdown) of how you could do this using the site.url variable in a post.
