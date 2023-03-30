---
name: HTML attachments
events:
  - name: link clicks (not implemented yet)
    description: Triggered when a HTML attachment link is clicked, right clicked, shift clicked, control clicked, or windows key/command key clicked.
    example_url: https://www.gov.uk/government/publications/equality-act-guidance
    tracker: link_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: navigation
      - name: external
      - name: link_domain
      - name: link_path_parts
      - name: method
      - name: text
      - name: type
        value: html attachment
      - name: url
---
