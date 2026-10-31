# Peymi — tema para Discourse

Tema autónomo del centro de ayuda de Peymi, basado en la identidad de [peymi.net/ar](https://peymi.net/ar/): Raleway, azul profundo, turquesa y cabecera clara. Incluye portada con buscador, tarjetas de categorías, lectura de artículos y diseño móvil.

## Instalación

1. Administración → Apariencia → Temas y componentes → Instalar → Desde un repositorio Git.
2. Importar `https://github.com/efrancou/discourse-peymi-theme`.
3. Elegir la paleta **Peymi** y asociar las **instancias existentes** de Search Banner, Custom Header Links, Easy Responsive Footer y DiscoTOC. Así se conservan sus textos, enlaces y ajustes.
4. Revisar la vista previa y marcar el tema como predeterminado.

Search Banner y Easy Responsive Footer son opcionales: el resto del tema funciona sin ellos. No activar simultáneamente dos banners de búsqueda. La instancia de Peymi usa Search Banner; una futura migración al Welcome Banner de Discourse debe trasladar sus textos y revisar los selectores.

No asociar el antiguo componente local **Peymi Docs corporativo**, que fue diseñado para Mint. Conservar Mint instalado permite revertir el cambio seleccionándolo de nuevo como predeterminado.

## Mantenimiento

Los cambios se publican en este repositorio y se incorporan desde el botón de actualización del tema en Discourse. No requiere JavaScript, servicios externos ni cambios en el servidor. Las fuentes variables Raleway y la ilustración se importan como assets locales del tema.

La paleta usa un turquesa más oscuro para enlaces y botones sobre blanco, manteniendo contraste. El turquesa original `#2EA8C8` se conserva como acento de marca. Los bloques de código conservan su tipografía monoespaciada.

Este tema solo cambia la presentación. Los permisos de categorías, el registro por invitación y el almacenamiento local se administran en Discourse.

## Licencias y referencias

Código: MIT. Raleway: SIL OFL 1.1. Ilustración y marca: consultar [ATTRIBUTIONS.md](ATTRIBUTIONS.md).

- [Estructura de temas](https://meta.discourse.org/t/structure-of-themes-and-theme-components/60848)
- [Assets de temas](https://meta.discourse.org/t/include-assets-e-g-images-fonts-in-themes-and-components/62459)
- [Instalación oficial](https://meta.discourse.org/t/installing-a-theme-or-theme-component/63682)
