

# 📊 Data Engineering Portfolio on Google Cloud



Este repositorio documenta laboratorios prácticos orientados al rol de **Ingeniero de Datos** en Google Cloud.
Cada lab aborda tareas reales como ingestión de datos, transformación, automatización y análisis con herramientas de GCP.

---


---

## 🎓 Sobre este portafolio

Este portafolio está basado en el curso oficial:

📘 **Introduction to Data Engineering on Google Cloud**

En este curso aprendí a:

- Comprender las responsabilidades del **Ingeniero de Datos**.
- Identificar los componentes centrales que se usan en **Google Cloud** para tareas de ingeniería de datos.
- Construir e implementar **canalizaciones de datos** con distintos patrones: ELT, ETL, replicación y más.
- Aplicar técnicas de **automatización** para facilitar flujos de trabajo en GCP.

Este repositorio refleja esos aprendizajes a través de laboratorios prácticos.

---


## ¿ Que haces un Ingeniero de Datos? 

Basicamente, un ingeniero de datos traslada los datos de fuentes a receptores en 4 etapas:

  - replicacion y migracion
  - transferencia
  - transformacion
  - almacenamiento

    <img width="851" height="283" alt="image" src="https://github.com/user-attachments/assets/8d5ccef2-1eaf-4952-915e-8386c5196d31" />

Un Ingeniero  de Datos crea canalizaciones de datos para posibilitar la toma de decisiones basadas en datos:

  - Llevar los datos hacia donde se los necesita   --->  transferencia y almacenamiento de datos SIN PROCESAR
  - Hacer que los datos resulten utilizables       --->  transformacion de datos
  - Agregar nuevo valor a los datos                --->  aprovisionamiento y enriquecimiento de datos
  - Asministrar los datos                          --->  seguridad,privacidad,descubrimiento y administracion
  - Llevar los procesos de datos a produccion      --->  supervision y automatizacion de las canalizaciones

---

## 📂 Contenidos del Portafolio

| Nº   | Lab / Proyecto                                                              | Rol en el pipeline                      | Temas principales                                                                                      | Link                                                                                                    |
|------|------------------------------------------------------------------------------|------------------------------------------|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| 01   | Datastream: Replicación de PostgreSQL en BigQuery                          | Replicación / Migración de datos         | Replicar datos en tiempo real desde Cloud SQL hacia BigQuery usando Datastream                          |  [Ver lab](<01 - Datastream - Replicación de PostgreSQL en BigQuery/README_Datastream_PostgreSQL_to_BigQuery.md>)|
| 02   | Cómo cargar datos en BigQuery                                               | Ingesta de datos                         | Cargar datos estructurados en BigQuery desde distintas fuentes utilizando consola y CLI                 | [Ver lab](<02 - Cómo cargar datos en BigQuery/README_Cargar_datos_BigQuery.md>)                         |
| 03   | BigLake: Qwik Start                                                         | Extracción y carga (EL)                  | Explorar BigLake para acceder a datos distribuidos sin necesidad de moverlos a BigQuery                 | [Ver lab](<03 - Bigtable/README_BigLake_Qwik_Start.md>) |                                                 |
| 04   | Dataform: Crear y ejecutar flujo de trabajo SQL                            | Extracción, carga y transformación (ELT) | Usar Dataform para transformar datos directamente en BigQuery mediante SQL                              | [Ver lab](<04 - Dataform/README_Dataform_SQL_Workflow_Lab.md>)                                         |
| 05   | Dataflow Streaming: Panel en tiempo real                                    | ETL (streaming)                          | Crear un pipeline en tiempo real con Dataflow, BigQuery y visualización con Looker Studio              | [Ver lab](<05 - Dataflow_streaming/README_Dataflow_Realtime_Dashboard_Lab.md>)                         |
| 06   | Dataproc Serverless: Spark + BigQuery                                       | ETL (batch)                              | Ejecutar un script en Spark para transformar datos y cargarlos en BigQuery                             | [Ver lab](<06 - Dataproc_spark/README_Usa Dataproc Serverless.md>)                                     |
| 07   | Cloud Run Functions: Automatización de carga a BigQuery                    | Automatización                           | Crear una función en Cloud Run que se activa por eventos y carga datos automáticamente en BigQuery     | [Ver lab](<07 - Cloud Run_autm/README_CloudRun_BigQuery_Automation_Lab.md>)                            |

### 📂 Labs extras

| Nº   | Lab / Proyecto                                                              | Rol en el pipeline                      | Temas principales                                                                                      | Link                                                                                                    |
|------|------------------------------------------------------------------------------|------------------------------------------|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| 08   | Cloud Data Fusion: Ingesta y transformación visual                          | ETL (batch visual)                       | Crear pipelines visuales con Cloud Data Fusion y cargar datos en BigQuery                              | [Ver lab](<08 - GSP807_Lab/README_pipelines_lotes_Cloud Data Fusion.md>)                               |
| 09   | Cloud Data Fusion: Realtime Pipelines                                       | ETL (streaming visual)                   | Pipeline en tiempo real usando Cloud Data Fusion + Pub/Sub + BigQuery                                  | [Ver lab](<09 - GSP808_Lab/README_pipelines_streaming_Cloud Data Fusion.md>)                           |
| 10   | Dataflow + BigQuery (Python SDK)                                            | ETL (batch con Python)                   | Crear y ejecutar un pipeline en Dataflow con Apache Beam para cargar datos en BigQuery                 | [Ver lab](<10 - Dataflow_real time_dashboard/README_Real-Time Dashboard with Dataflow.md>)            |
| 101  | Dataproc: Ejecución de trabajos Apache Spark                                | ETL (batch con Spark)                    | Crear y ejecutar canalizaciones de datos por lotes usando Spark en Dataproc                            | [Ver lab](<11 - Running Apache Spark jobs/README_Running Apache Spark jobs on Cloud Dataproc.md>)     |

---

## 🧰 Tecnologías y servicios utilizados

- **BigQuery**, **Cloud Storage**, **Cloud SQL**
- **Datastream**, **Dataform**, **Dataflow**, **Pub/Sub**
- **Dataproc**, **Apache Spark**, **Apache Beam**
- **Cloud Data Fusion**, **Cloud Run Functions**
- **BigLake**, **Looker Studio**

---

## 🏅 Credenciales y progreso

Podés ver todas las insignias, laboratorios completados y certificaciones en mi perfil de Google Cloud Skills Boost:

👉 [Ver perfil público en Google Skills Boots](https://www.cloudskillsboost.google/public_profiles/29490151-ce34-4b53-95b4-0c5938ce2bcc) 



---

> ## 📬 Contacto
>
> Si querés contactarme o colaborar:
>
> -  [LinkedIn](https://www.linkedin.com/in/tuusuario/)
> -  [GitHub](https://github.com/GermanPLS)
>
> ---
>
> *Este portafolio está en constante evolución a medida que avanzo en nuevos desafíos de datos en GCP.*
>
> ---








