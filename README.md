# 7pk2 Club — Web Legal

> Sitio web público con las páginas legales y de soporte de la app móvil **7pk2 Club**, alojado en GitHub Pages.

---

## ¿Para qué sirve este repositorio?

La app **7pk2 Club** es una tarjeta digital VIP para socios de la discoteca **La Zede del Sabor**. Google Play y App Store exigen que toda app pública tenga URLs accesibles para:

| Página | URL | Requerido por |
|---|---|---|
| Política de Privacidad | `/privacidad.html` | Google Play · App Store |
| Términos y Condiciones | `/terminos.html` | Google Play · App Store |
| Eliminación de cuenta y datos | `/baja.html` | Google Play (Data Safety) |

Este repo es **solo el sitio web legal** — el código fuente de la app móvil es privado y vive en un repositorio separado.

---

## Páginas

```
📄 index.html        Página principal con enlaces a las secciones
📄 privacidad.html   Política de privacidad (RGPD)
📄 terminos.html     Términos y condiciones de uso
📄 baja.html         Cómo solicitar la eliminación de cuenta y datos
🎨 style.css         Sistema de diseño Silent Luxury (paleta de la app)
```

---

## Diseño

El sitio replica la identidad visual de la app móvil:

- **Fondo**: `#131313` negro profundo
- **Acento**: oro champán `#F2CA50` / `#D4AF37`
- **Tipografía**: system-ui, sin serifa, espaciado amplio
- **Estilo**: Silent Luxury — sin bordes, solo tonal shifts de profundidad

---

## Despliegue

El sitio se publica automáticamente en **GitHub Pages** desde la rama `main`.

```
https://<usuario>.github.io/7pk2-club-web/
```

No requiere build ni dependencias — HTML y CSS estáticos.

---

## Titular de los datos

**La Zede del Sabor** · NIF B26945792  
Calle Sa Dragonera Nº4, 08192 Sant Quirze del Vallès, Barcelona  
✉️ Discotecasala7pk2@gmail.com
