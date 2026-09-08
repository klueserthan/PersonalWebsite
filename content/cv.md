---
title: 'CV'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: markdown
    content:
      title: ''
      text: '{{< print-button >}}'
    design:
      columns: '1'
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'Jan 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Methods
      username: me
  - block: resume-awards
    content:
      title: Grants
      username: me
      icon_contains: banknotes
  - block: resume-awards
    content:
      title: Awards
      username: me
      icon_contains: trophy
---
