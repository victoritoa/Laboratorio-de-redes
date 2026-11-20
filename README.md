Redes & Seguridad — Mi cuaderno de laboratorio

Repositorio personal donde voy documentando todo lo que aprendo sobre redes, cortafuegos y ciberseguridad ofensiva/defensiva. Es un "pupurrí" en constante crecimiento: apuntes, laboratorios prácticos, notas de fabricantes y writeups propios.

Estado Labs

📚 Contenido
El repositorio se organiza en módulos independientes. Cada carpeta contiene teoría, comandos, ejercicios y sus propias notas.

├── 01-fundamentos-redes/        # TCP/IP, modelo OSI, subnetting, DNS, DHCP...
├── 02-cortafuegos/              # iptables, nftables, pfSense/OPNsense...
├── 03-fabricantes/              # Notas de Palo Alto, Fortinet, Cisco...
│   └── palo-alto/
├── 04-laboratorios/             # Labs prácticos (HTB, TryHackMe, propios)
├── 05-certificaciones/          # Preparación OSCP y otras certificaciones
└── recursos/                    # Cheatsheets, topologías, plantillas de lab

La estructura irá evolucionando sobre la marcha. Lo que ves arriba es la hoja de ruta inicial.

Temas planeados

1. Fundamentos de redes
 Modelo OSI vs TCP/IP
 Encapsulación y cabeceras
 Subnetting y VLSM
 DNS, DHCP, ARP
 Routing básico (estático, RIP, OSPF)
 Análisis de tráfico con Wireshark

3. Cortafuegos
   
 Conceptos: reglas, estados, zonas, NAT
 iptables — sintaxis y prácticas
 nftables — el sustituto moderno
 pfSense / OPNsense — laboratorio virtual
 UFW y firewalld

5. Fabricantes (mundo enterprise)
   
 Palo Alto Networks
Arquitectura PAN-OS
Security Policy / Nat rules
App-ID, User-ID, Content-ID
Zones e interfaces
 Fortinet FortiGate (por definir)
 Checkpoint (por definir)
 
7. Laboratorios
 Writeups x
 Labs montados en mi propio entorno (VirtualBox / VMware / Docker)
 Escenarios de ataque y defensa combinados

9. Certificaciones
 Preparación OSCP — metodología, notas, herramientas
 (Otras por determinar: CCNA, PNPT, …)

🛠️ Herramientas que uso en los labs

Categoría	Herramientas
Análisis de red	Wireshark, tcpdump, netcat
Recon	nmap, dig, whois
Firewalls	iptables, nftables, pfSense, PAN-OS
Pentesting	Kali Linux, Metasploit, Burp Suite
Virtualización	VirtualBox, VMware, GNS3/EVE-NG

Notas importantes

Todo lo publicado aquí son apuntes de estudio de laboratorios legales (máquinas propia, HTB, THM o entornos controlados). Nada aquí está pensado para usarse contra sistemas sin autorización.
Los writeups de plataformas como HackTheBox siguen sus políticas: no publico flags ni soluciones completas de máquinas activas.

🤝 Contribuciones
Es un repositorio personal, pero si pasas por aquí y ves un error, una forma mejor de montar un lab o un tema que debería cubrir, los PR y las issues son bienvenidos.

📌 Por hacer / backlog

 Montar laboratorio de red virtualizado completo (router + fw + clientes)
 Lab de segmentación con VLANs
 Primer lab dedicado a Palo Alto (eval / versión de laboratorio)
 Cheatsheet definitiva de nftables
 Plantilla estándar para writeups de HTB
 
Última actualización: nov. 2026 — proyecto vivo, vuelve a mirar de vez en cuando.
