# qr-clock
a simple html page that displays a qrcode with your devices current time encoded within it, updating every minute.
note that this every minute is linked to the codes runtime and not the actual time.

there are 2 versions.

qrclock-o.html requires an internet connection to run as it calls this 
"https://cdn.rawgit.com/davidshimjs/qrcodejs/gh-pages/qrcode.min.js" script to generate the qrcode.

qrclock-l.html is suposed to be able to run locally by modifying line 5 to where ever you may have a local copy of 
"https://cdn.rawgit.com/davidshimjs/qrcodejs/gh-pages/qrcode.min.js" but I simply cannot get it to work on android 
(it should be fine on a personal computer).
