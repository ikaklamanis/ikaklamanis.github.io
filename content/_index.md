---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download Résumé
      #   url: uploads/resume_06_26.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      spacing:
        padding: ["3rem", "0", "2rem", "0"]
  - block: publications
    id: publications
    content:
      title: Publications & Manuscripts
    design:
      spacing:
        padding: ["2rem", "0", "2rem", "0"]
  - block: experience
    id: education
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
      spacing:
        padding: ["3rem", "0", "2rem", "0"]
  - block: cv-list
    id: teaching
    content:
      title: Teaching
      source: teaching
    design:
      spacing:
        padding: ["1rem", "0", "2rem", "0"]
  - block: cv-list
    id: talks
    content:
      title: Talks
      source: talks
    design:
      spacing:
        padding: ["1rem", "0", "2rem", "0"]
  - block: cv-list
    id: service
    content:
      title: Academic Service
      source: service
    design:
      spacing:
        padding: ["1rem", "0", "2rem", "0"]
  # - block: skills
  #   content:
  #     title: Skills & Hobbies
  #     username: admin
  # - block: awards
  #   content:
  #     title: Awards
  #     username: admin
  # - block: languages
  #   content:
  #     title: Languages
  #     username: admin
---
