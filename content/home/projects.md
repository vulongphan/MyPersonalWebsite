+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Projects"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  color = "navy"
  
  # Background gradient.
  gradient_start = "DeepSkyBlue"
  gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
Auxify Web Application: a project that allows Spotify Premium users to host listening rooms that other users can join. Users in a listening room can vote for which song to play first in a queue. The project integrates backend and frontend development and essentially a MERN (MongoDB, Express, ReactJS, NodeJS) application. MongoDB database is hosted on an EC2 Instance provided by the Amazon Web Service. The Auxify App is hosted by Heroku at http://auxify.herokuapp.com/

Arduino Robot controlled by Processing interface: a school project that makes use of the USB port communication between an Arduino board and Processing program. Controlled by interactive Processing interface, the robot is able to move in four directions and when it approaches an obstacle, an alarm will sound and LED lights will blink. The project is a demonstration of my knowledge in programming with C++ on an Arduino board, programming with Java in Processing and applying efficient USB port communicating protocol. The github repository is available at https://github.com/vulongphan/IntroToIM/tree/master/FinalProject
