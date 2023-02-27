---
name: accordion
events:
  - name: Accordion section
    description: When a section of the accordion is opened or closed.
    example_url: https://www.gov.uk/coronavirus
    tracker: event_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: select_content
      - name: type
        value: accordion
      - name: text
        value: text of selected accordion
      - name: index
        value:
        - name: index_section
        - name: index_link
        - name: index_section_count
      - name: index_total
        value: number of sections in accordion (not including 'show all')
      - name: action
        value: '"opened" when clicked to expand, or "closed" when clicked to collapse'
  - name: Show all sections
    description: When the 'Show all sections' control is used.
    tracker: event_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: select_content
      - name: type
        value: accordion
      - name: text
        value: text of show all link when clicked e.g. "Show all sections"
      - name: index
        value: 0
      - name: index_total
        value: number of sections in the accordion (not including 'show all')
      - name: action
        value: '"opened" when clicked to expand, or "closed" when clicked to collapse'
---
