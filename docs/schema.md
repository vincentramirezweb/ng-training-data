# Schema (Yoast SEO Premium + SASWP)

## Regla #1: evitar duplicados
- SASWP FAQ shortcode = ya genera FAQ schema → no agregar FAQPage manual.
- Yoast/WooCommerce puede generar Product schema → no duplicar Product manual.
- Organization + WebSite = recomendado global (header) 1 sola vez.

## Recomendación por tipo de página
- Hub (/mentorias/): WebPage + BreadcrumbList + (HowTo opcional) + FAQ (si no lo genera SASWP)
- Producto (Woo): Product + Offer + BreadcrumbList (ideal que lo maneje Yoast/Woo), HowTo opcional si hay sección “paso a paso”.
