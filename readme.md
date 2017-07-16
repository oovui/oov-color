# a color scheme based sass/scss for oovui ui library


the colors default theme is mainly based [ant.design](https://ant.design/docs/spec/colors#Color-application);

the colors scss model is mainly modified the [open-color](https://github.com/yeun/open-color);


# Install
```js
npm install oov-color --save

```

# Usage

Import the file to your project and use the variables and class.

Just for SCSS

```scss
// path: the install directory of oov-color
@import 'path/oov-color';   

body{
  background-color:$oov-c-green-6;
  color:$oov-c-gray-6;
}

```
### Or use oov-color with webpack  (Recommend)

```scss
// https://www.npmjs.com/package/sass-loader
@import '~oov-color';   

body{
  background-color:$oov-c-green-6;
  color:$oov-c-gray-6;
}

```