# linksToSelect
Module for turning a list of links into a navigational select menu.

## Sample Usage
``` javascript
let linksToSelectInst = linksToSelect(element, linksToSelectOptions);
```

## Settings
``` javascript
let linksToSelectOptions = {
	linkSelector: 'a',
    linkAttributeSelector: 'href',
    linkActiveClass: 'is-active',
    linksWrapperClass: 'lts-link-wrapper',
    selectClass: 'lts-select',
    destinationEl: null,
    onSelectChangeCallback: null
}
```

## Available Methods
* create()
* destroy()

## Revision History
* **1.0.0:** First commit.