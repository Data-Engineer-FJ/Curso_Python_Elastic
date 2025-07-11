# 📘 Curso Profesional Python + Elasticsearch

Bienvenido al repositorio oficial del **Curso_Python_Elastic**, una guía completa y práctica para aprender a integrar Python con Elasticsearch, Kibana, Beats y construir un proyecto completo tipo ETL + Análisis + Visualización.

---

## 🎯 Objetivos del Curso

- Dominar Elasticsearch desde cero con Python.
- Comprender la arquitectura de Elastic Stack (ES + Kibana + Beats).
- Crear, consultar, agregar y administrar datos desde Dev Tools y Python.
- Visualizar resultados en Kibana con dashboards reales.
- Automatizar tareas, generar alertas y reportes.
- Ejecutar un proyecto completo tipo ETL + Análisis + Dashboard.

---

## 📦 Estructura del Proyecto

```
├── 📘 Curso_Python_Elastic.pdf         ← Libro completo en PDF
├── README.md                           ← Portada del curso en GitHub
├── requirements.txt                    ← Librerías necesarias (JupyterLab, Elasticsearch, pandas, etc.)
├── setup/                              ← Instalación paso a paso sin Docker
│   ├── 01_install_python_env.md
│   ├── 02_install_elasticsearch.md
│   ├── 03_install_beats.md
│   ├── 04_test_connection.py
├── notebooks/                          ← Notebooks por capítulo
│   ├── 01_intro.ipynb                  ← ¿Qué es Elastic? ¿Qué es Kibana? Primeros pasos
│   ├── 02_indexing.ipynb               ← Crear índices, mappings, insertar docs
│   ├── 03_search.ipynb                 ← Queries básicas y avanzadas
│   ├── 04_bulk.ipynb                   ← Carga masiva con _bulk
│   ├── 05_pandas.ipynb                 ← Visualizar y explorar resultados con Pandas
│   ├── 06_aggs_basicas.ipynb           ← Agregaciones simples
│   ├── 07_aggs_anidadas.ipynb          ← Subagregaciones y visualización
│   ├── 08_security.ipynb               ← Seguridad con usuarios y roles
│   ├── 09_beats_intro.ipynb            ← Instalar y configurar Metricbeat y Filebeat
│   ├── 10_python_client.ipynb          ← Conectar con Python y validar
│   ├── 11_index_python.ipynb           ← Indexar documentos con Python
│   ├── 12_query_python.ipynb           ← Buscar desde Python
│   ├── 13_pandas.ipynb                 ← Convertir resultados en DataFrames
│   ├── 14_crud_python.ipynb            ← CRUD completo desde Python
│   ├── 15_automatizacion.ipynb         ← Automatizar tareas
│   ├── 16_kibana_visual.ipynb          ← Dashboards en Kibana
│   ├── 17_alertas.ipynb                ← Watchers y alertas básicas
│   ├── 18_proyecto_final.ipynb         ← Caso práctico de ventas
│   ├── 19_exportar_reporte.ipynb       ← Generar informes PDF
│   └── 20_buenas_practicas.ipynb       ← Recomendaciones y próximos pasos
│
├── devtools/                           ← Comandos para Kibana Dev Tools
│   ├── create_index.json
│   ├── insert_docs.json
│   ├── search_queries.json
│   ├── aggs.json
│   └── ...
│
├── beats_configs/                      ← Configuración de Metricbeat y Filebeat
│   ├── metricbeat.yml
│   ├── filebeat.yml
│   └── dashboards/                     ← Dashboards de ejemplo en JSON
│
├── proyecto_final/                     ← Proyecto práctico completo (Ej: Ventas)
│   ├── dataset_ventas.csv              ← Datos reales simulados
│   ├── script_index_ventas.py          ← Indexar dataset en Elasticsearch
│   ├── queries_proyecto.json           ← Consultas usadas
│   ├── reporte.ipynb                   ← Análisis con pandas + gráficos
│   └── export_report.py                ← Exportación automática de reportes
│
└── extras/                             ← Utilidades adicionales
    ├── templates_roles.json            ← Roles y permisos
    ├── watcher_examples.json           ← Watchers de monitoreo
    └── cleanup_scripts.py              ← Scripts para limpiar el entorno
```

---

## ⚙️ Requisitos

- Python 3.8 o superior
- Elasticsearch 8.x instalado localmente (sin Docker)
- JupyterLab
- Conexión a Internet para instalar librerías

Instala dependencias:

```bash
pip install -r requirements.txt
```

---

## 🚀 Ejecución rápida

```bash
git clone https://github.com/tu_usuario/Curso_Python_Elastic.git
cd Curso_Python_Elastic/
pip install -r requirements.txt
jupyter lab
```

Asegúrate de tener Elasticsearch corriendo en: `https://localhost:9200`  
Y Kibana en: `http://localhost:5601`

---

## 👨‍💻 Público objetivo

- Data Engineers
- Analistas de datos
- Desarrolladores backend
- Estudiantes de carreras TI
- Equipos de formación corporativa

---

## 📝 Licencia

Este proyecto está bajo la licencia MIT.  
Eres libre de usar, modificar y distribuir con fines educativos o comerciales.  
Consulta el archivo `LICENSE`.

---

## ✍️ Autor

**Fredy Johel Peña Alvarez**  
Data Engineer & Educador Técnico  
Proyecto profesional educativo sin Docker, ideal para entornos Linux Ubuntu.
