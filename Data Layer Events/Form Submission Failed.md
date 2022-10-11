# Form Submission Failed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "form_error",
  "detailed_event": "Form Submission Failed",
    "event_data": {
        "error_message": "<error_message>",
        "form_field_error_message": "<form_field_error_message>",
        "form_field_id": "<form_field_id>",
        "form_field_position": "<form_field_position>",
        "form_field_section": "<form_field_section>",
        "identifier": "<identifier>",
        "name": "<name>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.error_message|string|Captures the form error code or message associated with form errors.|Credit card declined, Required entries missing, EC3456, EC8976|||||||
|event_data.form_field_error_message|string|Captures the form field error code or message associated with form field errors.|email address invalid, date required. EC987767, EC4567|||||||
|event_data.form_field_id|string|Captures the ID of each field contained on a form.||||||||
|event_data.form_field_position|string|Captures the numeric position of each form field within a form \(i.e. 1, 2, 3\).|1, 2, 3, 4, 5||||1|||
|event_data.form_field_section|string|Captures the section containing each form field \(i.e. CC Info, Address\).|address1, address2, cc info, terms acceptance|||||||
|event_data.identifier|string|Captures the unique ID of the form.|F-0113, 2543, CU001, PI-0988|||||||
|event_data.name|string|Captures the human-friendly name of the form.|Payment Info, Mailing Address, Payment Address, Contact Us|||||||




