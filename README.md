[![bag.css](http://i.imgur.com/3m0NMdB.png)](http://ionicabizau.github.io/bag.css/example/)

# bag.css [![Support this project][donate-now]][paypal-donations]

The minimal library for fixed and fluid CSS containers.

You don't ndeed monolithic CSS frameworks for simple CSS containers (fluid/fixed). **bag.css** does the job and it weights ~150 bytes. :dizzy:

## Usage

In the [`dist`](/dist) directory there are three minified files:

 - `bag.fixed.css` (151 B): the fixed container
 - `bag.fluid.css` (100 B): the fluid container
 - `bag.all.css` (164 B): the previous two files' content put together

## Example

Include the CSS file in your page:

```html
<link rel="stylesheet" href="bag.all.css" type="text/css" charset="utf-8">
```

Then you can use the `.bag` and `.fluid`/`.fixed` classes:

```html
<div class="fluid bag">
   I am a fluid container.
</div>
<div class="fixed bag">
   I am a fluid container.
</div>
```
## Grid system?

The scope of the library is just to provide the easy way to
build fixed and fluid responsive containers. If you need to
split the rows in columns, you can use
[Gridly](https://github.com/IonicaBizau/gridly)

[![bag.css](http://i.imgur.com/mA8cdGx.png)](http://ionicabizau.github.io/bag.css/example/)

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

Run `npm i` to install the dependencies. Then, you can run the npm scripts using `npm run <script-name>`.

Run `npm run release` to recreate all the `dist` files.

## License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md