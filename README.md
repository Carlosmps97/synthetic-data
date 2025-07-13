# Generador de Datos Sintéticos con Streamlit

![Banner de Python y datos](https://placehold.co/800x200/3B82F6/FFFFFF?text=Generador+de+Datos+Sintéticos)

Este repositorio contiene el código fuente para una aplicación de generación de datos sintéticos. El objetivo es proporcionar una interfaz simple para configurar y generar conjuntos de datos personalizados.

---

## 📝 Descripción General

El proyecto utiliza una interfaz web creada con **Streamlit** para permitir a los usuarios definir las características de los datos que necesitan. Una vez configurado, el backend (diseñado para ejecutarse en Databricks o localmente) genera los datos según las especificaciones.

La interfaz permite:
* **Configurar Parámetros:** Definir visualmente las columnas, tipos de datos, distribuciones y volúmenes.
* **Gestionar la Generación:** Iniciar el proceso de creación de datos.
* **Visualizar Resultados:** Obtener vistas previas y resúmenes de los datos generados.

---

## 💻 Pila Tecnológica

Este proyecto se construye principalmente con las siguientes tecnologías:

* **Lenguaje:** Python
* **Interfaz de Usuario:** Streamlit
* **Configuración:** Archivos `.yaml` para definir esquemas y parámetros.
* **Gestión de Dependencias:** `requirements.txt` para listar todas las librerías de Python.

---

## 🚀 Cómo Empezar (Desarrollo Local)

Para ejecutar la aplicación en tu máquina local, sigue estos pasos:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/Carlosmps97/synthetic-data.git](https://github.com/Carlosmps97/synthetic-data.git)
    cd synthetic-data
    ```

2.  **(Recomendado) Crear un entorno virtual:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    # En Windows usa: venv\Scripts\activate
    ```

3.  **Instalar dependencias:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Ejecutar la aplicación Streamlit:**
    ```bash
    streamlit run app.py
    # (O el nombre de tu archivo principal de Python)
    ```