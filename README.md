# 🔍Analizador OCR Universal

## 📋 Descripción
Esta aplicación permite realizar **análisis preliminares y orientativos** de documentación histórica mediante tecnología OCR (Reconocimiento Óptico de Caracteres), proporcionando una **orientación primaria** para el abordaje sistemático y análisis académico de fuentes documentales.


## 🚀 Instalación

1. **Descargar** o clonar este repositorio.
     Para descargarlo, anda al boton "Code" y apretá "Descargar ZIP"
   <img width="456" height="384" alt="image" src="https://github.com/user-attachments/assets/8bb25729-5116-4010-ae41-31be65af0bb7" />

2. **Ejecutar** `Buscador de palabras OCR.bat`

3. **Instalar Phyton** a través de la página oficial desplegada automáticamente
   <img width="1618" height="585" alt="image" src="https://github.com/user-attachments/assets/d46232ec-8d05-4834-98f1-20063f8bcf46" />

5. **Aceptar** la instalación de las herramientas secundarias (Plopper, Tessdata, OCR, etc)

6. **Reiniciar** `Buscador de palabras OCR.bat`

7. **¡Listo!** El sistema está listo para usarse.


## 📚 Guía de Uso

1. **Seleccionar la carpeta** donde queres alojar los resultados.

2. **Cargar PDFs**: Selecciona uno o múltiples archivos PDF.

   ☝ **Nota**: Los documentos PDF a analizar son proporcionados por el usuario y pueden ubicarse en cualquier carpeta del sistema operativo.
 
3. **Vista previa**: Revisa los documentos cargados antes del análisis

4. **Configuración de Búsqueda**: Define términos específicos a buscar. Podes escribirlos manualmente o usar alguna de las plantillas con vocabularios predefinidos por área de estudio.

   📝Algunas de las plantillas proporcionadas:
      - 🏛️ **Educativa**: Términos relacionados con educación.
      - ⚡ **Alumbrado**: Infraestructura y servicios públicos de alumbrado.
      - 🏥 **Salud**: Vocabulario médico y sanitario.
      - 🏢 **Empresarial**: Términos comerciales y administrativos

    🎯 Recomendaciones para la configuración de Palabras Clave
      - **Use sinónimos** y variantes de términos importantes.
      - **Incluya plural y singular** de sustantivos relevantes.
      - **Considere variaciones históricas** del vocabulario.
      - **Pruebe con subcorpus** antes del análisis completo.

5. **Procesamiento**: Inicia el proceso de extracción de información y dejá que el sistema haga todo el trabajo.

6. **Resultados**: accedé al reporte detallado proporcionado en archivos individuales de Excel y formato texto (.txt
   📊 **Formato de los archivos Excel**:
   - **Resumen Ejecutivo** - Estadísticas de frecuencia y distribución de las palabras clave.
   - **Menciones Detalladas** - Lista completa de coincidencias encontradas.
   - **Metadatos** - Información relevante del documento del documento (fecha, páginas, etc.)
   - **Contexto Textual** - Fragmentos relevantes con contexto textual antes y después de la mención de la palabra clave.
   

## 🎯 Objetivo Principal

Facilitar el *análisis preliminar* de grandes volúmenes de documentación histórica para:
- *Identificar* documentos relevantes para investigaciones específicas.
- *Orientar* la selección de fuentes documentales. 
- *Mapear* temáticas y contenidos en corpus documentales extensos.
- *Acelerar* el proceso de revisión inicial de archivos históricos.
- *Proporcionar* una lectura distante del cuerpo total de documentos. 

## ✨ Características Principales

- 🚀 **Proyecto autónomo**: Incluye todas las herramientas necesarias (Tesseract, Poppler, etc.)

- 📦 **Instalación automática**: Configura estas herramientas sin intervención manual.  

- ✅ **Verificación**: El .bat verifica Python y dependencias automáticamente para que todo funcione correctamente.

- 🔍 **Análisis universal**: Compatible con cualquier tipo de documento PDF.
  
- 📊 **Reportes detallados**: Exportación a Excel con análisis completo. 

- 🌍 **Soporte multiidioma**: Español e inglés incluidos.

- 📋 **Plantillas temáticas**: Vocabularios predefinidos por sector.


## 🏗 Estructura del Proyecto

├── **🚀 Buscador de palabras OCR.bat**       ← INTERFAZ GRÁFICA DE USUARIO (EJECUTAR AQUÍ)

├── 🎯 gui_analizador_ocr_universal.py    ← Aplicación principal

├── 🔧 instalador_automatico.py           ← Instalador de dependencias

├── 📋 requirements.txt                   ← Dependencias Python

├── 📚 tessdata/                          ← Idiomas OCR (español/inglés)

├── 🖼 poppler/                           ← Herramientas procesamiento PDF 

├── 📋 plantillas temáticas               ← Vocabularios predefinidos

├── 📁 resultados_ocr/                    ← Carpeta de resultados

└── 📄 README.md                          ← Esta documentación


## 🤝 Contribuciones

Esta herramienta estuvo pensada para **acelerar la fase exploratoria** de la investigación histórica, permitiendo a académicos, estudiantes e investigadores **identificar rápidamente** documentos de interés dentro de colecciones documentales extensas, optimizando así el tiempo dedicado al análisis detallado de fuentes primarias. 
Sin embargo, creemos que puede llegar a ser útil para toda la comunidad académica en sus distintas facetas. Por eso, si tenes alguna sugerencia sobre como mejorar el sistema, incluir nuevas funciones o expandir su accesibilidad, podes escribir a vtaboada@mail.utdt.edu 

### ⭐ Si este proyecto te resulta útil, ¡dale una estrella en GitHub!
