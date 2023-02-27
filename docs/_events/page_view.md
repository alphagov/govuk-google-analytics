---
name: page view
events:
  - name: Page view
    description: When a page loads.
    tracker: page_view_tracker
    data:
    - name: event
      value: page_view
    - name: page_view
      value:
      - name: referrer
      - name: location
      - name: title
      - name: status_code
      - name: document_type
      - name: publishing_app
      - name: rendering_app
      - name: schema_name
      - name: content_id
      - name: browse_topic
      - name: taxonomy_main
      - name: taxonomy_all
      - name: taxonomy_main_id
      - name: taxonomy_all_ids
      - name: taxonomy_level1
      - name: language
      - name: history
      - name: withdrawn
      - name: first_published_at
      - name: updated_at
      - name: public_updated_at
      - name: publishing_government
      - name: political_status
      - name: primary_publishing_organisation
      - name: organisations
      - name: world_locations
      - name: dynamic
---
