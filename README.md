# MONACA OnsenUI + Angular 6+ schematics 

[![npm version](https://badge.fury.io/js/ng-monaca-schematics.svg)](https://badge.fury.io/js/ng-monaca-schematics)

[![Build Status](https://travis-ci.org/MSakamaki/ng-monaca-schematics.svg?branch=master)](https://travis-ci.org/MSakamaki/ng-monaca-schematics)
[![Build status(win)](https://ci.appveyor.com/api/projects/status/wikogf9fcyox6okh?svg=true)](https://ci.appveyor.com/project/MSakamaki/monaca-schematics)

[![DEPENDENCIES](https://david-dm.org/MSakamaki/ng-monaca-schematics.svg)](https://david-dm.org/MSakamaki/ng-monaca-schematics)
[![DEVDEPENDENCIES](https://david-dm.org/MSakamaki/ng-monaca-schematics.svg?type=dev)](https://david-dm.org/MSakamaki/ng-monaca-schematics?type=dev)

### install

```sh

npm install -g @angular/cli@6.0.8
npm install -g ng-monaca-schematics

```

### use

```sh
# generate project
ng new <project name> -c ng-monaca-schematics [--name=<application name>]

# create component
# aliases ( ng g ng-monaca-schematics:mc [name] )
ng generate ng-monaca-schematics:monaca-component [name]

```

### project development

#### local

 1. install a environment
   + install [Monaca Localkit](https://monaca.io/localkit.html) into local machine
   + Insert [Monaca Debugger](https://docs.monaca.io/en/products_guide/debugger/installation/) in mobile development machine
   + connect development machines to the same network
 2. run on a mobile device
   + run a `npm run ng.build` command.
   + Open `./www` directory with `Monaca Localkit`
 3. to preview

#### remote

 1. monaca cloud initialized
   + `npm run login`
 2. remote debugging
   + `npm run upload`
   + open browser [monaca ide page](https://monaca.mobi/en/dashboard)
   + open youre project
   + to preview or run on device
 3. remote build
   + `npm run build`
   + open browser [monaca ide page](https://monaca.mobi/en/dashboard)
   + open youre project
   + open menu [buld] to build history
  

### feature

 + [ ] npm publish
 + [x] npm start
 + [x] ng build
 + [x] ng test
 + [x] ng e2e
 + [ ] update monaca [browserlist](https://github.com/angular/devkit/blob/master/packages/schematics/angular/application/files/root/browserslist)
 + add `ng generate`
   + [x] component
   + [ ] page
   + [ ] toolbar
 + [x] monaca upload
 + [x] monaca cloud buildsing

#### workflow and commands

 + install
   + [x] install command
   + template using
     + [x] useing [monaca-lib template](https://github.com/monaca/monaca-lib/tree/master/src/template)
 + local building
   + [x] server
 + remote monaca 
   + [x] upload monaca cloud
   + [x] building monaca cloud

### run testing


```sh
# test
npm run test
npm run e2e

```
