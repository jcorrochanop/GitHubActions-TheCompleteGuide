# Lista de comandos git
Este documento lo voy a usar para ir anotando y organizando los comandos más importantes de Git que vaya aprendiendo. La idea es tener una referencia rápida y clara mientras avanzo en mi camino con Git y DevOps.

## Ver los cambios
El comnado git diff es un comando que muestra las diferencias línea por línea entre los archivos modificados y el último estado confirmado en el repositorio, permitiéndote ver qué cambios has hecho antes de añadirlos al área de preparación o hacer un commit.

```
git diff
```

## Crear un alias
Un alias en Git sirve para crear atajos personalizados que simplifican comandos largos o que usamos con frecuencia. En este caso, voy a crear un alias que me permita ver los logs de Git de una forma más esquemática y visual, facilitando la lectura del historial de commits con ramas y conexiones entre ellos.

```
git config --global alias.hist "log --oneline --decorate --graph --all"
```

## Usar alias
Para usar el alias, una vez creado, simplemente se escribe el nombre que le hayamos asignado en la terminal, como si fuera un comando de Git normal. Por ejemplo, si el alias se llama `hist`, bastará con ejecutar `git hist` para ver el log con el formato esquemático que hayamos configurado. Esto ahorra tiempo y mejora la legibilidad al revisar el historial del proyecto.

```
git hist
```
