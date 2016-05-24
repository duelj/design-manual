---
layout: page
title: Sidebar/pre footer
category: UI toolkit
published: true
---

- [Use](#use)
- [Behavior](#behavior)
- [Content guidelines](#content-guidelines)
- [Style](#style)
 {: class="toc"}

<p>Sidebars are present across most page templates to house information related to the main content of the page. On pages with leftside sub-navigation, sidebar content may be displayed as an optional pre-footer at the bottom of the main content.
Sidebars may can contain related posts, calls to action, metadata, email sign ups, contact information, etc. Primary layout variations as seen in basic sidebar format:
</p>

<div class="content-33 content-first">
#### Realted posts
![related_posts_example.jpg]({{site.baseurl}}/static/img/related_posts_example.jpg)

</div>

<div class="content-33 content-middle">
#### Related links
![related_links_example.jpg]({{site.baseurl}}/static/img/related_links_example.jpg)

</div>

<div class="content-33 content-last">
#### Metadata
![metadata_example.jpg]({{site.baseurl}}/static/img/metadata_example.jpg)

</div>

<h2 id="use">Use</h2>

### Related posts

<div class="content-67 content-first">

#### When to use
* This component is used to display lists of related content dynamically pulled from elsewhere in the site – blogs, events, and newsroom items, etc. – based on topic tag selections.
* The CMS has options to limit and focus the related content that is displayed:
  * Limit: Default is set to three of each types of content (blog, newsroom, events), but can be made more or less. Most common change is setting the limit to one of each type. This is helpful when tags aren’t used often so that content that is pulled in isn’t too outdated
  * Post types: can select which of the available post types (blogs, newsroom, events) appear in the component. Most common is to de-select Events, since they may not be relevant to the audiences for certain pages
  * Categories: For the blog post type, you can choose to have posts appear that are categorized a certain way based on the audience of the page and what will be most relevant to them. 

#### When other options are better
* When lists of items should not be automatically updated consider related links instead.
* When posts will be mixed with other types of content.

</div>

<div class="content-33 content-last">
##### Templates used on

[Landing page]()

[Sub-landing page]()

[Browse page]()

[Learn page]()

[Document detail]()

</div>


### Related links

<div class="content-67 content-first">

#### When to use
* When a specific, static piece of content and call to action needs to be displayed in the sidebar.
* When a static list of links or specific related posts need to be displayed in the sidebar.


#### When other options are better
* When all of the content is posts that can be dynamically populated. 
</div>

<div class="content-33 content-last">

##### Templates used on

[Landing page]()

[Sub-landing page]()

[Browse page]()

[Learn page]()

[Document detail]()

</div>

### Metadata

<div class="content-67 content-first">

#### When to use
* When displaying relevant metadata about a specific document or set of documents, such as for a rule, notice, or report, for users to easily reference.

#### When other options are better
* When anything other than metadata for a document detail page is being displayed.
</div>

<div class="content-33 content-last">

##### Templates used on


[Document detail]()

</div>

<h2 id="behavior">Behavior</h2>

<p>All variations of sidebar element move into pre-footer format at screen widths less than 901 px. The sidebar area can house multiple stacked sidebar elements.</p>

<div class="content-50 content-first">

#### Sidebar 901+

![behavior_sidebar_desktop.png]({{site.baseurl}}/static/img/behavior_sidebar_desktop.png)
</div>

<div class="content-50 content-last">

#### Sidebar 900 or less (transition to prefooter)

![behavior_sidebar_mobile.png]({{site.baseurl}}/static/img/behavior_sidebar_mobile.png)

</div>

<p>Pre-footer format is automatically used on pages that have a left side secondary navigation.
Below 601 px width, for legibility link styling on clickable headings remains in the standard format, but mobile link style is applied where possible.</p>

<div class="content-50 content-first">

#### Preftooer 901+ (with side nav.)
![behavior_prefooter_desktop_1.jpg]({{site.baseurl}}/static/img/behavior_prefooter_desktop_1.jpg)
</div>

<div class="content-50 content-last">

#### Prefooter 600 or less
![behavior_prefooter_mobile_1.jpg]({{site.baseurl}}/static/img/behavior_prefooter_mobile_1.jpg)
</div>


<h2 id="content-guidelines">Content Guidelines</h2>
* Slugs should be as succinct as possible, ideally 30 characters or less. They should be limited to one line.
* Description beneath heading should also be succinct, limited to 3 lines max; 100 characters.
* Call to action link should be limited to one line; 40 characters or less.



<h2 id="style">Style</h2>

<div class="content-33 content-first">

### Global

* Background: 5% grey (#F7F7F7)
* Multiple elements can be used in the sidebar/ pre footer but each should have their own slug label. 

</div>

<div class="content-67 content-last">
![style_global.png]({{site.baseurl}}/static/img/style_global.png)
</div>


<div class="content-33 content-first">

### Prefooter

* Content can be one or two columns in prefooter depending on need.
* Content is populated in a Z-order, chronologically.


</div>

<div class="content-67 content-last">
![style_prefooter.png]({{site.baseurl}}/static/img/style_prefooter.png)
</div>

<div class="content-33 content-first">

### Mobile

* All elements become single column.
* Mobile link style should be used in place of normal links


</div>


<div class="content-67 content-last">
![style_mobile.png]({{site.baseurl}}/static/img/style_mobile.png)
</div>


