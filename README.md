[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/@f0rce/lit-ace)

# lit-ace #

Even <strong>more</strong> embeddable and lightweight code 
editor Custom Element - just one tag, and no JS 
needed to provide [Ace](http://ace.c9.io/) - The High Performance Code Editor

## Usage example

<!---
```
<custom-element-demo>
  <template>
    <script src="./@webcomponents/webcomponentsjs/webcomponents-loader.js"></script>
    <script src="../../@webcomponents/webcomponentsjs/webcomponents-loader.js"></script>
    <script type="module" src="../../@f0rce/lit-ace/lit-ace.js"></script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
  <lit-ace theme="terminal" mode="javascript" value="console.log('Have a great day :)')">
  </lit-ace>
```


## Install

Install the component using [npm](https://www.npmjs.com/):

```sh
$ npm i @f0rce/lit-ace --save
```

Once installed, import it in your application:

```js
import "@f0rce/lit-ace/lit-ace.js";
```


## License

[MIT License](http://opensource.org/licenses/MIT)
