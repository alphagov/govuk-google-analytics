---
name: taxonomy_all_ids
description: An object containing the content attribute of the meta tag govuk:taxon_ids in 100 character parts. This is stored like this to get around the 100 character limit on attribute values. Regardless of the length of the meta tag, the object will always contain 5 key/value pairs. If the values are less than 500 characters, unused key/value pairs will be undefined. If the values are longer than 500 characters, the extra characters will be lost.
value: content attribute of meta tag govuk:taxon_ids
example: {
    "1": "ccfc50f5-e193-4dac-9d78-50b3a8bb24c5,68cc0b3c-7f80-4869-9dc7-b2ceef5f4f08,864fe969-7d5a-4251-b8b5-a5",
    "2": "0d57be943f,23a712ff-23b3-4f5a-83f1-44ac679fe615,a1c6c263-e4ef-4b96-b82f-e070ff157367,e2559668-cf36-4",
    "3": "7fc-8a77-2e760e12a812",
    "4": undefined,
    "5": undefined
}
required: no
type: string
redact: false
---
