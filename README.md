# &lt;flash-embed&gt;

> A [VanillaJS](http://vanilla-js.com/) Web Component for Flash Embeds.
> 
> Why? I don't know.

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="elements/flash-embed.html">
    ```

3. Start using it!

    ```html
    <flash-embed></flash-embed>
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`src`      | *string*                  | `none`             | URL of .swf file
`width`      | *number*                  | `none`             | Width of embed
`height`      | *number*                  | `none`             | Height of embed
