# Argon Vue Webpack
<div align="center">

![with-vue](https://img.shields.io/badge/made%20with-vue.js-green.svg?longCache=true&style=for-the-badge&logo=vue.js)
![with-webpack](https://img.shields.io/badge/made%20with-webpack-blue.svg?longCache=true&style=for-the-badge&logo=webpack)

</div>

Based on [webpack template](https://github.com/vuejs-templates/webpack) and [Argon](https://github.com/creativetimofficial/vue-argon-design-system) from [Creative Tim](https://creative-tim.com)

By [OsirisFrik](https://github.com/OsirisFrik)

![aegon](https://s3.amazonaws.com/creativetim_bucket/products/92/original/opt_argon_vue_thumbnail.jpg?1534236902)

## Documentation
* [Webpack](http://vuejs-templates.github.io/webpack)
* [Argon](https://demos.creative-tim.com/argon-design-system)

## Usage
This is a project template for vue-cli.
```bash
$ npm install -g @vue/cli
$ npm install -g @vue/cli-init
$ vue init OsirisFrik/argon-vue-webpack
$ cd my-project
$ npm install
$ npm run dev
```

## Argon Structure
```
|-- vue-argon-design-system
    |-- App.vue
    |-- main.js
    |-- router.js
    |-- assets
    |   |-- scss
    |   |   |-- argon.scss
    |   |   |-- bootstrap
    |   |   |-- custom
    |   |-- vendor
    |       |-- font-awesome
    |       |-- nucleo
    |-- components
    |   |-- Badge.vue
    |   |-- BaseButton.vue
    |   |-- BaseCheckbox.vue
    |   |-- BaseInput.vue
    |   |-- BaseNav.vue
    |   |-- BaseRadio.vue
    |   |-- BaseSlider.vue
    |   |-- BaseSwitch.vue
    |   |-- Card.vue
    |   |-- CloseButton.vue
    |   |-- Icon.vue
    |   |-- NavbarToggleButton.vue
    |-- layout
    |   |-- AppFooter.vue
    |   |-- AppHeader.vue
    |-- plugins
    |   |-- argon-kit.js
    |   |-- globalComponents.js
    |   |-- globalDirectives.js
    |-- views
        |-- Components.vue
        |-- Landing.vue
        |-- Login.vue
        |-- Profile.vue
        |-- Register.vue
        |-- components
            |-- BasicElements.vue
            |-- Carousel.vue
            |-- CustomControls.vue
            |-- DownloadSection.vue
            |-- Examples.vue
            |-- Hero.vue
            |-- Icons.vue
            |-- Inputs.vue
            |-- JavascriptComponents.vue
            |-- Navigation.vue
```

### template structure
```
|-- my-project
    |-- build
    |-- config
    |-- dist
    |-- src
        |-- TEMPLATE
    |-- static
        |-- img #Put here imgs files for vue-lazyload work
etc...
```