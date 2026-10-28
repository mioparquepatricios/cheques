# Cheques MIO — calendario en el celular

Página para ver en el celular el calendario de cheques a pagar de MIO.
`datos.json` está cifrado (AES-GCM, clave PBKDF2): sin la contraseña no se puede leer.
Lo genera y sube solo el programa "Cheques MIO" de la PC (módulo `celular.py`) cada vez que cambian los datos.
