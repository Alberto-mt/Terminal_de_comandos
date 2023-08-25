## Unix terminal
[![UNIX](https://img.shields.io/badge/UNIX_TERMINAL-FCC624?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/index.md)

### Filtros y comandos de texto (para trabajar con ficheros)
[![UNIX](https://img.shields.io/badge/Filtros_y_comandos_de_texto-44c04c?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Filtros_y_comandos_de_texto.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **sort [ubicación de fichero]**  | Ordenar las líneas de un fichero  |
| **sort -r [ubicación de fichero]**  | Ordenar las líneas de un fichero de manera inversa  |
| **tail [ubicación de fichero]**  | Sacar la cola de un archivo (10 últimas líneas)  |
| **tail -n 4 [ubicación de fichero]**  | Sacar la cola de un archivo indicando el número de líneas (4)  |
| **head [ubicación de fichero]**  | Sacar encabezado de un archivo (10 primeras líneas)  |
| **head -n 4 [ubicación de fichero]**  | Sacar encabezado de un archivo indicando el número de líneas (4)  |
| **wc [ubicación de fichero]**  | Sacar el número de líneas, bytes y palabras de un archivo  |
| **cut -c 2-7 [ubicación de fichero]**  | Sacar ciertos datos de un archivo (-c 2-7 >> carácteres del 2 al 7)  |
| **cut -d ":" -f1 [ubicación de fichero]**  | Sacar ciertos datos de un archivo por un delimitador de una columna (f1)  |
| **ls -lh \/ \| rev \| cut -d \" \" -f1 \| sort**  | Concatenar filtros (listar, dar la vuelta, cortar por un espacio en una columna y ordenar) |

#### Ejemplo
```bash
sort /etc/passwd

sort -r /etc/passwd

tail /etc/passwd

tail -n 4 /etc/passwd

head /etc/passwd

head -n 4 /etc/passwd

wc /etc/passwd

cut -c 2-7 /etc/passwd

cut -d ":" -f1 /etc/passwd

ls -lh / | rev | cut -d " " -f1 | sort
```

[![UNIX](https://img.shields.io/badge/Filtros_y_comandos_de_texto-44c04c?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Filtros_y_comandos_de_texto.md)
