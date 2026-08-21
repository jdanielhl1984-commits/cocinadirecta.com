# Proyecto: Venta Automatizada de Módulos de Cocina

## Modelo de negocio

- **Propuesta de valor:** venta de módulos de cocina de alta calidad (particulares y profesionales — paletas, lampistas) como intermediario con fábrica.
- **Margen comercial:** 45% de descuento/beneficio sobre PVP.
- **Fábrica:** Logisiete. Plazo de fabricación: ~60 días (debe mostrarse de forma visible en el checkout, no solo en condiciones legales).
- **Formatos de entrega:**
  - Paletizado en caja — estándar, sin recargo. El cliente o su instalador lo monta.
  - Módulo armado de fábrica (nunca decir "montaje" de cara al cliente, se confunde con instalación de la cocina) — coste real de Logisiete de referencia ~75€ fijo/pedido + ~14,93€/módulo (sin confirmar para todos los tipos), con margen aplicado al cliente: 199€ fijo + 19€/módulo armado. Se elige "todo o nada" para el pedido completo, no módulo a módulo. Pendiente confirmar con Logisiete si el coste varía por tipo de módulo (bajo/alto/columna) — un pedido mixto de prueba no cuadró con la fórmula simple.
  - Transporte: variable según peso total del pedido (dato real de Logisiete), no incluido en las cifras anteriores.
  - Los costados decorativos no llevan coste de armado (ya vienen listos en su caja).

## Arquitectura de la web

- **Home:** propuesta de valor y explicación del flujo de compra.
- **Catálogo:** módulos completos (cascos + frentes + herrajes bajo una misma referencia).
- **Venta cruzada:** aviso en carrito para zócalos, costados vistos, regletas de compensación.
- **Portal de transparencia de calidad:** grosor de cascos, herrajes, resistencia, acabados.

## Flujo de compra

1. Selección de módulos → carrito.
2. Pantalla de configuración final obligatoria antes de pagar: Paletizado (estándar) vs. Armado de fábrica (recargo fijo + variable, ver "Modelo de negocio").
3. Pago 100% por adelantado.
4. Pedido validado → se traslada a Logisiete para producción.

## Condiciones legales

- Cliente único responsable de medidas y cantidades introducidas.
- Plazo de fabricación de ~60 días, indicado de forma visible antes del pago.
- Producto fabricado a medida → sin derecho de desistimiento tras confirmación (a reflejar explícitamente, con checkbox de aceptación en el checkout, no solo en el texto legal).
- Protocolo RMA rápido para incidencias de transporte/desperfectos de origen.

## Reglas de contenido / copywriting

- **Nunca mencionar "Logisiete" ni "LOGI7" por su nombre en ninguna página pública.** Es el proveedor de fábrica; si el cliente lo conoce, puede saltarse el intermediario y contactar directamente. Referirse siempre como "nuestra fábrica asociada" o similar. Ojo: los PDFs del proveedor llevan su marca en cada página (cabecera y/o pie), así que no colgar esos PDFs tal cual ni mostrárselos a clientes — hay que maquetar el contenido con diseño propio.
- **El recargo exacto por armado no debe aparecer en la home ni páginas informativas.** Se puede mencionar la opción de "módulo armado de fábrica" como ventaja para profesionales, pero la cifra concreta solo se muestra en la pantalla de configuración final del checkout, justo antes de pagar. Mostrarlo con transparencia como beneficio ("cuantos más módulos armados, menos cuesta cada uno"), nunca disimulado.
- **Nunca usar la palabra "montaje" de cara al cliente** — se confunde con instalación de la cocina completa. Usar siempre "armado" o "módulo armado de fábrica".
- **Nunca dar a entender que se instala en la cocina del cliente.** Solo se vende el módulo (en caja o ensamblado de fábrica como pieza) — nunca el servicio de colocación/instalación en la vivienda. Usar "ensamblado de fábrica" o "módulo en caja", nunca frases que sugieran que alguien va a montar la cocina in situ. Para dudas de medidas o proyectos a medida, remitir a "consultar con nuestros expertos" en vez de ofrecer instalación.
- **Nunca hacer afirmaciones sobre lo que hace o no hace la competencia** (ej. "los módulos económicos del mercado suelen ser de 16mm"). Los datos técnicos propios (19mm, herrajes Blum, etc.) se presentan como hechos verificables sobre el producto propio, sin comparación directa ni generalización sobre otras marcas — riesgo de publicidad comparativa/desleal.
- **Voz de marca: "equipo"/"nosotros", nunca primera persona individual.** Aunque hoy sea una sola persona detrás del proyecto, la web debe sonar a equipo/empresa consolidada ("nuestro equipo", "profesionales con experiencia"), nunca "yo diseño tu cocina".
- **Nunca usar la frase "sin sala de exposición" (ni variantes).** Es jerga de negocio que confunde al cliente (no entiende si es ventaja o inconveniente). El footer usa: "Venta directa de módulos de cocina, puertas y accesorios."

