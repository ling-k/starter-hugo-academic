---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 140

title: Recent Posts
subtitle: 'still test temporary' 


content:
  # Page type to display. E.g. post, talk, publication...
  page_type: post 
  # Choose how many pages you would like to display (0 = all pages)
  filter_default: 0
  # Filter on criteria
  filter_button:
  - name: All
    tag: '*'
  - name: Deep Learning
    tag: Deep Learning
  - name: Test Tag
    tag: Test Tag
  - name: Other
    tag: Demo


design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 1

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
