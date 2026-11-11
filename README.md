# Trabajo Práctico Especial: Fundamentos de la Ciencia de Datos - Grupo 35

## Requisitos previos
- Python 3.10 o superior
- Git instalado en el sistema

## Instrucciones de ejecución local

Siga estos pasos exactos para reconstruir el ambiente de desarrollo y evaluar el código localmente sin conflictos de versiones.

### 1. Clonar el repositorio
```bash
git clone https://github.com/Smigol297/TPE-Fundamentos-ciencia-datos.git
cd TPE-Fundamentos-ciencia-datos
```

### 2. Crear y activar el entorno virtual
Es estrictamente necesario crear un entorno aislado antes de instalar las dependencias.

**En Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**En Linux/macOS:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Reconstruir el ambiente de PIP
Con el entorno virtual activado (debería ver `(.venv)` en su terminal), instale las dependencias exactas requeridas:
```bash
pip install -r requirements.txt
```

### 4. Ejecutar el proyecto
El análisis completo se encuentra en el archivo principal `TPE_Fundamentos_StackOverflow_Grupo35.ipynb`. Puede abrirlo utilizando la herramienta de su preferencia:

**Opción A: Visual Studio Code**
1. Abra la carpeta del proyecto clonado en VS Code.
2. Abra el archivo `TPE_Fundamentos_StackOverflow_Grupo35.ipynb`.
3. En la esquina superior derecha, seleccione el Kernel de Python correspondiente al entorno virtual `(.venv)` recién creado.
4. Ejecute todas las celdas de manera secuencial.

**Opción B: Jupyter Lab / Jupyter Notebook**
1. Con el entorno virtual activado en la terminal, inicie el servidor ejecutando `jupyter-lab` o `jupyter notebook`.
2. En la interfaz web que se abrirá automáticamente, navegue hasta el archivo `TPE_Fundamentos_StackOverflow_Grupo35.ipynb` y ábralo.
3. Asegúrese de que el kernel activo sea el asociado a este entorno.
4. Ejecute todas las celdas de manera secuencial (Run -> Run All Cells).


## Estructura del proyecto

* `TPE-Fundamentos-StackOverflow-Grupo35.ipynb`: Notebook principal con la limpieza en capas, el análisis exploratorio y la validación matemática de las 6 hipótesis.
* `Informe_Grupo35.pdf`: Documento ejecutivo detallando la metodología, los hallazgos estadísticos y las conclusiones de negocio.
* `requirements.txt`: Archivo de configuración para reconstruir el ambiente exacto de dependencias de PIP.
* `grafico-de-barras-Oficial.png`: Captura del reporte oficial de Stack Overflow, utilizada como "verdad de campo" para validar la integridad inicial de los datos.
* `datos_encuesta.zip`: Archivo comprimido que contiene los conjuntos de datos crudos (results.csv y schema.csv) de la Encuesta de Desarrolladores 2025.
