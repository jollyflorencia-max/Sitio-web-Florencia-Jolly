# Instrucciones para Configurar Formspree

## 🚀 Cómo Obtener tu Endpoint de Formspree

### Paso 1: Crear Cuenta en Formspree
1. Ve a https://formspree.io
2. Haz clic en "Sign Up" (Registrarse)
3. Puedes registrarte con tu **Gmail** (recomendado para abogados)

### Paso 2: Crear Formulario
1. Después del registro, haz clic en "New Form"
2. Completa los datos:
   - **Form name**: "Consulta Web - Florencia Jolly"
   - **Success message**: "¡Gracias! Recibimos tu consulta. Te contactaremos pronto."
   - **Email to send to**: Tu email personal (Gmail, Outlook, etc.)

### Paso 3: Obtener tu Endpoint
1. Una vez creado el formulario, Formspree te dará una URL como:
   ```
   https://formspree.io/f/xvgoeozk
   ```
2. **¡IMPORTANTE!** Copia esa URL - es tu endpoint único

### Paso 4: Actualizar tu Código
Necesitas reemplazar `TU_FORM_ID` en tu archivo `index.html`:

**Cambiar esto:**
```html
action="https://formspree.io/f/TU_FORM_ID"
```

**Por esto (ejemplo):**
```html
action="https://formspree.io/f/xvgoeozk"
```

## 🔄 Actualizar Archivos en GitHub

### Método 1: Editar en GitHub (Más Fácil)
1. Ve a tu repositorio en GitHub
2. Haz clic en `index.html`
3. Haz clic en el lápiz (Edit)
4. Busca la línea: `action="https://formspree.io/f/TU_FORM_ID"`
5. Reemplaza `TU_FORM_ID` por tu endpoint real
6. Commit changes

### Método 2: Subir Archivos Actualizados
1. Reemplaza `TU_FORM_ID` en tu archivo local `index.html`
2. Sube el archivo actualizado a GitHub (igual que antes)

## 📧 Cómo Recibirás los Emails

- ✅ Los emails llegan **directamente a tu email personal**
- ✅ Se incluye toda la información del formulario:
  - Nombre completo
  - Email del cliente
  - Teléfono
  - Servicio de interés
  - Mensaje
- ✅ Formspree incluye la IP y fecha del envío

## 🧪 Probar el Formulario

Una vez configurado:
1. Ve a tu sitio web
2. Llena el formulario con datos de prueba
3. Verifica que llegue el email a tu correo
4. ¡Listo para recibir consultas reales!

## 💡 Consejos para Abogados

- **Respuesta rápida**: Responde dentro de 2 horas laborales
- **Llamada inicial**: Ofrece llamada telefónica gratuita
- **Profesionalismo**: Siempre incluye tu número de matrícula
- **Seguimiento**: Guarda las consultas en un sistema CRM

## ❓ Soporte

Si tienes problemas:
- Verifica que el endpoint esté correctamente copiado
- Revisa la carpeta de spam en tu email
- Formspree tiene documentación en: https://formspree.io/docs/

## 🎉 ¡Tu sitio estará completamente funcional!

Una vez configurado, tendrás:
- ✅ Formulario de contacto profesional
- ✅ Emails directos a tu correo
- ✅ Sitio web 100% funcional para tu práctica legal
- ✅ Más consultas de clientes potenciales