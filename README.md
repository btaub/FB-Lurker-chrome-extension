# FB-Lurker-chrome-extension
Chrome extension to remove the Make Post box at the top of Facebook.

This extension does one thing, and one thing only...it removes the Make Post option across facebook.com. Here's what happens under the hood:

```javascript
document.getElementById("pagelet_composer").remove();
```

That's it.

# Example with extension enabled:

<img src="facebook-lurker.png" />

# Example without extension enabled:

<img src="facebook.png" />
