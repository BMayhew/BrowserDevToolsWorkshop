# Interesting Javascript to execute in console

## From React Todo App

```javascript
Array.from(document.querySelectorAll('.toggle')).forEach(button=>button.click())
```

## Monitor Events (get more info from elements on any web page)

```javascript
monitorEvents(window,'click')
```

## See Cookies Quickly

Note that cookies without the HttpOnly attribute are accessible on document.cookie from JavaScript in the browser.

```javascript
document.cookie
```

## Set Your Own Styles

```javascript
document.body.style.background = "url(https://media.giphy.com/media/Zx1ZEctOOvxK5VCwwE/giphy.gif)"
```

## Lots More Examples

http://bgrins.github.io/devtools-snippets/
https://www.freecodecamp.org/news/javascript-console-log-example-how-to-print-to-the-console-in-js/
https://itnext.io/5-ways-to-loop-over-dom-elements-from-queryselectorall-in-javascript-55bd66ca4128
