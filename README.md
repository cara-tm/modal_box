# CSS Modal Box

![Browsers](https://badges.herokuapp.com/browsers?firefox=1.0.8,60&googlechrome=1,67&iexplore=6,7,8,9,10,11&microsoftedge=13,42&opera=9.64,53&safari=5.17,11&android=7,2.3.6 "Browser support")
![Licence](https://camo.githubusercontent.com/9c0dc59d81d725b3904bda6613e541fa30cb2c8a/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f6c2f796574742e737667 "MIT")

Pure CSS Modal Box, "responsive" with a pretty good browsers support: IE6 minimum! ([See this demo here](https://codepen.io/cara-tm/full/ayzXPJ/))

Prevents other CSS rules conflicts; animation with Hardware-Accelerated features; fully responsive with width and height support within all screen sizes.

This component template has been tested successfully in (real systems not from emulators):

* Internet Explorer 6 (see below);
* Internet Explorer 7 (see below);
* Internet Explorer 8 (even in regressive 'Compatibility View'; see below);
* Internet Explorer 9;
* Internet Explorer 10;
* Internet Explorer 11;
* Microsoft Edge (all versions);
* Internet Explorer (Microsoft Windows Phone 7.5 system);
* Safari 5.x;
* Safari Mobile;
* Opera 9.64 PC;
* Opera 11 Linux;
* Opera Mini (Microsoft Windows Phone 7.5 system);
* Internet Explorer Mobile (Microsoft Windows Phone 8.x system);
* Opera Mini for android, version 7.5.x;
* Opera Mini android (latest version);
* Opera Mini 14 for iOS;
* UC Browser (Mini or HD version for Android & normal version for PC);
* UC Browser 10.x for iOS;
* default browser in Android 2.3.6 (TO DO: font sizes need adaptation);
* FireFox 1.0.8 minimum;
* FireFox 52 ESR;
* Midori 0.4;
* Google Chromium (all versions: PC & Mac; iOS & Android);
* Brave;
* Vivaldi;
* Camino 2.1 Mac;
* Shiira Mac;
* OmniWeb 5 Mac.

Here is a new version with the use of Flexbox & CSS Grid Layout for hipsters and nerds keeping a pretty good support within old browsers: IE6 minimum capable. Please note these new CSS features in this web design sample do not act any kind of noticed advantages.  [Online latest demo](http://sandbox.cara-tm.com/clients/cara/demo.html)

## Usage

First, you need to encapsulate your entire content page into a div with a class name `wrapper`.
Then, place the Modal Box template outside this `wrapper` block.
Simple!
Note. The default template is white and blue. For customization, [see this sample here](https://github.com/cara-tm/modal_box/blob/master/css/template.css)

## This content package (v1.2 onward)

This minimal default component (required) is distributed in white/blue colors (see screen shots) and do not include the styles for inner optional elements within the modal header ([File: `modal-box.min.css`](https://github.com/cara-tm/modal_box/blob/master/css/modal-box.min.css)).

In order to add these additional supports, please include the optional styles ([File: `custom.css`](https://github.com/cara-tm/modal_box/blob/master/css/custom.css)).

A red colored example, well commented, is available for your customization convenience ([File: `template.css` previously, file: `custom.css`](https://github.com/cara-tm/modal_box/blob/master/css/template.css)).
.

An independant `demo.html` file with full styles is available for integration example ([File: `demo.html`](https://github.com/cara-tm/modal_box/blob/master/demo.html)).

### Helpers for customization

This package is distributed with some class helpers:

* `tiny`: to create small width Modal Boxes (max-width: 20em) useful for login.
* `push__left`: to place the close button, or the entire Modal Box to the left;
* `push__right`: to place the entire Modal Box on the right;
* `footer-push__left`: to float the footer's links on the left;
* `footer-push__center`: to place the footer's links on the center;
* `footer__reverse`: to reverse the order of the footer's links;
* `footer-push__block`: to display all the footer's links empiled without the scroll bar (the footer adapts it's height accordingly);

See the templates for how tos integration.

## Custom template sample

Remove all the code between `<style>` and `</style>` from the `demo.html` page, then add before the final `</head>` tag:

    <link rel="stylesheet" href="css/modal-box.min.css" media="screen">
	<!-- Facultative: for optional elements -->
    <link rel="stylesheet" href="css/custom.min.css" media="screen">
	<!-- Sample custom colors styling (overwrite default) -->
    <link rel="stylesheet" href="css/template.css" media="screen">

![Template sample](https://github.com/cara-tm/modal_box/raw/master/template.png "The sample Template result").

## Custom template FLATERIAL (v1.4 onward)

Remove all the code between `<style>` and `</style>` from the `demo.html` page, then add before the final `</head>` tag (or see the `flaterial.html` file):

    <link rel="stylesheet" href="css/modal-box.min.css" media="screen">
	<!-- Facultative: for optional elements -->
    <link rel="stylesheet" href="css/custom.min.css" media="screen">
	<!-- Sample custom colors styling (overwrite default) -->
    <link rel="stylesheet" href="css/flaterial.css" media="screen">

![FLATERIAL template sample](https://github.com/cara-tm/modal_box/raw/master/flaterial-template.png "The FLATERIAL template result").

## Custom template for messaging (v1.5 onward)

See the file `message-box.html` for details:

![FLATERIAL template sample](https://github.com/cara-tm/modal_box/raw/master/messages-template.png "Messaging template result").

## Integration example

Here is an integration test within the default Textpattern template (v 4.7-dev) without any kind of conflicts even by putting the modal's styles at the beginning of the default.css file:

![TXP intégration sample](https://github.com/cara-tm/modal_box/raw/master/txp-integration.png "The sample Template result").


## Note

CSS rules has been verified troughout the online "Validate your CSS for different browsers" (features providing by Caniuse): [https://www.browseemall.com/Compatibility/ValidateCSS](https://www.browseemall.com/Compatibility/ValidateCSS
)

## Screen shots

See the 'png' images for all the different browsers.
