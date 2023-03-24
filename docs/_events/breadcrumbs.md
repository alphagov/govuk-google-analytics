---
name: Breadcrumbs
events:
  - name: link clicks
    description: Triggered when a breadcrumb link is clicked, right clicked, shift clicked, control clicked, or windows key/command key clicked.
    example_url: https://www.gov.uk/learn-to-drive-a-car
    tracker: link_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: navigation
      - name: external
        value: 'false'
      - name: index
        value:
        - name: index_link
        value: The position of the link within the breadcrumbs from left to right.
      - name: index_total
      - name: link_domain
      - name: link_path_parts
      - name: method
      - name: text
      - name: type
        value: breadcrumbs
      - name: url
---
