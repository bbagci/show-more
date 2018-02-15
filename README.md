# show-more

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/bbagci/show-more)

`<show-more>` is a custom element that shortens text to a "show more" link and fold outs by a click.

## Installation

```bash
bower install --save bbagci/show-more
```

```html
<link rel="import" href="/bower_components/show-more/show-more.html">
```

## Usage

Example 1 (just fold outs):

<!---
```
<custom-element-demo height="140">
    <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="show-more.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

```html
<p>Lorem ipsum <show-more>dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</show-more></p>
```

Example 2 (with run effect and prefix):

<!---
```
<custom-element-demo height="140">
    <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="show-more.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

```html
<p>Lorem ipsum <show-more milliseconds="1" prefix="&hellip; ">dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</show-more></p>
```

## HTML Attributes

Attribute | Value | Description
--- | --- | ---
milliseconds | number | Specifies the delay time between every character. Default value is 0
prefix | text | Specifies a prefix text that isn't a part of the link. Default text is ""

## CSS Properties

Property | Value | Description
--- | --- | ---
--show-more-color | HEX/RGB/... | Specifies the color of the "show more" link. Default value is #007bff

## License

MIT