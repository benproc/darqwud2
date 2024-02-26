---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        #- text: Read my latest paper on LLMs
         # icon: academicons/arxiv
          #url: https://arxiv.org/abs/2304.01852
        - text: Listen on Spotify
          icon: custom/spotify
          url: https://open.spotify.com/artist/12lcNetWkDskLYJAkGfXGH?si=0E3n5NV6RV2HFbW5YqEjmw
        - text: Listen on SoundCloud
          icon: custom/soundcloud
          url: https://soundcloud.com/darqwud
        - text: Listen on Apple Music
          icon: custom/apple
          url: https://music.apple.com/us/artist/darqwud/1688288143
          ##need to fix the icons
          
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: 'Check out my recent blog posts below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: card
---
