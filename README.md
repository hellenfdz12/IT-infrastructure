# Design and implementation of an IT Software Designed Data Center architecture, infrastructure and services

This project involves emulating setting up two geographically different sites with different ESXi hosts. Implementing DHCP, DNS, FreeIPA, and service monitoring for the two separate sites and establishing a secure connection between them using IPSec. DNS services will be accessible to users from both sites, and DHCP is used for automatic IP addressing on the LAN. FreeIPA is used for managing user information. The project includes online learning (Moodle), online storage (Nextcloud), and online support (osTicket) services. Monitoring is done for DNS, FreeIPA, online services, and the database using php server monitor. Security measures, such as traffic control, are implemented using Iptables.

# Diseño e Implementación de una Arquitectura, Infraestructura y Servicios de Centro de Datos Definido por Software (SDDC)

El proyecto consiste en simular la implementación de dos sitios geográficamente separados, cada uno con diferentes hosts ESXi. Se implementaron servicios de DHCP, DNS, LDAP (FreeIPA) y monitoreo de servicios para ambos sitios, además de establecer una conexión segura entre ellos mediante IPSec.

Los servicios de DNS son accesibles para los usuarios de ambos sitios, mientras que DHCP se utiliza para la asignación automática de direcciones IP dentro de las redes locales (LAN). FreeIPA se implementó para la gestión centralizada de usuarios, autenticación y políticas de acceso.

El proyecto también incluye la implementación de servicios en línea como:

Moodle para aprendizaje virtual.
Nextcloud para almacenamiento y gestión de archivos en la nube.
osTicket para soporte y gestión de solicitudes de servicio.

El monitoreo de la infraestructura se realiza mediante PHP Server Monitor, supervisando la disponibilidad y el rendimiento de los servicios DNS, FreeIPA, las aplicaciones en línea y la base de datos.

Asimismo, se implementaron medidas de seguridad para la protección de la infraestructura y el control del tráfico de red mediante iptables, garantizando comunicaciones seguras y una adecuada segmentación de los servicios entre ambos sitios.


