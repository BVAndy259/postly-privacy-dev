# Postly — Política de Privacidad

Página estática independiente del repositorio de Postly, lista para publicar en GitHub Pages y usar como **Privacy Policy URL** en el panel de Meta.

## Archivos

- `index.html`: página completa de la Política de Privacidad (HTML + CSS, sin JavaScript, sin cookies y sin dependencias externas).

## Antes de publicar

1. Reemplaza el correo de contacto `privacidad@postly.app` por un correo real que controles. Aparece en:
   - Sección 1 (Responsable del tratamiento).
   - Sección 10 (Tus derechos).
   - Sección 11 (Eliminación de datos).
   - Sección 14 (Contacto).
2. Revisa la fecha de “Última actualización” y la versión si vas a hacer cambios.
3. Si quieres identificar formalmente a una persona o empresa como responsable, agrega su nombre en la sección 1 y en el pie de página.
4. No agregues credenciales, tokens ni datos privados: GitHub Pages es público.

## Publicar en GitHub Pages

1. Crea un repositorio público, por ejemplo `postly-privacy`.
2. Sube `index.html` a la raíz del repositorio (o haz commit y push desde esta carpeta).
3. En GitHub, entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona:
   - **Source**: Deploy from a branch.
   - **Branch**: `main` (o la rama que uses), carpeta `/ (root)`.
5. Guarda y espera a que GitHub Pages publique el sitio.
6. La URL tendrá la forma:

```text
https://<tu-usuario>.github.io/postly-privacy/
```

7. Ábrela en una ventana de incógnito para comprobar que carga sin iniciar sesión.

## Usarla en Meta

1. En el panel de la app de Meta: **Configuración de la app → Información básica**.
2. Pega la URL de GitHub Pages en **URL de la política de privacidad**.
3. En **Dominios de la app**, agrega el dominio de tu sitio, por ejemplo:

```text
<tu-usuario>.github.io
```

Sin `https://`, sin ruta y sin barra final.

4. Guarda los cambios y vuelve a intentar la creación de la configuración o la activación de `public_profile`.

### URL de eliminación de datos (opcional, para más adelante)

Meta también tiene un campo **Data Deletion Instructions URL**. Puedes usar la misma página con el ancla de la sección correspondiente:

```text
https://<tu-usuario>.github.io/postly-privacy/#eliminacion-de-datos
```

## Si Meta no acepta el dominio de GitHub Pages

Algunos paneles de Meta son estrictos con subdominios compartidos. Si `usuario.github.io` no se acepta:

- Usa un dominio propio (por ejemplo, `postly.tudominio.com`) y configura un `CNAME` en GitHub Pages.
- O publica la misma página en Netlify, Vercel o Cloudflare Pages, que entregan HTTPS y un dominio propio del proyecto.
- Recuerda actualizar la URL en Meta y en **Dominios de la app** si cambias de hosting.

## Nota

Esta página es un documento informativo. No incluye analítica, cookies ni scripts de terceros. El contenido debe revisarse y adaptarse a la legislación y a los datos reales de Postly antes de usarlo en producción.
