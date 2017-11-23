# CSS variables demo

## Intro

Few lines of code to demonstrate what CSS variables are and how to use them.

This code is available here:

	https://github.com/sixty-nine/css-variables-demo

More information than you ever wanted to know about CSS variables can be found here:

	https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables


## Talk

 - CSS variables are just like variables in LESS or SASS
 - *UNCOOL*: They have an horrible syntax
	 - `--variable-name: value;` to set a value
	 - `var(--variable-name)` to get the value
 - *COOL*: Unlike LESS and SASS, CSS variables can be accessed from Javascript
 	- Get value
		- `element.style.getPropertyValue("--my-var")`
 		- `getComputedStyle(element).getPropertyValue(varName)`
 	- Set value
 		- `element.style.setProperty(varName, 'red')`
