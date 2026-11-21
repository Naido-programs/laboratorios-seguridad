# Prácticas de Seguridad Informática y Administración de Sistemas

Documentación paso a paso de las prácticas realizadas durante la
Certificación Profesional en Seguridad Informática (80 h prácticas, 2025).
Cada práctica incluye el procedimiento, capturas de pantalla y las
incidencias encontradas durante el proceso.

> **Nota:** todas las pruebas se realizaron en un laboratorio aislado
> con máquinas virtuales (VirtualBox), sobre sistemas vulnerables a
> propósito (Metasploitable 2 y 3). Las credenciales que aparecen son
> las que esos sistemas traen por defecto. No se atacó ningún sistema real.

## Tecnologías y herramientas

| Área | Herramientas |
|---|---|
| Administración de sistemas | Windows Server, Active Directory, GPO, DHCP, NAT/enrutamiento, recursos compartidos SMB |
| Redes | TCP/IP, Nmap, Angry IP Scanner |
| Seguridad ofensiva (laboratorio) | Kali Linux, Metasploit, Armitage, fuerza bruta de credenciales |
| Virtualización | VirtualBox |
| Sistemas operativos | Windows Server, Windows 10/11, Kali Linux |

## Índice de prácticas

### Administración de Windows Server
1. [Instalación y configuración inicial](practicas/instalar-windows-server/README.md)
   Instalación, nombre del equipo e IP fija.
2. [Active Directory, DHCP y NAT](practicas/directorio-activo-dhcp-nat-windows-server/README.md)
   Creación del dominio, unidades organizativas, usuarios, ámbito DHCP,
   unión de clientes al dominio y salida a Internet por NAT.
3. [Recursos compartidos y carpetas privadas](practicas/compartir-carpetas-en-windows-server/README.md)
   Disco adicional, carpeta pública y carpeta privada por usuario con permisos.
4. [Directivas de grupo (GPO)](practicas/directivas-de-grupo-windows-server/README.md)
   Restricción del Panel de control, símbolo del sistema y otras opciones.

### Redes y seguridad
5. [Escaneo de equipos y puertos](practicas/practica-angry-ip-scanner/README.md)
   Angry IP Scanner y fundamentos del escaneo de puertos.
6. [Escaneo de red con Nmap y fuerza bruta a FTP/SSH](practicas/uso-de-nmap-y-ataque-fuerza-bruta/README.md)
   Descubrimiento de hosts y auditoría de credenciales débiles.
7. [Auditoría de Metasploitable 3](practicas/metasploitable-3-windows-server/README.md)
   Enumeración de puertos y usuarios, acceso por SSH y control del firewall.
8. [Explotación con Armitage en Kali Linux](practicas/uso-de-armitage/README.m)
   Detección de vulnerabilidades y acceso a máquinas vulnerables.

## Entorno de laboratorio
- Anfitrión: [Ubuntu, Windows]
- Virtualización: VirtualBox con red interna y red NAT
- Máquinas: Windows Server, Windows (cliente), Kali Linux,
  Metasploitable 2 y 3

## Contacto
www.linkedin.com/in/arnaldo-cabeza-6564ab292 · naido.programs@gmail.com
