# Clase 03 - Git Desarrollo Colaborativo

## Ramas (Branches)

![Estructuras-ramas](_ref/basica.png)

![alt text](_ref/avanzada.png)

## Creando una rama
```sh
git branch <nombre-rama>
```

## Crear rama y moverse a esa rama

```sh
git switch -c <nombre-rama>
git switch -c feature/footer
```

## Listar ramas dentro de un repositorio

```sh
git branch
```

## Cambiar de ramas

```sh
git switch <nombre-rama>
git switch feature/ramas
git switch - # Toogle entre las últimas 2 ramas
```

## Borrar una rama

```sh
git branch -d <nombre-rama>
git branch -d feature/footer # Si los cambios existen en otra rama de nuestro repositorio voy a poder borrar la rama sin problemas pero si no existen tengo que forzar el borrado de la rama.
git branch -D feature/footer # Fuerzo el borrado de la rama cuando los cambios (commits) que tengo dentro de la rama, no forman parte de alguna de las ramas.
```

