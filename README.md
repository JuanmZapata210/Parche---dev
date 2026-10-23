# Parche Dev 2026

Sitio oficial del encuentro Parche Dev 2026, construido solo con HTML semántico.
Reto individual del Módulo 1 · HTML y CSS, RIWI.

Sitio publicado: https://github.com/JuanmZapata210/Parche---dev

## Páginas

- Inicio
- Agenda
- Ponentes
- Inscripción y confirmación
- Código de conducta

## Cómo verlo en tu computador

1. Clona el repositorio.
2. Ábrelo en VS Code.
3. Abre index.html con Live Preview.

## Decisiones que tomé

- (Explica al menos tres decisiones: por qué elegiste una etiqueta y no otra.)
- <button type="submit"> dentro del <form>, sin enlace adentro, si el botón llevaba un <a>, el clic navegaba a gracias.html y se saltaba la validación. Ahora el destino va en el action del formulario, así el navegador revisa los campos obligatorios antes de enviar.
- <input type="radio"> y type="checkbox">  usé radio para ciudad y momento porque solo se puede elegir una opción, y checkboxes para temas de interés porque se pueden elegir varias.
-Para la talla usé <select> porque son seis opciones de las que se elige una, y una lista desplegable ocupa menos espacio que seis radios.
- (Responde las preguntas del apartado “Investiga” del ticket 5.)
-¿Cómo se ven los espacios, las tildes y la arroba?
El navegador los codifica, porque la URL no admite todos los caracteres:
Espacio → + (por ejemplo Juan+Manuel).
Arroba @ → %40 (por ejemplo juanm%40correo.com).
Tildes y ñ → % seguido de dos bytes en hexadecimal: ú es %C3%BA, é es %C3%A9 y ñ es %C3%B1.
-¿Qué pasa con los campos que no llenaste?
Texto, correo, teléfono y textarea vacíos: aparecen con el valor vacío, por ejemplo celular=.
Checkboxes y radios sin marcar: no aparecen. Si no marcaste el taller, no verás taller= en la URL.
<select>: siempre se envía, porque siempre hay una opción seleccionada (por defecto, la primera, talla=XS).
-¿Por qué un formulario con contraseñas nunca debería usar method="get"?

Con get los datos viajan dentro de la URL, y eso los expone en muchos lugares.

## Lo que aprendí

- (Al menos tres aprendizajes de la jornada.)
-Aprendi a que mi codigo debe tener muy buena semantica para facilitar el navegar desde el tab, y la web reconoxca lo que es cada cosa y cada parrafo de mi proyecto tenga un sentido.
-Aprendi a usar de buena forma git y github, a subir cada actualizacion y ver copmo nos facilita todo si despues lo quiero abrir desde otro proyecto.
-Aprendi que solo con HTML si el codigo tiene buena semantica y esta bien redactado se puede entender muy bien sin necesidad de css, ademas aprendi muchas etiquetas nuevas.
## Hecho por

Juan Manuel Zapata Serna · [GitHub](https://github.com/JuanmZapata210)