# Javascript Load
The load event is commonly used to trigger scripts that access the contents of the page. In this example, a function called setup() gives focus to the text input when the page has loaded. The event is automatically raised by the window object when a page has finished loading the HTML and all of its resources: images, CSS, scripts (even third party content.) The setup() function would not work before the page has loaded because it relies on finding the element whose id attribute has a value of username, in order to give it focus.

## Components that make the app run
* Note that the event listener is attached to the window object nothe document object as this can cause cross-browser campatibility issues.
* If the script element is at the end of the HTML page, then the DOM would have loaded the form elements before the script runs, and there would be no need to wait for the load event.

## How to run the app?
* In your own terminal:
```
git clone https://github.com/bostonhuman/javascript-load
```
* Open `load.html` to run the app.
