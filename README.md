# &lt;x-dribbble&gt;

A [Polymer](http://polymer-project.org) element for querying results from the [Dribbble API](https://dribbble.com/api)

> Inspired by <a href="https://github.com/addyosmani/x-instagram/" target="_blank">Addy Osmani's x-instagram</a> and <a href="https://github.com/tamaspiros/x-flickr/" target="_blank">Tamas Piros's x-flickr</a>. Maintained by [Dano Alexander](https://github.com/altruity).


## Demo

[Check it live!](http://altruity.github.io/x-dribbble/)


## Install

Using [Bower](http://bower.io), run:

```bash
$ bower install --save x-dribbble
```


## Usage

1. Install the component using [Bower](http://bower.io/):

    ```sh
    $ bower install x-dribbble --save
    ```

2. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

3. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/x-dribbble/dist/x-dribbble.html">
    ```

4. Start using it!

    ```html
    <x-dribbble></x-dribbble>
    ```


## Options

NOTE: Currently no API key/authentication required with Dribbble's API (_as of Apr 20, 2014_)

Attribute      | Options         | Default          | Description
---            | ---             | ---              | ---
`list`         | *string*        | ``               | The category to query for (e.g 'popular')
`count`        | *integer*       | `10`             | The max number of results to return
`shotsPerRow`  | *integer*       | `5`              | The number of shots that will show up on a row


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## History

For detailed changelog, check [Releases](https://github.com/webcomponents/x-dribbble/releases).


## License

[MIT License](http://opensource.org/licenses/MIT)
