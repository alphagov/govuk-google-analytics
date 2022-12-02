---
name: page view
events:
  - name: Page view
    description: When a page loads.
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
      - name: section
        alias: section_page_view
      - name: taxon_slug
      - name: taxon_slugs
      - name: taxon_id
      - name: taxon_ids
      - name: themes
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
---
