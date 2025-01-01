---
title: 'Home'
date: 2025-01-01
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: All Eyes on Gaza
      text: Documenting the on-going genocide in Gaza from a European perspective 
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: diagonal-stripes.svg
          filters:
            brightness: 0.5
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: documentation
      text: check the different categories
      items:
        - name: media coverage
          icon: tv
          description: Media coverage of the on-going genocide in Gaza.
        - name: academic references
          icon: academic-cap
          description: Academic references of the israeli occupation of Palestine.
        - name: NGOs
          icon: lifebuoy
          description: NGOs that have been active.
        - name: podcasts
          icon: radio
          description: Podcasts that will make you aware of what is really going on in our societies and in Palestine.
        - name: corporations
          icon: building-office-2
          description: Corporations that are enabling Palestine's occupation and the on-going genocide.
        - name: take action
          icon: heart
          description: Various ways to help!
---
