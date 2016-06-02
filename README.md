# angular-c360
Angular components for working with data from [Configurator 360](configurator360.autodesk.com).

By using the [c360Context](services/c360Context.service.js) service to load a Configurator 360 model (either a new model or a saved model), you are given a javascript object representing the root part from your model.  This object contains a property for each child part, a property for each model property, and a function for each action (e.g. downloading drawings).  Each of the child parts contains all of this functionality as well -- all the way down the hierarchy.  This allows you to interact with your entire C360 model on the client side using javascript.

A sample application to see this library in action can be found [here](https://github.com/D3Automation/angular-c360-sample)

_**NOTE:** Currently only Angular 1 is supported, but an Angular 2 is in the works and should be available soon_

### Installing

Install using bower
```
bower install angular-c360
```

## Running the tests

_Not yet implemented_

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/D3Automation/angular-c360/tags). 

## Authors

* [D3 Automation](http://d3tech.net/solutions/automation/)

See also the list of [contributors](https://github.com/D3Automation/angular-c360/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
