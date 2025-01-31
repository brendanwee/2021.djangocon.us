---
abstract: With no 'standard' approach to front-end other than built-in templating
  and so many JS front-end frameworks and tools and options, it's easy to get thrown
  for a loop. HTMX lets us stick to what django is good at - server-side stuff, mainly
  - without feeling like we're missing out on modern tools.
accepted: true
category: talks
date: 2021-10-22 16:58:00 -0500
difficulty: Beginner
image: /static/img/social/presenters/jack-linke.png
layout: session-details
permalink: /talks/server-side-is-dead-long-live-server/
presenter_slugs:
- jack-linke
presenters:
- bio: "Jack Linke tends to learn the hard way - and shares the lessons from those
    experiences with others through blogging, tweets, and speaking engagements. He
    has been developing software and hardware projects off-and-on for most of his
    life, but much of his relevant web development experience has been hard-earned
    over the past four years during development of [Watervize](https://www.watervize.com)
    - a B2B2B SaaS web application (written in Django) to help irrigation water utility
    companies improve efficiency, analysis, and communication with staff and agriculture
    customers.\r\n\r\nJack's technology interests include Python, the Django project,
    HTMX, GIS, graph theory, data storytelling, and visualization. He is a frequent
    contributor to the open source community and a contributing member of the Python
    Software Foundation.\r\n\r\nHis speaking experience includes briefing Generals
    on topics ranging from budgets to technical concepts, instructing at formal training
    centers, and providing software demonstrations and feature walk-throughs.\r\n\r\nOutside
    of coding, Jack solves unusual math and logic problems, and makes a mess in the
    kitchen."
  company: Watervize
  github: ''
  name: Jack Linke
  photo_url: ''
  twitter: JackDLinke
  website: https://www.jacklinke.com
published: true
sitemap: true
slides_url: ''
summary: ''
tags:
- Django
- javascript
- web
- ux
- user experience
- front-end
- tools
- htmx
- ajax
talk_slot: full
title: Server-Side is Dead! Long Live Server-Side (+ HTMX)
video_url: ''
---

## Objectives

By the end of this talk, audience members will have a better understanding of what HTMX is, will understand concrete examples of how it can be applied to their django projects, and will have a list of resources for further learning and discussion.

## Outline

- The current state
    - Frameworks for days
    - Front-end roadmap
    - Django templates

- One potential approach

- Feature and approach walk-throughs
  For a variety of common web application features, we will take a look at a typical django approach and how one might approach the problem with django + htmx.

    1. Messaging inbox functionality (read/archive)
        - A traditional Django approach
        - Django + HTMX approach
    2. One-click settings
        - A traditional Django approach
        - Django + HTMX approach
    3. Multiple forms in multiple tabs
        - A traditional Django approach
        - Django + HTMX approach

- Tips, best practices, and pitfalls
    - CSRF Tokens
    - More Views
    - Complimentary JS libraries
    - Simplifying things with django-htmx
    - Additional resources
