# Mi Rutina

Registro personal de entrenamiento (app web estática).

El contenido de `index.html` está **cifrado** (AES-GCM 256 con clave derivada por PBKDF2-SHA256, 600.000 iteraciones). Sin la contraseña no se puede leer, aunque se descargue el repositorio. El código legible no se publica.

Al abrirla se pide la contraseña una sola vez por dispositivo ("Recordar en este dispositivo"); después abre directo y funciona sin conexión. Los registros se guardan solo en el navegador del dispositivo (exportá un respaldo .json cada tanto desde la app).
