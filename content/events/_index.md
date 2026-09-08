---
title: Talks
summary: Invited academic talks, public scholarship, and conference presentations.
type: landing
design:
  spacing: '3rem'
sections:
  - block: collection
    content:
      title: Invited academic talks
      count: 0
      order: desc
      filters:
        folders: [events]
        tag: Invited
    design:
      view: talk-entry
  - block: collection
    content:
      title: Media and public scholarship
      count: 0
      order: desc
      filters:
        folders: [events]
        # Union: press appearances plus public panels, round tables and
        # debate-house events that are not academic talks.
        tags: [Media, Public Scholarship]
    design:
      view: talk-entry
  - block: collection
    content:
      title: Conference presentations
      count: 0
      order: desc
      filters:
        folders: [events]
        tag: Conference
    design:
      view: talk-entry
      show_location: true
---
