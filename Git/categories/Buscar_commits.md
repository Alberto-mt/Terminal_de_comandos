## Git
[![GIT](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/index.md)

### Buscar commits
[![GIT](https://img.shields.io/badge/BUSCAR_COMMITS-447ac0?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Buscar_commits.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **git log --grep=\[palabra a buscar\]**  | Buscar commit por palabra en su descripción  |
| **git log -S \"\[cadena de caracteres\]\"**  | Buscar commit por palabras en su contenido  |

#### Ejemplo
```bash
# Buscar commit por "javascript" en su descripción
git log --grep=javascript

# Buscar commit por "Tienda online" en su contenido
git log -S "Tienda online"

# Una vez encontrado el commit, ya se puede hacer un checkout e ir a el
```

[![GIT](https://img.shields.io/badge/BUSCAR_COMMITS-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Buscar_commits.md)
