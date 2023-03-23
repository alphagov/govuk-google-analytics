---
name: taxonomy_all
description: An object containing the content attribute of the meta tag govuk:taxon_slugs in 100 character parts. This is stored like this to get around the 100 character limit on attribute values. Regardless of the length of the meta tag, the object will always contain 5 key/value pairs. If the values are less than 500 characters, unused key/value pairs will be undefined. If the values are longer than 500 characters, the extra characters will be lost.
value: content attribute of meta tag govuk:taxon_slugs
example: {
    "1": "finance-support,premises-rates,company-closure-administration-liquidation-and-insolvency,contract-wo",
    "2": "rking-hours,dismissals-redundancies,food-and-farming-industry,producing-distributing-food-food-label",
    "3": "ling,recruiting-hiring,recruiting-hiring,redundancies-dismissals,sale-goods-services-data,scientific",
    "4": "-research-and-development,self-employed",
    "5": undefined
}
required: no
type: string
redact: false
---
