## Unix terminal
[![UNIX](https://img.shields.io/badge/UNIX_TERMINAL-FCC624?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/index.md)

### Gestión de paquetes (Linux)
[![UNIX](https://img.shields.io/badge/Gestión_de_paquetes-c044b8?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Gestion_de_paquetes.md)
<br>**Software que podemos instalar en nuestro equipo a traves de la consola**

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **su root**  | Partimos de usuario root  |
| **nano /etc/apt/sources.list**  | Fichero de listado de repositorios de donde se descarga el software en mi sistema operarivo  |
| **apt-get update**  | Actualizar los repositorios y descargarnos ultimas versiones de software que hay en nuestro repositorio de linux (legacy)  |
| **apt-get install aptitude**  | Instalación de aptitude, igual que el anterior, pero de una forma más comoda (actual)  |
| **aptitude update<br>aptitude**  | Interfaz de aptitude  |
| **aptitude search php**  | Buscar paquete de php a instalar<br> · -p >> significa que el paquete no está instalado<br>· -i >> significa que el paquete está instalado  |
| **aptitude clean**  | Borrar la cache de aptitude para volver a instalar los paquetes  |
| **aptitude help**  | Listado de comandos  |
| **aptitude install php**  | Instalación de paquete php  |
| **php -v**  | Ver versión instalada de php  |

#### Ejemplo
```bash
su root

nano /etc/apt/sources.list

apt-get update

apt-get install aptitude

aptitude update
aptitude

aptitude search php

aptitude clean

aptitude help

aptitude install php

php -v
```

[![UNIX](https://img.shields.io/badge/Gestión_de_paquetes-c044b8?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Gestion_de_paquetes.md)
