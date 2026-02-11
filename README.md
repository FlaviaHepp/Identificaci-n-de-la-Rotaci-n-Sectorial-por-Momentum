# Identificación de la Rotación Sectorial por Momentum

Dónde está fluyendo el capital ahora

## 📌Descripción General

Este proyecto analiza el momentum agregado a nivel sectorial, utilizando el RSI promedio de las acciones que componen cada sector.

La idea central es detectar rotación de capital:
- el dinero no entra acción por acción, entra por sectores completos.

Cuando el RSI promedio de un sector se eleva de forma consistente, es una señal temprana de que:
- el capital está migrando hacia ese grupo,
- el mercado está re-priorizando ese segmento,
- puede estar iniciándose un nuevo liderazgo sectorial.

## 📍Insight Clave

¿Qué sector muestra el momentum relativo más fuerte en el corto plazo?

Un RSI sectorial elevado indica:
- presión compradora generalizada,
- fortaleza distribuida (no un solo ticker),
- probabilidad de continuidad del flujo.

## 💼Valor de Negocio

Identifica sectores líderes antes de que el consenso se forme.

Fundamental para:
- rotación sectorial,
- asignación táctica de activos,
- selección de ETFs sectoriales.
- Reduce riesgo de apostar por ganadores aislados.
- Permite alinear estrategias con el flujo real de capital.

Fuentes de Datos
- tickers
- ticker_id
- sector
- indicadores_tecnicos
- ticker_id
- fecha
- rsi_14

## 🧠Lógica del Análisis

- Se consideran únicamente los datos de los últimos 7 días.
- Se agrupan los tickers por sector.

Se calcula:
- RSI promedio sectorial,
- cantidad de tickers por sector.
- Se descartan sectores con baja representación.
- Se ordenan los sectores por momentum promedio.

## 📊Interpretación de Resultados

RSI sectorial alto (> 60)
→ Entrada de capital clara.
→ Sector en liderazgo.

RSI sectorial medio (45–55)
→ Zona neutral.
→ Sin rotación definida.

RSI sectorial bajo (< 40)
→ Salida de capital o debilidad estructural.

## 🧩Casos de Uso

- Rotación sectorial semanal.
- Selección de ETFs líderes.
- Filtro previo a selección de acciones.
- Confirmación de tendencias macro.
- Input para modelos multifactor.

## 🚀Posibles Extensiones

- Comparar contra benchmark (RSI relativo).
- Analizar cambios semana a semana.
- Integrar volumen sectorial.
- Medir dispersión interna del RSI.
- Combinar con SMA 200 para confirmar tendencia.

## ✒️Nota Final

Las acciones ganadoras suelen ser síntomas, los sectores ganadores son causas.

Este insight no pregunta qué acción comprar, pregunta dónde se está moviendo el dinero 🔄📈

## 👤Autora
Flavia Hepp Proyecto de SQL aplicó un análisis de riesgo basado en eventos.
