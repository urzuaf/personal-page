---
name: "dstracker"
title: "Dark Souls Tracker"
url: "https://urzuaf.github.io/darksoulstracker/"
herramientas: "Svelte, Astro"
---

Existen logros en **Dark Souls** para los cuales es necesario llevar un seguimiento preciso de los objetos que se poseen dentro del juego. Esto ayuda a evitar quedarse sin un objeto crucial o tener que comenzar un nuevo juego desde el inicio.  

Para resolver este problema, desarrollé una herramienta que permite llevar un registro de los jefes derrotados y de los objetos obtenidos a lo largo del juego, además de proporcionar indicaciones sobre dónde conseguir cada ítem.  

Como se trata de una aplicación que requiere la permanencia de datos, utilicé el almacenamiento local del navegador para guardar los ítems obtenidos en cada categoría. Esta información se carga cada vez que se accede a la página. En caso de que no existan datos previamente guardados, la aplicación recurre a los archivos **JSON** base incluidos en la herramienta.
