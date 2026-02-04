# Hero Banner Video - Gantry 5 Particle (Version 2.1.8)

Este repositorio contiene la versi贸n evolucionada del Hero Banner para el ecosistema **OpenSAI**. Esta actualizaci贸n (v2.1.8) introduce flexibilidad SEO avanzada y un sistema de renderizado blindado.

## 馃専 Novedades de la Versi贸n 2.1.8

* **Jerarqu铆a SEO Din谩mica:** Ahora es posible elegir desde el administrador si el t铆tulo principal debe ser un `<h1>` o un `<h2>`, permitiendo adaptar la part铆cula a la estructura de cualquier p谩gina.
* **Orden Sem谩ntico:** El subt铆tulo se ha fijado como `<h2>` para mantener una estructura l贸gica y profesional frente a los motores de b煤squeda.
* **Ocultaci贸n Blindada:** Se implement贸 una validaci贸n por conteo de caracteres (`length > 0`) y limpieza de espacios (`trim`). Esto garantiza que, si los campos de video o bot贸n no tienen contenido real, no se generar谩 c贸digo basura en el DOM.

## 馃殌 Funcionalidades Principales

* **Mobile First:** Dise帽o inteligente con flex-box din谩mico para dispositivos m贸viles.
* **Video Pop-up (Lightcase):** Integraci贸n nativa para reproducir contenido de YouTube en ventanas emergentes de alta velocidad.
* **Fondo Inteligente:** Soporte para im谩genes con anclaje vertical (Top/Center/Bottom) para evitar cortes indeseados en rostros o logos.

## 馃搧 Instalaci贸n

Copiar los archivos `banner_home.yaml` y `banner_home.html.twig` en la ruta:
`/templates/g5_hydrogen/custom/particles/`

> **Requisito:** Es indispensable tener activado el Atom **Lightcase** en la configuraci贸n de Atoms de Gantry 5 para el funcionamiento de los pop-ups de video.

## 鈿狅笍 Configuraci贸n SEO

Al configurar la part铆cula, elija la etiqueta del t铆tulo con responsabilidad:

* Use **H1** si la part铆cula es el encabezado principal de la landing page.
* Use **H2** si ya existe otro H1 en la p谩gina o si la part铆cula se usa en una secci贸n secundaria.

## 馃 Contribuciones

Esta versi贸n final liberada est谩 abierta a mejoras. Se invita a los colaboradores a proponer optimizaciones manteniendo siempre la licencia y los est谩ndares de documentaci贸n de OpenSAI.

---

**Licencia:** [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Coautores:** Yimer Rold谩n & Gemini (Google AI)

**OpenSAI 2026** - *Innovaci贸n en Open Business e IA*

---

驴Hay alg煤n otro detalle que quieras incluir en la documentaci贸n o estamos listos para cerrar esta versi贸n 2.1.8?
