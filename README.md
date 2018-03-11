BigPicture Editor
=============

BigPicture Editor is a notepad, in which you can pan and zoom infinitely many times.

This desktop application is based on [bigpicture.js](http://github.com/josephernest/bigpicture.js/).

![](http://gget.it/kfh4pqh2/bigpicture-editor.jpg)

Ready-to-use package
----

Here you can get Windows package : [BigPictureEditor_1.00.zip](http://bigpictu.re/files/bigpictureeditor_1.00.zip)

How to build
----

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) installed on your computer. From your command line:

```
# Clone this repository
git clone https://github.com/josephernest/bigpicture-editor && cd bigpicture-editor

# Install dependencies and run the app
npm install && npm start

# Package as a standalone executable file
# (This requires to install electron-packager first)
npm install electron-packager -g
electron-packager . --platform=win32 --arch=ia32 --icon=bigpicture.ico
```


About
----

Author : Joseph Ernest ([@JosephErnest](http:/twitter.com/JosephErnest))

License
----
MIT license
