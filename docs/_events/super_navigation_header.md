---
name: super navigation header
events:
  - name: Header menu bar buttons
    description:
    tracker: event_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: action
        value: opened/closed
      - name: event_name
        value: select_content
      - name: index
      - name: index_total
        value: 2
      - name: section
        value: Menu/Search
      - name: type
        value: header menu bar
      - name: text
        value: Menu/Search
  - name: GOV.UK logo
    description:
    tracker: link_tracker
    data:
    - name: event
      value: event_data
      name: event_data
      value:
      - name: event_name
        value: navigation
      - name: type
        value: header menu bar
      - name: text
        value: GOV.UK
      - name: section
        value: Logo
      - name: index
        value: 0
      - name: index_total
        value: 29
      - name: url
        value: https://www.gov.uk/
---
