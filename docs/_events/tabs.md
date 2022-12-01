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
        value: select_content
      - name: type
        value: tabs
      - name: url
        value: tab identifier/url hash
        example: "#scotland"
      - name: text
        value: text of tab heading
        example: "Scotland"
      - name: index
        value: index of the selected tab
      - name: index_total
        value: number of tabs in total
      - name: section
        value: granular section
---
