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
Curso_Python_Elastic/
│
├── Curso_Python_Elastic.pdf           ← Libro completo del curso (generado automáticamente)
├── requirements.txt                   ← Librerías necesarias (JupyterLab, ES client, pandas, etc.)
│
├── setup/                             ← Instalación paso a paso sin Docker
│   ├── 01_install_python_env.md
│   ├── 02_install_elasticsearch.md
│   ├── 03_install_beats.md
│   ├── 04_test_connection.py
│
├── notebooks/                         ← Notebooks por capítulo explicados paso a paso
│   ├── 01_intro.ipynb                 ← ¿Qué es Elastic? Primeros pasos
│   ├── 02_indexing.ipynb              ← Crear índices, mappings, insertar documentos
│   ├── 03_search.ipynb                ← Queries básicas y avanzadas
│   ├── ...                            ← Hasta CRUD, visualizaciones, alertas y más
│
├── devtools/                          ← Comandos para Kibana Dev Tools
│   ├── create_index.json
│   ├── insert_docs.json
│   ├── search_queries.json
│   ├── aggs.json
│
├── proyecto_final/                    ← Proyecto práctico completo
│   ├── dataset_ventas.csv             ← Dataset simulado
│   ├── script_index_ventas.py         ← Indexación automática
│   ├── reporte.ipynb                  ← Análisis y visualización
│   ├── export_report.py               ← Exportación de reportes PDF
│
├── extras/                            ← Utilidades adicionales
│   ├── templates_roles.json
│   ├── watcher_examples.json
│   ├── cleanup_scripts.py
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
