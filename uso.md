### Órdenes de uso habitual

- Todas las ordenes se deben ejecutar dentro del repositorio (directorio)

Inicializar un repositorio

```
git init
```

Añadir seguimiento y/o cambios sobre un  archivo o archivos

```
git add file1.ext file2.ext | mask | .

```

Descartar los cambios del archivo local

```
git restore file1.ext file2.ext | mask | .
```

Eliminar el seguimiento de un archivo o archivos, sin eliminar el local

```
git rm --cached file1.ext file2.ext | mask | .
```

Registrar los archivos en seguimiento permanentemente en el historial de versiones

```
git commit -m "[Breve descripcion del archivo o los cambios del mismo]"
```

Volver a un commit especifico temporalmente

```
git checkout id_commit | [master | headname]
```

Volver a un commit específico definitivamente. La opción hard aplica los cambios localmente

```
git reset id_commit [--hard]
```

### Órdenes útiles

Conocer el estado actual del repositorio

```
git status
```

Listar el histórico de versiones (commits)

```
git log
```
