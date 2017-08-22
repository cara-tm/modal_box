# CSS Modal Box

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

## Usage

First, you need to encapsulate your entire content page into a div with a class name `wrapper`.
Then, place the Modal Box template outside this `wrapper` block.
Simple!
Note. The default template is white and blue. For customization, [see this sample here](https://github.com/cara-tm/modal_box/blob/master/css/template.css)

## This content package (v1.2 onward)

This minimal default component (required) is distributed in white/blue colors (see screen shots) and do not include the styles for inner optional elements within the modal header ([File: `modal-box.min.css`](https://github.com/cara-tm/modal_box/blob/master/css/modal-box.min.css).

In order to add these additional supports, please include the optional styles [File: `custom.css`](https://github.com/cara-tm/modal_box/blob/master/css/custom.css).

A red colored example, well commented, is available for your customization convenience [File: `template.css` previously, file: `custom.css`](https://github.com/cara-tm/modal_box/blob/master/css/template.css).
.

An independant `demo.html` file with full styles is available for integration example [File: `demo.html`](https://github.com/cara-tm/modal_box/blob/master/demo.html).

## Custom template sample

Remove all the code between `<style>` and `</style>` from the `demo.html` page, then add before the final `</head>` tag:

    <link rel="stylesheet" href="css/modal-box.min.css" media="screen">
    <link rel="stylesheet" href="css/custom.min.css" media="screen">
    <link rel="stylesheet" href="css/template.css" media="screen">

![Template sample](https://github.com/cara-tm/modal_box/raw/master/template.png "The sample Template result")

## IE 8 and below support

Full support in IE9. If you need previous browsers compatibility, you can add this little script into your page:

    <script>
    /*! Alternative to :target selector (unique ID #open-modal) for
    IE8 and below; can be removed safely if you don't need it.
    */
    'use strict';var addEvent=function(a,b,d){try{a.addEventListener(b,d,!1)}catch(e){a.attachEvent('on'+b,d)}},el=document.getElementById('b-active'),target=document.getElementById('open-modal'),c=document.getElementById('close-modal');addEvent(el,'click',function(){hasClass(target,'visible')?removeClass(target,'visible'):target.className+=' visible'}),addEvent(c,'click',function(){document.getElementById('open-modal').className='modal-dialog dialog'});function hasClass(a,b){if('undefined'!=typeof b)return-1<(' '+a.className+' ').indexOf(' '+b+' ')}function removeClass(a,b){return a.className=a.className.replace(new RegExp('(?:^|s)'+b+'(?!S)'),'')}
    </script>

Note. This component template is a cross browsers visual solution, not a javascript case study for all browsers. Use your personnal scripting code depending of your needs. This poor javascript solution also affects a little bit the included CSS animation.

## Note

CSS rules has been verified troughout the online "Validate your CSS for different browsers" (features providing by Caniuse): [https://www.browseemall.com/Compatibility/ValidateCSS](https://www.browseemall.com/Compatibility/ValidateCSS
)

## Screen shots

Google Chromium (latest) PC preview:
![Google Chromium PC](https://github.com/cara-tm/modal_box/raw/master/google-chromium.png "Google Chromium PC")

.


.

See the 'png' images for all the different browsers.
