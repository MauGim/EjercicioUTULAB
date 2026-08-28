# S.I.G.S.M. - Sistema Informático de Gestión de Servicios Médicos 🚑

**Proyecto de Egreso - BT Tecnologías de la Información - 2026** *I.S.B.O. - Polo Educativo Tecnológico Vista Linda - ITS Paysandú - ESC Villa Muñoz*

S.I.G.S.M. es una plataforma web orientada a optimizar la logística de traslados médicos, la gestión de la documentación mediante códigos QR (estáticos y dinámicos) y la recopilación de métricas de satisfacción de los pacientes. 

## 🏗️ Arquitectura del Sistema

El proyecto está estructurado bajo el patrón de diseño **MVC (Modelo - Vista - Controlador)**, organizado por dominios de negocio (Módulos) en lugar de roles de usuario, para garantizar la escalabilidad y la separación de responsabilidades.

* **Módulo Ambulancias y Traslados:** Gestiona las rutas, estados de conducción de los choferes y la coordinación activa por parte de la Unidad de Enlace.
* **Módulo Documentación y Encuestas:** Gestiona el directorio de protocolos médicos (QR Estáticos) y el generador de encuestas/formularios para pacientes (QR Dinámicos).
* **Servicios Comunes:** Contiene la lógica transversal del sistema, como la autenticación, seguridad, conexión a bases de datos y la plantilla de diseño base (Layout).