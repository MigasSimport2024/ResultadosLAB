# 🧬 Hemograma San Ramón - Web App

Sistema de gestión y generación de hemogramas para el **Laboratorio Clínico Veterinario San Ramón**.  
Esta aplicación permite registrar resultados de pacientes, generar reportes en PDF profesionales de forma instantánea, mantener un historial local y facilitar el envío de resultados vía WhatsApp.

---

## 🚀 Características principales
- **Generación de PDF profesional:** Exporta resultados en formato A4 con logo circular corporativo y diseño limpio.
- **Sin instalaciones:** Funciona directamente en cualquier navegador compatible: iOS, Android, Windows, Mac.
- **Control de decimales:** Soporta entrada de datos con precisión decimal para resultados exactos.
- **Historial local:** Seguimiento automático de los últimos pacientes procesados usando **localStorage**.
- **Integración con Drive:** Acceso directo a la carpeta de almacenamiento en la nube para organizar y respaldar informes.
- **Envío rápido:** Botón de acción directa a WhatsApp para enviar el informe al cliente con un mensaje predeterminado.

---

## 🛠️ Tecnologías utilizadas
- **HTML5 / CSS3** — Estructura y diseño responsivo.
- **JavaScript (Vanilla)** — Lógica de la aplicación e historial local.
- **html2pdf.js** — Conversión de formularios web a documentos PDF de alta calidad.

---

## 📋 Instrucciones de uso
1. Abre el archivo **index.html** en tu navegador favorito (Safari, Chrome o Edge).  
2. Completa los campos del formulario con los datos del paciente; se aceptan valores decimales.  
3. **Paso 1:** Haz clic en **Generar y Descargar PDF**. El archivo se guardará automáticamente en tu dispositivo.  
4. **Paso 2:** Haz clic en **Subir a Drive** para abrir tu carpeta de historial y cargar el PDF recién generado.  
5. **Paso 3:** Ingresa el número de WhatsApp del cliente y haz clic en **Enviar WhatsApp** para iniciar la conversación con el mensaje predeterminado.

---

## 📂 Organización del Historial
- **Carpetas por periodo:** Para mantener un orden mensual eficiente, utiliza la carpeta de Google Drive provista y crea subcarpetas por mes o por semana.  
- **Historial Reciente:** La tabla de "Historial Reciente" dentro de la app muestra los últimos casos atendidos en el dispositivo actual, facilitando búsquedas rápidas y reenvíos.

---

## ✅ Buenas prácticas
- **Verificar datos antes de generar PDF** para evitar correcciones posteriores.  
- **Nombrar archivos con formato consistente** como `YYYY-MM-DD_NombrePaciente_ID.pdf` para facilitar búsquedas en Drive.  
- **Realizar copias de seguridad periódicas** de la carpeta de Drive si se usa para almacenamiento a largo plazo.

---

## 👨‍🔬 Créditos
**Desarrollado para:** Laboratorio Clínico Veterinario San Ramón  
**Responsable:** Dr. Adonis Ramón Sosa Gómez

