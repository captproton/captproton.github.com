---
layout: post
title: Outsource Your Blog
---

Blogs are simple pieces of software. It's the penultimate "sample application" that you build when learning frameworks like "Rails":http://rubyonrails.org/. But what I've found is, the more familiar I am with writing and managing blogging applications, the less I have any interest in doing it. Everything is too heavyweight, with themes and databases and complex administrative interfaces. I found myself yearning for something simple, uncluttered, and under my control.

When "GitHub announced support for user pages":http://github.com/blog/272-github-pages I knew in the back of my mind that this was going to be a big deal. At the time I didn't really know how it could be used for a blog since it seemed to just serve up static pages, but I definitely liked what I was hearing. After a couple of months went by, I finally decided to take the plunge and see what I could accomplish. Surprisingly, everything I wanted in a blog!

###Dead Simple Publishing

GitHub Pages are as simple as:

* Create a GitHub repository called yourname.github.com
* Push a 'master' branch to that repository
* GitHub will automatically build your page using "Jekyll":http://github.com/mojombo/jeyll

You may not have heard of Jekyll before (at least outside of the context of GitHub pages), but it is essentially an HTML generator that allows you to generate static HTML sites based on some very simple rules. Once you learn those rules, it's extremely simple to build sites that can be deployed anywhere that can serve up HTML (no server-side required).

You can also use a <code>CNAME</code> to redirect your own domain to GitHub.

h3. What About Comments? Images?

New tools have appeared that not only take care of all of the functionality I need for handling blog comments and image uploads, but do them better than any blog engine I have ever used.

"Disqus":http://www.disqus.com/ completely offloads blog post comments, and does a ridiculously good job of it. You get message threading, a great e-mail notification system, spam protection, and best of all it's as simple as a Javascript include in your blog post template.

Images are easy enough to add to a directory structure, but I find it even easier to use "Skitch":http://www.skitch.com/, drag an image to it, webpost it, and then use the direct image URL to embed it in the post.

h3. Why Do It?

I like using Ruby. I like writing my posts in Textile. I hate managing comments and complicated blog systems. If that sounds like you, you may want to look into outsourcing your own blog.