## Git
[![GIT](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/index.md)

### Volver a un commit anterior
[![GIT](https://img.shields.io/badge/VOLVER_A_UN_COMMIT_ANTERIOR-44c04c?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Volver_a_un_commit_anterior.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **git log --oneline**  | Ver listado de log de commits  |
| **git checkout \[identificador único del commit\]**  | Volver a un commit anterior  |

#### Ejemplo
```bash
# Guardar últimos cambios
git commit -am "update:  index.html - cambiar icono"
git log --oneline

# Hacer dos cambios en el proyecto y guardarlos por separado
git commit -am "update:  index.html - cambiar título"
git commit -am "update:  css/styles.css - estilos de cards"
git log --oneline

# Volver a commit anterior
git checkout 7a111c3
git log --oneline

# Volver a commit primero
git checkout 7a111c4
git log --oneline

# Importante >> a todos los cambios que se realicen a partir de aquí, se les podrá hacer commit,
# pero estará todavía trabajando en la rama main. Para que se haga un commit y se posicione por
# defecto en él, hay que crear una rama
git commit -am "update: index.html - último cambio"
git log --oneline
git branch canary a1111aa

# Ahora hay dos ramas
git branch

# Cambiar de rama
git checkout canary
git log
```

[![GIT](https://img.shields.io/badge/VOLVER_A_UN_COMMIT_ANTERIOR-44c04c?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Volver_a_un_commit_anterior.md)
