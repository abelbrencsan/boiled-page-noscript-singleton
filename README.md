# Boiled Page noscript singleton

Noscript SCSS singleton for Boiled Page frontend framework. It is intended to show an alert on the top of the page when JavaScript is not enabled. It uses `<noscript>` element for detection.

## Install

Place `_noscript.scss` file to `/assets/css/singletons` directory, and add its path to singleton block in `assets/css/app.scss` file.

## Usage

### Classes

Class name | Description | Example
---------- | ----------- | -------
`noscript` | Applies noscript. | `<div class="noscript"></div>`

### Examples

#### Example 1

The following example shows an alert ont the top of the page when JavaScript is disabled.

```html
<noscript>
  <div class="noscript">Please enable JavaScript in your browser!</div>
</noscript>
```
