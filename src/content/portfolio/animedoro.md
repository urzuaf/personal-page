---
name: "animedoro"
title : "Animedoro Timer"
url: "https://urzuaf.github.io/animedoro/"
herramientas: "Svelte"
insidelink: "/portfolio/animedoro"
descripcion: "Animedoro es una herramienta que permite configurar intervalos de estudio y descanso, buscando aplicar una variación del conocido método pomodoro"
imagen: "/animedoro.webp"
orden: "1"
---
Tras conocer la técnica de **Animedoro**, decidí implementarla como método de estudio para mis exámenes universitarios. Los resultados fueron bastante positivos, lo que me llevó a adoptarla como mi estrategia principal de estudio.

Sin embargo, el proceso de configurar manualmente un cronómetro en cada sesión resultaba tedioso. Por ello, opté por desarrollar mi propio temporizador, totalmente personalizado y con todas las configuraciones que pudieran resultarme útiles.  

Para la interfaz visual, opté por el uso de **gradientes en movimiento**, ya que transmiten una sensación de calma y tranquilidad, un aspecto valioso al momento de estudiar.  

El desarrollo de todas las funcionalidades se realizó en **Svelte**, siendo este mi primer proyecto con dicho framework. Para la gestión del estado, utilicé **stores** en conjunto con la API de **LocalStorage**, lo que permite almacenar los tiempos configurados. De esta manera, el temporizador conserva la configuración entre sesiones, eliminando la necesidad de ajustarlo manualmente en cada uso.  
