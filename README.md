# Greenfield-Angular-Setup
Greenfield Angular Setup

1. Download angular seed application: https://github.com/angular/angular-seed

2. Remove view 1 and 2 logic, route from myApp

<pre>
  <code>
    angular.module('myApp', [
      'ui.router'
    ])
</code>
</pre>

3. Move scripts between head tags in index.html

4. install angular with bower

https://github.com/angular-ui/ui-router

<code>bower install angular-ui-router --save</code>

5. Add scripts pointing to bower folder with angular and angular ui

<code><script src="bower_components/angular/angular.js"></script></code>
<code><script src="bower_components/angular-ui-router/release/angular-ui-router.js"></script></code>

6. 
