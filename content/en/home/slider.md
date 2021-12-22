---
widget: slider
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...
weight: 5  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 400px


item:
  - title: Hello
    content: '10 papers accepted 😄'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    # overlay_color: '#666'  # An HTML color value.
    overlay_img: logo.png  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    # cta_label: Download my app
    # cta_url: 'https://example.org'
    # cta_icon_pack: fas
    # cta_icon: graduation-cap
  - title: New Idea!
    content: 'We had a cool new idea yesterday! 😄'
    align: left
    overlay_color: '#555'
    overlay_img: ''
    overlay_filter: 0.5
    cta_label: Learn more
    cta_url: 'post'
    cta_icon_pack: fas
    #cta_icon: graduation-cap
  - title: Paper accepted!
    content: 'Our new paper on X accepted to ACL! 😄'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
  - title: Open Positions
    content: '10 open positions! 😄'
    align: right
    overlay_color: '#444'
    overlay_img: ''
    overlay_filter: 0.5
---
