
# Portal Génesis Integrada — Instrucciones de Mantenimiento

Este archivo contiene las instrucciones necesarias para mantener y actualizar el portal web "Génesis Integrada", alojado en GitHub Pages.

---

## Archivos clave en el repositorio

1. **index.html**
   - Archivo principal del portal.
   - Contiene el diseño y estructura completa de la página web.
   - Debe ser reemplazado cada vez que se actualice el contenido visual, enlaces o estructura.

2. **Cápsula_Apertura_Portal_IS_OPMB.mp4**
   - Video de apertura simbiótica.
   - Aparece directamente en el portal como elemento de bienvenida.
   - Se debe reemplazar si se actualiza la cápsula audiovisual.

3. **Símbolo_Reapertura_IS_Versión_Imprimible.pdf**
   - Documento simbólico descargable.
   - Accesible desde el footer del sitio para quienes deseen profundizar.

4. **sello.png**
   - Imagen del símbolo de reapertura de la Inteligencia Simbiótica.
   - Se muestra como ícono en el pie de página.

---

## Proceso de actualización

### A. Reemplazo manual

1. Iniciar sesión en GitHub.
2. Ir al repositorio del portal.
3. Hacer clic en “Add file” > “Upload files”.
4. Subir los archivos modificados:
   - index.html (completo)
   - Cápsula_Apertura_Portal_IS_OPMB.mp4
   - Símbolo_Reapertura_IS_Versión_Imprimible.pdf
   - sello.png
5. Confirmar con “Commit changes”.

### B. Buenas prácticas

- Evita carpetas internas si no modificas las rutas del HTML.
- Mantén siempre una copia de seguridad del `index.html`.
- Verifica los enlaces internos después de cada modificación.

---

## Automatización futura (opcional)

Puedes configurar GitHub Actions para:

- Validar que los archivos estén presentes.
- Enviar alertas si algún recurso es eliminado o renombrado.
- Hacer commits automatizados desde una carpeta de sincronización externa.

(Se incluirá un script y archivo `.yml` en próximas versiones)

---

Custodio: Oscar Patricio Montecinos Becerra
Organismo: IS — Inteligencia Simbiótica Viva
Creación simbiótica: en curso, evolutiva, abierta.

