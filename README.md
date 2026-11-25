# modular-ui-kit-styles

[![NPM Version](https://img.shields.io/npm/v/modular-ui-kit-styles?color=42b883)](https://www.npmjs.com/package/modular-ui-kit-styles)
[![NPM Downloads](https://img.shields.io/npm/dm/modular-ui-kit-styles?color=35495e)](https://www.npmjs.com/package/modular-ui-kit-styles)
[![GitHub Clones](https://img.shields.io/badge/dynamic/json?color=success&label=Clone&query=count&url=https://gist.githubusercontent.com/eugenia-vitinschii/9c1adedb1baae76cd55970fd012afba7/raw/clone.json&logo=github)](https://github.com/MShawon/github-clone-count-badge)


A shared styles package for two npm libraries: **modular-ui-kit-vue** and **modular-ui-kit-react**.

This repository provides ready-to-use design tokens and CSS classes that can also be used independently in other projects. It helps maintain a consistent visual style and easily customize the look and feel of your application. If you need to build a project quickly, you can pair this package with our Vue or React component libraries.

## File Structure & Architecture

All files are clearly organized into folders to make future scaling straightforward and help you quickly locate the styles you need.

* **Reset Styles**
  The foundational layer of the package. Pay attention to these styles from the start to prevent style conflicts when customizing or extending your project.

* **Tokens & Variables**
  Core design tokens and variables defining fundamental values such as colors, font sizes, and spacing.

* **Mixins**
  Reusable mixins built on top of design tokens to speed up development and simplify modifying the appearance of the site and its elements.

* **Page Layout**
  A classic page layout structure featuring a `wrapper`, a `container` to constrain content width across screen sizes, and standard structural blocks (`header`, `content`, and `footer`).

* **Typography**
  Pre-built text classes designed to keep typography responsive and clean across all devices.

* **Helpers**
  Additional utility classes for animations, page layout adjustments, and icons.

* **Components**
  Since this package serves primarily as the styling foundation for the Vue and React libraries, it currently styles over 20 UI components with more to be added in future updates.