## Datos técnicos del proveedor (para catálogo y ficha de producto)

- **⭐ Argumento de venta clave: paneles de 19mm.** La mayoría de módulos económicos del mercado son de 16mm. Este dato debe tenerse en cuetna como comparación (no solo como ficha técnica) en home, catálogo y fichas de producto — es el diferenciador más fuerte frente a la competencia barata.

- ⭐ Argumento de venta clave: paneles de 19mm. Destacar la robustez de los 19 mm como estándar propio de alta gama, usando afirmaciones categóricas sobre nuestro producto (ej. "Estructura reforzada con paneles de 19 mm para máxima resistencia y cero pandeo") SIN mencionar directamente a marcas competidoras ni generalizar sobre el resto del mercado para evitar problemas de publicidad desleal.

- **Puerta Venecia PET** (modelo principal, el más solicitado): 22mm de grosor, cantos ABS de 1mm microbiselados, tirador integrado, acabado antihuellas (PET), resistente a calor/químicos/impacto. Colores: Blanco Brillo/Mate, Grafito Brillo/Mate, Negro Mate, Gris Claro Mate, Cashmere Mate, Taupe Mate.
- **Estructura de módulos (bajos y altos):** costados 16mm, paneles horizontales 19mm, trasera 8mm laminada dos caras, cantos vistos ABS 1mm, cantos ocultos 0.4mm melamínico. Baja emisión de formaldehído, certificación TSCA CARB2.
- **Herrajes:** bisagras Blum Clip-top Blumotion (cierre suave, apertura 110°), cajones Blum MERIVOBOX o Grass NOVA PRO (guías 50cm de fondo, hasta 40kg de carga), colgadores ocultos Indaux con sistema antivuelco (65kg/unidad, 130kg por juego, probado con 260kg sostenido 1 semana).
- **⚠️ Regla de precio importante:** los colores de puerta con acabado **metalizado** (Cobre, Oro, Bronce, Verde Metal, Azul Zenit, Acero Metalizado, Antracita Metalizado) llevan un **recargo del 10% sobre el precio de tarifa de la puerta** (no del módulo completo). Este recargo es independiente del recargo por montaje de fábrica y hay que contemplarlo aparte en la lógica de cálculo de precio del servidor cuando se implemente el catálogo con selección de color.

## Base de datos (Supabase)

- Proyecto Supabase separado del de abrozon.
- **Tabla `modulos` creada** con columnas: `id`, `created_at`, `nombre`, `tipo`, `precio_base` (a revisar — el precio real depende de combinación estructura+puerta, no es un valor único), `alto_cm`, `ancho_cm`, `fondo_cm` (pendiente de pasar a mm para coincidir con el estándar de Logisiete), `acabado_puerta`, `colores_disponibles` (array), `destacado` (bool). Primera fila de prueba insertada: "Bajo 1 puerta 60cm".
- **Pendiente:** rediseñar el modelo de precios como tabla relacionada (`modulos` + tabla `precios` por combinación de módulo × color de estructura × color de puerta), en vez de un campo `precio_base` único — decisión ya tomada, falta implementar.
- **Convención de medidas:** alto × ancho × fondo, en mm (formato de Logisiete), no cm.

## Estructura de fabricación (Logisiete)

- Colores de estructura disponibles: Lino, Antracita Hidrófugo, Blanco Hidrófugo, Roble Salvaje — cada uno con precio distinto.
- El precio de cada módulo depende de la combinación color de estructura + color de puerta.
- Altura estándar de módulos bajos: 80cm (800mm) — corregir cualquier referencia previa a 82cm.
- Regla de fabricación: módulos hasta 60cm de ancho → 1 puerta; desde 70cm de ancho → 2 puertas (se calcula a partir del ancho, no se guarda como campo independiente).

## Decisiones técnicas tomadas

- **No Shopify / no-code.** Se descartó por preferencia de no depender de una plataforma externa.
- **Código propio**, con ayuda de IA como en el proyecto previo (abrozon.com — subastas, GitHub, código a mano dirigido por IA).
- **Pagos: Stripe Checkout.** El cliente introduce la tarjeta en una página ya construida por Stripe (no se programa el cobro desde cero). Reduce drásticamente el riesgo de seguridad sin perder control sobre el resto de la experiencia.
- **Regla de oro:** el precio final SIEMPRE se recalcula y valida en el servidor (nunca solo en el navegador del cliente), para que nadie pueda manipular el total antes de pagar.
- **Nunca se guardan datos de tarjeta** en la base de datos propia — de eso se encarga Stripe.

## Stack

- **GitHub** — control de versiones del código.
- **Supabase** — base de datos (Postgres) + backend mediante Edge Functions. Guarda módulos, pedidos, clientes. Row Level Security para que nadie acceda a pedidos ajenos.
- **Stripe** — pasarela de pago.
- **Frontend** — HTML/CSS/JS, empezando por `index.html`.

