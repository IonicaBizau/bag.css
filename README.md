
[![bag.css](http://i.imgur.com/3m0NMdB.png)](http://ionicabizau.github.io/bag.css/example/)

# bag.css

 [![Patreon](https://img.shields.io/badge/Support%20me%20on-Patreon-%23e6461a.svg)][patreon] [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![AMA](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/bag.css.svg)](https://www.npmjs.com/package/bag.css) [![Downloads](https://img.shields.io/npm/dt/bag.css.svg)](https://www.npmjs.com/package/bag.css) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> The minimal library for fixed and fluid CSS containers.


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
   I am a fixed container.
</div>
```
## Grid system?

The scope of the library is just to provide the easy way to
build fixed and fluid responsive containers. If you need to
split the rows in columns, you can use
[Gridly](https://github.com/IonicaBizau/gridly).


[![bag.css](http://i.imgur.com/mA8cdGx.png)](http://ionicabizau.github.io/bag.css/example/)

## :memo: Documentation


The `bag.all.css` file handles the semantic classes:


 - `bag`: that means the element should be a container (fluid or fixed)
 - `fixed`: together with `bag`, this will create a fixed container (e.g. `<div class="fixed bag").
 - `fluid`: together with `bag`, this will create a fluid container (e.g. `<div class="fluid bag").


If you only need fixed (fluid) containers on your page, you will probably want to load just `bag.fixed.css` (`bag.fluid.css`).


Depending on the window width, the fixed container will have the following widths:


 - **1170px**, min-width: 1200px
 - **970px**, min-width: 992px
 - **750px**, min-width: 768px
 - **100%**, less than 768px


## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :moneybag: Donations

Another way to support the development of my open-source modules is
to [set up a recurring donation, via Patreon][patreon]. :rocket:

[PayPal donations][paypal-donations] are appreciated too! Each dollar helps.

Thanks! :heart:


Run `npm i` to install the dependencies. Then, you can run the npm scripts using `npm run <script-name>`.


Run `npm run release` to recreate all the `dist` files.



## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[patreon]: https://www.patreon.com/ionicabizau
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
