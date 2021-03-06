Job Module
==============================================================================

This is one of the modules; helps building up the main application [ahlev.com](https://ahlev.com).

The architecture design could be found in [main app](https://github.com/3alinka/ember-ahlev-app)

Detail
------------------------------------------------------------------------------
It takes care of job management.


Compatibility
------------------------------------------------------------------------------

* Ember.js v3.12 or above
* Ember CLI v2.13 or above
* Node.js v10 or above


Installation
------------------------------------------------------------------------------

```
ember install https://github.com/ohahlev/ember-engine-ahlev-job
```

Mount
------------------------------------------------------------------------------
```
Router.map(function() {
  this.mount('ember-engine-ahlev-job', { path: 'ahlev-job'});
});
```

Usage
------------------------------------------------------------------------------

This provides:
- components
- routes
- services


Contributing
------------------------------------------------------------------------------

See the [Contributing](CONTRIBUTING.md) guide for details.


License
------------------------------------------------------------------------------

This project is licensed under the [MIT License](LICENSE.md).
