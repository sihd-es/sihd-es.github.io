# SiHD Embedded Signup HTML

Archivo incluido:

- `connect-whatsapp.html`

## Cómo publicarlo

Copia `connect-whatsapp.html` en la raíz del repositorio `sihd-es.github.io`.

La URL quedará:

```text
https://sihd.es/connect-whatsapp.html
```

## Backend

Esta página solo implementa el frontend del flujo de Meta Embedded Signup.

Cuando el backend esté listo, edita esta constante dentro del HTML:

```js
const SIHD_BACKEND_CALLBACK_URL = "";
```

y pon el endpoint real, por ejemplo:

```js
const SIHD_BACKEND_CALLBACK_URL = "https://api.sihd.es/api/v1/whatsapp/embedded-signup/callback";
```

No guardar access tokens en HTML ni en GitHub Pages.
