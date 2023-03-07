---
name: print page
events:
  - name: print page
    description: When a 'print this page' button is used
    example_url: https://www.gov.uk/guidance/register-a-trust-as-a-trustee
    tracker: event_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: print_page
      - name: index
      - name: index_total
      - name: section
      - name: type
        value: print page
---
