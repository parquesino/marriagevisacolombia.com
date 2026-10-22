# marriagevisacolombia.com — landing de Spouse Visa (EN)

Sitio estático en inglés, estética azul propia (`#1e3a8a`). Sin build. Deploy = push a `main` → GitHub Pages. Repo: `parquesino/marriagevisacolombia.com`. Dominio vía `CNAME` (`www.marriagevisacolombia.com`).

## Objetivos (iguales en todas las landings)

1. Generar leads por WhatsApp.
2. Vender consultas estratégicas de $80 (100% abonables al contratar).
3. Transmitir: (a) contratar un abogado es una decisión inteligente; (b) Camila Ocampo / Colombian Passport es la firma correcta para contratar.

## Estructura

- `index.html` — landing principal (Spouse Visa, $650).
- `meta/index.html`, `yt/index.html` — copias por canal (Meta / YouTube): mismos contenidos, con links de calendario propios, `noindex` y badges sin link. **Al editar precios/copy, replicar en las 3.**
- `citizenship-and-residency-by-marriage/index.html` — página de ciudadanía y residencia (con secciones de Camila, precio único y tarifas añadidas en oct-2026).
- `eligibility-result.html`, `meta/eligibility-result.html`, `yt/eligibility-result.html` — páginas de resultado del quiz (con links de calendario por canal).
- Sin CSS compartido: cada HTML lleva su propio `<style>` inline.

## Modelo de precio vigente (oct-2026)

- Precio oficial único en la web: **$650 USD** (ex-Protected). Sin nombres de plan (Essential/Protected/Turnkey).
- Essential (descuento) y Turnkey ($2,900) solo existen en consulta; ni mención en web.
- Garantía: reaplicaciones por inadmisión sin honorarios hasta la aprobación. Cada nuevo estudio oficial ($56) lo paga el cliente al Estado. No cubre el rechazo definitivo.
- Tabla a 2 columnas (Servicio | Precio fijo). Beneficiario a **$300** (unificado con la propiedad principal; el ex-Protected local era $200).
- CTA sin repetir el precio: recuerda que los $80 se descuentan al contratar.

## Reglas vigentes (oct-2026)

1. **Cero fugas**: badges a `#reviews` o `<span>` sin link; logo del footer sin enlace; flotante nativo de WhatsApp (verde `#22C55E`, tooltip, aparece a 4s/scroll) en vez de Chaty (pixel eliminado).
2. **No inventar cifras**: fuentes válidas son las tarjetas Protected originales, `colombianpassport.com/our-services/spouse-visa-full-service` y lo que pida el dueño.
3. Push a `main` = deploy. Verificar en vivo con hard refresh.
4. No tocar `canonical`, links de calendario por canal ni la estructura de `citizenship-and-residency-by-marriage` fuera de lo listado.
