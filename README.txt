RE:MOTO LAB · SITIO PÚBLICO V10.15 DOMAIN + ANALYTICS RC1
==========================================================

Estado
------
Release Candidate 1 con dominio oficial y Google Analytics 4 integrado.

Dominio canónico
----------------
https://www.duplikey.mx/

Google Analytics 4
------------------
Measurement ID: G-52P1XFVECT

La etiqueta de Google está instalada inmediatamente después de <head>.
No añadir una segunda etiqueta GA4 mientras este ID siga activo.

Eventos medidos
---------------
- page_view: automático por GA4.
- whatsapp_click: clic en enlaces de WhatsApp y origen aproximado del CTA.
- generate_lead: envío desde Cotización rápida o mini-chat.
- mini_chat_open: apertura de la burbuja de ayuda.
- compatibility_result: resultado del verificador.
- compatibility_missing_model: clic en “No aparece tu modelo”.
- modal_open: apertura de servicios, legales, ética, garantía, etc.
- case_image_open: ampliación de un Caso de éxito.
- contact_cta_click: acceso a la sección de contacto.
- social_click: clic en Facebook o Instagram.

Privacidad de analítica
-----------------------
Los eventos personalizados NO envían a Analytics:
- nombre del cliente
- teléfono
- ciudad
- texto escrito en formularios o mini-chat

El evento compatibility_result utiliza únicamente selecciones del catálogo
público del verificador: modelo, año, sistema, estado e interés.

SEO / dominio
-------------
Actualizado al dominio oficial https://www.duplikey.mx/ en:
- canonical
- og:url
- og:image
- Twitter image
- JSON-LD (url, @id, image y logo)
- sitemap.xml
- robots.txt

Se añadió meta robots:
index,follow,max-image-preview:large

Siguiente paso después de publicar
-----------------------------------
1. Confirmar que https://www.duplikey.mx/ carga esta versión.
2. Comprobar Google Analytics > Tiempo real.
3. Configurar Google Search Console para el dominio duplikey.mx.
4. Enviar https://www.duplikey.mx/sitemap.xml a Search Console.
5. Después integrar Bing Webmaster Tools, preferiblemente importando Search Console.

Notas de publicación
--------------------
Publicar únicamente este paquete público.
No subir archivos privados de catálogo o herramientas internas.
