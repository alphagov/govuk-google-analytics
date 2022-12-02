---
name: accordion
events:
  - name: Accordion section
    description: When a section of the accordion is opened or closed.
    example_url: https://www.gov.uk/coronavirus
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
        value: index of the accordion section (starting from 1)
      - name: index_total
        value: number of sections in accordion (not including 'show all')
      - name: action
        value: '"opened" when clicked to expand, or "closed" when clicked to collapse'
  - name: Show all sections
    description: When the 'Show all sections' control is used.
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
