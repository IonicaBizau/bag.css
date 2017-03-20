
[![bag.css](http://i.imgur.com/3m0NMdB.png)](http://ionicabizau.github.io/bag.css/example/)

# bag.css

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Version](https://img.shields.io/npm/v/bag.css.svg)](https://www.npmjs.com/package/bag.css) [![Downloads](https://img.shields.io/npm/dt/bag.css.svg)](https://www.npmjs.com/package/bag.css)

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


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:



Run `npm i` to install the dependencies. Then, you can run the npm scripts using `npm run <script-name>`.


Run `npm run release` to recreate all the `dist` files.



## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
