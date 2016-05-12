---
layout: page
title: Atomic Design
category: UI toolkit
published: true
---

- [Use](#use)
- [Atomic elements](#atomic-elements)
{: class="toc"}

Atomic design is methodology created by [Brad Frost](http://bradfrost.com/) for creating modular design systems. There are five distinct levels in atomic design (atoms, molecules, organisms, templates, and pages) that create a hierarchy from details to full page styles. 
{: class="lead-in"}

<h2 id="use">Use</h2>
<p>These priciplas were lifted from Brad Frost’s book on atomic design. For more information see his [GitHub repository]().</p>

* They **promote consistency** and cohesion across the entire experience.
* They **speed up your team's workflow**, saving time and money.
* They establish a **more collaborative workflow** between all disciplines involved in a project.
* They establish a **shared vocabulary** between everyone in an organization, including outside vendors.
* They provide **helpful documentation to help educate** stakeholders, colleagues, and even third parties.
* They **make cross-browser/device, performance, and accessibility testing easier**.
* They serve as a **future-friendly foundation** for teams to modify, extend, and improve upon over time.

### When to use
Consumerfinance.gov is built using atomic design elements, which are integrated into both the front end as well as the CMS. If the project is going to live on consumerfinance.gov atomic design elements should be used as the foundation to build from. This promotes consistency and speeds up the workflow when building new pages.


### When to use something else
* If the project is internal facing or must be tied to an existing thrid-party technology
* If the project is a mini-site that exists outside of consumerfinance.gov

<h2 id="atomic-elements">Atomic Elements</h2>

<div class="content-33 content-first">
#### Atoms
<p>Atoms are the smallest and most basic building blocks of our web interfaces. Atoms could be text headings, a form label, an input or a button. These small blocks are combined to make molecules which serve as larger functional components on a page.</p>
</div>

<div class="content-67 content-last">
![atoms_1.png]({{site.baseurl}}/static/img/atoms_1.png)
</div>
