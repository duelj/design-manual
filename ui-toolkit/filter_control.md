---
layout: page
title: Filterable list control panel
category: UI toolkit
published: true
---

- [Use](#use)
- [Behavior](#behavior)
- [Content guidelines](#content-guidelines)
- [Style](#style)
 {: class="toc"}

<p>The filter control panel allows users to whittle down number of items in a list to help them focus in on a specific piece of content they may be looking for, or find content relevant to them based on specific filter parameters, housed in an expandable above the list.</p>

<p>Layout as seen on a browse filterable template:</p>

<nomarkdown>
<img src="{{site.baseurl}}/static/img/filter_top_2.png" alt="filter control example" height="100%" width="100%">
</nomarkdown>

<h2 id="use">Use</h2>

<div class="content-67 content-first">
<p>Use filters in conjunction with search to help users narrow down large amounts of data or content.</p>

#### When to use
* When presenting more than 20 documents or listings together for users to browse through. 
* Users interacting with content will want to focus their searching activities on this specific group of content, rather than using the general site search.
* Data has relevant characteristics to filter on, for example product and issue for complaint data, location and property type for HMDA, date range and categories for articles


#### When other options are better
* The total amount of content can be skimmed in a list of 20 items or less.
* Characteristics available as filter options, such as topics, dates, and categories, are not relevant to the content.  
* Search alone is sufficient for user needs

</div>

<div class="content-33 content-last">
##### Templates used on

[Filterable list page]()
</div>

<h2 id="behavior">Behavior</h2>

<p>Filters live in an [expandable](http://cfpb.github.io/design-manual/ui-toolkit/expandables.html) style element allowing controls  to be hidden when not in use/needed.</p>

<p>On page load, the filter is collapsed by default. After filter is applied it remains open, except for mobile breakpoint (< 601 px) where is is collapsed after filtering to make vertical space for the notification to be viewed on screen.</p>

<p>When a user applies a filter setting, a notification automatically appears below the panel indicating number of results or errors.</p>

<div class="content-50 content-first">
#### Breakpoints 601+ (2-3 column)
![filter_behavior_desktop_1.jpg]({{site.baseurl}}/static/img/filter_behavior_desktop_1.jpg)
</div>

<div class="content-50 content-last">
#### Breakpoints 600 and less (1 column stacked)
![filter_behavior_mobile_1.jpg]({{site.baseurl}}/static/img/filter_behavior_mobile_1.jpg)
</div>

<h2 id="content-guidelines">Content Guidelines</h2>

* Headings and labels should be as succinct as possible, ideally 10 characters or less. Do not use colon (:) or other punctuation after the header.
* Help text in text fields should be 40 characters or less. 
* Answer options beneath heading should also be succinct, roughly 25 characters or less.
* Headings and answer options should be sentence case (unless specifically Proper Nouns or Titles)
 



<h2 id="style">Style</h2>

<nomarkdown>
<img src="{{site.baseurl}}/static/img/filter_style_1.png" alt="filter style" height="100%" width="100%">
</nomarkdown>

<div class="content-67 content-first">
* Follow [form](http://cfpb.github.io/design-manual/ui-toolkit/form-fields.html) patterns for grouping, layout, and messaging.
* Maximum three column wide layout, options stack vertically below 601 pixels.
* Notification messaging sits below filter and above results
</div>


<div class="content-33 content-last">

##### Component parts

[Buttons]()

[Expandable]()

[Form Fields]()

[Links]()

[Typography]()
</div>