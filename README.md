# Angular 1.x

![](http://new.tinygrab.com/7020c0e8b075dac69e0da439ec6ad3a3f18bcf6a01.png)

## Intro

- SPA
 - Single Page Apps
   - ![](https://msdn.microsoft.com/dynimg/IC690875.png)
    - one-page app
    - similar to a desktop application
    - dynamically load content
    - technologies
      - AJAX
      - Websockets
        - bidirectional stateful real-time client-server communication
        - over a single TCP connection
      - Browser plugins
        - (is outdated)
        - Silverlight, Flash, or Java applets
      - Data transport (XML, JSON and AJAX)
        - client updates a partial area of the DOM
    - lifecycle
      - fully loaded in the initial page load
      - divided by small fragments of the page
      - actions & updates
 - Conventional (traditional) Web Applications
   - ![](http://codecompiled.codecompiled.netdna-cdn.com/wp-content/uploads/2015/04/HTML-APP-CACHE.png)
    - b
    - c

## Conceptual Overview
- is fully client-side SPA framework
- by Google, 2009
- ![](http://new.tinygrab.com/7020c0e8b009c1ab1600bcf42ef07b1ed32f40fb0e.png)
- https://angularjs.org/
- resolves problems
  - separate DOM manipulation & business logic (for testing purposes)
  - client & server parts are separated (for parallel development)
- includes
  - CRUD apps (data-binding, validation, routing, server communication, etc)
  - testing (end-to-end, mocks)
  - a
- lifecycle
  - ![](http://singlepageappbook.com/assets/overview.png)
   - compilation step creates pure HTML
   - browser re-renders into the live view
   - step is repeated for subsequent page views
   - (in server-side meaning - controller and model interact within a server process to produce new HTML views)
   - the controller and model state are maintained within the client browser
   - Therefore new pages are generated without any interaction with a server

## Angular
- Quick Start (\w example)
 - add external resource (angular cdn)
   - https://ajax.googleapis.com/ajax/libs/angularjs/1.5.0/angular.min.js
 - the basics (hello name)
   - https://jsfiddle.net/n4kkkm2q/
 - Add Some Control
   - 
- Installation
- Templating
  - are written with HTML
  - contains Angular-specific elements and attributes
  - types
    - Directive
      - a markers on a DOM element (such as an attribute, element name, comment or CSS class), that tell AngularJS's HTML compiler to attach a specified behavior to that DOM element or even to transform the DOM element and its children
      - ngBind, ngModel, and ngClass
      - normalization process
        - cut "x-" & "data-"
        - cut ":", "-" and "_"
        - to camelCase
    - Markup
    - Filter
    - Form control
- Bootstrap
- Directives
 - ng-app
  - an root element
 - ng-bind
 - ng-model
  - for 2-way binding
 - ng-class
 - ng-controller
 - ng-repeat
 - ng-show & ng-hide
- Two-way Data Binding
 - is an automatic way of updating the view whenever the model changes
- Controllers
- Scope
 - $scope / $rootScope
- Views
- Services
 - Constants & Values
 - Services
 - Factories
- Developing & Debugging
- Digest Cycle & Watches
 - The "watch"
- Form Validation
- Promises
 - Q and $q
 - The Deferred Object
 - Route Resolve
- Modules
- Directives

## Examples
- Hello World (https://www.youtube.com/watch?v=uFTFsKmkQnQ)
- ToDo (https://www.youtube.com/watch?v=WuiHuZq_cg4)

## Read & Watch
 - http://www.angularbasics.co.uk/#
 - https://egghead.io/technologies/angularjs
