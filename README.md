# Simulación de Red Empresarial en Cisco Packet Tracer

Este proyecto simula la configuración de una red empresarial utilizando **Cisco Packet Tracer**. La red consta de varias escuelas interconectadas a través de un proveedor de servicios, implementando diversos protocolos y tecnologías de redes. La configuración abarca desde el diseño lógico hasta la implementación de configuraciones avanzadas de red, incluyendo seguridad y optimización.

## Tecnologías y Configuraciones Implementadas

- **VLANs**: Se crea una segmentación de la red utilizando VLANs para diferentes grupos de usuarios (Personal, Alumnos, Wifi-Invitados, y Administración).
- **Enrutamiento Dinámico (RIPv2)**: Implementación de un protocolo de enrutamiento dinámico para interconectar las redes de diferentes ubicaciones.
- **DHCP**: Configuración de servidores DHCP para asignar direcciones IP dinámicas a los dispositivos de la red interna.
- **NAT/PAT**: Configuración de traducción de direcciones de red para permitir que múltiples dispositivos internos compartan una única IP pública y configurar accesos externos.
- **ACLs (Listas de Control de Acceso)**: Implementación de políticas de seguridad para controlar el acceso entre redes internas, externas y la DMZ.
- **Seguridad de Puertos**: Configuración de seguridad en los switches para proteger los puertos de acceso contra intentos no autorizados.

## Archivos del Proyecto

- **`DiseñoDeRed.pkt`**: Archivo de Cisco Packet Tracer que contiene la configuración completa de la red.
- **`Memoria_Configuracion_Redes.pdf`**: Documentación con la descripción paso a paso del proceso de configuración y las justificaciones de las decisiones tomadas.

## Requisitos

- **Cisco Packet Tracer**: Herramienta utilizada para la simulación y configuración de redes.
- **Conocimiento en configuración de dispositivos mediante Cisco IOS**: Se ha trabajado con comandos CLI para la configuración de routers, switches y otros dispositivos.
- **Conocimientos sobre enrutamiento, VLANs, DHCP, NAT y seguridad en redes**.

## ¿Cómo usar este repositorio?

1. **Descargar el archivo `.pkt`** y abrirlo en **Cisco Packet Tracer**.
2. **Revisar la configuración**: Explorar las configuraciones de los routers, switches y demás dispositivos de red.
3. **Pruebas de conectividad**: Verificar que todos los dispositivos en la red estén correctamente conectados y puedan comunicarse entre sí, utilizando las pruebas de **ping** y **tracert**.

## Pasos de Implementación

1. **Diseño de la Red**: Se creó un esquema de red lógica que conecta tres escuelas a un proveedor de Internet, configurando diversos dispositivos para cumplir con los requisitos de conectividad y seguridad.
2. **Configuraciones de Dispositivos**: Los routers y switches fueron configurados para habilitar el enrutamiento, la asignación de IPs mediante DHCP, y el uso de VLANs para segmentación de la red.
3. **Configuración de Seguridad**: Se implementaron listas de control de acceso (ACLs) para asegurar la red interna y permitir solo el acceso necesario a los recursos externos.

---

Este repositorio muestra cómo diseñé e implementé una red empresarial completa utilizando diversas tecnologías y configuraciones avanzadas. Es un claro ejemplo de mi experiencia práctica en la creación y gestión de redes, y de cómo continúo desarrollando mis habilidades y demostrando mi capacidad como administradora de sistemas
