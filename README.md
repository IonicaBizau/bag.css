<!-- Please do not edit this file. Edit the `blah` field in the `package.json` instead. If in doubt, open an issue. -->








[![bag.css](http://i.imgur.com/3m0NMdB.png)](http://ionicabizau.github.io/bag.css/example/)











# bag.css

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Ask me anything](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/bag.css.svg)](https://www.npmjs.com/package/bag.css) [![Downloads](https://img.shields.io/npm/dt/bag.css.svg)](https://www.npmjs.com/package/bag.css) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

<a href="https://www.buymeacoffee.com/H96WwChMy" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png" alt="Buy Me A Coffee"></a>







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


























## :question: Get Help

There are few ways to get help:



 1. Please [post questions on Stack Overflow](https://stackoverflow.com/questions/ask). You can open issues with questions, as long you add a link to your Stack Overflow question.
 2. For bug reports and feature requests, open issues. :bug:
 3. For direct and quick help, you can [use Codementor](https://www.codementor.io/johnnyb). :rocket:





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
I open-source almost everything I can, and I try to reply to everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:


 - Starring and sharing the projects you like :rocket:
 - [![Buy me a book][badge_amazon]][amazon]—I love books! I will remember you after years if you buy me one. :grin: :book:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)


Thanks! :heart:





Run `npm i` to install the dependencies. Then, you can run the npm scripts using `npm run <script-name>`.


Run `npm run release` to recreate all the `dist` files.






















## :scroll: License

[MIT][license] © [Ionică Bizău][website]






[license]: /LICENSE
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
[badge_patreon]: https://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: https://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: https://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: https://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
