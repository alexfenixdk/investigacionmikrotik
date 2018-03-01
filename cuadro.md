## ¿Qué es Mikrotik RouterOS?
MilkroTik RouterOS es un sistema operativo basado en el kernel de Linux 2.6 usado en el ardware de los Microtik RouterBOARD que es la división de hardware de la marca Mikrotik. Se caracteriza por poseer su propio S.O de fácil configuración. Estos dispositivos poseen la ventaja de tener una relación costo /beneficio muy alta.
## Configuraciones de los equipos con RouterOS
RouterOS soporta varios métodos de configuración como son:
-   Acceso local vía teclado y monitor
-   Consola serial con una terminal
-   Acceso vía Telnet y SSH vía una red
-   Una interfaz gráfica llamada WinBox
-   Una API para el desarrollo de aplicaciones propias para la configuración
-   En caso de no contar con acceso local y existe un problema con las direcciones IP RouterOS soporta una conexión basada en direcciones MAC usando las herramientas customizadas Mac-Telnet y herramientas de Winbox

A Partir de su versión RouterOS v4 agrega el lenguaje de Scripting Lua, que expande las posibilidades para programar y automatizar el sistema.

Vamos a ver ahora todos los features que nos brinda RouterOS, ya sea que lo usemos en un RouterBoard o en una PC.

Firewall

El firewall integrado implementa el filtrado de paquetes y provee funciones de seguridad que son usadas para el manejo del flujo de datos desde y hacia el router. Junto con el NAT, previene el acceso no autorizado a una red conectada directamente. Puede filtrar por direcciones IP, tuerto TCP/UDP, rango de puertos, protocolos, entre otros parámetros. Soporta además lista de direcciones estáticas y dinámicas y puede interceptar paquetes con un patrón definido. Cuenta además con soporte para IPv6.

Routing

RouterOS soporta rutas estáticas y varios protocolos de rutas dinámicas.

-   Para IPv4 soporta RIP v1 y v2, OSPF v2, BGP v4
-   Para IPv6 soporta RIPng, OSPFV v3 y BGP

También soporta VRF, políticas basadas en rutas, rutas basadas en interfaz y ECMP. Se puede utilizar el Firewall para marcar los paquetes que lleguen desde una conexión determinada y que estos salgan por un proveedor distinto.

MPLS

MPLS (Multiprotocol Label Switching), puede ser utilizado para reemplazar los paquetes IP salientes, la decisión del reenvío ya no se realiza en base al header IP o tabla de enrutamiento, sino en etiquetas adjuntadas al paquete. Este acercamiento acelera el reenvío del paquete porque la búsqueda del destino es más simple que la búsqueda del enrutamiento. La Eficiencia en el proceso de reenvío es el mayor beneficio de MPLS.

Algunos de los features de MPLS soportados son:

-   Enlazado de etiquetas estáticas para IPv4
-   Protocolo de distribución de etiquetas para IPv4
-   Túneles RSVP
-   Descubrimiento automático y basado en la señalización VPLS MP-BGP
-   MPLS IP VPN basado en MP-BGP

VPN

RouterOS soporta diversos métodos de conexión VPN para establecer una conexión segura sobre redes abiertas o internet. Estos métodos son:

-   IPSec
-   Túneles de punto a punto (OpenVPN, PPTP, PPPoE, L2TP)
-   Features avanzados PPP (MLPPP, BCP)
-   Túneles simples (IPIP, EoIP)
-   Soporte a túneles 6 a 4 (IPv6 sobre IPv4)
-   VLAN
-   VPN basado en MPLS

Nos permite interconectar de forma segura varias redes permitiéndonos interconectar varias localidades, usar los recursos de la organización mientras nos movilizamos y aumentar la seguridad de nuestras conexiones inalámbricas.

Conexiones inalámbricas

Las siguientes son algunas de las tecnologías wireless soportadas:

-   Punto de acceso y cliente inalámbrico IEEE802.11a/b/g/n
-   Protocolos propietarios Nstreme y Nstreme2
-   Sondeo de clientes
-   RTS/CTS
-   Sistema de distribución inalámbrica
-   Punto de acceso virtual
-   Encriptación WEP, WPA, WPA2
-   Lista de control de acceso
-   WMM
-   Protocolo de ruteo inalámbrico MME
-   Entre otros

Los protocolos Nstreme le permiten a RouterOS extender el alcance y la velocidad de la conexión inalámbrica cuando se utiliza los routers de Mikrotik en cada extremo. Soporta además NStreme dual que permite utilizar dos antenas en cada extremo, una para recibir y otra para enviar.

Hotspot

