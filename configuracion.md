### Configurar la identidad del usuario de git

```
git config --global user.name "Paco Porras"
git config --global user.email paco@porras.org
```

### .gitignore

En la carpeta raiz del proyecto

```
echo ["file_to_ignore" | "/folder/to/ignore"] >> .gitignore
git add .gitignore
git commit -m "Comentario sobre .gitignore"
```
