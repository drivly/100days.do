# 100 Days of Drivly Open

## Day 1: [Lodash.do](https://lodash.do) 

Easily Transform Data Through a Simple Web API

For example, if you have a large and complex JSON document that's not in your preferred format:

<http://json.fyi/northwind.json>

```json
{
  "Customer": [
    {
      "fax": "030-0123456",
      "city": "Berlin",
      "email": null,
      "phone": "030-3456789",
      "mobile": null,
      "region": null,
      "address": "Obere Str. 0123",
      "country": "Germany",
      "entityId": 1,
      "postalCode": "10092",
      "companyName": "Customer NRZBB",
      "contactName": "Allen, Michael",
      "contactTitle": "Sales Representative"
    },
  ]
}
```

You could easily restructure and re-organize it:

<https://lodash.do/map/Products.name/json.fyi/northwind.json>

```json
{
  "Customer/NRZBB": {
    "fax": "030-0123456",
    "city": "Berlin",
    "email": null,
    "phone": "030-3456789",
    "mobile": null,
    "region": null,
    "address": "Obere Str. 0123",
    "country": "Germany",
    "entityId": 1,
    "postalCode": "10092",
    "companyName": "Customer NRZBB",
    "contactName": "Allen, Michael",
    "contactTitle": "Sales Representative"
  }
}
```

