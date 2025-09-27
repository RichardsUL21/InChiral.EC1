# 🌀 Inchiral – Detección de Quiralidad

![Logo del proyecto](imagenes/logo_inchiral.png)

**Inchiral** es una aplicación interactiva y educativa desarrollada en **Streamlit**.  
Su propósito es detectar la **quiralidad** en moléculas, analizar sus posibles estructuras, generar **estereoisómeros** y permitir su **visualización 3D**.

---

## 🎯 Propósito del proyecto
- Comprender el concepto de **quiralidad** en química orgánica.  
- Determinar si una molécula es **quiral o aquiral**.  
- Generar y visualizar **estereoisómeros en 3D**.  
- Servir como recurso **didáctico** en el aprendizaje de química.  

---

## 🧪 ¿Qué es la quiralidad?
La **quiralidad** es una propiedad geométrica de ciertas moléculas cuya estructura **no es superponible con su imagen especular**, como ocurre con las manos (izquierda y derecha).  

Esto origina moléculas llamadas **enantiómeros**, que pueden compartir propiedades químicas pero mostrar **efectos biológicos distintos**.  
Un ejemplo histórico es el caso de la **talidomida**, donde un enantiómero era terapéutico y el otro dañino.

---

## 📸 Vista previa de la aplicación

### Pantalla principal
![Vista principal](imagenes/streamlit_home.png)

### Ejemplo de detección de quiralidad
![Detección de quiralidad](imagenes/streamlit_chiral.png)

### Visualización 3D
![Visualización 3D](imagenes/streamlit_3d.png)

---

## 📂 Estructura del proyecto
- `app.py`: Código principal de la aplicación.  
- `imagenes/`: Carpeta con logos y recursos gráficos.  
- `requirements.txt`: Dependencias necesarias para ejecutar la app.  

---

## ⚙️ Instalación y uso
### Requisitos
- **Python 3.9 o superior**  
- Paquetes principales:  
  - `streamlit`  
  - `rdkit`  
  - `pandas`  

### Instalación
```bash
git clone https://github.com/RichardsUL21/InChiral.EC1.git
cd InChiral.EC1
pip install -r requirements.txt
## 📊 Comparación de Licencias

| Licencia | Características | Pertinencia para este trabajo |
|----------|-----------------|-------------------------------|
| **GNU GPL v3.0** | Obliga a que cualquier modificación o redistribución mantenga la misma licencia. Garantiza libertad de uso, estudio, modificación y distribución. | Asegura que el proyecto siga siendo software libre en futuras versiones, protegiendo el código de usos privativos. Ideal para un enfoque académico y colaborativo. |
| **MIT License** | Permite usar, modificar y distribuir con mínimas restricciones, incluso en proyectos propietarios, siempre que se mantenga la atribución original. | Ofrece máxima flexibilidad, incluso para uso comercial. Sin embargo, no garantiza que las mejoras futuras permanezcan abiertas. |

---

## ✅ Elección de Licencia

Se eligió la **GNU General Public License v3.0 (GPL-3.0)** porque:  

- Garantiza que el proyecto se mantenga como **software libre** en futuras versiones.  
- Protege contra la apropiación **privativa** del código.  
- Refuerza el espíritu **académico y colaborativo** en el que se desarrolló este trabajo.  

👉 Puedes consultar el texto completo de la licencia aquí:  
[GNU GPL v3.0 – Texto oficial](https://www.gnu.org/licenses/gpl-3.0.html)

