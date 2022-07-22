# Comandos de GIT

### Agregar todos los archivos del proyecto
```
    git add .
```

### Agregar un archivo

```
    git add nombrearchivo
```

### Linkear con nuestro repositorio
```
    git remote add origin link.git
```

### Donde link es por ej

- https://github.com/D-M-Gonzalez/AfterGit.git

### Confirmar cambios con commit
```
    git commit -m "un mensaje"
```

### Cambiar de rama ( branch )
```
    git checkout nombrerama
```

### Crear una rama nueva ( branch )
```
    git checkout -b nombrerama
```

### Combinar dos ramas
```
    git checkout rama
    git merge ramaacombinar
```

### Guardar cambios en github remoto
```
    git push origin nombrerama
```

### Traer cambios de github remoto
```
    git pull origin nombrerama
```

### Forzar cambios
```
    --force
```

### Por ej va a subir las cosas a origen sin importar que error de:
```
    git push --force origin master
```

# GIT Ignore

    El archivo git ignore sirve para poder decirle a git que ignore ciertos archivos en nuestro directorio

### Para utilizarlo:

- Crear archivo llamdo ".gitignore"
- Dentro del mismo agregar los nombres de los archivos y carpetas

```
    # Con este símbolo escribo comentarios

    archivo.js

    /carpeta

    /carpeta/archivo.js
```

- Los archivos se escriben directamente con la extensión. En caso de estar dentro de carpetas hay que escribir la ruta completa.
- Las carpetas se pueden escribir con la "/" dando a entender que queremos ignorar la carpeta completa.