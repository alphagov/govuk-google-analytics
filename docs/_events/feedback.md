---
name: feedback
events:
  - name: Is this page useful? Yes
    description:
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: form_submit
      - name: section
        value: Is this page useful?
      - name: text
        value: "Yes"
      - name: type
        value: feedback
  - name: Is this page useful? No
    description:
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: form_submit
      - name: section
        value: Is this page useful?
      - name: text
        value: "No"
      - name: type
        value: feedback

  - name: Report a problem with this page
    description:
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: form_submit
      - name: section
        value: Is this page useful?
      - name: text
        value: Report a problem with this page
      - name: type
        value: feedback
  - name: Send me the survey
    description:
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: form_submit
      - name: section
        value: Help us improve GOV.UK
      - name: text
        value: Send me the survey
      - name: type
        value: feedback
  - name: Send
    description:
    data:
    - name: event
      value: event_data
    - name: event_data
      value:
      - name: event_name
        value: form_submit
      - name: section
        value: Help us improve GOV.UK
      - name: text
        value: Send
      - name: type
        value: feedback        
---
