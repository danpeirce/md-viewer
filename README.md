# md-viewer

A HTML5 portable Markdown viewer.

md-viewer uses the Markdown.Converter class from [PageDown](https://code.google.com/p/pagedown/) to perform
Markdown to HTML conversion.

## Using md-viewer

On a PC store the markdown file in the same folder as 

* md-viewer.html
* md-viewer.css
* GitHubFlavor.css
* Markdown.Converter.js

To use md-viewer on Windows 11, simply open **md-viewer.html** in a browser (so far only tested in Chrome and Firefox on Windows11).
Don't know what platform the author used it on but the automatic reloading has not worked for me.

If stored on a ESP32 all the files except the markdown file should be in the same folder on the ESP32. The browse button on the md-viewer PC browser page
will allow one to load a markdown file from the PC.

I have used it both as a local file on windows 11 and served from a ESP32 WiFi webserver. 
See [https://github.com/danpeirce/ESP32_OTA_FILESYS](https://github.com/danpeirce/ESP32_OTA_FILESYS)

Styling is controlled by `md-viewer.css`. The default style imports **GitHubFlavor.css**, which was taken from
[https://github.com/ajmcmiddlin/md-viewer](https://github.com/ajmcmiddlin/md-viewer).

## License

md-viewer is available under the [MIT license](http://opensource.org/licenses/mit-license.php), the same as
PageDown/Mardown.Converter.
