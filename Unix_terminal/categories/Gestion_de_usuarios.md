## Unix terminal
[![UNIX](https://img.shields.io/badge/UNIX_TERMINAL-FCC624?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/index.md)

### Gestión de usuarios
[![UNIX](https://img.shields.io/badge/Gestión_de_usuarios-c08a44?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Gestion_de_usuarios.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **whoami**  | Saber el tipo de usuario que somos  |
| **id**  | Información ampliada del usuario identificado actualmente  |
| **useradd -g users -d /home/[nombre usuario] -s /bin/bash -m -k -D [nombre usuario]**  | Crear un usuario nuevo<br> · -g >> grupo<br> · -d >> Directorio home del usuario<br> · -s >> Shell que va utilizar<br> · -m -k >> Crear home del usuario y archivos iniciales<br> · -D >> Default   |
| **passwd [contraseña]**  | Añadir contraseña a usuario ya creado (pide que se introduzca la contraseña dos veces, pero no se muestra) |
| **cat /etc/groups**  | Fichero con la información de grupos  |
| **cat /etc/passwd**  | Fichero con la información de usuarios creados en el sistema  |
| **cat /etc/shadow**  | Fichero con la información de usuarios y contraseñas  |
| **su**  | Identificación como administrador (pedirá credenciales de root)  |
| **su alberto**  | Identificarse como usuario (pedirá credenciales del usuario)  |

#### Ejemplo
```bash
whoami

id

useradd -g users -d /home/pepe -s /bin/bash -m -k -D pepe

passwd 111111

cat /etc/groups

cat /etc/passwd

cat /etc/shadow

su

su pepe
```

[![UNIX](https://img.shields.io/badge/Gestión_de_usuarios-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Gestion_de_usuarios.md)
