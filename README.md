# SVN Comandos

## Comandos

# Cliente para Windows

[Download SlikSVN Subversion client](https://sliksvn.com/download/)

### Descargar una ruta

```bash
svn --username NOMBREDEUSUARIO --password PASSWORD co [https://svn.SERVER_NAME.com:8443/svn/dir/child/etc/etc/]
```

### Agregar archivos nuevos para subirlos despues al SVN

```bash
svn add 'NOMBRE DEL ARCHIVO A AGREGAR'
```

### Comando para subir el "lote" de archivos que se agregaron anteriormente

```bash
svn commit -m 'NOMBRE DE LO QUE VAS A ENVIAR'
```

### Actualiza la ruta local con lo que hay en el repositorio

```bash
svn update 
```

### Muestran los cambios realizados en la ruta

```bash
svn status 
```

### Elimina un archivo de manera local

Si se desea que los cambios se "vayan" al SVN es necesario hacer un *COMMIT*

```bash
svn rm 'NOMBRE DEL ARCHIVO' 
```