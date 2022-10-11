# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load_started",
  "detailed_event": "Page Load Started",
    "page_data": {
        "country": "<country>",
        "language": "<language>",
        "page_location": "<page_location>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.country|string|The country the site is associated with.||||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_data.page_location|string|The url of the page currently being viewed.||||||||




