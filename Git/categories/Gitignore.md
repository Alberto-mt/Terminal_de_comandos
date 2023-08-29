## Git
[![GIT](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/index.md)

### Gitignore
[![GIT](https://img.shields.io/badge/GITIGNORE-44c04c?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Gitignore.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **touch .gitignore**  | Crear archivo gitignore |
| **nano .gitignore<br>ó<br>vim .gitignore**  | Editar archivo gitignore |
| **git add .gitignore**  | Añadir archivo gitignore |

#### Ejemplo de archivo editado .gitignore
```bash
# Ignora archivos del sistema Mac
.DS_Store

# Ignora la carpeta node_modules
node_modules/

# Ignora archivos de compilación y ejecutables
*.exe
*.dll
*.class

# Ignora archivos de configuración
config.ini
settings.ini

# Ignora archivos de log
*.log
```
#### Ejemplo
```bash
# Crear gitignore
touch .gitignore

# Editar gitignore
nano .gitignore
# ó
vim .gitignore

# Ver estado y añadir archivo
git status
git add .gitignore
```

[![GIT](https://img.shields.io/badge/GITIGNORE-44c04c?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Gitignore.md)
