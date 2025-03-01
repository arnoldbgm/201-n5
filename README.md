# 201-n5

## Historias de usuario

### HU1: Añadir css al landing page

Como usuario de Telefonica Chile, quiero que se mejore el funcionamiento del landing page migrando todo el aplicativo a HTML y CSS.

Criterios de Aceptación:

1. **Condicion 1** Se debe tener una estructura html y css

2. **Condicion 2** Se debe de migrar todo el css que se encontra el etiqueta `<style>` a un archivo css.


### HU2: Añadir Js al landing page

Como usuario de Telefonica Chile, quiero que se mejore el funcionamiento del landing page migrando todo el aplicativo a HTML, CSS y Js.

Criterios de Aceptación:

1. **Condicion 1** Se debe tener una estructura html, css y js

2. **Condicion 2** Se debe de migrar todo el css que se encontra el etiqueta `<script>` a un archivo css.


---

### Flujo para trabajar con las historias de usuario

1. Crear una rama (en la rama van a centrarse en desarrollar la historia de usuario)

```
git branch [rama]
EJM => git branch migracion-css
```

2. Nos movemos a la rama
```
git checkout [rama]
EJM => git checkout migracion-css
```

3. Comenzamos a desarollar toda la historia y una vez finalizado hacemos un ACP

```
git add .
git commit -m "Feat: Implementacion de css"
git push origin [rama]
```

4. Hacemos un Pull Request (El PR consiste en unir los cambios de tu rama main con tu [rama] de tu historia de usuario)

5. Nos vamos a la rama main y la actualizamos bajandonos los ultimos cambios
```
git checkout main
git pull
```