[![Build status](https://travis-ci.org/PolymerElements/iron-flex-layout.svg?branch=master)](https://travis-ci.org/PolymerElements/iron-flex-layout)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/PolymerElements/iron-flex-layout)

## &lt;iron-flex-layout&gt;

The `<iron-flex-layout>` component provides simple ways to use
[CSS flexible box layout](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Flexible_boxes),
also known as flexbox. This component provides two different ways to use flexbox:

1. [Layout classes](https://github.com/PolymerElements/iron-flex-layout/tree/master/iron-flex-layout-classes.html).
The layout class stylesheet provides a simple set of class-based flexbox rules, that
let you specify layout properties directly in markup. You must include this file
in every element that needs to use them.

Sample use:

   <link rel="import" href="../iron-flex-layout/iron-flex-layout-classes.html">

   <custom-style>
     <style is="custom-style" include="iron-flex iron-flex-alignment"></style>
   </custom-style>

   <div class="layout horizontal layout-start">
     <div>cross axis start alignment</div>
   </div>

1. [Custom CSS mixins](https://github.com/PolymerElements/iron-flex-layout/blob/master/iron-flex-layout.html).
The mixin stylesheet includes custom CSS mixins that can be applied inside a CSS rule using the `@apply` function.

A complete [guide](https://elements.polymer-project.org/guides/flex-layout) to `<iron-flex-layout>` is available.

## Changes in 2.0
- removed the deprecated `/deep/` classes -- files removed: `classes/iron-flex-layout.html`, `classes/iron-shadow-flex-layout` 

