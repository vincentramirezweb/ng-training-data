# Conversiones y tracking

## Metas de conversión
1) Formulario (lead)
2) Compra directa (WooCommerce)
3) Comunidad (Skool)

## Eventos recomendados (GA4)
- `form_submit` / `generate_lead` (según implementación)
- `begin_checkout`
- `purchase`
- `outbound_click_skool` (click URL contiene `skool.com/ng-training-6385`)

## Medición por página (recomendado)
- /mentorias/ → clicks a productos + form submissions
- Jobber product → form submissions + purchases
- Premium product → form submissions + purchases + outbound_click_skool
