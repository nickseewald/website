+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

title = "About Nick"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
# hero_media = "banner.jpg"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"

  # Background gradient.
  gradient_start = "#4bb4e3"
  gradient_end = "#2b94c3"

  # Background image.
  image = "banner.jpg"  # Name of image in `static/img/`.
  image_darken = 0.5  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "top left"  # Options include `left`, `center` (default), or `right`.
  image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["5em", "0", "4em", "0"]

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
#[cta]
#  url = "/../files/Seewald-Curriculum-Vitae.pdf"
#  label = "Curriculum Vitae"
#  icon_pack = "fas"
#  icon = "book"
#
#[cta_alt]
#  url = "https://sourcethemes.com/academic/"
#  label = "View Documentation"

## Note. An optional note to show underneath the links.
#[cta_note]
#  label = '<a class="js-github-release" href="https://#sourcethemes.com/academic/updates" data-repo="gcushen/hugo-#academic">Latest release<!-- V --></a>'


+++
<hr style="background-image: linear-gradient(to right, #fff, #fff)"/>

<div>
  <a class="btn btn-light" style="text-decoration:none;" href="../files/seewaldCV.pdf" target="_blank">
    <i class="fas fa-book" style="padding-right:.5em;"></i>
    Curriculum Vitae
  </a>
