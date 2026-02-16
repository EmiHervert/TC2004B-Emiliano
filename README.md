# TC2004B - Análisis de Ciencia de Datos

**Nombre:** Emiliano Hervert de la Cruz  
**Matrícula:** A01412606  
**Semestre:** Febrero-Junio 2026

## Descripción

Repositorio personal para el curso TC2004B. Contiene notebooks y proyectos del semestre.

## Estructura

TC2004B-Emiliano/  
├── README.md  
├── .gitignore  
├── notebooks/     # Jupyter Notebooks  
└── data/          # Datasets (cuando aplique)

## Contenido por Semana

### Semana 1
- Práctica de Git/GitHub
- Primer notebook con dataset Iris
- Familiarización con herramientas

## Contacto

- Email: <a01412606@tec.mx>
- GitHub: [@EmiHervert](https://github.com/EmiHervert)

## Setup Local

### Requisitos
- Python 3.8+
- Git

### Instalación

#### 1. Clonar repositorio
```bash
git clone https://github.com/EmiHervert/TC2004B-Emiliano.git
cd TC2004B-Emiliano
```

#### 2. Crear y activar ambiente virtual

**Mac/Linux:**
```bash
python3 -m venv tc2004b_env
source tc2004b_env/bin/activate
```

**Windows (PowerShell):**
```bash
python -m venv tc2004b_env
tc2004b_env\Scripts\Activate.ps1
```

#### 3. Instalar dependencias
```bash
pip install -r requirements.txt
```

### Probar localmente

#### 1. Ejecutar Jupyter
```bash
jupyter notebook
```

#### 2. Hacer una prueba
Para verificar que todo funcione correctamente haz lo siguiente:
- Navega a `notebooks/`
- Abre el .ipynb
- Ve a Kernel → Restart & Run All

Una vez que todo funcione, puedes cerrar Jupyter con Ctrl+C en la terminal.

### Desactivar ambiente
```bash
deactivate
```

### Problemas Comunes

**Falta instalar módulo venv**
- Esto es necesario en distribuciones basadas en Debian/Ubuntu
- Ejecuta: `sudo apt install python3-venv`

**Error: comando no encontrado**
- Verifica que Python esté instalado: `python --version`

**Error de permisos (Windows)**
- Ejecuta: `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`

**ModuleNotFoundError**
- Verifica que el ambiente esté activo
- Reinstala dependencias: `pip install -r requirements.txt`
