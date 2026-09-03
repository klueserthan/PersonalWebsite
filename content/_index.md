---
title: ''
summary: ''
date: 2026-09-03
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/cv.pdf
      headings:
        about: 'About'
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: lg
      avatar:
        size: large
        shape: rounded
  - block: markdown
    id: research
    content:
      title: What I work on
      subtitle: ''
      text: |-
        No parliament, ministry, or party can process more than a fraction of the demands a society produces. Every institution runs rules, formal and informal, that decide which problems get seen and which get ignored. I study those rules: which issues governments, coalitions, and parties take up, who has the standing to force a problem onto their agendas, and what it means for representation that this power is increasingly exercised from outside those institutions.

        That question runs through three lines of work. In the executive, I look at how bureaucratic structures shape what governments can attend to and translate into law. In party systems, I ask why four decades of rising economic inequality have produced so little political response, work that is becoming the book *Lost in Transmission* (Cambridge University Press, with Alexander Horn and Leo Ahrens). On digital platforms, I follow the migration of attention to actors with no formal role in democratic politics: influencers, recommendation systems, content moderation regimes, and now AI-generated media.

        My current project, *Curated Inequality*, brings these together. It asks what happens to citizens' sense of the income distribution when the reference environment that used to be a neighbourhood or a workplace is an algorithmically curated video feed. Methodologically I mostly work with text-as-data and multimodal classification, survey and online experiments, and time-series cross-section data, with qualitative process tracing where mechanisms inside institutions are at stake.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Selected publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: talks
    content:
      title: Recent talks
      count: 4
      filters:
        folders:
          - events
        exclude_future: true
      order: desc
    design:
      view: card
  - block: collection
    id: news
    content:
      title: From the blog
      page_type: blog
      count: 3
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
