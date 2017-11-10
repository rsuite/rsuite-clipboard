###  Clipboard

|Prop name|Type|Default|Description|
|---|---|---|---|
|text|`String`|--|Text to be copied to clipboard.|
|children|`String`|--|CopyToClipboard is a simple wrapping component, it does not render any tags, so it requires the only child element to be present, which will be used to capture clicks.|
|onCopy|`function(text,result)`|--|Optional callback, will be called when text is copied|

###  Clipboard.copy
If you don't want to use `Clipboard`, you can execute this function to copy text in clipboard.
```
 @param {String} text - Text to be copied to clipboard. 
 @param {Element} prevElem - The elements before the fake elements,defalut value is document.body.firstElementChild. 
 @return {Boolean} - Whether copy success.
```

###  Clipboard.select
Programmatically select the text of a HTML element.
```
 @param {HTMLElement} Element
```