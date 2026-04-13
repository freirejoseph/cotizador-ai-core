# Configuración SSH de acceso al servidor

## Archivo local en Windows
Ruta:

`C:\Users\Usuario\.ssh\config`

## Contenido del archivo

```text
Host cotizador-server
    HostName 192.168.1.40
    User joseph
    ServerAliveInterval 60
    ServerAliveCountMax 5

## Método GitHub para el servidor

El servidor Ubuntu utiliza autenticación Git por SSH key.

### Validación
```bash
ssh -T git@github.com
