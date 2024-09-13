# MIS_PRIMEROS_PASOS_GITEA


**cREACION DE MI PERFIL EN GITEA**
```
Escribir un repositorio con el nombre .profile
```

**INICIAR PRIMER REPOSITORIO GITEA**

conectarse por SSH
```
ssh ELC202A@192.168.1.77
```

Dirijirse a la carpeta en la que se creara el repositorio
```
cd srv/dev-disk-by-uuid-9ffedf72-d861-4e55-9fad-66a10af08eeb/
```

Detallles a considerar

Git te sugiere **agregar el directorio a la lista de directorios seguros**
```
git config --global --add safe.directory /srv/dev-disk-by-uuid-9ffedf72-d861-4e55-9fad-66a10af08eeb/Servidores/GITEA

```
Configurar el Nombre de la **Rama Inicial**
```
git config --global init.defaultBranch <nombre>
```
Para la main
```
git config --global init.defaultBranch main
```

```
touch README.md
```

```
```



---

----

------

## Verifica el estado del repositorio local

```
git status
```

 ## Obtener los últimos cambios del repositorio remoto
 
Para sincronizar tu repositorio local con el repositorio remoto en GitHub, utiliza el comando git fetch para obtener los últimos cambios del repositorio remoto sin aplicarlos automáticamente a tu rama local:

```
git fetch origin

```

## Fusionar los cambios del remoto en tu rama local

Luego, fusiona los cambios obtenidos con tu rama local. Generalmente, querrás fusionar los cambios en la rama principal (como main o master). Asegúrate de estar en la rama en la que deseas fusionar los cambios:

```
git checkout main  # O usa 'master' u otra rama según sea necesario

```
##  Actualizar tu rama local con un solo comando 
```
git pull 
```
O
```
git pull origin main  # O 'origin/master', según tu configuración
```

```
```

```
```


```
```
