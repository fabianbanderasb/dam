## Observaciones

Actualizar versiones de npm y node.

Este es la solución para el error que tuve, podés probarla.

El paquete @angular/cli@16.1.0 requiere una versión de Node.js igual o superior a 16.14.0 o >=18.10.0,
 y una versión de npm igual o superior a 6.11.0 o ^7.5.6 || >=8.0.0. Sin embargo, en tu caso,
 tienes instalada la versión de Node.js v12.22.9 y la versión de npm 8.5.1.

## Setting up the local environment and workspace

Install the Angular CLI
You can use the Angular CLI to create projects, generate application and library code,
 and perform a variety of ongoing development tasks such as testing, bundling, and deployment.

To install the Angular CLI, open a terminal window and run the following command:

```
npm install -g @angular/cli
```

## Create a workspace and initial application

You develop apps in the context of an Angular workspace.

To create a new workspace and initial starter app:

Run the CLI command ng new and provide the name my-app, as shown here:

```
ng new my-app
```

The ng new command prompts you for information about features to include in the initial app. Accept the defaults by pressing the Enter or Return key.

The Angular CLI installs the necessary Angular npm packages and other dependencies. This can take a few minutes.

The CLI creates a new workspace and a simple Welcome app, ready to run.
