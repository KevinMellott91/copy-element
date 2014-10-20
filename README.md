# &lt;copy-element&gt;

> A copyright element using [VanillaJS](http://vanilla-js.com/).

## Demo

[Check it live!](http://kevinmellott91.github.io/copy-element.html)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install copy-element --save
```

Or [download as ZIP](https://github.com/kevinmellott91/copy-element/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/copy-element/src/copy-element.html">
    ```

3. Start using it!

    ```html
    <copy-element start-year="2007">My Awesome Company</copy-element>
    <copy-element>My Awesome Company</copy-element>
    ```

## Options

Attribute     | Options     | Default         | Description
---           | ---         | ---             | ---
`start-year`  | *int*       | `undefined`     | (Optional) If provided, then the year in which the copyright took effect will be included in the copyright statement.

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/kevinmellott91/copy-element/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
