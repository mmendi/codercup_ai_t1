El problema que resuelve

Cotizar trabajos de electricista en Argentina a mano es un quilombo: tenés que buscar los precios de mano de obra de AAIERIC (que se actualizan mes a mes por porcentaje), armar el presupuesto en Word o Excel, calcular márgenes, convertir a distintas monedas si el cliente lo pide, exportarlo prolijo, y después mandarlo por WhatsApp o mail. Cada paso es manual y repetitivo, y es fácil que se te escape un ítem desactualizado o un cálculo mal hecho.

Cómo lo soluciona

1. Precios AAIERIC siempre al día sin depender de un PDF
Tenés 91 ítems base precargados. Cuando AAIERIC saca la variación del mes, vos ingresás el porcentaje y el sistema ajusta los precios automáticamente (applyPriceIncrease), con opción de deshacer si te equivocás (undoLastPriceIncrease). Nada de copiar-pegar tablas de un PDF a mano.

2. Armado de presupuesto rápido
Catálogo propio de ítems y de combos (paquetes de tareas que se repiten, tipo "instalación de tablero completo") que se agregan al presupuesto con un click (addCatalogItemToBudget, addComboToBudget), en vez de tipear cada línea de nuevo cada vez.

3. Cálculo automático de totales y margen
computeTotals y computeMargin hacen las cuentas por vos — subtotal, recargos, margen de ganancia — así sabés al toque si el presupuesto te conviene antes de mandarlo.

4. Multi-moneda
Podés mostrar precios en distintas monedas sin tener que rehacer el presupuesto entero.

5. Gestión de clientes
Guardás los datos de cada cliente (renderClientsView, useClientInBudget) y los reusás en el próximo presupuesto sin volver a cargarlos.

6. Exportación e historial
Generás PDF o PNG con tu marca y colores (buildPdfFromPreview, downloadAs), lo compartís directo por WhatsApp (shareFileToWhatsApp), y queda guardado en un historial (renderHistorial) con estado (pendiente, aceptado, vencido) para hacer seguimiento.

7. Todo en un solo archivo, sin servidor
Es HTML/JS/CSS puro con localStorage, así que no depende de internet ni de pagar hosting — funciona en el celular o la compu tal cual la abrís.

En resumen: convierte un proceso manual, lento y propenso a errores en algo de minutos, con los precios de mano de obra siempre actualizados y todo en tu propio dispositivo.
