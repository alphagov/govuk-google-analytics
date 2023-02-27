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

---
