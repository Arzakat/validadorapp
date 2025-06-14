Errores encontrados:
-Variable "contraseña": Rename this local variable to match the regular expression '^[a-z][a-zA-Z0-9]*$'. Se cambia variable por "contrasena". Pero de acuerdo al documento, se recomienda quitar. 
-Se retiraron comentarios de FIXME en pom-xml.
-Recomendó quitar los public de las clases ya que JUnit5 posee packages de visibilidad que mejora la lectura del código.
-Solicitó añadir una línea de importación de Logger para llevar un registro de log en vez de un print como buena práctica.

Preguntas Finales:
¿Qué tipo de errores detectó SonarQube que podrían haber pasado desapercibidos?
-El error de expresiones regulares que si bien no es un error es un warning de buenas prácticas. También aprendimos que JUnit5 tiene como opcionales los modificadores de acceso y SonarCube prioriza menos código.
No es un error pero recomendó utilizar Logger para generar un registro de log en vez de un print que puede perderse en la consola.
¿Qué ventajas tiene el análisis estático respecto al dinámico?
-Permite detectar errores sin ejecutar código desde el inicio, es más rápido al ser automatizado y previene errores como malas prácticas, de sintaxis, etc.
¿Cómo impacta SonarQube en la calidad del software antes del despliegue?
-Detecta bugs antes de subir código a producción, ayuda a tener un código limpio sin exceso de palabras "basura", promueve las buenas prácticas, reduce fallos críticos y automatiza revisiones de código, otorga mayor confiabilidad y menores correcciones post despliegue.
¿Qué políticas o reglas personalizarías según el tipo de proyecto?
-Un estándar de código desde el comienzo del desarrollo y entregaría mayor seguridad priorizando automatizaciones que eviten vulnerabilidades en el proyecto.

Grupo 1:
Gabriela López
Camilo Cáceres
Jenny Morgan
