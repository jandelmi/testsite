widget = "pages"  # Use the Pages widget
headless = true   # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
active = true     # Activate this widget? true/false
weight = 1        # Order that this section will appear.
headless = true   # This file represents a page section.

title = "Recent Publications"

[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "publication"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 0
  
  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    exclude_featured = false
    exclude_past = false
    exclude_future = false
    publication = ""
    date = ""
    
[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 2
