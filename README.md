# NgBolivia

Este proyecto fue generado utilizando [Nx](https://nx.dev).

<p align="center"><img src="https://raw.githubusercontent.com/nrwl/nx/master/nx-logo.png" width="450"></p>

🔎 **Nx es un conjunto de Herramientas de Desarrollo Extendibles para Monorepos.**

## Agregando capacidades al espacio de trabajo

Nx soporta muchos plugins, los cuales agregan capacidades para desarrollar diferentes tipos de aplicaciones y diferentess herramientas.

Estas capacidades incluyen la generación de aplicaciones, librerías, etc... Así como las herramientas de desarrollo para pruebas y tambien para la construcción de la aplicación.

A continuación hay algunos plugins que se usted puede agregar al espacio de trabajo.

- [React](https://reactjs.org)
  - `npm install --save-dev @nrwl/react`
- Web (sin framework de frontends)
  - `npm install --save-dev @nrwl/web`
- [Angular](https://angular.io)
  - `npm install --save-dev @nrwl/angular`
- [Nest](https://nestjs.com)
  - `npm install --save-dev @nrwl/nest`
- [Express](https://expressjs.com)
  - `npm install --save-dev @nrwl/express`
- [Node](https://nodejs.org)
  - `npm install --save-dev @nrwl/node`

## Generar Aplicaciones

Correr el comando `nx g @nrwl/react:app my-app` para generar una aplicación.

> usted puede usar cualquiera de sus, usted puede usar cualquiera de los plugins anteriores para generar aplicaciones tambien.

Al usar Nx, usted puede crear múltiples aplicaciones y librerías en el mismo espacio de trabajo.

## Generar una librería

Corra el comando `nx g @nrwl/react:lib my-lib` para generar una librería.

> Tambien puede usar cualquiera de los plugins de arriba para generar librerías tambien.

Las librerías son compartidas a través de otras librerías y aplicaciones. Pueden ser importadas de `@ng-bolivia/milib`.

## Servidor de desarrollo

Correr el comando `nx serve mi-app` para un nuevo servidor de desarrollo. Navegue a http://localhost:4200/. La app se recargaraá si usted hace cualquier cambio a los archivos fuente.

## Entendiendo su espacio de trabajo

Correr el comando `nx dep-graph` para ver un diagrama de las dependencias de sus pryectos.

## Para más ayuda

Visite [Nx Documentation](https://nx.dev) para aprender más.
