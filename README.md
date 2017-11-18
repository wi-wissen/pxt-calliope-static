# Static MakeCode Editor (PXT) for Calliope mini

PXT as a static web page. You can download and run in a local web server.

> ~~This is an interesting alternative for single-user offline use of the editor.~~
> Be aware that you need for your first start an internet connection. This is for compiling the first hex file on a Microsoft server.

## Online

**[pxt-calliope-static.wi-wissen.de](http://pxt-calliope-static.wi-wissen.de/)** shows the gh-pages branch.

## Local

Clone the repository.
```
git clone https://github.com/wi-wissen/pxt-calliope-static
```
Install a simple web server and run it.
```
npm install -g http-server
http-server -c-1 pxt-calliope-static/release
```
Open Editor: [`http://127.0.0.1:8080`](http://127.0.0.1:8080).

## Changes to [calliope-mini/pxt-calliope-static](https://github.com/calliope-mini/pxt-calliope-static)

* reset button works now as start/stop button
* removed tracking
* removed unused (and incomplete?) docs
* added compiled hex for futher use
* changed branding
* included google fonts
* added help menu
* added help for usb
* replaced toc and privacy documents

## ToDos

* [ ] get offline mode working
* [ ] get excercises/tutorials inside editor working. ([see here](https://makecode.com/writing-docs/tutorials))


