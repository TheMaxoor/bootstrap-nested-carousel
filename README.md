# bootstrap-nested-carousel
A fork from Bootstrap Carousel module to allow nested carousels


## Warning
This package has not been heavily tested.  
Feel free to open an issue if you experience something weird.  

Please also note that the main js file is written using ES6 features. You may have to use a Javascript compiler to use it in your project.
A build version will be generated later.

## Install

You can get it via NPM :

```
npm i bootstrap-nested-carousel
```

or yarn

```
yarn add bootstrap-nested-carousel
```


## Getting Started
You just need to [include Bootstrap modules individualy](https://getbootstrap.com/docs/4.1/getting-started/webpack/#importing-javascript) and import **bootstrap-nested-carousel**'s `carousel.js` instead of Bootstrap's one.

```javascript
import 'bootstrap/js/dist/util'; // required
import 'bootstrap-nested-carousel';
...
```

You can use this module like you would use the default Bootstrap 4.1 Carousel ([Official documentation](https://getbootstrap.com/docs/4.1/components/carousel/)). 


