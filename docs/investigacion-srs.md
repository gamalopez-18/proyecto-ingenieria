# Investigación: Especificación de Requerimientos de Software (SRS/ERS)

**Integrantes:**
* Gamaliel López Pazos
* Irving Emiliano Rivera Matus

---

## 1. ¿Qué es un SRS/ERS y qué problemas evita?
Una Especificación de Requerimientos de Software (SRS, por sus siglas en inglés, o ERS en español) es un documento técnico que describe de manera completa y detallada el comportamiento esperado de un sistema de software antes de ser desarrollado, abarcando tanto sus funciones como sus restricciones operativas (IEEE, 1998). 

Su elaboración evita problemas críticos en el desarrollo: previene malentendidos entre el cliente y los programadores, reduce el retrabajo costoso al detectar errores en etapas tempranas, evita el crecimiento descontrolado del alcance (*scope creep*) y sirve como base objetiva para validar que el producto final cumpla con lo acordado (Sommerville, 2011).

## 2. Secciones del estándar IEEE 830
El estándar IEEE 830-1998 propone una estructura dividida en tres grandes secciones principales (IEEE, 1998):
1. **Introducción:** Define el propósito del documento, el alcance del sistema (qué hará y qué no), definiciones/acrónimos (glosario), referencias y una visión general del resto del documento.
2. **Descripción general:** Presenta el contexto del producto (perspectiva), un resumen de las funciones principales, las características de los usuarios, las restricciones técnicas o legales, y los supuestos y dependencias.
3. **Requerimientos específicos:** Es el núcleo técnico del documento. Detalla los requerimientos de interfaces externas, los requerimientos funcionales (acciones del sistema), requerimientos de rendimiento, restricciones de diseño y atributos de calidad del software (disponibilidad, seguridad, mantenibilidad).

## 3. Características de un buen requerimiento
Según el estándar IEEE 830 y Pressman (2010), todo requerimiento debe ser: **correcto, no ambiguo, completo, consistente, clasificado por importancia, verificable, modificable y trazable**.
* **Ejemplo malo (ambiguo y no verificable):** *"El sistema debe ser rápido al buscar productos y tener una interfaz amigable."* (No define qué significa "rápido" ni cómo medir "amigable").
* **Ejemplo bueno (no ambiguo y verificable):** *"El sistema debe mostrar los resultados de búsqueda de productos en un tiempo máximo de 2 segundos para catálogos de hasta 10,000 registros."*

## 4. Plantillas, herramientas y elección del equipo
Para redactar y versionar un SRS existen herramientas tradicionales como Microsoft Word o Google Docs (usando plantillas IEEE 830 o Volere), herramientas especializadas de gestión de requisitos (como IBM DOORS o Jira) y enfoques modernos basados en **Markdown y Control de Versiones (Git/GitHub)**.

**Plantilla elegida y justificación:** El equipo utilizará una **plantilla basada en el estándar IEEE 830 adaptada a formato Markdown (`SRS.md`)**. Se eligió esta opción porque permite almacenar la documentación junto con el código fuente en GitHub, facilita el control de versiones (historial de cambios y autoría) y permite vincular directamente cada requerimiento funcional con los *Issues* y tableros de *GitHub Projects*.

---

## Declaración de uso de IA
Se utilizó inteligencia artificial generativa (Gemini) como apoyo para estructurar el formato Markdown del documento y sintetizar la redacción de las respuestas. Toda la información técnica fue verificada contra la norma IEEE Std 830-1998 y los libros de texto de Pressman y Sommerville citados a continuación.

## Referencias (APA 7)
* Institute of Electrical and Electronics Engineers. (1998). *IEEE Recommended Practice for Software Requirements Specifications* (IEEE Std 830-1998). IEEE Computer Society. https://doi.org/10.1109/IEEESTD.1998.88286
* Pressman, R. S. (2010). *Ingeniería del software: Un enfoque práctico* (7.ª ed.). McGraw-Hill Interamericana.
* Sommerville, I. (2011). *Ingeniería de software* (9.ª ed.). Pearson Educación.
