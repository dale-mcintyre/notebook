+++
# Required
title = "{{ replace .File.ContentBaseName "-" " " | title }}"
date = {{ .Date }}
draft = true

# Optional - Post settings
# slug = "custom-url-slug"
# summary = "A brief summary shown in the archive list (if not set, Hugo auto-generates one)"
# description = "Used for SEO meta description"

# Taxonomy
# tags = ["mandarin", "travel", "beijing"]
# categories = ["language-learning"]

# Location
# location = "Beijing, China"

# Reading time override (Hugo auto-calculates, but you can set manually)
# readingTime = 5

# If you want to hide from the archive list
# private = true

# Series (for multi-part posts)
# series = ["My Yunnan Trip"]
# series_order = 1
+++

<!-- 
IMAGE REFERENCE CHEATSHEET
===========================
Image in static/img/:
![Description](/img/filename.jpg)

Image in static/posts/img/:
![Description](/posts/img/filename.jpg)

Line break: two spaces at end of line  
New paragraph: blank line between text

PUBLISH CHECKLIST
=================
1. Change draft = true to draft = false
2. git add .
3. git commit -m "Add post: title"
4. git push
-->

Your content here...