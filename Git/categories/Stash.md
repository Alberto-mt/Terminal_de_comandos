## Git
[![GIT](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/index.md)

### Stash (realizar cambios trabajando con memoria virtual)
[![GIT](https://img.shields.io/badge/STASH-c08a44?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Stash.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **git stash**  | Guardar los cambios en memoria (stash) sin nombre  |
| **git stash save \'\[nombre\]\'**  | Guardar los cambios en memoria (stash) conn nombre  |
| **git stash show**  | Mostrar lo que hay en memoria  |
| **git stash apply**  | Recuperar los cambios del stash más reciente y aplicarlos a tu directorio de trabajo sin eliminar el stash . Se puede especificar un stash en particular utilizando su nombre o el índice del stash, por ejemplo: "git stash apply stash@{3}".  |
| **git stash pop**  | Recuperar los cambios del stash más reciente y aplicarlos a tu directorio de trabajo, eliminando el stash de la lista de stashes. Al igual que con "git stash apply", se puede especificar un stash en particular utilizando su nombre o el índice del stash.  |
| **git stash drop**  | Eliminar un stash sin aplicar los cambios. Por ejemplo: "git stash drop stash@{3}" eliminará el stash con el índice 3 de la lista de stashes.  |
| **git stash clear**  | Eliminar todos los stashes  |

#### Ejemplo
```bash
# Trabajando en la rama "cliente", se hacen cambios que no se preparan y hay que cambiar a otra rama para realizar cambios.
# Antes de cambiar de rama haciendo un checkout, hay que guardar los cambios en una memoria virtual
# (para no llevar los cambios a la otra rama y al volver a la anterior seguir teniendolos)

# Partiendo de la rama cliente
git stash
git status
git stash show
git checkout canary

# Una vez se acaba de trabajar en canary y se quiere volver a trabajar en cliente, se comprueba lo que hay en memoria.
git stash show

# Volver a dejarlo como se tenia para poderlo agregar
git stash pop

# Borrar lo que tengo en el stash (Ya se han realizado otros cambios o no interesa)
git stash clear
git stash show
```

[![GIT](https://img.shields.io/badge/STASH-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Stash.md)
