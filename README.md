# toggle-switch by a8z
[![Size](https://img.shields.io/github/size/andyfrantz/a8z-toggle-switch/build/toggle-switch.css?label=Size&style=for-the-badge)](https://github.com/andyfrantz/a8z-toggle-switch/master/build/toggle-switch.css)
[![Stars](https://img.shields.io/github/stars/andyfrantz/a8z-toggle-switch?style=for-the-badge)](https://github.com/andyfrantz/a8z-toggle-switch/stargazers)
[![Issues](https://img.shields.io/github/issues/andyfrantz/a8z-toggle-switch?style=for-the-badge)](https://github.com/andyfrantz/a8z-toggle-switch/issues)
[![License](https://img.shields.io/github/license/andyfrantz/a8z-toggle-switch?style=for-the-badge)](https://github.com/andyfrantz/a8z-toggle-switch/blob/master/LICENSE)

A toggle switch build with pure CSS, that can be used in forms as input checkboxes.

## Preview
<img src="https://raw.githubusercontent.com/andyfrantz/a8z-toggle-switch/master/docs/preview-toggle-switch.png">

## Installation

### CSS
```<link rel="stylesheet" href="build/toggle-switch.css">```

### HTML
```
<label class="a8z-toggle-switch">
	<input checked type="checkbox" id="ID_HERE">
	<span class="toggle">
		<span class="switch"></span>
	</span>
</label>
```

## Options

| Option | Data Attribute |
| ------ | ------ |
| Rounded | `data-style="rounded"`
| Square | `data-style="square"`
| No Text | `data-text="false"`
| Disabled | add the `disabled` attribute to the input tag
| Checked | add the `checked` attribute to the input tag
| Sizes | `data-size="xl"`<br>`data-size="lg"`<br>medium (default)<br>`data-size="sm"`<br>`data-size="xs"`
| Colors | `data-color="red"`<br>`data-color="orange"`<br>`data-color="yellow"`<br>`data-color="green"`<br>`data-color="blue"`<br>`data-color="purple"`<br>`data-color="gray"`<br>`data-color="brown"`<br>`data-color="pink"`<br>`data-color="indego"`<br>`data-color="teal"`
| Labels | `data-label="left"`<br>label on right (default)<br>
| content text / width | use the `style` attribute to modify the css variables<br>`style="--a8z-ts-input-checked-content:'VISIBLE'; --a8z-ts-input-unchecked-content: 'HIDDEN'; --a8z-ts-width: 90px;"`


## Features
* CSS only - no JavaScript!
* No dependencies
* Fully reponsive
* Fully customizable (change input content text / widht)
* Fully self contained
* 11 color schemes
* Labels on the left and the right
* Keyboard Accessible - accessibility (a11y)
* Focus Styles - accessibility (a11y)
* Supports all modern browsers
* Search engine friendly
* Screen reader friendly
* Doesn't dump a bunch of global styles that'll screw with your other CSS
* Everything is customizable with scss variables if using the scss source file
* Everything is customizable if overwriting the css variables in the `a8z-toggle-switch` class

