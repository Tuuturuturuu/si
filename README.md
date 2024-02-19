# Ejercicios-Charla-Github-Avanzado-2024

Ejercicios a realizar en la charla "Github avanzado" del mes de la informática 2024

## Ejercicios

1. Crear un workflow usando [este ejemplo](https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-python) que nos ejecute el archivo _prueba.py_ con el comando `python ./src/prueba.py`

2. Crear una rama y cambiar a ella desde nuestro pc y hacer un cambio dentro del archivo _prueba.py_

3. Crear una pull request para unir la rama creada con la rama principal desde github o desde nuestro pc

4. Aceptar la pull request solo si pasa los test

5. Crear un repositorio cuyo nombre sea tu nombre de usuario y cambiar la descripción

6. En este repositorio, crear un archivo _./docs/index.md_, poner cualquier cosa y lanzar github pages con raíz en _/docs_, añadiendo dentro el archivo \_config.yml con el siguiente contenido:

```yaml
lsi: false
safe: true
source: "."
incremental: false
highlighter: rouge
gist:
  noscript: false
markdown: GFM
```
