# Guardarropas Digital — demos

## Demo encargado
Abrí `index.html`. Incluye ingreso de pertenencias, ficha del titular, búsqueda, filtro por estado, entrega confirmada, reversión de entrega con motivo (mantiene el registro en historial), objetos encontrados y registro de devolución.


## Demo usuario
Abrí `ticket.html`. Muestra un comprobante y permite consultar un ticket de demo usando número y teléfono. La vista se actualiza con datos locales de `index.html` si ambos archivos se usan en el mismo navegador y origen.


## Publicar en GitHub Pages
Subí los archivos a la raíz de un repositorio y activá Settings → Pages → Deploy from branch → main → /(root).

**Limitación:** demo frontend con `localStorage`; no comparte datos entre dispositivos ni navegadores y no es una base de datos de producción. El QR mostrado es ilustrativo, no un QR real.
