## Git
[![GIT](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/index.md)

### Deshacer commit
[![GIT](https://img.shields.io/badge/DESHACER_COMMIT-c08a44?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Deshacer_commit.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **git reset --hard HEAD**  | Saber cual es el commit de cabecera donde estoy  |
| **git reset --hard HEAD~0**  | Posicionarse en el último commit  |
| **git reset --hard HEAD~1**  | Posicionarse en el penultimo commit  |
| **git reset --hard \[identificador único del commit\]~1**  | Ir a commit e indicar que se borren todos los commits hasta el anterior a él  |

#### Ejemplo
```bash
# Hacer cambios en index.html

# Hacer un commit
git status
git commit -am "update:   index.html"
git log --oneline

# Saber cual es el commit de cabecera donde estoy
git reset --hard HEAD

# Eliminar cambios del último commit
# Posicionarse en el último commit
git reset --hard HEAD~0
# Posicionarse en el penultimo commit
git reset --hard HEAD~1
# Comprobar que se elimino el commit
git log

# Borrar cualquier commit
# Hacer cambios y hacer commit
git status
git commit -am "update:   index.html - añadir librería"
git log --oneline
# Ir a commit e indicar que se borren todos los commits hasta el anterior a él
git reset --hard a1112c1~1
git log --oneline

# Eliminar último commit, pero guardando últimos cambios
git status 
git add .
git commit -m "update:   index.html - eliminar librería"
git log --oneline
git reset HEAD~1
git log --oneline
git status

# Salen últimos cambios realizados, pero no estan preparados para hacer un commit
```

[![GIT](https://img.shields.io/badge/DESHACER_COMMIT-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Deshacer_commit.md)
