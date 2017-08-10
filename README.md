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
* UC Browser (Mini or HD version for Android & normal version for PC);
* FireFox 2 minimum;
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
Note. The default template is white and blue. For customization, [see this sample here](https://github.com/cara-tm/modal_box/blob/master/css/custom.css)


## IE 8 and below support

Full support in IE9. If you need previous browsers compatibility, you can add this little script into your page:

    <script>
    /*! Alternative to :target selector (unique ID #open-modal) for
    IE8 and below; can be removed safely if you don't need it.
    */
    if(document.all&&!document.addEventListener){var el=document.getElementById('b-active'),target=document.getElementById('open-modal');el.attachEvent('click',function(){toggle(target,'visible')})}function toggle(a,b){var d=a.className.match(/\S+/g)||[],f=d.indexOf(b);0<=f?d.splice(f,1):d.push(b),a.className=d.join(' ')};
    </script>

## Note

CSS rules has been verified troughout the online "Validate your CSS for different browsers" (features providing by Caniuse): [https://www.browseemall.com/Compatibility/ValidateCSS](https://www.browseemall.com/Compatibility/ValidateCSS
)

## Screen shots

Google Chromium (latest) PC preview:
![Google Chromium PC](https://github.com/cara-tm/modal_box/raw/master/google-chromium.png "Google Chromium PC")

.

Safari Mobile preview: 
![Safari MObile](https://github.com/cara-tm/modal_box/raw/master/safari-mobile.PNG "Safari Mobile")

.

Opera Mini 7.5 Android preview (Note. Scrolling is activated along the page document): 
![Opera Mini 7.5 Android](https://github.com/cara-tm/modal_box/raw/master/opera-mini-7.5-android.png "Opera Mini 7.5 Android")

.

Internet Explorer 7 preview: 
![Internet Explorer 7](https://github.com/cara-tm/modal_box/raw/master/ie7.png "Internet Explorer 7")
 
