# Ember Tabbed Interface

Trying to create a dyanamic tabbed interface. Where a route is opened as a tab??? We are also trying to do it. 

Demo: http://aalasolutions.com/ember/tab/

## Important files

### app/reopens/link-component.js [link](https://github.com/aalasolutions/ember-tabbed-interface/blob/master/app/reopens/link-component.js)
Customize all `{{link-to}}` components
### app/site/component/header-tabs [link](https://github.com/aalasolutions/ember-tabbed-interface/tree/master/app/site/components/header-tabs)
Manage tabs and call the actions in the services, mainly used to display the tabs
### app/site/services/headtabs/service.js [link](https://github.com/aalasolutions/ember-tabbed-interface/blob/master/app/site/services/headtabs/service.js)
Handles all the tab events like, add/edit/remove/swap/switch


**Other** files including initializer to include the service in every route, and include the link-componenet reopn in the main `app.js` 

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://www.ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone https://github.com/aalasolutions/ember-tabbed-interface.git` this repository
* change into the new directory
* `npm install`
* `bower install`

## Running / Development

* `ember server`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://www.ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

