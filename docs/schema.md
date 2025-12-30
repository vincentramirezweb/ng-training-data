# Schema — Implementación (Yoast + SASWP + WooCommerce)

## Reglas anti-duplicado
- Si SASWP genera FAQ schema vía shortcode -> NO agregar FAQPage manual.
- Si Yoast/WooCommerce genera Product schema -> NO duplicar Product manual.
- Organization + WebSite -> recomendado en HEADER global (sitewide), una sola vez.

---

## Global (sitewide): Organization + WebSite
(poner en header)

- Organization:
  - name: NG Solutions Training
  - url: https://ngsolutions.training/
  - email: info@ngsolutions.training
  - logo: https://ngsolutions.training/wp-content/uploads/2024/06/Logo_GN_training-1@4x-scaled.webp
  - sameAs: Facebook + Instagram
  - knowsLanguage: es/en

- WebSite:
  - SearchAction: https://ngsolutions.training/?s={search_term_string}
  - inLanguage: es-US

---

## Por página: BreadcrumbList
Recomendado para productos y /mentorias/ (si Yoast no lo genera bien).
Formato:
Inicio > Mentorías > Producto

---

## Producto Jobber — Product/Breadcrumb/HowTo
- Product:
  - sku: Jobber
  - image: https://ngsolutions.training/wp-content/uploads/2025/10/Portadas-para-el-sitio-web-26.png
  - price: 1000 USD
- HowTo: "Cómo organizar y automatizar..." (pasos)
- FAQ: generado por SASWP

---

## /mentorias/ — WebPage + Breadcrumbs + HowTo + FAQ
- WebPage: nombre/descripción comercial
- HowTo: "Cómo elegir tu mentoría"
- FAQ: manual SOLO si SASWP no lo genera
