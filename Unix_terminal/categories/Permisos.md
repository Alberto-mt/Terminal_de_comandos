## Unix terminal
[![UNIX](https://img.shields.io/badge/UNIX_TERMINAL-FCC624?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/index.md)

### Permisos
[![UNIX](https://img.shields.io/badge/Permisos-44c04c?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Permisos.md)

#### Listado de permisos
| Propietario  | Demás usuarios  | Demás grupos  |
|---|---|---|
| **drwx**  | **rwx**  | **rwx**  |
| **-rw-**  | **r--**  | **r--**  |

| Letra  | Descripción  |
|:-:|---|
| **d**  | Directorio  |
| **r**  | Lectura  |
| **w**  | Escritura  |
| **x**  | Ejecución  |
| **-**  | Sín designación  |

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **ls -lh**  | Listado de permisos de archivo  |
| **chmod 777 documento:txt**  | Dar todos los permisos a todos  |
| **chmod 700 documento:txt**  | Dar todos los permisos unicamente al propietario  |
| **chown [nombre de usuario]:users documento.txt**  | Cambiar dueño de archivo siendo root (usuario:grupo)  |
| **groups [nombre de usuario]**  | Saber a que grupo pertenece un usuario  |

#### Tipos de permiso
| Tipo  | Descripción  |
|:-:|---|
| **000**  | Sín permisos  |
| **100**  | Sólo permisos de ejecución  |
| **200**  | Sólo permisos de escritura  |
| **400**  | Sólo permisos de lectura  |
| **600**  | Permisos de lectura y escritura  |
| **700**  | Todos los permisos  |

#### Ejemplo
```bash
chmod 777 documento:txt
ls -lh
-rwxrwxrwx

chmod 700 documento:txt
ls -lh
-rwx------

chown pepe:users documento.txt
ls -lh

groups pepe
ls -lh
```

[![UNIX](https://img.shields.io/badge/Permisos-44c04c?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Permisos.md)
