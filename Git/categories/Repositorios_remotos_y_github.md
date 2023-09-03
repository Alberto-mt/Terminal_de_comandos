## Git
[![GIT](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/index.md)

### Repositorios remotos y GitHub
[![GIT](https://img.shields.io/badge/REPOSITORIOS_REMOTOS_Y_GITHUB-44c04c?style=for-the-badge&logo=GIT&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Repositorios_remotos_y_github.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **git remote add origin \[url repositorio\]**  | Vincular dirección de repositorio  |
| **git push origin main**  | Subir cambios a repositorio  |
| **git fetch --all**  | Bajarse a local todas las ramas que hay en remoto (GitHub) |
| **git pull origin main**  | Bajar cambios a repositorio local  |
| **git clone git@github.com:\[usuario\]/\[repositorio\].git**  | Clonar repositorio con SSH  |

#### Conectarse de forma segura a github con SSH
[Conexión SSH](https://docs.github.com/es/authentication/connecting-to-github-with-ssh)
#### Ejemplo
```bash
# En GitHub crear cuenta y crear nuevo repositorio
# Vincular dirección de repositorio
git remote add origin https://github.com/Alberto-mt/pruebaGit.git

# Subir cambios a repositorio (pide usuario y contraseña)
git push origin main
git push

# Bajarse a local todas las ramas que hay en remoto (GitHub)
git fetch --all

# Bajar cambios a repositorio local
git pull origin main
git pull

# Clonar repositorio con SSH
git clone git@github.com:Alberto-mt/pruebaGit.git
```

[![GIT](https://img.shields.io/badge/REPOSITORIOS_REMOTOS_Y_GITHUB-44c04c?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Git/categories/Repositorios_remotos_y_github.md)
