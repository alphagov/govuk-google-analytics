---
name: links
events:
  - name: External links
    description: When a link is followed to a page outside of www.gov.uk.
    tracker: specialist_link_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: navigation
      - name: external
        value: true
      - name: link_domain
      - name: link_path_parts
      - name: method
      - name: text
      - name: type
        value: generic link
      - name: url
  - name: Download links
    description: When a link is followed to an asset such as a PDF.
    tracker: specialist_link_tracker
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: file_download
      - name: external
      - name: link_domain
      - name: link_path_parts
      - name: method
      - name: text
      - name: type
        value: generic download
      - name: url
---
