# 🧪 Pre-Entrega Automation Testing - SauceDemo

Proyecto de automatización de pruebas desarrollado en el marco del curso de **Automation QA** de **Talento Tech**.

---

## 📋 Descripción de la Pre-Entrega

El objetivo de esta pre-entrega es la automatización de flujos funcionales básicos en la plataforma e-commerce [SauceDemo](https://www.saucedemo.com/) utilizando **Python** y **Selenium WebDriver**, estructurado bajo el framework de pruebas **Pytest**.

### 🎯 Módulos y Pruebas Automatizadas
1. **`test_login.py` (Autenticación):**
   * Validación de inicio de sesión exitoso con credenciales válidas (`standard_user`).
   * Validación de alertas y restricciones con usuarios bloqueados o datos incorrectos.
2. **`test_inventory.py` (Catálogo / Inventario):**
   * Verificación de redirección correcta a la página de inventario (`/inventory.html`).
   * Validación del título de la página ("Products" / "Swag Labs").
   * Comprobación de visibilidad de productos en el catálogo y visualización del primer producto (nombre y precio).
3. **`test_cart.py` (Carrito de Compras):**
   * Interacción para añadir el primer producto al carrito de compras.
   * Verificación del incremento correcto en el contador del ícono del carrito.
   * Validación de que el producto seleccionado aparezca correctamente dentro del carrito.

---

## 🛠️ Tecnologías y Herramientas Utilizadas

* **Lenguaje:** Python 3.12
* **Automatización Web:** Selenium WebDriver
* **Framework de Testing:** Pytest
* **Reportes:** Pytest-HTML
* **Control de Versiones:** Git y GitHub

---

## 📂 Estructura del Proyecto

```text
automation-saucedemo-jimena-ruiz/
├── reports/              # Reportes HTML generados en las ejecuciones
│   └── reporte.html
├── tests/                # Casos de prueba automatizados (Login, Inventory, Cart)
├── pytest.ini            # Configuración de argumentos por defecto para Pytest
├── requirements.txt      # Listado de dependencias del proyecto
└── README.md             # Documentación del proyecto
```

---

## ⚙️ Instalación y Configuración

### 1. Clonar el repositorio
git clone https://github.com/J-code-bit/automation-saucedemo-jimena-ruiz.git
cd automation-saucedemo-jimena-ruiz

### 2. Instalar las dependencias necesarias
* Asegúrate de tener instalado Python en tu equipo.
* Ejecuta el comando para instalar las librerías automáticamente mediante el archivo de requerimientos:
  `pip install -r requirements.txt`
* O bien, instala las librerías de forma manual ejecutando:
  `pip install selenium pytest pytest-html`

---

## 🚀 Ejecución de las Pruebas y Reportes

* Para ejecutar todas las pruebas y generar automáticamente el reporte de resultados, utiliza el comando:
  `pytest --html=reports/reporte.html --self-contained-html`

* Una vez finalizada la ejecución, puedes visualizar el informe detallado abriendo el siguiente archivo en tu navegador:
  * `reports/reporte.html`

---

## 👩‍💻 Autora

* **Jimena Ruiz** — Curso de Automation QA (Talento Tech)

