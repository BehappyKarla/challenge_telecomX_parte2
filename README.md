# challenge_telecomX_parte2
Challenge Telecom X - Análisis de Evasión de Clientes (Churn)
📌 Propósito del Proyecto
Este proyecto analiza los patrones de evasión de clientes (Churn) en Telecom X para:

Identificar factores clave que influyen en la decisión de abandonar el servicio
Segmentar clientes según su riesgo de evasión
Proponer estrategias de retención efectivas
Preparar datos para modelos predictivos futuros
📂 Estructura del Proyecto
Challenge_TelecomX/
│
├── Imagenes/                  # Gráficos del análisis
│   ├── DistribuciondeChurn.png
│   ├── TasadeChurnporTipodeContrato.png
│   ├── MetodosdePagoconMayorTasadeAbandono.png
│   ├── DistribuciondeFacturacionMensualporEstadodeCliente.png
│   ├── CorrelaciondeVariablesNumericasconChurn.png
│   └── DistribuciondeClientesporNiveldeRiesgo.png
│
├──README.md                   # Este archivo
├── Challenge_TelecomX_LATAM.ipynb  #Código elaborado en Google Colab
├── TelecomX_Data.json          # Datos originales
└── TelecomX_diccionario.md     # Diccionario
🔍 Hallazgos Visuales Clave
1. Distribución de Churn
Distribución de Churn

2. Impacto del Tipo de Contrato
Contratos

3. Métodos de Pago con Mayor Tasa de Abandono
Métodos de Pago

4. Distribución de Facturación Mensual por Estado del Cliente
Facturación Mensual

5. Correlación de Variables Numéricas con Churn
Correlación

6. Distribución de Clientes por Nivel de Riesgo
Riesgo

🔹 Conclusiones e Insights
Los clientes con contratos mensuales, pocas líneas de servicio, y facturación más alta son significativamente más propensos a abandonar la empresa.
Existe una relación directa entre el número de servicios contratados y la retención: los clientes que usan más servicios tienden a quedarse.
La antigüedad del cliente también es un fuerte indicador: los más nuevos son más volátiles. Ciertos métodos de pago podrían estar asociados a experiencias menos satisfactorias.
💡 Recomendaciones
Incentivar contratos a largo plazo. Ofrecer descuentos o beneficios a clientes con contratos mensuales para migrarlos a planes anuales.
Fomentar la contratación de más servicios. Diseñar bundles o paquetes personalizados que aumenten el número de servicios por cliente.
Campañas de fidelización temprana. Dirigir programas de onboarding, soporte o promociones a los clientes más nuevos (0–6 meses).
Monitorear métodos de pago asociados a mayor churn. Analizar si ciertos métodos presentan más quejas o inconvenientes y mejorarlos.
Establecer alertas tempranas. Utilizar variables como Cuentas_Diarias, TotalServicios y MesesDeAntiguedad para crear un modelo predictivo de evasión.
🚀 Cómo ejecutar el notebook en tu propio Google Colab
Si prefieres trabajar con tu propia copia del proyecto, puedes hacerlo fácilmente desde Google Colab:

