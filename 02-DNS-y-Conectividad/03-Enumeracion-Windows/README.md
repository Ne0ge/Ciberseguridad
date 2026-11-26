# Enumeración de Windows

## Objetivo

Identificar usuarios locales, políticas de cuentas e información relevante del sistema operativo mediante herramientas nativas de Windows.

## Herramientas utilizadas

- net user
- net accounts
- systeminfo

## Usuarios locales

### net user

Usuarios identificados:

- ADMIN
- Administrador
- Invitado
- DefaultAccount
- WDAGUtilityAccount

## Políticas de cuentas

### net accounts

Configuraciones observadas:

- Duración máxima de contraseña: 42 días
- Umbral de bloqueo: 10 intentos
- Equipo configurado como estación de trabajo

## Información del sistema

### systeminfo

Datos obtenidos:

- Sistema Operativo: Windows 11 Pro
- Arquitectura: x64
- Fabricante: GHIA
- Modelo: MINI PC
- Grupo de trabajo: WORKGROUP
- DHCP habilitado

## Aprendizajes

- Identificación de usuarios locales.
- Revisión de políticas de seguridad.
- Obtención de información del sistema operativo.
- Enumeración básica de equipos Window
