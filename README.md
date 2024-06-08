# Reading notes 102n2

- Author: Linder Hassinger
- Space: Enter Tech School

## Pasos para actualizar nuestra repo (ACP)

1. Add
2. Commit
3. Push

- Ejemplo para mapear archivo por archivo
  
```bash
git add la_ruta_de_los_archivos
git add 102/read01.md
git add 102/read02.md
```

- Ejemplo para mapear todos los archivos con un solo comando

```bash
git add .
```

`.` => Aquí (Hace referencia a la carpeta en donde estamos)

- Ejemplo para hacer un commit

```bash
git commit -m "mensaje referente a los cambios que hicimos"
git commit -m "Creando la carpeta 102 para almacenar las lecturas"
```

- Ejemplo para subir nuestros cambios a github.com
  
```bash
git push origin main (debemos especificar a que rama queremos subir los cambios)
```
