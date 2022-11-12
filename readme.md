# Ness
Site Block Chrome Extension Example

## Configuration
- In the app.js file replace
    - // {code} with code you want to run when it detects the website
    - {site} with the websites you want to block
- To add more blocked sites simply copy and paste 
```js
if (window.location.hostname === "{code}") {
    // {code}
}
```
To add another blocked site

## Installation
- Download the source code
    - Configure it to your liking
    
- Go to chrome://extensions (or whatever your browser is) 
    - Enable Developer Mode
    - Click Load Unpacked
    - Go to the path of Ness
- Your done!

## Example
- Go to the Example folder for an exmaple
