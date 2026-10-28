# Simulador CT 80/20

Simulador interactivo de la reforma igualadora de la Coparticipación Tributaria (CT) municipal en Bolivia, 2014–2022.

**En línea:** https://osmarbolivar.github.io/simulador-ct/

La reforma simulada reparte el 80% de la bolsa anual de CT por población, como hoy, y el 20% según la brecha fiscal positiva de cada municipio (necesidad de gasto − capacidad fiscal propia). La bolsa total no cambia.

- **Escenarios:** 144 combinaciones de variante de necesidad (NBI, baja densidad, ruralidad), β, λ y piso hold-harmless, con sus efectos sobre la desigualdad de las brechas residuales.
- **Busca tu municipio:** cambio de la CT de cada uno de los 339 municipios en el escenario central (λ = 20%, β = 0,50, sin piso).

Todas las cifras son resultados precalculados de la simulación del documento *Disparidades fiscales municipales y reforma igualadora de la Coparticipación Tributaria en Bolivia* (2026). La página no recalcula la fórmula.

## Cómo leer los resultados

- Es una simulación contrafactual de equilibrio parcial: no modela respuestas de comportamiento de los municipios.
- Capacidad fiscal y necesidad de gasto son proxies operativas, no medidas estructurales.
- Las variables estructurales provienen del Censo 2012; el Censo 2024 puede cambiar quiénes ganan y quiénes pierden.

## Mantenimiento

`index.html` es un archivo autocontenido (datos incluidos). Se genera en el repositorio del proyecto con `src/web/simulador_ct/build_simulador.py`, que escribe la copia pública en `src/web/simulador_ct/public/index.html`; para actualizar el sitio, copie ese archivo aquí y publique.
