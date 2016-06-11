# PouchDB-typescript-definitions

New Typings for PouchDB 5.3.1

## HOW TO USE:

The file declares following global object:

- PouchDB - normal access
- pDB - short form to access

There are also interfaces for all the options / responses of PouchDB.
Access via:

- PouchRes - short form to access: pouchDB.Response;
- PouchOpt - short form to access: pouchDB.Options;


##DEPENDENCIES:

Promises definitions are on standard ES6 Promises, as implemented by es6-shim


## DEVELOPMENT INSTALLATION:

### Install Typings Library

As Super User (Linux/Unix/Mac) / Administrator (Windows):

    npm install typings -g

### Install required typings

Inside the project:

    typings install
