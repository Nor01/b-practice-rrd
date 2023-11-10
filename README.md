# Ejercicio de practica con RRD

Una breve app que permita tener 3 enlaces para moverse entre Home, About y Contact pages.

## Instrucciones

Crear 3 componentes: Home, About, Contact

Una vez instalada la libreria `rrd` podemos importar en nuestro App el provider que se llama BrowserRouter y como `children` pasamos Route y Link.
Entendiendo que `Link` contiene la logica del `navigate y history.pushState` y que Route contiene la logica del `currentPath` para determinar el componente a renderizar.

## Ayuda

> npm create vite@latest
> npm i react-router-dom

import { BrowserRouter as Router, Route, Link } from 'react-router-dom'
