[Volver al índice general](../README.md)

# UD1 – Análisis del entorno y detección de necesidades tecnológicas

## Índice de apartados
- [ ] **1. Análisis del sector tecnológico**


# El sector técnologico en Sevilla


Si 2023 fue el año de Málaga en los titulares, 2024-2025 está siendo el año de la consolidación de Sevilla en cifras reales. El sector vive un momento de expansión agresiva, liderado por un Sevilla TechPark (PCT Cartuja) que bate récords y un sector aeroespacial blindado.

Lo más relevante: Sevilla ha adelantado a Málaga en número de empresas tecnológicas activas (251 frente a 234 según datos de El Referente en 2025), aunque Málaga sigue ganando en facturación total por el tamaño de sus multinacionales.


![techpark](/UD1/img/ud1_1.jpg)

## Datos Clave del Ecosistema (2024-2025)


El motor principal es Sevilla TechPark (antiguo PCT Cartuja), que actúa como el pulmón económico de la ciudad.

**Facturación Récord:** La actividad económica del parque creció un 13,7% en el último año, alcanzando los 5.513 millones de euros.

**Empleo Tech:** El parque solo ya emplea a 31.667 personas (+7,2%).

**Concentración de I+D:** Sevilla concentra casi el 17% de todo el empleo dedicado a I+D de los parques tecnológicos de España.







- [ ] **2. Selección de la empresa o contexto de trabajo**



# Selección de empresa

### ProfesionalCloud

![ProfesionalCloud](/UD1/img/ud1_2.jpg)

ProfesionalCloud es una empresa que provee servicios cloud (Cloud Service Provider) y soluciones informáticas integrales para empresas. A diferencia de un servicio de hosting web básico, ellos se enfocan en la infraestructura como servicio (IaaS) y el mantenimiento corporativo.

**Cloud Computing:** Permiten a las empresas tener toda su oficina en la nube. Los empleados acceden a su escritorio, programas y archivos desde cualquier lugar.

**Servidores Virtuales (VPS):** Alquiler y gestión de servidores para alojar aplicaciones empresariales.

**Ciberseguridad y Backups:** Ofrecen copias de seguridad remotas y protección contra ataques (Ransomware), asegurando la continuidad del negocio.

**Mantenimiento Informático:** Soporte técnico tanto remoto como presencial para resolver incidencias de hardware y software.

**Telefonía IP (VoIP):** Centralitas virtuales para comunicaciones empresariales.





- [ ] **3. Identificación de necesidades tecnológicas**



# Identificición de necesidades tecnológicas

El reciento TechPark necesita urgentemente administradores de sistemas capaces de gestionar la convergencia entre las redes IT tradicionales y las nuevas redes OT (Operational Technology). Es decir, no solo gestionar ordenadores, sino administrar la red de sensores y servidores que controlarán la energía y la seguridad física del recinto.







- [ ] **4. Oportunidades y viabilidad del proyecto**



# Oportunidad y viabilidad del proyecto  



Detectamos una "brecha de modernización" en el Parque Científico y Tecnológico Cartuja. Aunque el entorno promueve la innovación, muchas empresas instaladas en edificios de la época Expo 92 o posteriores siguen operando con infraestructura "On-Premise" (servidores físicos locales) obsoleta.

Esto agilizaría problemas como el soporte eléctrico del parque y aumentaría la Integridad y Seguridad de la información utilizada por las empresas.




- [ ] **5. Obligaciones legales y normativas**



# Obligaciones legales y normativa

### Marco Normativo y Cumplimiento Legal

La migración de la infraestructura al entorno Cloud se ha diseñado cumpliendo estrictamente con la legislación vigente, garantizando la seguridad jurídica del cliente:

***Cumplimiento del RGPD (Art. 32):*** Se han seleccionado centros de datos ubicados en territorio nacional/europeo para garantizar la soberanía del dato. Se implementan medidas técnicas de seudonimización y cifrado de datos personales.

***Seguridad según el ENS:*** Dado el entorno del PCT Cartuja y la posible interconexión con la administración pública, la arquitectura de sistemas propuesta sigue los estándares del Esquema Nacional de Seguridad, asegurando la trazabilidad de accesos y la integridad de la información.

***Garantía de Disponibilidad (Business Continuity):*** Se establecen mecanismos de copia de seguridad (Backups) automatizados y redundantes para cumplir con la obligación de recuperación de datos ante desastres.



- [ ] **6. Guion inicial del proyecto**


Guion inicial del proyecto
Hoja de ruta para modernizar la infraestructura del cliente mediante una migración integral a una nube privada basada en Debian GNU/Linux.

Fase 1: Auditoría Previa
Inventario del hardware "On-Premise" obsoleto y análisis de compatibilidad de aplicaciones.

Evaluación de requisitos para la red OT (sensores) del parque.

Fase 2: Despliegue Infraestructura Debian
Provisionamiento de servidores VPS con Debian Stable para garantizar máxima estabilidad y seguridad (LTS).

Bastionado del sistema (Hardening) y configuración de redes definidas por software.

Fase 3: Migración de Servicios
Traslado de datos y aplicaciones al entorno Cloud Debian (Servidores web, Bases de datos, Samba).

Virtualización de sistemas heredados incompatibles mediante KVM sobre el host Debian.

Fase 4: Operativa y Mantenimiento
Implementación de monitorización nativa y gestión remota segura (SSH/VPN).

Automatización de copias de seguridad (Backups) y scripts de mantenimiento.




## Enlaces a recursos de la unidad

- [Documentos de la unidad](./documentos/)
- [Diagramas e imágenes](./img/)

  ## Bibliografía / Webgrafía 
- Autor1, Título del libro o artículo, Editorial/Año.
- Sitio web oficial: [Enlace](https://www.ejemplo.com)
- Tutoriales y guías recomendadas: [Enlace](https://www.ejemplo2.com)

