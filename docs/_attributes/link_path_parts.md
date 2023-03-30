---
name: link_path_parts
description: An object containing a URL in 100 character parts, usually the href attribute of a link. This is stored like this to get around the 100 character limit on attribute values - many URLs are longer than this. Regardless of the length of the URL, the object will always contain 5 key/value pairs. If the URL is less than 500 characters, unused key/value pairs will be undefined. If the URL is longer than 500 characters, the extra characters will be lost.
value:
example: { 1: "/conditions/vaccinations/flu-influenza-vaccine/", 2: undefined, 3: undefined, 4: undefined, 5: undefined }
required: yes
type: string
redact: true
---
