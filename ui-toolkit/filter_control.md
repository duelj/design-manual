---
layout: page
title: Filterable list control panel
category: UI toolkit
published: true
---

- [Use](#use)
- [Behavior](#behavior)
- [Style](#style)
- [Content guidelines](#content-guidelines)
 {: class="toc"}

<p>Overview of landing page template at 901 screen width or larger.</p>

<nomarkdown>
<img src="{{site.baseurl}}/static/img/filter_top_1.png" alt="filter control example" height="100%" width="100%">
</nomarkdown>

<h2 id="use">Use</h2>

<div class="content-67 content-first">
<p>Controls that allow users to whittle down number of items in a list, housed in an expandable above the list. Use filters in conjunction with search to help users narrow down large amounts of data or content.</p>

#### When to use
* Presenting large amounts of data or content (more than 10 pages of whatever items?)
* Data has relevant characteristics to filter on, for example product and issue for complaint data, location and property type for HMDA, date range and categories for articles
* Users interacting with the content will be interested in more structure than keyword search alone can offer, and more options than a simple list of categories or tags

#### When to use something else
* The total amount of content can be paged through relatively quickly
* Search alone is sufficient for user needs
* Characteristics of the data available as filter categories are not relevant to user needs
</div>

<div class="content-33 content-last">
##### Page components included

[Browse page]()
</div>

<h2 id="behavior">Behavior</h2>
<p>Filters live in an exapandable style element to allow for controls hidden when not in use/needed. The filter controls follow form patterns for grouping, layout, and messaging.
Filters live in an expandable molecule Filter should be maximum of three columns wide with, and should stack as needed for smaller screen sizes. Notification messaging follows the filter control expandable, this way it always precedes the list of results.</p>

<div class="content-50 content-first">
#### Breakpoints 601+ (2-3 column)
![filter_behavior_desktop.png]({{site.baseurl}}/static/img/filter_behavior_desktop.png)
</div>

<div class="content-50 content-last">
#### Breakpoints 600 and less (1 column stacked)
![filter_behavior_mobile.png]({{site.baseurl}}/static/img/filter_behavior_mobile.png)
</div>

<h2 id="style">Style</h2>

<nomarkdown>
<img src="{{site.baseurl}}/static/img/filter_style_1.png" alt="filter style" height="100%" width="100%">
</nomarkdown>

* On page load filter is collapsed
* After filter is applied it remains open, except for mobile breakpoint (< 600px) where is is collapsed after filtering to make vertical space for the notification to be viewed on screen.
* Notification messaging sits below filter and above results

<nomarkdown>
<img src="{{site.baseurl}}/static/img/notifications_style.png" alt="filter notifications style" height="100%" width="100%">
</nomarkdown>

<h2 id="content-guidelines">Content Guidelines</h2>

* Headings and labels should be as succinct as possible, ideally ______ characters  or less.
* Answer options beneath heading should also be succint, roughly ______ characters.
* Call to action link should  ______ characters or less.


