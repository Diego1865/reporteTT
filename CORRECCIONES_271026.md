# Correcciones de la revisión del 27 de octubre de 2026

Se revisaron las 131 inserciones, 27 eliminaciones y los dos comentarios del archivo REVISADO271026-ReporteTT_2026-B172.docx. Los cambios de texto se agrupan en 66 párrafos, incluido un párrafo de espaciado. Se trasladaron a las fuentes LaTeX conservando la estructura del proyecto; no se copiaron los saltos de línea ni las marcas de maquetación de Word.

| Observación | Aplicación |
| --- | --- |
| Desarrollar OCR y NLP | Introducción en main.tex. |
| Desarrollar API y SEP | Capitulo1.tex; se conserva API en las menciones posteriores. |
| Situar referencias al final de las descripciones del estado del arte | Capitulo1.tex. |
| Referencias [R] en la tabla comparativa | Citas mediante claves BibTeX en cada herramienta. |
| Citar los cuatro cuadrantes del modelo en espiral | Referencia de Boehm en Capitulo3/metodologia.tex. |
| Definir TT y uniformar las etapas | TT I y TT II en metodología y arquitectura. |
| Eliminar promesas de retroalimentación inmediata | Tabla de ventajas del marco teórico; se aclara también el alcance en el glosario y en la comparación. |
| Presentar las dos citas consecutivas como rango | Macro citerango, con claves bibliográficas y sin fijar números. |
| Denominar MVC patrón arquitectónico | Texto y pie de figura en Capitulo2.tex. |
| Desarrollar UX | Capitulo2.tex. |
| Referencias [R] de herramientas de software | Fuentes oficiales de React, Next.js, FastAPI, Docker, VS Code, GitHub y Compute Engine. |
| Desarrollar AI, SQL e IPN; usar SEP tras definirla | Factibilidad técnica y legal. |
| Definir RN, RF y RNF; introducir las tablas | Casos de uso y requerimientos, con referencias automáticas a las tablas. |
| Nombres de requerimientos que comienzan con Visualización | RF-08, 09, 10, 12, 13, 14, 16, 20, 21, 23 y 30, tanto en el resumen como en sus fichas. |
| Corregir Anaálisis NLP | RF-27. |
| Desarrollar REST, HTTP, DAO, MIME, JPEG, HTTPS y JSON | Capítulo 4 y sus archivos incluidos; se evita repetir la definición de API. |
| Objetos con prefijo dos puntos y base de datos rectangular | Diagrama editable en Capitulo4/secuencia.tex, incluido desde diagramas.tex. Se conserva la imagen original como antecedente. |
| Referencias [R] en alineación, tamaño, separación y uniformidad | Fuentes de OpenCV y NIST para los procedimientos de base; las normalizaciones se identifican como decisiones del proyecto. |
| Referencia [R] de conversión a la escala 0–10 | Se identifica explícitamente como transformación propuesta por el proyecto, pendiente de calibración, sin atribuirla a una fuente inexistente. |
| Referencia [R] del promedio general | Definición de media aritmética de NIST; ponderación y umbrales descritos como decisiones de diseño pendientes de validación. |
| Referencias [R] de CER y WER | Documentación de ambas métricas de Hugging Face Evaluate. |
| Referencias en el glosario | Las 40 entradas tienen citas; se aclara el alcance local y se corrigen las definiciones de bcrypt, embeddings y pangrama. |

## Ajustes derivados de comprobar las fuentes

- Google Handwriting Input se describe como antecedente retirado de Google Play, con continuidad en Gboard.
- Tesseract se describe como orientado al texto impreso, con limitaciones en manuscritos.
- Calligraphr se identifica correctamente como herramienta de creación de fuentes, sin atribuirle evaluación pedagógica no documentada.
- WriteApp conserva su lugar en el análisis, pero sus funciones no verificables se marcan ND. Para sustituir ND se necesita documentación técnica o una evaluación directa de esa plataforma.
- El rango bibliográfico sobre legibilidad cita estudios de escritura manuscrita, en lugar de referencias sobre embeddings e indicadores educativos generales.
- Las citas numéricas escritas a mano en RNF-01 y RNF-02 se sustituyen por claves BibTeX.
- Las referencias de software documentan las herramientas; no se presentan como cotizaciones de los importes estimados.
- Se actualiza la nota bibliográfica de la LFPDPPP conforme al texto consultado, sin cambiar el análisis jurídico del capítulo.

## Verificación

- No hay claves bibliográficas inexistentes, etiquetas ausentes ni archivos incluidos faltantes en la comprobación estática.
- Las 40 definiciones del glosario contienen referencias.
- No quedan marcadores [R] ni las grafías TT1, TT2 y Anaálisis NLP en las fuentes.
- La comprobación de espacios de Git no reporta errores.
- Compilación y revisión visual: en curso.
