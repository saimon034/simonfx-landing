# SimonFX Landing

Sitio web estático listo para publicar gratis en GitHub + Netlify.

## Modificar WhatsApp

Abre `index.html` y busca:

```js
const WHATSAPP_NUMBER = "0000000000";
```

Cámbialo por tu número con código de país y sin `+`, sin espacios.

Ejemplo:

```js
const WHATSAPP_NUMBER = "573001234567";
```

## Poner pasarela de pago directa

Busca:

```js
const CHECKOUT_LINK = "";
```

Pega tu link de pago:

```js
const CHECKOUT_LINK = "https://tu-link-de-pago.com";
```

Si lo dejas vacío, los botones llevan a WhatsApp.
