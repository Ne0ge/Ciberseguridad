# DNS y Conectividad

## Objetivo

Comprender cómo funciona la resolución de nombres y el recorrido de los paquetes a través de Internet.

## Herramientas utilizadas

- nslookup
- tracert
- arp -a
- route print

## Resolución DNS

### nslookup google.com

Hallazgos:

- DNS local identificado.
- Resolución correcta del dominio.
- Obtención de dirección IPv4 e IPv6.

### nslookup github.com

Hallazgos:

- Resolución correcta del dominio.
- Obtención de dirección IP pública.

### nslookup microsoft.com

Hallazgos:

- Resolución correcta del dominio.
- Obtención de dirección IP pública.

## Traceroute

### tracert google.com

Hallazgos:

- Primer salto identificado como gateway local.
- Tráfico pasando por múltiples routers.
- Llegada exitosa al servidor de Google.

## Tabla ARP

### arp -a

Hallazgos:

- Identificación de dispositivos dentro de la red local.
- Relación entre direcciones IP y direcciones MAC.

## Tabla de Rutas

### route print

Hallazgos:

- Gateway predeterminado: 192.168.1.1
- Ruta por defecto configurada correctamente.

## Aprendizajes

- Funcionamiento de DNS.
- Resolución de nombres.
- Comunicación entre dispositivos de red.
- Uso de ARP.
- Interpretación de tablas de enrutamiento.
