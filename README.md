# ionic-2-dropbox-api
Ionic and dropbox integration.
To get dropbox app key go to https://www.dropbox.com/developers/apps.
Add Dropbox provider by executing this command: ionic g provider Dropbox
Add redirect url of your app in dropbox app you created earlier.

Dropbox login is done using ionic native webview.
Add plugin for webview ionic plugin add cordova-plugin-inappbrowser.


Dropbox login wont work in web.. So build the app for your specific platform and then run it.
