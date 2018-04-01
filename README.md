# encore

## Steps
==> npm install -g @angular/cli

==> ng new encore

==> npm install electron --save-dev

==> 
Add 
~~~
  "main": "main.js",
~~
  to package.json below license entry

Add
~~
    "electron": "ng build && electron .",
    "electron-aot": "ng build --prod && electron ."

~~
to package.json under scripts

## For dev
==> npm run electron

==> npm install ngx-electron --save

==> npm install -g ionic cordova

==> ionic build

==> ionic serve

== > 

# Links

https://electronjs.org/docs/tutorial/first-app

https://github.com/crisbeto/angular-svg-round-progressbar

https://github.com/ThorstenHans/ngx-electron

https://robferguson.org/blog/2017/11/09/build-a-desktop-application-with-ionic-3-and-electron/