# Master
# 🌙 Sistema de Clasificación Automática de Consultas — Tres Lunas Serenas

Este repositorio contiene la solución de Procesamiento de Lenguaje Natural (PNL) desarrollada para **Tres Lunas Serenas** (comercio electrónico de velas artesanales, sales gourmet y productos de bienestar). 

El proyecto evalúa y compara tres arquitecturas avanzadas basadas en *Transformers* (**DistilBERT**, **BERT Base** y **XLM-RoBERTa**) para clasificar automáticamente las intenciones de los clientes y alimentar un sistema de enrutamiento inteligente para un chatbot de atención 24/7.

---

## 🎯 Caso de Uso

El crecimiento del comercio electrónico de Tres Lunas Serenas incrementó la saturación en los canales de atención (WhatsApp, correo electrónico y chat web). Para automatizar la respuesta sin perder la calidez de la marca, el sistema clasifica el texto de los clientes en tres categorías clave:

1. **`Informacion_Producto` (Label 0):** Consultas sobre ingredientes, aromaterapia, cera de soya, usos de sales gourmet o recomendaciones generales.
2. **`Soporte_Reclamos` (Label 1):** Reportes de frascos dañados, inconformidades con pagos, cancelaciones o solicitudes de facturación.
3. **`Envios_Logistica` (Label 2):** Preguntas sobre tiempos de entrega, costo de flete, coberturas y seguimiento de guías.

---

## 💻 Entorno de Ejecución

Para replicar el entrenamiento y la evaluación de los modelos, se recomienda el siguiente entorno de ejecución:

* **Plataforma:** Google Colab o entorno local Linux/Windows.
* **Acelerador de Hardware:** GPU Nvidia T4 (o superior) con mínimo 12 GB de VRAM.
* **Versión de Python:** Python 3.10+
* **Frameworks Principales:** PyTorch, Hugging Face `transformers`, `datasets` y `accelerate`.

---

## 🚀 Pasos de Ejecución

### 1. Clonar el Repositorio
```bash
git clone [https://github.com/tu-usuario/tres-lunas-serenas-nlp.git](https://github.com/tu-usuario/tres-lunas-serenas-nlp.git)
cd tres-lunas-serenas-nlp
