# program.house/site

program.house is a fun and free online platform for learning web development and sharing with others.

* Learn quickly with documentation and tutorials built directly into the editor
* Share your creations with a community of other learners
* See what others are creating

This repository contains the program.house site sourcecode. **Note: it's currently not live, or anywhere near completion!**

### Installation
If you are interested in running a local copy of program.house, you'll need at least [Node.js 6](https://nodejs.org/en/download/current/).

```sh
$ git clone https://github.com/programdothouse/site program.house-site --recursive-submodules
$ cd program.house-site

$ npm install
```

You also need to compile assets with
```sh
$ npm run build
```

Finally, the server can be started using
```sh
$ npm start
```
You may then visit [localhost:7070](http://localhost:7070/).

### Development
During development, you will need to build assets every time you change them. There is a helper script for automatically building assets whenever they are changed:
```sh
$ npm run watch
```

---

Pull requests are greatly appreciated, and feel free to leave/comment on issues on the [issue tracker](https://github.com/programdothouse/site/issues), or, if they relate to the program.house project editor, on [the editor issue tracker](https://github.com/programdothouse/editor/issues).
