---
name: share this page
events:
  - name: follow us
    description: Triggered when a 'follow us' social media link is used.
    example_url: https://www.gov.uk/government/organisations/department-for-digital-culture-media-sport
    tracker: link_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: navigation
      - name: external
        value: true
      - name: index
      - name: index_total
      - name: link_domain
      - name: link_path_parts
      - name: method
      - name: text
      - name: type
        value: follow us
      - name: url
  - name: share this page
    description: Triggered when a 'share on' social media link is used.
    example_url: https://www.gov.uk/government/news/new-protections-for-children-and-free-speech-added-to-internet-laws
    tracker: link_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: share
      - name: external
        value: true
      - name: index
      - name: index_total
      - name: link_domain
      - name: link_path_parts
      - name: method
      - name: text
      - name: type
        value: share this page
      - name: url
---
