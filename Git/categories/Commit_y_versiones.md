## Git
[![GIT](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/index.md)

### Commit y versiones
[![GIT](https://img.shields.io/badge/COMMIT_Y_VERSIONES-447ac0?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Commit_y_versiones.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **git commit -m "\[descripción del comentario\]"**  | Guarda los cambios realizados en un repositorio de código en un momento específico |
| **git commit -am "\[descripción del comentario\]"**  | Hacer commits directamente sín hacer un "add" de cada archivo |
| **git log --oneline**  | Log de descripción de commit |
| **git log**  | Log con todos los datos de commit |

#### Ejemplo
```bash
# Agregar archivo y ver su estado
git add index.html
git status

# Hacer commit
git commit -m "Create: index.html"

# Comprobar el estado de la rama main y que está limpio
git status

# Log de descripción de commit
git log --oneline

# Log con todos los datos de commit
git log

# Hacer cambios en archivos del proyecto y hacer commits directamente sín hacer un "add" de cada archivo
git status
git commit -am "update: proyecto"

# Ver diferencias entre ambos commits
git log --oneline
git diff 0000001 0000002
```

[![GIT](https://img.shields.io/badge/COMMIT_Y_VERSIONES-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Commit_y_versiones.md)
