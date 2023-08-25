## Unix terminal
[![UNIX](https://img.shields.io/badge/UNIX_TERMINAL-FCC624?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/index.md)

### Procesos (Linux y Mac)
[![UNIX](https://img.shields.io/badge/Procesos-c08a44?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Procesos.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **whatis [comando]**  | Saber que hace un comando  |
| **ps -ef**  | Procesos que tengo abiertos actualmente  |
| **pstree -Agu**  | Arbol de procesos  |
| **kill [PID(process id)]**  | Cerrar el bash de una sesión (su pepe), indicando el PID (process id)  |
| **killall (aplicación)**  | Cerrar todos los procesos de una aplicación  |
| **jobs**  | Procesos que se están ejecutando en segundo plano  |
| **top**  | Monitoreo de los procesos en tiempo real  |

#### Ejemplo
```bash
whatis ps
# ps >> reporta una imagen de los procesos actuales

ps -ef

pstree -Agu

kill 1907

killall firefox

jobs

top
```

[![UNIX](https://img.shields.io/badge/Procesos-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Procesos.md)
