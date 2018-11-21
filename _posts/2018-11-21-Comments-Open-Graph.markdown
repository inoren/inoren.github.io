---
layout: page
title:  "Comments and Open Graph"
date:   2018-11-21 11:10 +0100
categories: Examination 1
type: Post
---
<div class="post-meta">
<h3>Implementing comments to blog posts</h3>
<p>In my blog I have used Disqus for posting comments on my posts. For this a Disqus acount is needed. I than created a file called disqus.html in my _includes directory. In this file I placed the code provided by Disqus for a Jekyll page. In the disqus_config function I edited the page URL and page identifier.</p>
<p>To get the comments to show up at the right place I just call the discus.html file in my post layout in the _layouts directory.</p>

<h3>Open Graph</h3>
<p>Open Graph turns your pages into graph objects with the help of meta tags.
The meta tags let you specify which elements of you page you want to show when your page is shared.</p>
<p>I have put my meta data for Open Graph in a separate file, open-graph.html, in my _includes directory. I than call this file in the head of my default layout. The content I chose to include is page title, content type, URL and and image. The image is the same for all shared pages, but the URL, type and title is page specific with the help of Liquid.</p>
</div>