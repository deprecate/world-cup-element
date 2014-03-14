# &lt;world-cup&gt;

Web Component to display World Cup winners

> Maintained by [Your Name](https://github.com/yourname).

## Demo

> [Check it live](http://zenorocha.github.io/world-cup-element).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/world-cup.html">
    ```

3. Start using it!

    ```html
    <world-cup year="2014"></world-cup>
    ```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`year`     | *string*                  | `1950`, `1954`, `1958`, `1962`, `1966`, `1970`, `1974`, `1978`, `1982`, `1986`, `1990`, `1994`, `1998`, `2002`, `2006`, `2010`, `2014`               | World Cup Edition

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m `Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/zenorocha/world-cup-element/releases).

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha