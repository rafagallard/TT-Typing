# TT-Typing

Aplicación de mecanografía en español para aprender a escribir sin mirar el teclado, con ejercicios progresivos y práctica sin presión.

## Funciones

- 12 lecciones: F/J, fila central, G/H, filas superior e inferior, palabras, mayúsculas, acentos y Ñ, números, signos, historias y reto de 60 segundos.
- Guía de teclas y dedos por colores, con opción para ocultar las letras.
- Perfiles locales, historial, precisión y palabras por minuto (PPM).
- Pausa automática al salir del campo de práctica o cambiar de pestaña.
- Teclado QWERTY español o inglés. La ubicación de signos y acentos depende del teclado físico.

## Uso

Abre `index.html` en un navegador moderno, preferentemente en una computadora con teclado físico. Crea un perfil con el botón + y comienza por F y J.

La precisión cuenta todos los intentos. Una lección se marca como lograda al terminar con al menos 90% de precisión. PPM = caracteres correctos / 5 / minutos activos.

## Publicación en GitHub Pages

En Settings → Pages, selecciona Deploy from a branch, rama `main`, carpeta `/(root)` y guarda.

URL prevista después de habilitar Pages y completar el despliegue: https://rafagallard.github.io/TT-Typing/

## Datos y privacidad

Los perfiles y resultados se guardan únicamente en el almacenamiento local del navegador. No hay cuentas, servidor, analítica ni sincronización entre dispositivos. Borrar los datos del navegador elimina el progreso. El progreso de la versión anterior alojada en otro dominio no se transfiere automáticamente.

## Desarrollo

Aplicación estática autocontenida, sin dependencias ni compilación. HTML, CSS y JavaScript están en `index.html`; los comentarios explican las funciones principales.

Se verificaron sintaxis y lógica de puntuación, pausas, finalización, perfiles y límite del reto. No se completó una revisión visual automatizada en navegador.
