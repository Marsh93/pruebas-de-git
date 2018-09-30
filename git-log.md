# git log

Muestra el historial de commits

`git log --pretty=format:"%h - %an, %ar : %s"`

Muestra el historial con el formato que indicamos.

## Limitar la salida del historial

`git log -n`: Cambiamos la n por cualquier número entero. Ejemplo:
`git log -2` nos mostrará los 2 commits más recientes.
`git log --after="2018-09-24 00:00:00`: Muestra los commits realizados después de la fecha especificada.
`git log --before="2018-09-24 00:00:00`: Muestra los commits realizados antes de la fecha especificada.

Las banderas del comando `git log` se pueden usar juntas según convenga. Ejemplo:
`git log --after="2018-09-24 12:00:00" --before="2018-09-27 12:30:00"`