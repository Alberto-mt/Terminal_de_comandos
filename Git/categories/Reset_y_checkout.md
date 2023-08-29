## Git
[![GIT](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/index.md)

### Reset y checkout
[![GIT](https://img.shields.io/badge/RESET_Y_CHECKOUT-c044b8?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Reset_y_checkout.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **git reset [identificador único del commit]**  | Mover la rama actual a un commit anterior, eliminando todos los commits posteriores  |
| **git reset HEAD [nombre de archivo]**  | Resetear cambios en el HEAD (dejarían los cambios de estar perparados) |
| **git checkout [nombre de archivo]**  | Dejar archivo como estaba despues de modificarlo (los cambios se deshacen) |

#### Ejemplo
```bash
# Mover la rama actual a un commit anterior, eliminando todos los commits posteriores
git reset abc123

# Hacer cambios en el título de index.html
git status

# Añadir archivo y prepararlo para el commit
git add .
git status

# Resetear cambios hechos en el HEAD (dejarían los cambios de estar preparados)
git reset HEAD index.html
git status

# Hacer cambios en index.html y volver a dejar archivo como estaba despues de modificarlo
git checkout index.html
```

[![GIT](https://img.shields.io/badge/RESET_Y_CHECKOUT-c044b8?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Reset_y_checkout.md)
