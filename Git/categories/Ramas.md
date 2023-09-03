## Git
[![GIT](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/index.md)

### Ramas
[![GIT](https://img.shields.io/badge/RAMAS-c044b8?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Ramas.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **git branch \[nombre de rama\]**  | Crear rama  |
| **git branch**  | Listado de ramas  |
| **git checkout \[nombre de rama\]**  | Cambiar de rama para desarrollar en ella  |
| **git branch -D \[nombre de rama\]**  | Borrar rama  |
| **git fetch**  | Actualizar rama  |
| **git merge \[nombre de rama\]**  | Fusionar rama  |
| **git cherry-pick \[id del commit\]**  | Permite aplicar los cambios introducidos por un commit específico o un rango de commits a la rama actual. Es útil cuando se quieren hacer cambios de forma selectiva desde otra rama sin fusionar toda la rama.  |

#### Ejemplo
```bash
# Crear rama canary
git branch canary

# Listado de ramas
git branch

# Cambiar de rama para desarrollar en ella
git checkout canary

# Crear html de proyecto en canary y commitear
git status
git add .
git commit -m "create:    index.html"
git log --oneline
git checkout main
git log --oneline

# Borrar rama
git branch -D canary

# Fusionar rama canary con main
git status
git commit -am "update:    index.html - acabado"
git log --oneline
git checkout main
git help merge
git help branch
git merge canary

# Cherry-pick
# Fusionar los cambios de un commit, sin fusionar todos los cambios (sin hacer merge)
# Posicionarse en la rama donde se quiere fusionar el commit
git checkout main
git cherry-pick a1234a3
```

[![GIT](https://img.shields.io/badge/RAMAS-c044b8?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Ramas.md)
