# Nota de Ingreso Neonatología HSVP

## Sistema de Historia Clínica de Ingreso — Servicio de Neonatología  
**Hospital San Vicente de Paúl (HSVP) — Ibarra, Ecuador**

---

## ⚠️ Propiedad Intelectual

Este software es propiedad intelectual exclusiva de su autor, **Dr. Carlos Culki**, médico residente del Servicio de Neonatología del Hospital San Vicente de Paúl.

- **Uso autorizado exclusivamente** para el personal médico del Servicio de Neonatología del Hospital San Vicente de Paúl.
- **Queda prohibida** su reproducción, distribución, modificación o uso en otros servicios o instituciones sin autorización expresa y por escrito del autor.
- Cualquier uso no autorizado constituye una infracción a los derechos de propiedad intelectual conforme a la legislación ecuatoriana vigente (Ley de Propiedad Intelectual y normativa del SENADI).

---

## 📋 Descripción

Aplicación web de una sola página (HTML/CSS/JavaScript puro, sin dependencias externas ni servidor) para optimizar el registro de ingreso de pacientes neonatales.

### Funcionalidades principales

- Registro completo de datos de filiación (RN, madre, padre)
- Cálculo automático de edad al ingreso y edad gestacional por FUM con clasificación
- Secciones condicionales según origen del paciente (Centro Obstétrico, Alojamiento, Emergencia, Referencia)
- Escalas clínicas automáticas: APGAR (1'/5'/10'), Score de Downes con interpretación, Capurro
- Examen físico regional con valores predeterminados editables
- Búsqueda y registro de diagnósticos CIE-10 con aprendizaje automático
- Plan de manejo completo en formato ADCAVANDIMELCO
- Cálculo automático de hidratación IV, VIG (mg/kg/min) con semáforo, descuento de leche y medicamentos
- Tabla de medicamentos con dosis calculada por peso (mg/dosis, ml/dosis, días de ATB)
- Exportación a **Word (.docx) en 2 columnas** — compatible con hoja de evolución MSP
- **Marca de agua invisible** en cada documento (metadata, ID único de trazabilidad, comentario XML)
- Registro automático de pacientes exportable a CSV
- Auto-guardado continuo en localStorage
- Disclaimer obligatorio de uso responsable
- Funciona completamente **offline** — sin internet, sin servidor, sin instalación

---

## 🔒 Seguridad y Trazabilidad

Cada documento Word generado contiene:
- **ID único** formato `HSVP-NEO-YYYYMMDD-XXXX` registrado en el log de la app
- **Metadata de autor** embebida (visible en Propiedades del archivo)
- **Comentario XML oculto** con médico, HCU, fecha y hora exacta
- **Log de uso** exportable a CSV con todos los documentos generados

---

## 🚀 Uso

1. Abrir el enlace en cualquier navegador moderno (Chrome, Firefox, Safari, Edge)
2. No requiere instalación ni conexión a internet

---

## 📁 Versiones

| Versión | Fecha | Cambios principales |
|---------|-------|---------------------|
| v30 | 2025-04 | Marca de agua invisible, trazabilidad, Word 2 columnas offline |
| v29 | 2025-04 | Exportación Word 2 columnas sin dependencias |
| v28 | 2025-04 | Corrección disclaimer, funciones restauradas |
| v27 | 2025-04 | Registro de pacientes, exportación CSV |
| v21 | 2024-12 | Versión inicial |

---

## ⚖️ Licencia

**© 2024-2025 Dr. Carlos Culki — Todos los derechos reservados.**

Propiedad intelectual exclusiva del autor. Registro pendiente ante SENADI (Servicio Nacional de Derechos Intelectuales — Ecuador).

Queda prohibida la reproducción, distribución o uso de este software fuera del ámbito autorizado sin el consentimiento expreso y por escrito del autor.
