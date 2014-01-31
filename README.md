&lt;character-count&gt;
===============

A custom element using polymerJS for character count - Based on customelements.io

Web Component wrapper for [Twitter's button](https://twitter.com/about/resources/buttons#tweet) using Polymer.

## Usage

1. Import Web Components':

	```xml
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/polymer.js"></script>
	```

2. Import Custom Element:

	```xml
<link rel="import" href="src/character-count.html">
	```

3. Start using it!

	```xml
<character-count></character-count>
	```

## Options

Attribute | Options       | Default                    | Description
---       | ---           | ---                        | ---
`name`    | *string*      | `textarea-text`            | The name attribute of the textarea
`height`  | *int*         | `200`                       | The height of the texarea
`width`   | *int*         | `500`                      | The width of the textarea


© Sóstenes Gomes
