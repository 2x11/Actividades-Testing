[![](https://presenterse.com/wp-content/uploads/2021/06/maxresdefault-4.jpg)](https://mindhubweb.com/ "Mindhub web")

<strong><center><h1>Actividad 26</h1></center></strong>

## Integrantes del equipo QA
 * Fernando Zigarra
 * Daiana Abal
 * Gerónimo Tapia
 * Daniel Zambrana

## Descripción

### Actividad Git/Git-hub

Esta actividad tiene como objetivo, que aprendan a crear ramas, moverse entre ellas y que puedas subir archivos, commits entre cada una de ellas.

Puedes usar como guía el archivo tutorial.

1. Uno de los integrantes creara un repositorio en git-hub llamado “Actividades Testing”, debe agregar todos los integrantes del equipo como colaboradores.
2. Todos deben clonar el repositorio de manera local y crear su propia rama para trabajar.
3. Cada integrante elegirá una actividad realizada en clase(casos de prueba, evidencias, sugerencias, etc).
4. Muevete de tu rama main hacia la rama que creada:
    + Agrega tus casos de prueba, graficos de jira, capturas, etc.
    + Añádelos con el comando git add
    + Commitealos y hazle push para que puedas mandar todos los cambios al repositorio remoto.

5. Finalmente realizar un merge en la rama principal y armar una caratula con markdown indicando todo el trabajo realizado en las diferentes actividades visualizando las imágenes subidas. Deben colocar también los nombres de los integrantes.
6. Uno solo entrega el link del repositorio.

## Comandos utilizados

```{r}
# Inicializar git localmente
git init

# Enlazar repositorio con Github
git remote add origin https://github.com/2x11/Actividades-Testing.git

# Agregar los cambios de manera local
git add .

# Commitear los cambios
git commit -m "nombre del commit"

# Hacer push
git push origin "nombre de la rama"
```
