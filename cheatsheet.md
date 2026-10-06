# Git Cheatsheet

## `git status`

Nos permite ver cuál es el estado actual de nuestro repositorio y cada cambio en curso.

---

## `git add`

Selecciona los cambios que queremos incluir en nuestro próximo commit.

---

## `git commit`

Guarda los cambios que anteriormente agregamos con `git add` y les pone un mensaje para saber qué hicimos.

---

## `git push`

Envía los commits que tenemos localmente a nuestro repositorio remoto.

---

## `git pull`

'Jala' los cambios que existen en el repositorio remoto y los agrega a mi versión local en mi computadora.
Es útil cuando alguien más hizo cambios en el repositorio y quiero tener la versión más reciente en mi computadora.

---

## `git log`

Muestra el historial de commits que se han realizado en el repositorio.

---

## `git diff`

Sirve para ver exactamente qué cambió en los archivos antes de hacer un commit.
Por ejemplo, si modifiqué un archivo y ya no recuerdo qué cambié, me deja comparar la versión anterior con la que tengo actualmente.

---

## `git restore`

Con este comando podemos deshacer cambios que todavía no hemos guardado en un commit.
---

## `git restore --stage`

Sirve para quitar un archivo del área de preparación (staging area) después de haber utilizado `git add`, sin eliminar los cambios que hicimos en el archivo.

---
