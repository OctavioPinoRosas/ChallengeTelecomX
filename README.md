# 📊 Análisis de Evasión de Clientes - Telecom X

Este proyecto forma parte de un desafío de ciencia de datos enfocado en analizar la evasión de clientes (churn) en la empresa **Telecom X**. El objetivo es explorar los factores que contribuyen a la pérdida de clientes, proporcionando análisis y visualizaciones que sirvan como base para estrategias de retención.
---

## 🚀 Descripción y objetivo del desafío

Telecom X enfrenta una alta tasa de cancelaciones de servicio. El desafío será recopilar, procesar y analizar los datos, utilizando Python y sus principales bibliotecas para extraer información valiosa. A partir del análisis se podran desarrollar estrategias para reducir la evasión (cancelación del servicio por parte de los clientes).  
Como parte del equipo de análisis de datos, el objetivo es:
- Importar y explorar datos desde una API en formato JSON.
- Procesar, limpiar y transformar los datos.
- Analizar variables relacionadas con la evasión de clientes.
- Producir un informe con hallazgos, visualizaciones y recomendaciones.
---

## 📄 Estructura del proyecto
- Extraccion
- Transformacion
    - Conociendo los datos
    - Manejo de inconsistencias
    - Corrigiendo los tipos de datos
- Carga y analisis
    - Analisis desciptivo
    - Distribución de evación
    - Recuento de evación por variables categoricas
    - Recuento por variables numericas
- Informe final
    - Introduccion
    - Limpieza y tartamiento de datos
    - Analisis exploratporio de datos
    - Conclusiones e insights
    - Recomendaciones

---

## 📁 Estructura del repositorio

```bash
ChalengeTelecomeX/
│  
├── DataBase/                 # Archivos de datos  
├── TelecomX_LATAM.ipynb/     # Análisis completo en un Notebook  
├── Images/                   # Gráficos generados  
├── README.md                 # Este archivo  
└── requirements.txt          # Lista de dependencias  
```

---

## 📥 Instalación

1. Clona este repositorio:

```
git clone https://github.com/OctavioPinoRosas/ChallengeTelecomX.git
```

2. Instala las dependencias:

```bash
pip install -r requirements.txt
```

---

## 📦 Dependencias Principales

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- requests
- json
- jupyter

> Todas se encuentran en `requirements.txt`.

---

## 🔗 Fuente de Datos

Los datos provienen de una API simulada:

- [📁 JSON de Clientes](https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_Data.json)
- [📄 Diccionario de Datos](https://github.com/ingridcristh/challenge2-data-science-LATAM)

## 📊 Conclusiones del proyecto obtenidas al final del analisis de los datos

Analizando las graficas a partir de los datos, podemos concluir que la principal causa de cancelación del servicio es el alto gasto mensual/diario de los usuarios, debido al costo mas elevado de la fibra optica, en comparación al DSL. Tambien se puede ver que, a pesar de que los clientes que se quedan tienden a tener menores gastos en los servicios de TelecomX, su fidelidad a lo largo de los años ha dado mayores ganancias a la compañia, esto visto en que los clientes que permanecen tienden a tener un mayor gasto total.  
Ademas, se debe notar que los clientes que pagan con cheques electronicos, tienden a abandonar mas, que los que tienen pagos automaticos, como lo es en una tarjeta de credito o transferencia bancaria. Puede deberse a que al ver el gasto, al realizar el pago, tienden a verlo como un pago alto, siedo mas propensos a dar de baja el servicio, que los clientes que tienen el cobro automatico, pues estos no ven el cobro, por lo cual no es uno de sus principales gastos a recortar.  
Otro factor a conciderar es el del tipo de contratos, ya que los que pagan mes a mes tienden a abandonar mas facilmente, que los que tienen un contrato a dos años, con lo cual es evidente que resulta mas Beneficioso tener un contarto a largo palzo, incluso a un año, ya que tambien tiene un menor porcentaje de cancelacion.

## 📊 Recomendaciones obtenidas a partir del analisis de los datos

A partir de las conclusiones obtenidas mediante el análisis de los datos, podemos llegar a las siguientes recomendaciones para mejorar la retención de clientes e incrementar los beneficios para la empresa:  
- Convencer a los clientes de que realicen el pago de forma automatica, ya sea por medio del cobro de tarjeta de credito o transferencia bancaria
- Iniciar a los clientes en el servico de internet mediante el tipo DSL, y despues que migren a fibra optica si lo concideran necesario.
- Los clientes con el servicio de fibra optica que considren abandonar, se les convensa de dar la oportunidad de probar con el servicio DSL, explicandoles el beneficio de un menor coste, ademas de poder darles alguna promoción, como lo seria un mes gratis o un descuento inicial en el servicio DSL.
- Convencer a los clientes en obtener un contrato a largo plazo, preferentemente a dos años, o en su defecto a un año. Pudiendo dar algun beneficio al cliente, como lo seria un menor coste por mes, al realiar le contrato, comparado con el costo de mes a mes.
- Ademas, para incrementar los ingresos de la empresa, se tiene un 21.7% de clientes que no cuentan con servicio telefonico, siendo un potencial de clientes para este servicio. Se les podria ofrecer este servicio dando alguna promoicion o descuento, ademas de que los clientes que cuentan con DSL, les es más varato el instalar el servicio telefonico.
