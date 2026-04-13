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
