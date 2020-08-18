# Studies with Node.JS
> I'm Trying to learn Node.JS and created this API. In here I've learned concepts of Node.Js, API Rest, HTTP Methods, Parameters Type and the awesome middlewares.

[![Linkedin][linkedin-shield]][linkedin-url]

## Installation

Clone this repository:

```sh
~$: git clone https://github.com/lucasbalieiro/nodejs_studies.git
```

Then you can use your favorite package manage to install the dependencies:

```sh
npm install
```
or
```sh
yarn install
```
## Insominia

This API work with few routes and the repository includes an export from a [Insominia][insominia-url] Workspace with all available routes, so you can import and try it.

## Running
With Yarn
```sh
yarn dev
```
or
with NPM
```sh
npm run dev
```
## Routes of the API
This API simulates a simple project management:

_GET_ '/projects?title=_searched-title-tag_' - List all projects and a opicional filter parameter.

_POST_ '/projects' - Creates a new project with a json in the body containing "title" and owner.

_PUT_'projects/:id' - Updates a specific project

_DELETE_ 'projects/:id' - Delete a specific project

## Middlewares
This is the coolest thing that I've learned in this study. This projects has 2 middlewares.

* Logs all the routes printing in the console the Method, url and time of the request; Works in all routes

* Validate if the id of the project in the request is a valid UUID. Just configured for the _PUT_ and _DELETE_ routes

## Release History

* 0.0.1
    * Everything seems to work

## Meta

Distributed under the XYZ license. See ``LICENSE`` for more information.

[My Github](https://github.com/lucasbalieiro)


<!-- Markdown link & img dfn's -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/lucasbalieiro/?locale=en_US
[insominia-url]: https://insomnia.rest/