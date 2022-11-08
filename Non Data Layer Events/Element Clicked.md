# Element Clicked

### This event is used for cases in which a non-anchor tag is used as a link.

For example, if a `<button>` tag is used in combination with Javascript to represent a download link, you would need to add these attributes to trigger the event to be collected when the element is clicked.

Do not include the “data-dom-event” data attribute on any other elements that you do not want to be tracked.

Check the implementation notes for data-dom-event descriptions.
```
<button
  data-dom-dom_event="<dom_event>"
>
```

## Parameters Definitions

|Data Attribute Name|Data Source Type|Data Source|Description|
| --- | --- | --- | --- |
|dom_event|Custom Code|Custom Code|The value in the data-dom-event attribute|



