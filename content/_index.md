---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-02-28
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: sohanjs
      text: "M.Sc. Autonomy Technology student at FAU Erlangen-Nürnberg | Passionate about Artificial Intelligence, Computer Vision, and Robotics."
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Sohan_Joseph_Saldanha_CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '🤖 My Interests & Research'
      subtitle: ''
      text: |-
        I am a graduate student specializing in **Autonomy Technology** at **FAU Erlangen-Nürnberg** with a focus on **Human-System Interfaces, Sensor & Perception**. My research interests lie in **Artificial Intelligence, Computational Visual Perception, Computer Vision, Machine Learning, and Robotics**.

        I have worked on projects involving **LiDAR-based localization, chatbot development, web scraping automation, curriculum learning in AI, and embedded systems**. Currently, I am exploring **image recognition, smart buildings, and AI-driven wearables**.

        I am open to collaborations, internships, and discussions on innovative research topics. Let's connect!
    design:
      columns: '1'

  - block: collection
    id: research-projects
    content:
      title: Research & Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: publications
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: events
    content:
      title: Upcoming Events
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: news
    content:
      title: Recent News & Achievements
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-card
    content:
      title: 🚀 Let's Collaborate!
      text: |-
        If you're interested in **AI, Robotics, Computer Vision, Embedded Systems**, or any related topics, I’d love to connect! I am always looking for exciting projects, research collaborations, and innovative discussions.

        Feel free to reach out via **[LinkedIn](https://www.linkedin.com/in/sohanjs/)** or **[GitHub](https://github.com/sohanjs111)**!
      button:
        text: Connect with Me
        url: https://www.linkedin.com/in/sohanjs/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
