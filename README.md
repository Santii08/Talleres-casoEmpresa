# Talleres-casoEmpresa
# Sistema de Gestión de Encuestas Académicas
## Universidad de La Sabana · AREM 2025

Este repositorio documenta el análisis, modelado y solución del proceso de gestión de encuestas de percepción académica, desarrollado como proyecto real en el curso de Arquitectura Empresarial (AREM).

---

## ¿Qué problema resuelve?

Johanna, coordinadora del Área de Desarrollo Estratégico, recibía un reporte consolidado del proveedor de encuestas y debía filtrar manualmente los datos de cada programa, crear un Excel individual por director y enviarlo por correo. El proceso se repetía para cada una de las carreras de la universidad, era propenso a errores y dependía completamente de una sola persona.

---

## ¿Qué se hizo?

Se analizó el proceso completo usando marcos de Arquitectura Empresarial (TOGAF), se modelaron sus cinco vistas (negocio, datos, aplicaciones, infraestructura y seguridad), se identificaron los cuellos de botella y las brechas de cumplimiento normativo con la Ley 1581 de 2012, y se construyó una solución funcional.

---

## ¿Qué contiene el repositorio?

**Análisis y documentación:** diagramas de flujo, ERD, mapa de infraestructura, análisis STRIDE, checklist de cumplimiento normativo e integración de vistas arquitectónicas.

**Solución técnica:** dos herramientas ejecutables (.exe) y un dashboard en Power BI que reemplazan el proceso manual completamente.

---

## ¿Cómo funciona la solución?

1. El proveedor entrega dos archivos Excel con los datos de la encuesta
2. Johanna ejecuta el generador — selecciona los archivos y hace clic en Generar
3. El programa produce automáticamente los reportes por facultad con el formato correcto
4. Johanna abre Power BI, hace clic en Actualizar y el dashboard refleja el estado actual

---

## Demo de la Solución
Se deja anexo en el proyecto la demo de la solución en un .zip, el cual contiene los programas, el power bi y un manual de instrucciones.
https://drive.google.com/drive/folders/1oaXBs_xLqiCbGnRJV8utc5J6UxOT6LtC?usp=sharing

---

## Herramientas utilizadas
Draw.io · Power BI · Python · TOGAF · STRIDE · ISO 27001 · Ley 1581 de 2012
