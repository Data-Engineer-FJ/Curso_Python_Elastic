# 📘 Curso_Python_Elastic

Curso completo y práctico de **Python + Elasticsearch**, diseñado para profesionales de datos, ingenieros de software y estudiantes avanzados. Incluye notebooks interactivos, scripts para Dev Tools de Kibana, configuraciones con Beats y un proyecto final ETL con visualización y análisis.

---

## 📌 Contenido

📂 Estructura del repositorio:

```
Curso_Python_Elastic/
│
├── 📘 Curso_Python_Elastic.pdf         ← Libro completo en PDF
├── README.md                           ← Portada del curso en GitHub
├── requirements.txt                    ← Librerías necesarias (JupyterLab, Elasticsearch, pandas, etc.)
│
├── notebooks/                          ← Notebooks por capítulo
│   ├── 01_intro.ipynb                  ← ¿Qué es Elastic? ¿Qué es Kibana? Primeros pasos
│   ├── 02_indexing.ipynb               ← Crear índices, mappings, insertar docs
│   ├── 03_search.ipynb                 ← Queries básicas y avanzadas
│   ├── 04_bulk.ipynb                   ← Carga masiva con _bulk
│   ├── 05_pandas.ipynb                 ← Visualizar y explorar resultados con Pandas
│   └── ...                             ← Más notebooks según avance
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

## 🎯 Objetivos del curso

- Instalar y configurar Elasticsearch de forma local.
- Conectar Python con Elasticsearch usando `elasticsearch-py`.
- Crear, consultar, actualizar y eliminar documentos.
- Realizar búsquedas simples y avanzadas.
- Aplicar agregaciones y scripts dinámicos.
- Visualizar datos con `pandas` y construir dashboards en Kibana.
- Integrar todo en un proyecto final realista.

---

## ⚙️ Requisitos

- Python 3.8+
- Docker (opcional para correr Elasticsearch)
- JupyterLab
- Elasticsearch 8.x

Instala las dependencias con:

```bash
pip install -r requirements.txt
```

---

## 🚀 Ejecución rápida

```bash
# 1. Clona el repositorio
git clone https://github.com/Data-Engineer-FJ/Manual_Python_Elastic.git

# 2. Entra al proyecto
cd Manual_Python_Elastic

# 3. Instala dependencias
pip install -r requirements.txt

# 4. Lanza JupyterLab
jupyter lab
```

---

## 📚 Recursos incluidos

- 🧠 10+ notebooks con teoría + práctica
- 📄 Scripts listos para DevTools de Kibana
- 📊 Dashboards con Filebeat y Metricbeat
- 📁 Proyecto final: ETL + visualización
- 📘 PDF del curso completo para impresión

---

## 👨‍🏫 Público objetivo

- Data Engineers
- Analistas de datos
- Desarrolladores Backend
- Arquitectos de soluciones
- Estudiantes avanzados

---

## 📝 Licencia

Este proyecto está bajo licencia MIT.  
Puedes usarlo, modificarlo y compartirlo libremente. Consulta el archivo `LICENSE` para más detalles.

---

## ✉️ Autor

**Data Engineer FJ [Fredy Johel Peña Alvarez]**  
Proyecto educativo y profesional para aprendizaje de Elasticsearch.



