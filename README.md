# 🏥 Dashboard de Análisis de Salud con Big Data y Power BI (2015–2025)

## 📌 Descripción
Este proyecto académico implementa un **dashboard interactivo** basado en **Big Data y Power BI** para analizar la evolución, distribución y brechas en infraestructura hospitalaria y personal médico en las instituciones de salud del Perú entre **2015 y 2025**.  
El sistema busca **apoyar la toma de decisiones estratégicas en salud pública**, ofreciendo visualizaciones claras y datos procesados de manera escalable en la nube.

---

## 🎯 Objetivos

### Objetivo General
Implementar un dashboard interactivo basado en Big Data y Power BI que permita analizar la evolución, distribución y brechas en infraestructura y personal médico en instituciones de salud del Perú (2015–2025).

### Objetivos Específicos
- Analizar la evolución anual del personal médico (médicos, enfermeros, obstetras, técnicos).  
- Evaluar la disponibilidad y distribución geográfica de infraestructura hospitalaria (consultorios, camas, ambulancias).  
- Comparar recursos disponibles entre entidades públicas, privadas y regionales.  
- Identificar regiones con mayores brechas en capacidad operativa hospitalaria.  
- Desarrollar un dashboard dinámico en Power BI para autoridades sanitarias.  

---

## 🏗️ Arquitectura de Big Data

El proyecto sigue una arquitectura en tres etapas: **Ingesta, Procesamiento y Visualización**.
<img width="1024" height="755" alt="arqui-pica" src="https://github.com/user-attachments/assets/5196aa4a-9530-4127-b977-a0baeb7763ac" />


### 🔹 Ingesta
- Datasets CSV (2015–2025)  
- Azure Landing Zone  

### 🔹 Procesamiento
- Azure HDInsight Clusters  
- Apache Spark  
- Azure Databricks  
- Azure Data Factory  
- Azure Data Lake Storage (Bronze, Silver, Gold)  

### 🔹 Visualización
- Azure Database (Generic)  
- Power BI (reportes y dashboards interactivos)  

---

## 🛠️ Herramientas Utilizadas
- **Azure:** HDInsight, Databricks, Data Factory, Data Lake Storage, Database  
- **Procesamiento:** Apache Spark  
- **Visualización:** Power BI  
- **Datos:** Archivos CSV (2015–2025)  

---

## 📊 Resultados Esperados
- Dashboard interactivo en **Power BI** que muestra evolución y distribución de infraestructura hospitalaria y personal médico.  
- Identificación de **brechas regionales** en capacidad hospitalaria.  
- Comparaciones entre entidades públicas, privadas y regionales.  
- Información accesible para apoyar decisiones estratégicas en **salud pública**.

<img width="530" height="284" alt="Captura de pantalla 2025-08-20 103308" src="https://github.com/user-attachments/assets/9a1f755f-91ca-4d8e-adc9-67d68f0f3523" />
<img width="508" height="284" alt="Captura de pantalla 2025-08-20 103248" src="https://github.com/user-attachments/assets/889b31d1-3a43-47ee-8ab2-d004eb5ef9c8" />
<img width="515" height="286" alt="Captura de pantalla 2025-08-20 103224" src="https://github.com/user-attachments/assets/95d80943-5bc9-4aa1-b49b-ec002bfea27a" />
<img width="514" height="281" alt="Captura de pantalla 2025-08-20 103328" src="https://github.com/user-attachments/assets/0e96a3ed-0c12-40ed-9490-053b21852fb5" />


---

## 📄 Licencia
Este proyecto es de uso académico y está bajo la **Licencia MIT**.