## Roadmap acordado

**Diseño y contenido web**
1. ~~Home, catálogo y página de diseño 3D (boceto visual)~~ — hecho.
2. Ficha de producto individual (detalle de módulo, selector de color/acabado, medidas).
3. Pantalla de configuración final del checkout (Flat-pack vs. Montado, recargo).
4. Página de accesorios (zócalos, costados, regletas) para venta cruzada.
5. Textos legales: aviso legal, política de privacidad, cookies, condiciones generales de venta completas (forma de pago, exclusión de derecho de desistimiento, garantías legales de 2-3 años, jurisdicción).

**SEO**
6. Investigación de palabras clave reales (ya se detectó que la gente busca "módulos de cocina" en vez de nombres de marca).
7. SEO on-page: títulos, meta-descripciones, URLs limpias, datos estructurados de producto (schema.org) para que Google muestre precio/disponibilidad en resultados.
8. Contenido: páginas o blog que capturen búsquedas informativas (ej. "cuánto cuesta reformar una cocina", guías de medidas) — genera tráfico antes de que el cliente esté listo para comprar.
9. SEO local para la parte de servicio/diseño si se dirige también al Vallès Oriental.

**Negocio y estructura**
10. Nombre definitivo de marca (de momento "CocinaDirecta" como placeholder) y dominio.
11. Ámbito geográfico de arranque (Cataluña vs. toda España).
12. Estructura fiscal/mercantil: autónomo, SL nueva, o marca dentro de estructura existente — afecta a facturación e IVA.
13. Confirmar con Logisiete los términos exactos de la relación de distribuidor (exclusividad de zona, condiciones de pedido).
14. Pactar por escrito con Logisiete quién asume el coste en incidencias (error de fabricación vs. daño de transporte).

**Operativa post-venta**
15. Sistema de facturación conectado al checkout (emisión automática al confirmarse el pago).
16. Atención al cliente: canal de soporte y tiempos de respuesta.
17. Seguimiento de pedido durante los 60 días de fabricación (aunque sea manual al principio).
18. Gestión de stock/disponibilidad — aviso si Logisiete descataloga un acabado.

**Parte técnica**
19. Estructura del proyecto en GitHub (frontend + funciones Supabase separadas).
20. Base de datos en Supabase: tablas de módulos (con precio real del servidor), pedidos, clientes.
21. Catálogo y carrito (frontend) conectado a datos reales.
22. Edge Function que recalcula el precio real (módulos + recargo 10% si aplica) y crea la sesión de pago en Stripe.
23. Función que confirma el pago (webhook de Stripe) y guarda el pedido solo cuando el pago es real.
24. Aviso automático a producción — envío del pedido a Logisiete (inicialmente puede ser un email automático).
25. Analítica básica (qué módulos se ven, dónde abandona el cliente el carrito).

**Marketing / captación**
26. Estrategia de primeros clientes — partiendo de cero en visibilidad, el canal B2B (contacto directo con paletas/lampistas) es más rápido que esperar a SEO/Ads.

**Estado actual:** boceto visual de home, catálogo, ficha de producto y diseño 3D terminados. Web publicada en GitHub Pages. Base de datos Supabase creada, tabla `modulos` en construcción (pendiente rediseñar modelo de precios y confirmar tarifas reales de armado con Logisiete).

## Notas para la IA

- **El usuario ya tiene experiencia dirigiendo IA para programar** (proyecto previo: abrozon.com, web de subastas con Supabase + GitHub Pages, todo el código generado por IA y copiado/pegado por el usuario como director creativo). No es su primer proyecto — puede seguir instrucciones técnicas paso a paso con confianza, pero prefiere explicaciones claras sin dar por hecho jerga.
- Para cambios pequeños en archivos ya existentes: indicar el texto exacto a buscar y su reemplazo, no reescribir el archivo entero.
- Para cambios grandes o reestructuraciones: preguntar antes de tocar el archivo.
- No acortar el código al mostrarlo completo.
- La parte de interfaz de Supabase/GitHub está solo en inglés — el usuario necesita que se le indique con precisión dónde pulsar y qué escribir, campo a campo, sin dar por sentado que reconoce los nombres en inglés.
- El código y las tablas de esta tienda van en un proyecto de GitHub/Supabase separado del de abrozon — nunca mezclar ambos.
- La web se despliega en GitHub Pages (repo: github.com/jdanielhl1984-commits/cocinadirecta.com, público). Mismo patrón que abrozon: cuidado con caché y nombres de archivo al depurar errores.
- **Antes de fijar cualquier cifra o regla de negocio como definitiva, verificar con datos reales de Logisiete** (presupuestos, tarifas) en vez de asumir fórmulas simples — ya ha pasado que una suposición razonable (10% fijo de recargo, luego 75€+14,93€/módulo) resultó no coincidir con los números reales de un pedido mixto. Preferir "pendiente de confirmar" a dar por buena una cifra sin contrastar.
