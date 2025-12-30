# Análisis exploratorio y segmentación de clientes en e-commerce

## Descripción del proyecto
Este proyecto presenta un análisis exploratorio de datos (EDA) y una segmentación de clientes aplicada a un dataset de e-commerce. El enfoque principal está en comprender el comportamiento de precios, descuentos, ventas y clientes, con el objetivo de generar insights accionables que apoyen la toma de decisiones de negocio.

---

## Objetivo del análisis
- Explorar la estructura y calidad del dataset.
- Analizar precios y descuentos por categoría.
- Evaluar ingresos y volumen de ventas por categoría.
- Identificar patrones temporales en las ventas.
- Segmentar clientes según su comportamiento de gasto y uso de descuentos.
- Proponer recomendaciones de negocio basadas en los hallazgos.

---

## Dataset
El dataset corresponde a transacciones de un e-commerce e incluye información sobre:
- Identificadores de cliente y producto
- Categorías de productos
- Precios y descuentos aplicados
- Precio final de compra
- Método de pago
- Fecha de compra

El dataset no presenta valores nulos ni registros duplicados, lo que permite un análisis confiable sin imputaciones adicionales.

---

## Metodología aplicada
El análisis se desarrolló utilizando las siguientes técnicas:

- Limpieza y revisión de datos (EDA inicial)
- Análisis descriptivo de precios y descuentos
- Análisis de ingresos y volumen de ventas por categoría
- Análisis temporal de ingresos mensuales
- Segmentación de clientes mediante clustering (3 grupos)
- Interpretación de resultados con enfoque de negocio

---

## Principales insights
- El volumen de ventas no siempre se traduce en mayores ingresos: algunas categorías destacan por ticket promedio más alto.
- La política de descuentos es homogénea entre categorías, lo que sugiere oportunidades de optimización de margen.
- Existen diferencias claras en el comportamiento de clientes según su gasto y sensibilidad al descuento.
- Se observa una estacionalidad moderada, con meses de mayor y menor desempeño claramente identificables.
- Los métodos de pago presentan una distribución equilibrada, sin una preferencia dominante.

---

## Recomendaciones de negocio
- Ajustar la política de descuentos hacia un enfoque más focalizado por categoría y tipo de cliente.
- Proteger el margen en clientes de alto valor mediante beneficios no monetarios.
- Aplicar estrategias de upselling y bundles en clientes de menor gasto.
- Planificar campañas promocionales considerando la estacionalidad observada.
- Mantener todos los métodos de pago disponibles y priorizar otras palancas de crecimiento.

---

## Estructura del repositorio
```text
analisis-eda-segmentacion-ecommerce/
├── notebooks/
│   └── analysis.ipynb
├── report/
│   └── Ecommerce_EDA_Segmentation_Report_ES.pdf
├── README.md
