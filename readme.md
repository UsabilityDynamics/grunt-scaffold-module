[![Coverage Status](https://img.shields.io/coveralls/UsabilityDynamics/grunt-scaffold-module.svg)](https://coveralls.io/r/UsabilityDynamics/grunt-scaffold-module)

* Unlinke our older scaffold modules, the new "grunt-scaffold-*" modules are much more involved into the projects they scaffold.

### Usage
At the command-line, cd into an empty directory, run this command and follow the prompts.

```js
var project = require('grunt-scaffold-module').getProject();
console.log( project.features );
```

When install globally, following CLI commands may be used.
```
scaffold-module
scaffold-module --help
scaffold-module update
scaffold-module validate
scaffold-module test
```

The legacy method still works as well.
```
grunt-init scaffold-module
```
