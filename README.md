# Pruebas Funcionales

### ¿Qué tipo de errores podrías detectar con esta prueba funcional?

- Errores de respuestas del servidor, 
- El ingreso de texto,
- Búsquedas inválidas.

### ¿Por qué es importante automatizar pruebas desde la perspectiva del usuario?

- Garantizar una buena experiencia de usuario
- Verificar que los cambios no rompan las funcionalidades esenciales
- Probar las funcionalidades en una simulación de casos reales.
- La automatización permite realizar pruebas rápidas, reiteradas veces y sin posibles errores humanos.

### ¿Qué limitaciones tiene Selenium y cómo las superarías?

- Por si sola solo se automatizan pruebas por navegador, por lo que se debe implementar junto con otras herramientas para realizar otro tipo de pruebas.
- Si bien es una buena herramienta para evaluar el funcionamiento como si fuera un usuario, no tiene la capacidad de dar un informe de experiencia de usuario completa como los aspectos gráficos, facilidad de navegación, etc. En este casos sí podría requerirse de testing manual de usuarios u otro tipo de herramientas.
- Dependiendo del tiempo de carga de scripts y velocidad de internet puede haber errores al intentar acceder a funcionalidades que aún no estén cargadas, para esto se puede indicar un tiempo de espera entre acciones.

### ¿Qué validaron?

- Si una búsqueda en la web https://duckduckgo.com/ sobre inmuebles en Bogotá arroja resultados validándolo satisfactoriamente.

### ¿Qué podría fallar si esta prueba no existiera?

- Los tiempos de respuesta.
- Errores en el servidor.
- La falta de información en búsquedas.

### Sugerencias para nuevos casos funcionales: 

- Alargar un poco más la interacción, agregando un click a una página aleatoria, devolverse y probar lo mismo con varias páginas.
- Cambiar la búsqueda por otra y realizar pruebas con la nueva búsqueda.

