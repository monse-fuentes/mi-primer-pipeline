# Mi Primer Pipeline Automatizado

El pipeline configurado tiene la función de automatizar la validación del proyecto cada vez que se realiza un cambio en el repositorio, su funcionamiento inicia automáticamente al realizar un push en GitHub, posteriormente descarga el contenido del repositorio, instala la dependencia HTMLHint y ejecuta una prueba de linter sobre el archivo index.html para verificar que el código no contenga errores de sintaxis y cumpla con las reglas básicas de escritura. 
En caso de detectar errores, el pipeline marca el proceso en rojo y bloquea la validación hasta que el problema sea corregido.
