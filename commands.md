### Rama
```
    git checkout -b rama-villanos
```
Al hacer push la primera vez toca ejecutar este comando:
```
    git push --set-upstream origin rama-villanos
```

si quiero cambiar el repositorio remoto:
```
    git remote set-url origin <nueva-url-del-repositorio>

```

Mostar las ramas 
```
    git branch
```

Eliminar ramas 
```
    git branch -d <nombre-rama> 
```

Eliminar ramas forzada
```
    git branch -d <nombre-rama> -f
```    

Traer las ramas de otros compañeros
```
    git pull --all 
``` 
Pasarse a la rama del compañero
```
    git branch --all 
    git checkout <nombre_rama>
``` 

Limpiar ramas no necesarias
```
    git remote prune origin
```
Eliminar ramas localmente
```
    git branch -d <nombre-rama> 
```

