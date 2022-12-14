
# Lo que necesitas para comenzar

Antes de agregar cualquier l铆nea de c贸digo, lo m谩s importante es tener un entorno listo para comenzar a trabajar 馃挭

## Instalaci贸n de **NodeJS** 馃崁

 **NodeJS** es un entorno de tiempo de ejecuci贸n multiplataforma de c贸digo abierto para desarrollar aplicaciones web del lado del servidor.

**Todas nuestras aplicaciones, tanto en frontend y backend trabajan en funci贸n de un servidor. Necesitamos alg煤n entorno de desarrollo para ello. En este caso nos decantaremos full con Node.**

- Descargue el instalador del sitio web de [Node JS](https://nodejs.org/en/). Descargue la versi贸n LTS, no la 煤ltima.
- Ejecute el instalador. 
- Siga los pasos del instalador, acepte el acuerdo de licencia y haga clic en el bot贸n siguiente. 
- Reinicie su sistema/m谩quina (a veces es necesario )

### Chequeando si Node JS instal贸 correctamente
 Abre tu s铆mbolo del sistema, tu terminal, lo que sea que uses. Menos powershell, me cae mal 馃拋鈥嶁檧锔?

  ```bash 
  # te entregar谩 la versi贸n de node
  $ node -v
  ```
  
  ```bash 
  # te entregar谩 la versi贸n de npm-> node package manager, eso pa intalar las cosas jijij
  $ node -v
  ```
  *Si no recuerdas que es [NPM](https://www.npmjs.com/) es el administrador de dependencias de node, con 茅l podremos instalar librer铆as, herramientas, todo lo que necesites para trabajar con Node JS*

  ### Creemos un archivo Javascript

  
  Probemos si tienes todo lo necesario para ejecutar scripts con node.

                  **Recuerda ejecutar el Script en el mismo directorio del archivo**
``` javascript 
// alo.js
console.log("Alo?")
```

``` bash
# Para ejecutar script
$ node alo.js
$ Alo?
```



馃挍 [Siempre para aprender cosas o repasar, recomiendo jugar con Node School](https://nodeschool.io/) 馃挍

馃挍 [Learn You Node es muy recomendable](https://github.com/workshopper/learnyounode) 馃挍

  ```bash
 Todas las instatalaciones de Node School requiere de instalaciones globales, si est谩s en OSX probablemente tengas problemas.
 #Aqu铆 la soluci贸n (proximamente)
 ```


## Sistema de control de versiones 馃惐

**Github** Es el sistema de control de versiones m谩s popular. Hay muchos m谩s pero empezaremos con esta; instalaremos git, crearemos repos y lo subiremos a github.

- Descarga el instalador de [GIT](https://github.com/mojonapower/frontend-by-yourself) para Windows.