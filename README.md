<div style="background-color: #FFF2D2; border: 1px solid #FFF2D2; color: #784600; overflow: hidden; padding: 8px 35px 8px 14px; border-radius: 4px; position: relative;">
		The Last Insert Key Add-In will be deprecated and no longer available for use starting on <b>September 17, 2024</b>. For any product questions or feature requests, please reach out to the <a href="https://community.geotab.com/s/topic/0TO2J000000NNbGWAW/feedback-hub?language=en_US">Feedback Hub</a>.
</div> 

# addin-last-insert-key
This Add-In automates the generation of a report for the most recent assignment of an NFC key or driver to a vehicle within the from date. Options are provided to select the from date and sorting. Generation of a downloadable report is accomplished with a single click.


## Installation
Add the configuration below to the to the system setting -> add-ins section of the MyGeotab database

```json
{
  "name": "Last Insert Key Report",
  "supportEmail": "support@geotab.com",
  "version": "0.0.1",
  "items": [{
    "url": "https://cdn.jsdelivr.net/gh/Geotab/addin-last-insert-key@master/dist/lastInsertKey.html",
    "path": "ActivityLink/",
    "menuName": {
      "en": "Last Insert Key"
    },
    "icon": "https://cdn.jsdelivr.net/gh/Geotab/addin-last-insert-key@master/dist/images/icon.png"
  }]
}
```