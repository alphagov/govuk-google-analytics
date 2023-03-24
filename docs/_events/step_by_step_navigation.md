---
name: step by step navigation
events:
  - name: Open/close step
    description:
    example_url: https://www.gov.uk/learn-to-drive-a-car
    tracker: event_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: action
        value: opened/closed
      - name: event_name
      - name: index
      - name: index_total
      - name: text
      - name: type
        value: "step by step"
  - name: Show/hide all steps
    description:
    example_url: https://www.gov.uk/learn-to-drive-a-car
    tracker: event_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: action
        value: opened/closed
      - name: event_name
      - name: index
        value: 0
      - name: index_total
      - name: text
      - name: type
        value: "step by step"
  - name: link clicks
    description: Triggered when a link within a step by step is clicked, right clicked, shift clicked, control clicked, or windows key/command key clicked.
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
      - name: index
        value:
        - name: index_section
          value: The section that this link is in. The section in this case refers to the step number.
        - name: index_link
          value: The position of the link within its section.
      - name: index_total
      - name: link_domain
      - name: link_path_parts
      - name: method
      - name: text
      - name: type
        value: step by step
      - name: url
      - name: section
        value: The name of the step
---
