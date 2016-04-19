---
layout: post
title:  "My third post with images!"
date:   2016-04-19 10:28:06 +0530
categories: jekyll update
---

#### Including images

Here's an example of including an image in a post:

![Astrix]({{ site.url }}/dablog/assets/me.jpg)

{% highlight git %}

git add .
git status // to see what changes are going to be commited
git commit -m 'Some descriptive commit message'
git push origin master

git checkout gh-pages // go to the gh-pages branch
git rebase master // bring gh-pages up to date with master
git push origin gh-pages // commit the changes
git checkout master // return to the master branch


{% endhighlight %}


Chances are, at some point, you’ll want to include images, downloads, or other digital assets along with your text content. While the syntax for linking to these resources differs between Markdown and Textile, the problem of working out where to store these files in your site is something everyone will face.

Because of Jekyll’s flexibility, there are many solutions to how to do this. One common solution is to create a folder in the root of the project directory called something like assets or downloads, into which any images, downloads or other resources are placed. Then, from within any post, they can be linked to using the site’s root as the path for the asset to include. Again, this will depend on the way your site’s (sub)domain and path are configured, but here are some examples (in Markdown) of how you could do this using the site.url variable in a post.
