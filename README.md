# erdblock-website

## Description
Show an simple block, with given values.


## Config
| Name           | Description  | Values |
| -------------- | ------------- | ----- |
| `url`            | Link to the Webpage | `http://www.google.de` |
| `title`          | Title of the Webpage (frontend use) | `Google` |
| `description`    | Descripton to show | `This is a link to Google` |


## Example
````javascript
var website = require("erdblock-website")()
website.locals.config.title.setValue("Example")
website.locals.config.url.setValue("http://www.example.com/")
website.locals.config.description.setValue("Zwei flinke Boxer jagen")
erdblock.addPlugin(website);
````
