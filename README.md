# MEANtest - MongoDB, ExpressJS, Angular, Node

Siguen como base el siguiente tutorial: https://medium.com/netscape/mean-app-tutorial-with-angular-4-part-1-18691663ea96
Con algunos cambios para soportar cambios recientes en la libreria Rxjs


Prerrequisitos:

NodeJS - https://nodejs.org/en/download/ 
MongoDB — https://www.mongodb.com/download-center#community


Son dos proyectos: 

"todoapp" contiene el backend de la aplicación usando MongoDB y ExpressJS.

Para crear el proyecto desde 0, ejecuten los siguientes comandos en consola.

```
npm install -g express express-generator
express --view=ejs todoapp
cd todoapp
npm install
npm install --save bluebird mongoose mongoose-paginate nodemon
```

Para ejecutar el proyecto:

```
cd todoapp
npm start
```


"todoapp-angular" contiene el frontend, en Angular 

Para crear el proyecto desde 0, ejecuten los siguientes comandos en consola.

```
npm install -g @angular/cli
ng new todoapp-angular --style=scss
cd todoapp-angular
npm install
```

Para usar bootstrap y font-awesome:

```
npm install --save bootstrap@4.0.0-beta @ng-bootstrap/ng-bootstrap font-awesome
```

Para ejecutar el proyecto:

```
cd todoapp-angular
npm serve
```