#  RPA Challenge - Generación de Contratos Automática

Este proyecto es una solución de automatización desarrollada en **UiPath Studio** que resuelve el desafío de procesar datos dinámicos y generar documentación personalizada en formato PDF.

##  Funcionalidades
- **Lectura de Datos:** Extrae información de un archivo Excel (`challenge.xlsx`).
- **Procesamiento de Plantillas:** Utiliza un documento de Word como base (`plantilla_contrato.docx`).
- **Inyección de Datos:** Reemplaza etiquetas dinámicas como `[NOMBRE]` y `[CARGO]` mediante lógica de automatización.
- **Exportación masiva:** Genera archivos PDF individuales para cada registro en una carpeta organizada.

##  Detalles Técnicos
- **Rutas Relativas:** El proyecto es portable; no depende de rutas fijas, funcionando al ser clonado en cualquier equipo.
- **Gestión de Plantilla:** Se configuró el "Ámbito de aplicación de Word" sin guardado automático para mantener la integridad de la plantilla original.
- **Formato de Salida:** Conversión automática a PDF con nomenclatura personalizada.

##  Estructura del Proyecto
- `Main.xaml`: Lógica principal del robot.
- `challenge.xlsx`: Fuente de datos de los usuarios.
- `plantilla_contrato.docx`: Formato base para los contratos.
- `Contratos/`: Carpeta de almacenamiento de resultados.

  ###  Requisitos previos
Para ejecutar esta automatización, se requiere:
- **UiPath Studio** (Community o Enterprise Edition).
- **Microsoft Office** (Word y Excel) instalado localmente y con licencia activa.
- Extensión de **UiPath para Word y Excel** habilitada en Studio.

---
*Proyecto desarrollado como parte de mi portafolio de RPA.*
