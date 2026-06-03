# Fieloop — Landing Page

## El negocio
Fieloop es un servicio de tarjetas de lealtad digital para negocios locales en México (cafeterías, restaurantes, salones de belleza, barberías, retail). El producto digitaliza las tarjetas de sellos físicas de papel, llevándolas a Apple Wallet y Google Wallet. Opera como white-label sobre la plataforma Boomerangme.

## El archivo principal
El archivo de la landing page es `index.html` — es un solo archivo HTML con todo el CSS y JS incluido.

## Paleta de colores (regla 60-30-10)
- 60% Blanco frío: `#FAFCFF` — fondo principal
- 30% Azul noche: `#12234F` — nav, secciones alternas, footer
- 10% Naranja: `#F97316` — acentos, CTAs, bullets, logo

## Tipografía
- Plus Jakarta Sans — única fuente en todo el sitio
- Pesos usados: 300, 400, 500, 700, 800

## Reglas importantes
- Nunca cambiar colores globales sin instrucción explícita
- Nunca cambiar tipografía sin instrucción explícita
- Nunca modificar la estructura de desktop — todos los cambios de layout son mobile-first (max-width: 768px)
- El logo usa un SVG de infinito entre "fiel" y "p"
- Siempre hacer commit al branch: claude/fieloop-landing-styling-mBujD

## Lo que ya está implementado
- Carrusel táctil con scroll snap en sección "¿Cómo funciona?" y "Planes" (móvil)
- Wallet cards lado a lado en móvil
- Iconos SVG vectoriales en lugar de emojis
- Badge "Más popular" en esquina superior derecha de la card destacada
- Grid con líneas divisorias en casos de uso (móvil)
- Dot estrella en el carrusel de planes para el plan del medio
