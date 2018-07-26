---
layout: page
title: A unified navigation for gov.uk

---
{% include styles.md %}

<!-- /////////////// INTRODUCTION /////////////  -->

<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
# A unified navigation for gov.uk
{{ end_block }}

<!-- Row -->{{ row }}
{{ col-10-l }}

{{ intro }}
Navigating across GOV.UK is literally impossible. It’s not one website, it’s two. Or three. Or six, depending on who you ask.

With hundreds of content types, millions of users and six years of research, we began trying to fix a problem that proved to be fundamental and far-reaching: how do we allow users to get from one end of the site to another?
{{ end_block }}

<!-- End column --> {{ end_block }}
<!-- End row --> {{ end_block }}
<!-- End grid --> {{ end_block }}

<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
![Alt text]({{ site.baseurl }}/images/dot-grid.png)
<!-- End row --> {{ end_block }}
<!-- End grid --> {{ end_block }}




<!-- /////////////// PART 1.1 — USERS /////////////  -->
<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
{{ section-title }}
## User needs
{{ end_block }}

{{ body-content }}
However many sites it is behind the scenes, GOV.UK operated according to one major principle: from the beginning, it was split by user group.
‘Mainstream’ users were those using the site for ‘personal’ reasons — applying for a licence, getting a marriage certificate — while ‘Whitehall’ users interacted with the site on a ‘professional’ basis.

Each user group was thought to have its own separate needs, and content was organised accordingly.
{{ end_block }}
<!-- End row --> {{ end_block }}

<!-- Row -->{{ row }}
{% include publishing-apps.html %}
<!-- End row --> {{ end_block }}
<!-- End grid --> {{ end_block }}

<!-- /////////////// PART 1.2 — GROUPING CONTENT /////////////  -->
<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
{{ section-title }}
## Grouping content
{{ end_block }}

{{ body-content }}
In order to begin linking up our content, we needed to figure out what our users where looking at, and why.

GOV.UK has hundreds of content types — an unfortunate hangover from Transition. These needed to be sorted and categorised if we wanted to bring any kind of logic to our user journeys.
{{ end_block }}
<!-- End row --> {{ end_block }}
<!-- End grid --> {{ end_block }}

<!-- Row --> {{ row }}
![Alt text]({{ site.baseurl }}/images/templates.png)
<!-- End row --> {{ end_block }}

<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
{{ body-content }}
We used card sorting to group 72 content types into 5 ‘super groups’.  We used treejack tests to refine our groups with publishers throughout government, and later with thousands of end users.

This gave us a good idea of what kind of content we were publishing, but we needed to know why our users were reading.
{{ end_block }}
<!-- End row --> {{ end_block }}

<!-- Row -->{{ row }}
{% include content-types.html %}
<!-- End row --> {{ end_block }}


<!-- End grid --> {{ end_block }}

<!-- /////////////// PART 1.2 — GROUPING USERS /////////////  -->
<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
{{ section-title }}
## Grouping users
{{ end_block }}

{{ body-content }}
To figure out why our users were looking at different content types, we sifted through all the research done since the launch of GOV.UK. 

This helped us to group our users by three main Jobs To Be Done. 
Jobs To Be Done give a good idea of what a user is trying to achieve, and why.
 
Each job includes a range of tasks, and each task requires the user to interact with a variety of content page types.
{{ end_block }}
<!-- End row --> {{ end_block }}
<!-- End grid --> {{ end_block }}


<!-- Job stories -->
<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
{% include job-stories.html %}
<!-- End row --> {{ end_block }}
<!-- End grid --> {{ end_block }}

<!-- /////////////// PART 1.2 — PLOTTING USER JOURNEYS /////////////  -->
<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
{{ section-title }}
## Plotting user journeys
{{ end_block }}

{{ body-content }}
We had the what, and we had the why. But to fix navigation, we had to marry the two by matching content groups to job stories. 

This allowed us to track our users across the site as they completed different jobs, and gave us an idea of how different content types needed to link up.
{{ end_block }}
<!-- End row --> {{ end_block }}
<!-- Row --> {{ row }}
![Alt text]({{ site.baseurl }}/images/journey.png)
<!-- End row --> {{ end_block }}
<!-- End grid --> {{ end_block }}


<!-- /////////////// PART 2 — THE DESIGN /////////////  -->
<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
{{ section-title }}
## Designing the page
{{ end_block }}

{{ body-content }}
GOV.UK has an incredibly pared back aesthetic. This is for universality, accessibility and clarity.

The simplicity means that our content needs to be of good quality, and the hierarchy needs to be clear. Content should always serve a purpose, and the purpose should be led by one of five user needs.

What users need to do on a page can be high level, such as orientating or leaving the page. Or they can be specific, such as seeing the next steps in a series, seeing what else is related, or seeing more of them same.

By using the five levels of need, we were able to arrange content on the page clearly and consistently.
{{ end_block }}
<!-- End row --> {{ end_block }}

<!-- Row --> {{ row }}
{{ row }}
{% include page-layout.html %}
{{ end_block }}
<!-- End row --> {{ end_block }}

<!-- End grid --> {{ end_block }}

<!-- /////////////// PART 2.1 — COMPONENTS /////////////  -->
<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
{{ section-title }}
## Components
{{ end_block }}

{{ body-content }}
We developed a flexible list component that would change depending on it’s position and content. 
{{ end_block }}
<!-- End row --> {{ end_block }}

<!-- Row --> {{ row }}
{{ col-8-r }}
![Alt text]({{ site.baseurl }}/images/component-1.png) 
{{ end_block }}
<!-- End row --> {{ end_block }}

<!-- Row --> {{ row }}
{{ col-8-r }}
![Alt text]({{ site.baseurl }}/images/component-2.png) 
{{ end_block }}
<!-- End row --> {{ end_block }}

<!-- Row --> {{ row }}
{{ col-8-r }}
![Alt text]({{ site.baseurl }}/images/component-3.png) 
{{ end_block }}
<!-- End row --> {{ end_block }}

<!-- End grid --> {{ end_block }}

<!-- /////////////// PART 2.1 — TESTING /////////////  -->
<!-- Grid --> {{ grid }}
<!-- Row -->{{ row }}
{{ section-title }}
## Testing
{{ end_block }}

{{ body-content }}
We quickly realised that testing the designs would be tricky.

We needed to test with thousands of users, across many content types, and we would be validating three very distinct parts at the same time:



Whether the links made sense and were helpful to users
Whether the link placement was optimal
Whether our user journeys were correct
{{ end_block }}
<!-- End row --> {{ end_block }}
<!-- End grid --> {{ end_block }}

{{ row }}
{% include research.html %}
{{ end_block }}
