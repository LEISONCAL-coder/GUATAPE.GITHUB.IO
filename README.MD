# 📋 AUDITORÍA TÉCNICA PRO – VÍA GUATAPÉ

### Acta Digital de Auditoría y Control Constructivo

![Image](https://www.huila.gov.co/info/huila_bco/media/pubInt/thumbs/thpubInt_700X400_14189.webp)

![Image](https://estaticos.elcolombiano.com/binrepository/780x585/0c10/780d565/none/11101/UACW/nuevas-vias-en-antioquia_47455786_20250321125507.jpg)

![Image](https://www.pereira.gov.co/info/pereira_se/media/pub/thumbs/thpub_700X400_639.webp)

![Image](https://prensalibrecasanare.com/uploads/posts/2019-05/1558090947_recetor-alcantarillas-veredas11.jpg)

Aplicación web desarrollada en **HTML, CSS y JavaScript puro** para la generación digital de actas de auditoría técnica en obras viales rurales.

Diseñada específicamente para el proyecto:

**Vía Rural Granada – Guatapé (Sector La Sonadora y La Peña)**

Optimizada para uso en **campo (celular / tablet)** y generación inmediata de **PDF imprimible**.

---

## 🚀 Características

* ✅ Evaluación técnica por ítem constructivo
* 🚦 Sistema semáforo (Cumple / No cumple / N/A)
* 📸 Evidencia fotográfica múltiple por actividad con **compresión automática**
* 📝 Observaciones detalladas
* 🖨 Generación de PDF lista para impresión
* 📱 Diseño 100% responsive
* 🌐 **PWA Complete**: Funciona sin servidor y **offline** (gracias a Service Workers)
* 🖊 **Firma Digital Táctil**: Integración de Canva para dibujar firmas directamente en la pantalla
* 📦 **Guardado y Carga**: Exportación e importación de actas en formato **.json**
* 🔒 Sin base de datos ni almacenamiento externo

---

## 🧱 Estructura del Proyecto

```
📁 auditoria-tecnica-pro/
 ├── 📄 index.html
 ├── 📄 manifest.json (Configuración PWA)
 └── 📄 sw.js (Service Worker para uso offline)
```

El archivo contiene:

* Maquetación HTML completa
* Estilos CSS (responsive + impresión)
* Lógica JavaScript embebida

No requiere:

* Frameworks
* Librerías externas
* Backend
* Base de datos

---

## 📂 Módulos de Auditoría Incluidos

### 1️⃣ Preliminares

* Localización y replanteo
* Verificación de EPP
* Desmonte y limpieza

### 2️⃣ Construcción de Placa Huella

* Excavaciones mecánicas y manuales
* Terraplenes
* Subbase granular
* Concreto Clase D (21 MPa)
* Concreto ciclópeo
* Acero de refuerzo
* Transporte de materiales

### 3️⃣ Construcción de Cunetas

* Excavación manual
* Descapote
* Concreto estructural
* Refuerzo
* Transporte de sobrantes

### 4️⃣ Obras de Drenaje

* Solados
* Muros y disipadores
* Tubería PVC 36"
* Llenos compactados

### 5️⃣ Obras Adicionales

* Demoliciones
* Señalización vertical
* Transporte de escombros

---

## ⚙️ Funcionalidades Técnicas

### 📅 Fecha automática

Se establece automáticamente al cargar el documento.

### 🖼 Carga dinámica de logos

Permite adjuntar:

* Logo Alcaldía
* Logo Interventoría

### 📸 Galería por ítem

Cada fila contiene:

* Subida múltiple de imágenes
* Eliminación individual con clic
* Visualización tipo galería

### 🚦 Sistema de estados

Cambio dinámico de color según selección:

* 🟢 CUMPLE
* 🔴 NO CUMPLE
* ⚪ N/A

### 🖨 Modo impresión optimizado

Incluye:

* Ajustes tipográficos
* Control de saltos de página
* Conservación de colores
* Eliminación automática de botones y controles

### 💾 Exportación / Importación (JSON)

* Permite guardar el estado completo del acta en un archivo `.json`
* Permite cargar un acta previamente guardada para continuar la edición o reimprimir
* Incluye botones flotantes dedicados a la gestión de datos

### ✍️ Firmas Digitales (Táctil)

* Espacios dedicados para el Ingeniero Interventor, Residente y Supervisión.
* Integración con ventana modal Canvas para escritura directa con el dedo o stylus.

---

## 📱 Diseño Responsive

En dispositivos móviles:

* Las tablas se transforman en tarjetas
* Las etiquetas se generan automáticamente
* Las imágenes se organizan en 2 columnas
* Las firmas se apilan verticalmente

---

## 🖥️ Uso

### 1️⃣ Clonar repositorio

```bash
git clone https://github.com/tuusuario/auditoria-tecnica-pro.git
```

### 2️⃣ Abrir archivo

```
index.html
```

Abrir directamente en navegador (Chrome recomendado).

### 3️⃣ Diligenciar información

* Contratista
* Fecha
* Abscisas
* Interventor
* Evaluación por ítem
* Adjuntar evidencias

### 4️⃣ Generar PDF

Presionar:

```
🖨 Generar PDF
```

O usar:

```
Imprimir → Guardar como PDF
```

---

## 🔒 Consideraciones

* No guarda información al cerrar el navegador.
* Las imágenes se almacenan temporalmente en memoria.
* Ideal para generar PDF inmediatamente después de diligenciar.
* No sustituye sistema oficial de gestión documental.

---

## 🛠 Posibles Mejoras Futuras

* Guardado automático en `localStorage`
* Generación automática de consecutivo
* Firma digital táctil
* Exportación directa a PDF sin diálogo
* Backend opcional con almacenamiento en nube
* Dashboard de seguimiento de auditorías
* Integración con sistemas municipales

---

## 👷 Perfil de Usuario

* Ingeniero Interventor
* Residente de obra
* Supervisor municipal
* Inspector técnico
* Entidades públicas

---

## 📄 Licencia

Uso institucional y técnico.
Puede modificarse y adaptarse según requerimientos contractuales.

---

## 📌 Estado del Proyecto

🟢 Versión estable funcional
📱 Optimizada para trabajo en campo
🖨 Lista para generación de actas oficiales en PDF

---

Si deseas, puedo prepararte también:

* 📘 Manual de usuario profesional
* ☁ Versión con almacenamiento en nube
* 🖊 Versión con firma digital
* 🏛 Versión con branding institucional
* 🧾 Versión con numeración automática de actas

Solo dime cuál deseas desarrollar.
