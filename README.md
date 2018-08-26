# Instalación de MongoDB en Windows

1. Descargar el instalador para windows [instalador de MongoDB](https://www.mongodb.com/download-center#community).
2. Seleccionar Community Server para obtener el botón de descarga.
3. Instalación
	* Clic en Next.
	* Aceptar terminos y clic en Next.
	* Clic en Complete.
	* Clic en Next.
	* Clic en Next.
	* Clic en Install.
	* Clic en Finish.

4. Crear el path de mongod
	* Ir a la ruta "C:\Program Files\MongoDB\Server\4.0\bin" de ubicación el archivo mongod.exe, en el computador.
	* Clic der en equipo.
	* Clic en Propiedades
	* Clic en Configuraciones avanzadas del sistema.
	* Clic en Variables de entorno.
	* Seleccionar "path".
	* Clic en Editar.
	* Clic en Nuevo.
	* Pegar la ruta copiada "C:\Program Files\MongoDB\Server\4.0\bin".
	* Aceptar, aceptar y aceptar.

5. Crear las carpetas de almacenamiento de MongoDB.

```
	C:\data
	C:\data\db

```

6. Abrir la consola "cmd", "git bash" o powerShell, y escribir:

```
	mongod

```

7. Abrir otra consola "cmd", "git bash" o powerShell, y escribir:

```
	mongo

```
