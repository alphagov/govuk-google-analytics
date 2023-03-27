---
name: header menu bar
events:
  - name: link clicks
    description: Triggered when the GOVUK logo, a header "menu" section link, or a link under the search component is clicked, right clicked, shift clicked, control clicked, or windows key/command key clicked. Note that this is currently implemented with three index values e.g. "1.1.1". This is noted in our technical debt documentation.
    example_url: https://www.gov.uk/
    tracker: link_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: navigation
      - name: external
      - name: index
        value:
        - name: index_section
          value: The section that this link is in (Menu is 1, Search is 2)
        - name: index_link
          value: The position of the link within its section. GOVUK Logo has an index of 0.
        - name: index_section_count
          value: 2 (Menu and Search)
      - name: index_total
        value: Total links across all sections (currently 28)
      - name: link_domain
      - name: link_path_parts
      - name: method
      - name: text
      - name: type
        value: header menu bar
      - name: url
      - name: section
        value: The heading of the section the link is under, e.g. "Topics", "Government Activity"
  - name: button click
    description: When the Menu or Search button is expanded or collapsed.
    example_url: https://www.gov.uk/
    tracker: event_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: select_content
      - name: type
        value: header menu bar
      - name: text
        value: text of selected button
      - name: index
        value:
        - name: index_section
        - name: index_link
        - name: index_section_count
      - name: index_total
        value: number of buttons in header
      - name: action
        value: '"opened" when clicked to expand, or "closed" when clicked to collapse'
---
