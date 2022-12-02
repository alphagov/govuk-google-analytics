---
name: tabs
events:
  - name: Tab interaction
    description: When a tab is selected.
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
      - name: type
        value: tabs
      - name: url
        value: tab identifier/url hash e.g. "#scotland"
      - name: text
        value: text of the selected tab
      - name: index
        value: index of the selected tab
      - name: index_total
        value: number of tabs in total
---
