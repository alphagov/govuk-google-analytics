# GOV.UK Google Analytics 4 Implementation Record

This site contains a record of the data structure implemented for Google Analytics 4 by GOV.UK.

## Event data structure

Events should have a data file in `_events` of the following structure. This is used to construct the information on the event detail page.

This structure can contain more than one event. For example accordions have one event for an accordion section, and a different one for the show/hide all control.

If an attribute name matches a data file in `_attributes`, the site will link to that attribute from the event detail page.

Attributes can be given a value, but only if that value differs from the value in the attribute data. If no value is included the site will use the value from the attribute data.

Where the same attribute is used for more than one purpose, an alias can be supplied. If an attribute data contains the same alias, the site will link to that attribute. See below for more information.

```
name: overall name (this is used on the events list page, and to link events to attributes)
events:
  - name: name of an event
    description: description of the event
    data:
      - name: name of attribute
        value: attribute value (optional)
      - name: name of attribute
        value:
          - name: name of attribute
            value: attribute value (optional)
            alias: attribute alias (optional)
  - name: name of another event
    description: description of the event
    data:
      - name: name of attribute
        value: attribute value (optional)
```

## Attribute data structure

Attributes should have a data file in `_attributes` of the following structure. This is used to construct the information on the attribute detail page.

```
name: name of the attribute (this is used on the attributes list page, and to link attributes to events)
alias: attribute alias (optional)
description: further detail about this attribute (optional)
value:
example: an example value for this attribute, shown on the event detail page, if no value is given in the event data file (optional)
required: yes/no
type: the type e.g. string, number, 1-indexed number
redact: true/false
```

### Attribute aliases

Where an attribute is used by different events and the detail of that attribute differs, an alias can be used.

For example, consider the following events, which both use the `language` attribute for different purposes.

```yml
# _events/event_a.md
name: event_a
events:
- name: a fictional event
  data:
    - name: event_data
      value:
        - name: language
          value: JavaScript
          alias: language_event_data

```

```yml
# events/event_b.md
name: event_b
events:
- name: a different fictional event
  data:
    - name: page_view
      value:
        - name: language
          value: en
          alias: language_page_view
```

To support these events, the following attribute data files could be created.

```yml
# _attributes/language_event_data.md
name: language
alias: language_event_data
description: A computer language
```

```yml
# _attributes/language_page_view.md
name: language
alias: language_page_view
description: An international language
```
