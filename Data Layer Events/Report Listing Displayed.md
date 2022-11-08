# Report Listing Displayed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "view_item_list",
  "detailed_event": "Report Listing Displayed",
    "ecommerce": {
        "listing_filter_count": <listing_filter_count>,
        "number_of_items": <number_of_items>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|ecommerce.listing_filter_count|integer|Captures the number of filters applied to a listing.|0, 20, 12||||0|||
|ecommerce.number_of_items|integer|Count of the number of results in a list of reports|1, 21, 111, 166||||0|||




