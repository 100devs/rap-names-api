# rap-names-api

# Rap Names API

[1]: <https://github.com/100devs/rap-names-api>

Rap Names API allows you to search a database of every rapper named chance the rapper and 21 savage. 

#### Demo
![Screen Recording 2022-06-07 at 2 02 42 PM](https://user-images.githubusercontent.com/44770822/172462757-a11f76d8-1159-4ca9-be67-910ccf990e9e.gif)

https://user-images.githubusercontent.com/44770822/172461956-0d2b326b-c4f9-4ad3-8b24-a82606bd32a2.mov



http://patchpanel.alecortega.com

![alt tag](http://oi61.tinypic.com/sp8axi.jpg)

#### Package Managers

````
// Bower
bower install patch-panel
// NPM
npm install patch-panel
````

#### Settings

| Option | Type | Deault | Description |
|--------|------|--------|-------------|
|buttonSelector | string | '.patch-button' | Changes the selector that triggers the panel animation.|
|itemSelector | string | '.patch-item' | Changes the selector for all child items that make up the grid (items that are shown).|
|panelSelector | string | '.patch-panel' | Changes the selector for all panel items (panels are automatically hidden).|
|toggleSpeed | int | 300 | Changes the speed at which panels are animated.|


#### Initialization Example

```javascript
$(element).patchpanel({
  toggleSpeed: 600
});
```

#### Gotchas

* All elements are automatically hidden upon initialization with jQuery. Since there's a delay between the DOM loading and javascript initializing, the panels may flicker from visible to hidden. You can avoid this by placing the following in your stylesheet:

````javascript
.patch-panel {
  display: none;
}
````

#### Future Updates

* Better handling of events so that only two panels are triggered at any one time.
* Callback events for panel triggered, and panel finished collapsing.
* Handling of items of multiple heights.
* Add super simple stylesheet that adds proper styling.

#### Dependencies

jQuery 2.1

#### License

Copyright (c) 2015 Alec Ortega

Licensed under the MIT license.
