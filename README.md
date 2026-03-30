# Proyecto Final — Bootcamp de Análisis de Datos

Tres proyectos de análisis de datos que cubren SQL, análisis exploratorio, pruebas estadísticas y dashboards.

---

## Proyectos

### 1. 📚 Base de Datos de Libros — Análisis SQL
Análisis de una plataforma de reseñas de libros usando PostgreSQL. Se exploraron tendencias de lectura, rendimiento de editoriales y patrones de engagement de usuarios.

**Hallazgos clave:**
- 819 libros publicados después del año 2000 en el catálogo
- Penguin Books lidera con 42 títulos de más de 50 páginas
- J.K. Rowling tiene el promedio de calificación más alto (4.29) entre autores con 50+ calificaciones
- Los usuarios más activos (50+ calificaciones) escriben en promedio 24 reseñas de texto

**Herramientas:** Python, Pandas, SQLAlchemy, PostgreSQL

---

### 2. 📞 CallMeMaybe — Detección de Operadores Ineficaces
Identificación de operadores de call center con bajo rendimiento usando métricas de comportamiento y pruebas de hipótesis estadísticas.

**Hallazgos clave:**
- El 87% de los operadores fue clasificado como ineficaz según tasa de llamadas perdidas, tiempo de espera y volumen de llamadas salientes
- Se confirmó estadísticamente que los operadores ineficaces tienen mayor tasa de llamadas perdidas (p=0.006) y mayor tiempo de espera (p<0.001)
- El problema más común: bajo volumen de llamadas salientes

**Herramientas:** Python, Pandas, Matplotlib, Seaborn, SciPy, Tableau

📊 Dashboard 1: 

https://public.tableau.com/views/VisualizacionesProyectoFinal_Telecom_1/Dashboard1?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

📊 Dashboard 2:

https://public.tableau.com/views/VisualizacionesProyectoFinal_Telecom/Dashboard2?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


---

### 3. 🛒 Sistema de Recomendaciones — Prueba A/B
Evaluación de si un nuevo sistema de recomendaciones mejoró la conversión de compras a lo largo de un embudo de 3 etapas.

**Hallazgos clave:**
- Se encontraron 441 usuarios presentes en ambos grupos y fueron eliminados del análisis
- El nuevo sistema mejoró significativamente la conversión en "agregar al carrito" (p=0.0007)
- No hubo mejora significativa en compras finales (p=0.30)
- No se alcanzó el umbral mínimo de mejora del 10% — no se recomienda implementar

**Herramientas:** Python, Pandas, Matplotlib, SciPy, Statsmodels

---

## Estructura del proyecto

```
Final_Project_DA/
│
├── sql_libros/
│   └── sql_books_analysis.ipynb
│
├── telecom/
│   ├── analysis_telecom.ipynb
│   └── telecom_limpio.csv
│
└── prueba_ab/
    └── recommender_system_test.ipynb
```

---

```

> **Nota:** El proyecto de SQL requiere una conexión a PostgreSQL. Las credenciales están incluidas en el notebook.

---

## Contacto

LinkedIn: www.linkedin.com/in/camilo-mantilla-data
