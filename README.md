# Notes to Self
## Locations of key files/directories

* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
  * about.md
  * research.thml
  * posts.html
  * talks.html
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

## YAML front matter
Commonly used in Jekyll sites (like those hosted on GitHub Pages). It appears at the top of a Markdown (.md) or HTML file to define metadata about the page.
```
---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
```
Here’s what each line means:
* `layout: archive` tells Jekyll to use the archive layout for this page.
* `title: "Research"` sets the page’s title to “Research”.
* `permalink: /research/` sets the URL path of the page to yourdomain.com/research/.
* `author_profile: true` enables an author bio/profile box (depends on the theme used).

## Jekyll Notes
* [Adding last modified date](https://tomkadwill.com/adding-last-modified-date-to-jekyll)

## HTML Notes
* To open a link in a new tab, 
  * add the `target="_blank"` to the anchor tag to open the link in a new tab
  * add `rel="noopener noreferrer"` to the anchor tag as a security measure to prevent tabnabbing
```html
<a target="_blank" rel="noopener noreferrer" href="http://your_url_here.html">Link</a>
```
* [Basic HTML Guide](https://easyhtmlcss.com/)
* Create a collapsible list item for abstracts
```html
<ul style="list-style-type:none;">
 <li>
  <details>
   <summary>
    Abstract
   </summary>
   <p>
    INSERT ABSTRACT HERE
   </p>
  </details>
 </li>
</ul>
```


