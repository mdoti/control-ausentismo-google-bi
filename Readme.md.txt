📊 Sistema de Monitoreo de Capital Humano & Ausentismo
Solución de Business Intelligence: Google Sheets + Google Calendar API
📌 Escenario y Problemática (El "Dolor")
En un entorno administrativo con un volumen considerable de funcionarios, la gestión del ausentismo se realizaba de forma centralizada en una planilla de cálculo estática.

Desafío: La falta de visibilidad en tiempo real dificultaba la planificación de coberturas inmediatas.

Limitación: Los supervisores de área no tenían acceso ágil a la información desde dispositivos móviles, lo que generaba cuellos de botella en la toma de decisiones operativa.

💡 La Solución Implementada
Diseñé un flujo de datos automatizado que actúa como puente entre el registro administrativo y la operativa de campo.

Capa de Datos (Back-end): Una estructura de Google Sheets optimizada con validación de datos para categorizar motivos de inasistencia (médica, licencia, artículo, etc.).

Capa de Automatización: Implementación de Google Apps Script (o funciones de sincronización) para reflejar automáticamente los registros en un Calendario Compartido de Google.

Capa de Visualización (Front-end): * PC: Tablero de control para auditoría y reportes mensuales.

Mobile-First: Disponibilidad de la información en Google Calendar para todos los jefes de sector, permitiendo ver quién falta y por qué desde su celular en segundos.

🚀 Impacto en el Negocio
Reducción del tiempo de respuesta: Eliminación de llamadas y consultas manuales para verificar dotación de personal.

Planificación Proactiva: Mejora en la asignación de reemplazos y turnos.

Transparencia: Registro histórico auditable para liquidación de haberes y control de gestión.