# challenge-amigo-secreto_curso01

Amigo Secreto
Este proyecto es una aplicación web simple para organizar un sorteo de "Amigo Secreto" (Secret Santa). Permite agregar nombres de amigos a una lista y luego realizar un sorteo aleatorio donde cada persona es asignada a otra, asegurando que nadie se asigne a sí misma.
Funcionalidades

Agregar Nombres:

Ingresa el nombre de un amigo en el campo de texto.
Haz clic en "Añadir" para agregar el nombre a la lista.
No se permiten nombres duplicados ni vacíos.
Cada nombre en la lista tiene un botón "Eliminar" para removerlo si es necesario.


Sortear Amigos:

Una vez que haya al menos 2 nombres en la lista, haz clic en "Sortear amigo".
La aplicación genera una asignación aleatoria (derangement) donde cada persona regala a otra, sin auto-asignaciones.
Los resultados se muestran en una lista debajo del botón, en formato "Nombre -> Amigo Secreto".


Lógica de Sorteo:

Utiliza un algoritmo de shuffle (Fisher-Yates) y verifica que no haya asignaciones fijas, reshuffleando si es necesario.
Implementado puramente en JavaScript del lado del cliente, sin backend.



Tecnologías Utilizadas

HTML: Estructura de la página.
CSS: Estilos proporcionados, con variables para colores y diseño responsivo.
JavaScript: Lógica para manejar la lista de nombres, validaciones y el sorteo.
