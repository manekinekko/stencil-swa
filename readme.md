# Stencil App Starter

Stencil is a compiler for building fast web apps using Web Components.

Stencil combines the best concepts of the most popular frontend frameworks into a compile-time rather than run-time tool.  Stencil takes TypeScript, JSX, a tiny virtual DOM layer, efficient one-way data binding, an asynchronous rendering pipeline (similar to React Fiber), and lazy-loading out of the box, and generates 100% standards-based Web Components that run in any browser supporting the Custom Elements v1 spec.

Stencil components are just Web Components, so they work in any major framework or with no framework at all. In many cases, Stencil can be used as a drop in replacement for traditional frontend frameworks given the capabilities now available in the browser, though using it as such is certainly not required.

Stencil also enables a number of key capabilities on top of Web Components, in particular Server Side Rendering (SSR) without the need to run a headless browser, pre-rendering, and objects-as-properties (instead of just strings).

## Getting Started

To start a new project using Stencil, clone this repo to a new directory:

```bash
npm init stencil app
```

and run:

```bash
npm start
```

To build the app for production, run:

```bash
npm run build
```

To run the unit tests once, run:

```
npm test
```

To run the unit tests and watch for file changes during development, run:

```
npm run test.watch
```

## Deploy to Azure Static Web Apps

Follow the quick [Getting Started](https://bit.ly/2ABy9Cb![screenshot-1589921212097](https://user-images.githubusercontent.com/1699357/82376694-c3a29880-9a22-11ea-887c-f1330b13a1b6.png)
) guide for Azure Static Web Apps and use the following configuration:

![screenshot-1589919283815](https://user-images.githubusercontent.com/1699357/82375928-a28d7800-9a21-11ea-8b9b-1648e46f6048.png)


![screenshot-1589919296064](https://user-images.githubusercontent.com/1699357/82375745-4de9fd00-9a21-11ea-8534-37a5f42059c1.png)

![screenshot-1589919311088](https://user-images.githubusercontent.com/1699357/82375732-4b87a300-9a21-11ea-8e89-d78fe65454d0.png)

Once you build is done. You should get the generated URL for your app:
![screenshot-1589921212097](https://user-images.githubusercontent.com/1699357/82376815-fa78ae80-9a22-11ea-8148-ee025d06df25.png)