La puerta de enlace de Mikrotik Hotspot permite crear una red de acceso público para usuarios alámbricos e inalámbricos. Al usuario le será presentada una pantalla de login cuando accede al navegador web. Una vez provee credenciales validos se le dará acceso a internet. No es necesaria ninguna instalación de un software, el hotspot dirigirá cualquier conexión al formulario de login. Podemos administrar además las conexiones de los usuarios, uso de ancho de banda, tiempo de conexión y más.

Hotspot soporta autenticación standard de servidores RADIUS o el administrador de usuarios integrados que nos permite una administración centralizada de todos los usuarios en nuestra red.

Web Proxy

RouterOS cuenta con un servidor proxy para el almacenamiento en cache de recursos en la web, aumentando la velocidad de acceso entregando al cliente archivos en cache a la velocidad interna de la red. RouterOS provee las siguientes características de un servidor proxy:

-   Proxy HTTP regular
-   Proxy transparente
-   Lista de acceso por fuente, destino, URL o método solicitado
-   Almacenamiento del cache en Discos externos
-   Soporte a proxy SOCKS
-   Lista de acceso cache para especificar el recursos deben ser accedidos directamente y cuales vía otro servidor
-   Entre otros.

Finalmente RouterOS nos provee una serie de herramientas para administrar nuestra red y para optimizar las tareas. Algunas de estas son:

-   Prueba de ancho de banda
-   SSH
-   Herramientas para el envio de Email y SMS
-   Tabla de conexiones activas
-   Servidor TFTP
-   Servidor NTP
-   SNMP
-   RADIUS
-   Entre otros.

RouterOS le agrega diversas funcionalidades a los mismo routers de Mikrotik como a cualquier PC que pudiéramos tener por ahí sin uso y, que con este sistema operativo le podamos implementar alguna función. Y hablando directamente de los RouterBoards de Mikrotik, estos han mostrado ser eficientes y robustos en un ambiente crítico de producción.
## Cuadro Comparativo de equipos Mikrotik

| Nombre         | Características               |Precio                         |
|----------------|-------------------------------|-----------------------------|
|hEX PoE lite  ![](https://c.76.my/Malaysia/rb750upr2-mikrotik-soho-router-5-port-hex-poe-lite-rb750up-24v-passive-sublimegroup-1605-22-SublimeGroup@3.jpg)  |`'5xEthernet con salida PoE para cuatro puertos, USB, CPU de 650MHz, 64MB de RAM, RouterOS L4'`            |'_$ 59.95 USD_'            |
|PowerBox   ![](https://img.routerboard.com/mimg/1004_hi_res.png)     |`"CPU de 650MHz, 64MB de RAM, 5xEthernet con salida PoE para cuatro puertos, RouterOS L4, estuche para exteriores, fuente de alimentación"`            |"_$ 69.00 USD_"            |
|RB2011iLS-IN     ![](https://img.routerboard.com/mimg/1106_hi_res.png)  |`Carcasa metálica de escritorio, 5xEthernet, 5xGigabit Ethernet, jaula SFP, PoE out en el puerto 10, CPU 600MHz, 64MB RAM, RouterOS L4`| _$ 109.00 USD_|
|RB1100AHx4   ![](https://www.gowifi.co.nz/images/stories/virtuemart/product/RB1100AHx4.jpg)   |`Potente enrutador de montaje en rack de 1U con 13 puertos Gigabit Ethernet`| _$ 299.00 USD_|
|CCR1016-12G  ![](https://img.routerboard.com/mimg/1306_hi_res.png)    |`1U rackmount, 12x Gigabit Ethernet, LCD, 16 núcleos x CPU de 1.2GHz, 2GB de RAM, 17.8mpps fastpath, Hasta 12Gbit / s de rendimiento, RouterOS L6`| _$ 645.00 USD_|
|CCR1036-12G-4S  ![](https://cdn3.volusion.com/grf3j.jp4es/v/vspfiles/photos/CCR1036-12G-4S-EM-2.jpg) |`1U rackmount, 12x Gigabit Ethernet, 4xSFP jaulas, LCD, 36 núcleos x CPU de 1.2GHz, 4GB de RAM, 24 mpps fastpath, Hasta 16 Gbit / s de rendimiento, RouterOS L6`| _$ 995.00 USD_|
|CCR1036-8G-2S + EM ![](http://vesuviustreamline.com/userfiles/productlargeimages/product_1429.jpg) |`1U rackmount, 8x Gigabit Ethernet, 2xSFP + jaulas, LCD, 36 núcleos x CPU de 1.2GHz, 16GB de RAM, 41.5mpps fastpath, Hasta 28Gbit / s de rendimiento, RouterOS L6`| _$ 1295.00 USD_|



