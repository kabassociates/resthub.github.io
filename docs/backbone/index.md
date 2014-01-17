---
layout: docs
title: Backbone.js Stack
permalink:  home/
prev: spring/tutorial
next: backbone/layout
---

<div class="toc"></div>

## Presentation

RESThub Backbone stack provides a client-side full stack and guidelines for building enterprise grade HTML5 applications. 
It could be used with any server backend: Ruby, PHP, NodeJS, JEE, Spring, Grails ...

In addition to the existing librairies included in the stack, it provides additional functionalities (mainly Backbone.js addons) 
designed to allow you to build a real enterprise grade application, and described in this documentation.

The Backbone.js 2.1.2 stack includes the following librairies:

* jQuery 1.9.1 ([documentation](http://docs.jquery.com/Main_Page))
* Backbone.js 1.0 ([documentation](http://documentcloud.github.com/backbone/)) and its [localstorage adapter]
  (http://documentcloud.github.com/backbone/docs/backbone-localstorage.html)
* Underscore.js 1.4.4 ([documentation](http://documentcloud.github.com/underscore/))
* Underscore.String 2.3.0 ([documentation](https://github.com/epeli/underscore.string#readme))
* Require.js 2.1.5 with [i18n](http://requirejs.org/docs/api.html#i18n) and [text](http://requirejs.org/docs/api.html#text) plugins
  ([documentation](http://requirejs.org/docs/api.html))
* Handlebars 1.0 ([documentation](http://handlebarsjs.com))
* A console shim + client logging to server mechanism
* Twitter Bootstrap 2.3 ([documentation](http://getbootstrap.com/2.3.2/)) and its JS plugins
* Form Validation: [Backbone Validation](http://github.com/thedersen/backbone.validation)
* Parameters support on view routing: [Backbone Query Parameters](http://github.com/jhudson8/backbone-query-parameters)
* Datagrid: [Backbone Datagrid](http://loicfrering.github.com/backbone.datagrid/)
* Paginated lists: [Backbone Paginator](http://addyosmani.github.com/backbone.paginator/)
* Asynchronous calls: [Async](http://github.com/caolan/async/)
* Dispatching keyboard shortcuts: [Keymaster](http://gobby/keymasterithub.com/madr)
* Get and set relations (one-to-one, one-to-many, many-to-one) for Backbone models: [Backbone Associations](http://dhruvaray.github.io/backbone-associations/)
* Parsing, validating, manipulating, and formatting dates: [Moment](http://momentjs.com/)

Before going deeper in the RESThub Backbone stack, you should read the great documentation
[Developing Backbone.js Applications](http://addyosmani.github.com/backbone-fundamentals/) by Addy Osmani,
it is a great introduction to pure Backbone.js.

## Versions & Changelogs

Backbone Stack current version is **2.1.2**.

You can find RESThub Backbone Stack release changelogs on our [Github repository](https://github.com/resthub/resthub-backbone-stack) :

* 2013-07-26: [RESThub Backbone.js stack 2.1.2 has been released](https://github.com/resthub/resthub-backbone-stack/blob/master/CHANGELOG.rst>)
* 2013-05-17: [RESThub Backbone.js stack 2.1.1 has been released](https://github.com/resthub/resthub-backbone-stack/blob/master/CHANGELOG.rst>)
* 2013-03-26: [RESThub Backbone.js stack 2.1.0 has been released](https://github.com/resthub/resthub-backbone-stack/blob/master/CHANGELOG.rst>)
* 2012-12-04: [RESThub Backbone.js stack 2.0.0 has been released](http://pullrequest.org/2012/12/04/resthub-2.html)!

## Bootstrap your project

There are 2 ways to use it in your project:

* If you are starting a new RESThub Spring + Backbone stack project, the better way to use it is to use one of the Backbone.js webappp
  Maven Archetypes described [here](/docs/spring/bootstrap)
* You can simply download [latest RESThub Backbone.js stack](https://github.com/resthub/resthub-backbone-stack/archive/master.zip),
  and extract it at the root of your webapp

The [Todo RESThub example](https://github.com/resthub/todo-backbone-example) project is the reference example project using this stack.

## Tutorial

You should follow RESThub Backbone Stack tutorial in order to learn step by step how to use it. Available with or without answers :
[here](/docs/backbone/tutorial)