---
layout: page
title: Document detail
category: UI toolkit
published: true
---


- [Use case](#use)
- [Behavior](#behavior)
- [Content guidelines](#content-guidelines)
- [Style](#style)
 {: class="toc"}

<p>Document detail page types provide summary information about a document or related group of documents. These pages help users better understand the relevancy and context of documents before deciding whether or not to download or engage further.</p>

<p>Each document detail page template has three basic content areas:</p>

<div class="content-50 content-first">
![docdetail_top_example.png]({{site.baseurl}}/static/img/docdetail_top_example.png)
</div>

<h2 id="use">Use case</h2>

<div class="content-67 content-first">

#### When to use
* When the primary goal of the page is to encourage users to download a resource or understand the context around a document. 
* When creating a filterable list of items, document detail pages house the items within the filterable list.
 

#### When other options are better
* When providing the full text of an article or detailed content, but not specifically focused on a document for download, use the more general [Learn page template]().
</div>

<div class="content-33 content-last">
##### Page components included
<p>Within each area of the template, various components may be selected to best fit the content of the specific page being created.</p>

#### Area 1
[Item introduction]()


#### Area 2

[Full width text field]()
[Table]()
[Expandable]()

#### Area 3

[Metadata / Related posts / Related links]()
[Contact information]()
[Email sign up]()
</div>

<h2 id="behavior">Behavior</h2>

<p>Below the 901 px breakpoint, the sidebar stacks below the main content area.</p>

<div class="content-50 content-first">

#### Breakpoints 901+
![docdetail_behavior_desktop.png]({{site.baseurl}}/static/img/docdetail_behavior_desktop.png)
</div>

<div class="content-50 content-last">

#### Breakpoints 900 and less
![docdetail_behavior_mobile.png]({{site.baseurl}}/static/img/docdetail_behavior_mobile.png)
</div>

### Post Preview

<p>When document detail pages are accessed via entries within a filterable list, information about each page is displayed on [filterable list pages]() via the post preview component.</p>

<div class="content-67 content-first">

#### Post preview within a filterable list at breakpoints 601+
![post_preview_desktop_1.png]({{site.baseurl}}/static/img/post_preview_desktop_1.png)
</div>

<div class="content-33 content-last">

#### Breakpoints 600 and less
![post_preview_mobile_1.png]({{site.baseurl}}/static/img/post_preview_mobile_1.png)
</div>

<h2 id="content-guidelines">Content guidelines</h2>

### Document detail page

* Page content should provide context for the document housed on the page and should help users get a sense of what will be in the document; what answers it provides, what they will learn, etc.
* Multiple documents should only be grouped on a single page when they are different versions of a single document, or help to provide context that wouldn’t be there without the docs being shown together.


### Post preview
* May use up to two category labels, but strongly recommended to assign one category label per page.
* Function of the post preview is to provide context to the user to help them decide if the document has the information they need. Language should provide a “nudge” to action. 
* Post preview will be linked, so no need to provide “Click here to read more” direct call to action, or link to the doc detail page within the preview description text.
* Post preview text should be limited to 2-3 sentences; 50 words. 

<h2 id="style">Style</h2>

### Document detail page

#### Area 1: Item introduction
* Using the item introduction is required.

#### Area 2: Main content
* At least one component is required here.

#### Area 3: Sidebar
* Strongly recommend using the metadata sidebar component in order to display basic information about the document(s) housed on this page.
* When the metadata sidebar is used, it must appear at the top of the sidebar area. 


### Post preview

#### Possible metadata inputs shown

<nomarkdown>
<img src="{{site.baseurl}}/static/img/post_style.png" alt="post preview inputs" height="100%" width="100%">
</nomarkdown>


<div class="content-50 content-first">
1. Category label - minicon, H4 (2 max)

2. Date - H5 Grey #75797C **(required)**

3. Image (thumbnail) - 30px padding

4. Event date icon - Unique option for events, dynamic icon with 15px padding

5. Post title - H3 **(required)**
</div>

<div class="content-50 content-last">
6. Sub-heading - H6

7. Description - Avenir paragraph **(required)**

8. Author label - Avenir paragraph

9. Secondary link - Standard hyperlink

10. Topics tags - H6 Grey #75797C, 80% gold #FAAF4C dotted underline and round bullet
</div>



