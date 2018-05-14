---
project: achievibit
title: kibibit's Document Explorer
layout: homepage
---

# kibibit's Document Explorer - Jekyll theme

Basically, there are **3 page layouts** at the moment:

- #### homepage
  have navigation

- #### default
  clean page with a `bulma.io` markdown theme. have navigation

- #### postmortem
  meant to be used to write postmortem posts.
    currently, there's only a "Back" button to take you to the homepage
  TODO: need to document variables needed for the page

## Available Includes

By default, the theme supports the following includes:

- #### backy
  use `include backy.html` in order to include a back button to the homepage (or use like `include backy.html upbyone=true` in order to go up one step)
  
  ##### DEMO
  {% include backy.html %}
- #### explain
  use `include explain.html details="<explanation>"` to add an index after a specific word. the `details` variable will be included in the footer
  
  
  ##### DEMO
  {% include explain.html details="explanation" %}
- #### navigation
  use `include nav.html` to add the navigation bar to your page
  
  
  ##### DEMO
  {% include nav.html %}
- #### date
  use `include date.html day="2015-10-21"` to include a date tag.
  date tags support the following variables: `day`, `zone`, `location` (`include date.html day="2015-10-21" zone="UTC" location="Tel-Aviv, Israel"`)
  
  
  ##### DEMO
  {% include date.html day="2015-10-21" zone="UTC" location="Tel-Aviv, Israel" %}

----

created by Neil Kalman thatkookooguy@kibibit.io

<span class="kb-logo"><a href="http://kibibit.io">kibibit</a></span>


### Example Variables:

this is the **homepage** layout
