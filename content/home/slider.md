+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10 # Order that this section will appear.

# Slide interval. 
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "400px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.


  
[[item]]
  title = ""
  content = ""
  align = "center"

  use_pages = true
  pages_title = "Recent Publications"
  pages_type = "publication"

  overlay_color = "#56B4E9"  # An HTML color value.
  overlay_img = "headers/cliff.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.




[[item]]
  title = "Book a Workshop"
  content = "Workshop in the data analysis, data manipulation and visualization in R, modeling, Shiny, and more."
  align = "center"

  overlay_color = "#56B4E9"  # An HTML color value.
  overlay_img = "headers/tree.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.
  
  cta_label = "See Available Workshops"
  cta_url = "/training"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"
  
  use_pages = false
  
[[item]]
  title = ""
  content = ""
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#56B4E9"  # An HTML color value.
  overlay_img = "headers/canyon.JPG"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Get Academic"
  # cta_url = "https://sourcethemes.com/academic/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"
  use_pages = true
  pages_title = "Recent Posts"
  pages_type = "post"
  
[[item]]
  title = "Let's Build Something"
  content = "Data solutions for R packages, Shiny apps, and other data science and research needs."
  align = "center"

  overlay_color = "#56B4E9"  # An HTML color value.
  overlay_img = "headers/ocean.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.
  
  cta_label = "See Available Services"
  cta_url = "/consulting"
  cta_icon_pack = "fas"
  cta_icon = "hammer"
  
  use_pages = false
  
[[item]]
  title = ""
  content = ""
  align = "center"

  use_pages = true
  pages_title = "Recent Talks and Workshops"
  pages_type = "talk"

  overlay_color = "#56B4E9"  # An HTML color value.
  overlay_img = "headers/cliff.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.
+++
