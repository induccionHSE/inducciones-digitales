# Inducciones Digitales HSEQ
 
Sistema de gestión del ciclo completo de inducciones corporativas: presentación interactiva en HTML, evaluación de conocimientos, generación automática de certificado y control de vigencia por cédula.
 
Reemplaza las presentaciones en PowerPoint estáticas por módulos interactivos con evidencia documental automatizada.
 
> **v1.0 — Producción**
 
---
 
## Funcionalidades
 
| Módulo | Descripción |
|---|---|
| **Inducción HTML interactiva** | Presentación migrada de PPT a HTML con mayor visualización e interacción |
| **Evaluación integrada** | Botón al final de la inducción que abre evaluación en Google Forms |
| **Certificado automático** | Generación y envío de certificado PDF al aprobar la evaluación |
| **Guardado en Drive** | Certificado almacenado automáticamente en carpeta organizada por trabajador |
| **Consulta de vigencia** | Sistema de búsqueda por cédula que rastrea respuestas y envía reporte de vigencia al correo |
 
---
 
## Flujo
 
```
Trabajador accede a inducción HTML
        │
        ▼
Completa evaluación (Google Forms)
        │
        ▼
Apps Script evalúa resultado
   ├── Aprobado → genera certificado PDF
   │              → envía al correo
   │              → guarda en Drive
   └── No aprobado → notifica para repetir
        │
        ▼
Sistema de vigencia (búsqueda por cédula)
   └── Consulta historial → envía reporte al correo
```
 
---
 
## Stack
 
- **Inducción:** HTML + CSS + JavaScript (single file)
- **Evaluación:** Google Forms
- **Backend:** Google Apps Script
- **Certificados:** PDF generado en GAS
- **Almacenamiento:** Google Drive
- **Vigencia:** Apps Script + Gmail
 
---
 
## Contexto normativo
 
- **Decreto 1072 de 2015** — Inducción y reinducción obligatoria
- **Resolución 0312 de 2019** — Evidencia documental de capacitaciones
- **ISO 45001:2018** — Competencia y toma de conciencia
 
---
 
## Autor
 
**Holman Moreno** — HSEQ Coordinator · Petroleum Engineer
📧 holman3001@gmail.com
🔗 [github.com/induccionhse](https://github.com/induccionhse)
 
