##jquery-seeThru demo pages

Build the demo pages using `assemble` (node.js and `grunt-cli` required):

```sh
$ npm install
$ grunt assemble
```

Make sure you are serving the demo pages via `http(s)://` as `file://` will throw cross domain exceptions when accessing the video data via canvas.