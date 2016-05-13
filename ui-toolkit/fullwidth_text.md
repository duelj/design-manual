---
layout: page
title: Full width text
category: UI toolkit
published: true
---

- [Use](#use)
- [Behavior](#behavior)
- [Style](#style)
- [Content guidelines](#content-guidelines)
 {: class="toc"}

<p>The table shows the variations of the full width text element.</p>

|Content|Media|Inset content|
---|---|---
|![content_quote_example.png]({{site.baseurl}}/static/img/content_quote_example.png)|![content_media_example.png]({{site.baseurl}}/static/img/content_media_example.png)|![content_inset_example.png]({{site.baseurl}}/static/img/content_inset_example.png)|


<h2 id="use">Use</h2>

<p>The full width text element in its different variations is the foundation of the main content area of many pages. It functions to house longer passages of text utilizing the full content area width in a given template. The most basic version of the element is a flowing section of text, however, the ability to add media, quotes, calls to action, related links, and tables in line make it extremely versatile. </p>

<div class="content-67 content-first">

### Content

#### When to use
* When there are multiple paragraphs of text to be shown on a page. Especially if multiple sections are involved
* When text content is the main focus of a page, rather informing users on moving to another section of the website


#### When to use something else
* When multiple columns of text are needed consider using the half [width link blob]()
* When the goal of the text is to drive users to other sections of the site.
</div>

<div class="content-33 content-last">
##### Templates used on

[Landing page]()

[Sub-landing page]()

[Browse page]()

[Learn page]()

[Document detail page]()

</div>



<div class="content-67 content-first">
### Media

#### When to use
* When an image is needed in the context of a passage of text
* On a blog or article page when more images are needed that the featured image

#### When to use something
* When a single video is being featured on a page
* When multiple columns or a grid of images are needed

</div>

<div class="content-33 content-last">
##### Templates used on

[Landing page]()

[Sub-landing page]()

[Browse page]()

[Learn page]()

[Document detail page]()

</div>


<div class="content-67 content-first">
### Inset

#### When to use
* When ancillary information is needed in context of flowing text, such as quotes, call to action, related links, etc. 
* This molecule is used to display related metadata in the sidebar for rules, notices, etc.

#### When to use something else
* When anything other than metada for a document detail page is being displayed.

</div>


<div class="content-33 content-last">
##### Templates used on


[Document detail page]()

</div>


<h2 id="behavior">Behavior</h2>

### Content & media
<p>Content and media elements that are  fullwidth at desktop size remain full width across all breakpoints. However, heading, link, and buttons all follow responsive patterns.  </p>

<div class="content-50 content-first">
#### Sidebar 901+
![behavior_content_desktop.png]({{site.baseurl}}/static/img/behavior_content_desktop.png)
</div>

<div class="content-50 content-last">
#### Sidebar less than 600
![behavior_content_mobile.png]({{site.baseurl}}/static/img/behavior_content_mobile.png)
</div>

### Inset
<p>All variations of inset elements move into full width format at screen widths less than 600px as seen below.</p>

<div class="content-50 content-first">
#### Sidebar 601+
![behavior_inset_desktop.png]({{site.baseurl}}/static/img/behavior_inset_desktop.png)
</div>

<div class="content-50 content-last">
#### Sidebar less than 600
![behavior_inset_mobile.png]({{site.baseurl}}/static/img/behavior_inset_mobile.png)
</div>

<h2 id="style">Style</h2>

<nomarkdown>
<img src="{{site.baseurl}}/static/img/style_contentmedia.png" alt="content and media style" height="100%" width="100%">
</nomarkdown>


### Content and media
* Insets change to this fomat below 600px viewports 
* Side padding is removed  so element is flush left and right
* Top and bottom padding remains 30px

<nomarkdown>
<img src="{{site.baseurl}}/static/img/style_inset.png" alt="inset style" height="100%" width="100%">
</nomarkdown>


### Inset 
* All inset elements are 270px wide
* 30px of padding until the 600px breakoint. 
* They should be right aligned to the main content area. 
* Inset has no top rule of it’s own but relies on the module that it contains to dictate whether a top rule is shown
* Molecules in the inset should follow pre footer styling below 600px

<h2 id="content-guidelines">Content Guidelines</h2>

* Content guidelines will be dependent on the type of content the is inserted into the content area. See individual component guidelines for specifics.
