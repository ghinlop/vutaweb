<center>

[![Vutaweb.Vn](./dist/images/logo.png)](https://vutaweb.vn)

</center>

# VutaWeb Template
Template build by EJS Template Engine Frameword & Compiler by Gulp

## Verison 2.0.5
- Fixed Sticky menu for mobile screen
- Update CSS fixed bug sticky menu

*Before Fixed*
```html
<header class="header" uk-sticky="animation: uk-animation-slide-top; sel-target: .sologan; cls-active: header-fixed shadow; top: 20">
    <div class="uk-container">
        <div class="row align-items-center">
            <a href="/" class="col-md-3 col-10 logo py-2 text-md-left text-center">
                <img alt="" src="/dist/images/logo.png">
            </a>
            <div class="col-md-9 col-2 nodesk">
                <a class="d-md-none" uk-toggle="target: nav" uk-icon="icon: grid; ratio: 1.5"></a>
                <nav class="d-block" uk-offcanvas="mode: push; overlay: true">
<div class="uk-offcanvas-bar">
```

*After Fixed*
```html
<header class="header" uk-sticky="media: 769; animation: uk-animation-slide-top; sel-target: .sologan; cls-active: header-fixed shadow; top: 20">
    <div class="uk-container">
        <div class="row align-items-center">
            <div class="col-md-3 logo py-2 px-md-3 px-0">
                <div
                uk-sticky="
                top: 20; 
                animation: uk-animation-slide-top; 
                cls-active: bg-white;
                width-element: true">
                    <a href="/">
                        <img alt="" src="/dist/images/logo.png">
                    </a>
                    <a class="d-md-none uk-position-small uk-position-center-right" uk-toggle="target: nav" uk-icon="icon: grid; ratio: 1.5"></a>
                </div>
            </div>
            <div class="col-md-9 col-2 nodesk">
                <nav class="d-block" uk-offcanvas="mode: push; overlay: true">
                    <div class="uk-offcanvas-bar">
```

## Verison 2.0.4
- Fix class flex-md-1 min-width: 769px
- Fix Menu reponsize in Mobile, Tablet, Desktop
- Fix z-index in Mobile

## Verison 2.0.3
- Fix z-index Navbar off-canvas for screen min-width: 768px
- Unset effect ::before and ::after for "a" tag for screen min-width: 768px
- Update main.css, main.scss 

## Verison 2.0.2
- Fix break Navbar for screen width 960px
- Fix close button modal dont work
- Change class .container -> .uk-container
- change font-size for Nodal title
- Update main.css, main.scss, inc/_global.scss, inc/_mixin.scss

## Verison 2.0.1
- Change Cover Index
    - Call Modal Step
    - Change CSS with new class **.custom-input-form-right**

## Verison 2.0.0
### Changelog
- Add & Update Vuta Framework - Vutaweb.css
    - **Bootstrap v4.1.1**
        - Css Import
        - ~~Bootstrap Javascript~~
    - **Font Awesome v4.7.0**
        - Css Import
    - **UIKit v3.0.0 rc6**
        - Css Import
        - UIKit Javascript Required
            - uikit.min.js
            - uikit-icons.min.js
- Index Page  --> *done*
- News Page --> *done*
- Detail Page --> *done*
- Price Page --> *done*
- Single Page --> *done*
- ~~Contact Page~~ --> *building*
