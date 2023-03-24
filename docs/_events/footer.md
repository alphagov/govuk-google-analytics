---
name: Footer
events:
  - name: link clicks
    description: Triggered when a footer link is clicked, right clicked, shift clicked, control clicked, or windows key/command key clicked.
    example_url: https://www.gov.uk/
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
          value: The section that this link is in. "Topics" are 1, "Government activity" are 2, "Meta links" (Help, Privacy etc.) are 3, The Open Government Licence link is 4, and the Crown Copyright link is 5.
        - name: index_link
          value: The position of the link within its section.
        - name: index_section_count
          value: 5
      - name: index_total
      - name: link_domain
      - name: link_path_parts
      - name: method
      - name: text
      - name: type
        value: footer
      - name: url
      - name: section
        value: One of "Topics", "Government Activity", "Support Links", "Licence", or "Copyright"
---
