# Creador de Horario Premium

Este proyecto es una página web para crear, editar y guardar un horario semanal de cursos.  
El horario está diseñado en modo oscuro con un estilo visual premium, bloques de cursos resaltados y opción para descargar el horario como imagen.

## Vista general

El sistema permite organizar clases desde lunes hasta domingo, usando intervalos de una hora.  
Cada curso se muestra como un bloque dentro del horario, indicando:

- Nombre del curso
- Lugar o aula
- Día
- Hora de inicio
- Hora de fin
- Color personalizado

El horario no tiene título en la imagen final, por lo que la exportación se ve más limpia y profesional.

## Funcionalidades

- Crear cursos nuevos.
- Editar cursos existentes.
- Eliminar cursos seleccionados.
- Cambiar día, hora de inicio y hora de fin.
- Personalizar el color de cada curso.
- Guardar los cambios en el navegador usando `localStorage`.
- Restaurar el horario original.
- Descargar el horario como imagen PNG.
- Exportar solo el horario, sin botones ni controles.
- Diseño en modo oscuro.
- Bloques de cursos con efecto visual destacado.
- Lugar/aula separado visualmente del nombre del curso.

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript
- LocalStorage
- html2canvas
