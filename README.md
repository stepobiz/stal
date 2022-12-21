# Stal

This is the project for manage 4 angular Library of tools developed by StepoBiz

The libraries is
- autocomplete
- carder
- eventer
- paginator

The library is not dependent on each other. The guide is based on the firs module as example but all is the same.

## Development server

For use library cloned localy, in your project is necessary build it and use the dist folder as npm link, like in this example:
```
ng build autocomplete
cd dist/autocomplete
sudo npm link
```

after go in your project and link it to library
```
cd your_project_folder
npm link @stal/autocomplete
```

If you want edit library an se real time result in your project, execute the watch builder in library folder:
```
ng build autocomplete --watch
```