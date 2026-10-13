---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  # Portrait, name, tagline, Contact and CV buttons, profile icons and contact card
  # (layouts/partials/blox/profile-hero.html). Name, role and icons come from `content/authors/admin/`.
  - block: profile-hero
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # One sentence on your research, shown under your name
      text: I study how scientific knowledge is produced, organized, and diffused, and how emerging technologies such as artificial intelligence are reshaping science and innovation.
      cv_url: 'https://polimi365-my.sharepoint.com/:b:/g/personal/11017079_polimi_it/IQBg707-OmdTRrCL6_GvDeuxAec1eI2toAOMR_WIlIhJO1A?e=Az0p6J'
      # Contact card. The Contact button emails `email`. Add `phone` to show a phone line.
      contact:
        email: danielfernando.desouza@polimi.it
        office: Via Lambruschini 4b, Milan
        office_url: 'https://maps.google.com/?q=Via+Lambruschini+4b,+20156+Milano'
        address: Department of Management, Economics and Industrial Engineering, Polytechnic University of Milan, Via Lambruschini 4b, 20156 Milan, Italy
---
