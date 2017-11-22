# Choate Modal

[![Build Status](https://travis-ci.org/stephan281094/modal.svg)](https://travis-ci.org/stephan281094/modal)

> A simple dependency-free JavaScript modal, used on the choate.edu marketing site.

## Demo

![Demo Image](https://raw.githubusercontent.com/DrianHillman/choate-modal/master/example/choate-modal-demo-720_30.gif)

## How to implement
* Include `modal.css` and `modal.min.js`
* Create a wrapper node with a class: `.modal-wrapper`
* Add modals containing `data-modal="somename"` inside the wrapper
* Open the modal by clicking any `data-modaltrigger="somename"`
* Or simply call the open function: `modal.open('awesome')`

## Developing
* `npm i`
* Run `npm run dev` to run webpack and watch for changes
* Code in `/src`, but use the compiled `/dist/modal.min.js` as your final production file

## License
Originally developed by [Stephan](https://github.com/stephan281094) and released under [MIT](LICENSE).
