This repository contains my [Alfred](http://alfredapp.com/) extensions and others' Alfred extensions that I've customized to my taste.

# INSTALLATION

After ensuring that you have Alfred installed, just download the extension and double click.

# AVAILABLE SCRIPTS

## Share with Dropbox and goo.gl URL shorterner

+ This places your file in your Dropbox Public folder and shortens the final url with goo.gl.
+ Make sure you key in your correct Dropbox ID
+ I've chosen goo.gl because adding a ".info" at the end of the URL gives you nice tracking stats
+ There's a nice fallback that just spits out your default url if goo.gl fails for some strange reason.

## Magic Mouse Fix Acceleration

* Quick script that kill mouse acceleration and sets sensitivity to acceptable limits
* makes your Magic Mouse behave more like Windows
* see [my blog post](http://journal.kaush.co/475/run-kill-mouse-acceleration-on-login-with-keyboard-maestro) for more details.

## Get Front most Chrome tab's url in markdown format

Sublime Text is my primary editor of choice for markdown. [Brett Terpstra has these amazing set of useful services](http://brettterpstra.com/projects/markdown-service-tools/)  that allow one to quickly insert the urls from your frontmost tab to an application. Sublime Text for some reason simply doesn't understand this service when installed correctly. It was taking too much time, so i figured i'd port that to an Alfred extension that sort of circumvents platform problems.

It's a simple ruby script that echoes the urls in markdown format to the frontmost application.

All credit for this goes to the amazing [Brett Terpstra](http://brettterpstra.com/projects/markdown-service-tools/).
