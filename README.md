# CHALLENGE: AMIGO SECRETO

Este proyecto es una aplicación web sencilla para realizar un sorteo simple de **Amigo Secreto**. Permite ingresar nombres de amigos en una lista y luego sortear aleatoriamente uno de ellos, mostrando el resultado directamente en la interfaz.

## Funcionalidades

### Agregar Nombres
- El usuario escribe un nombre en el campo de texto.
- Al hacer clic en el botón **Añadir** o presionar la tecla **Enter**, el nombre se añade a la lista de amigos.
- Se valida que el nombre no esté vacío y que no haya nombres duplicados para asegurar una lista limpia.
- La lista visible se actualiza dinámicamente con los nombres agregados.

### Mostrar Lista de Amigos
- Los nombres agregados se despliegan en una lista visible.
- Cada nombre aparece como un ítem `<li>` en la lista para referencia rápida.

### Sortear Amigo
- Al presionar el botón **Sortear amigo**, la aplicación selecciona un amigo aleatorio de la lista.
- Se muestra el nombre seleccionado en la lista de resultados bajo el botón.
- Si no hay nombres en la lista al momento del sorteo, se muestra una alerta indicando que hay que agregar amigos primero.

## Lógica y Diseño de Desarrollo

- Toda la lógica está implementada en JavaScript puro, corriendo en el navegador sin necesidad de backend.
- Se utiliza un array `amigos` para almacenar los nombres ingresados.
- Funciones separadas y claras para:
  - Agregar amigos (`agregarAmigo()`)
  - Actualizar la lista visual (`actualizarListaAmigos()`)
  - Realizar el sorteo (`sortearAmigo()`)
- Validaciones robustas para evitar entradas vacías o duplicadas.
- Actualización dinámica del DOM para reflejar los cambios sin recargar la página.
- Manejo de eventos para optimizar la experiencia, incluyendo soporte para tecla Enter.
- Alertas informativas para guiar al usuario.

## Tecnologías Utilizadas

- **HTML**: Estructura de la página con inputs, botones, listas y elementos semánticos.
- **CSS**: Estilos cuidadosamente diseñados para una interfaz limpia y amigable.
- **JavaScript**: Código en `app.js` para gestionar el estado, interactividad y lógica del sorteo.

---

Este proyecto sirve como ejercicio para fortalecer conceptos fundamentales de programación como manejo de arrays, funciones, condicionales, validaciones y manipulación del DOM, todo dentro de un contexto práctico y visualmente agradable.

