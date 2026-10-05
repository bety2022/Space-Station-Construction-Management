# 🚀 Salesforce App: Space Station Construction Management

![Salesforce](https://img.shields.io/badge/Salesforce-Lightning%20Platform-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![Trailhead](https://img.shields.io/badge/Trailhead-Mountaineer-00A1E0?style=for-the-badge&logo=salesforce)
![Badge](https://img.shields.io/badge/Badge-Build_a_Space_Station_App-FFB800?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 📌 Visión General del Proyecto

Este repositorio documenta el diseño, la configuración de datos, las reglas de automatización y los paneles analíticos creados en la plataforma **Salesforce Lightning Platform** para la gestión declarativa del proyecto **Space Station Construction**.

El proyecto cubre el ciclo de vida completo de la construcción, control de recursos y auditoría de la estación espacial, culminando con la obtención exitosa de la insignia oficial de Trailhead **"Build a Space Station App"**.

---

## 🛠 Arquitectura y Componentes Desarrollados

### 1. Modelo de Datos Relacional y UX
* **Aplicación Personalizada:** Creación de la app **Space Station Construction** con pestañas de navegación dedicadas (`Space Stations`, `Reports`, `Dashboards`).
* **Objeto Principal:** `Space Station` (Estación Espacial).
* **Objetos Relacionados (Master-Detail):**
  * `Resource` (Personal, Tripulación e Inspectores).
  * `Supply` (Piezas, herramientas y suministros).
* **Interfaz de Usuario:** Personalización de páginas Lightning para registros como **Mothership**, incorporando listas relacionadas compactas y componentes de conversación en vivo vía **Chatter**.

### 2. Reglas de Negocio e Integridad de Datos (*Validation Rules*)
* **Auditoría de Utilización:** Implementación de reglas de validación en el objeto `Resource` para exigir una asignación mínima del 150% en roles clave (*Exhaust Port Inspector*):
  ```text

 
### 3. Automatización Declarativa de Procesos (*Flow Builder*)

* **Flujo Desencadenado por Registro (`Record-Triggered Flow`):** *Fully Operational Space Station*.
* **Lógica de Ejecución:** Cuando el campo `Shield Status` cambia a **Fully Operational**:
1. Actualización automática del campo `Project Status` a **Complete**.
2. Publicación automatizada en el feed de **Chatter** notificando la protección total de la estación espacial.



### 4. Informes y Dashboards (*Reports & Dashboards*)

* **Reporte `Supplies`:** Reporte tabular agrupado por estación con cálculo agregador de costos (`Quantity`, `Unit Cost`, `Total Cost`).
* **Dashboard `Construction`:** Visualización gráfica en barra del costo total acumulado por estación espacial.

---

## 📸 Proceso de Implementación Paso a Paso

| N.º | Descripción del Paso | Vista Previa |
| --- | --- | --- |
| **01** | Creación del espacio de trabajo y app **Space Station Construction**. | [(https://github.com/bety2022/Space-Station-Construction-Management/blob/main/1.png)] |
| **02** | Progreso de validación en Trailhead (+100 pts). | *(Arrastra aquí la imagen 2)* |
| **03** | Configuración inicial del registro de la estación espacial **Mothership**. | *(Arrastra aquí la imagen 3)* |
| **04** | Vinculación de listas relacionadas (`Resources` y `Supplies`). | *(Arrastra aquí la imagen 4)* |
| **05** | Comprobación de requisitos del modelo de objetos (+100 pts). | *(Arrastra aquí la imagen 5)* |
| **06** | Configuración y activación del flujo en **Flow Builder** (*Fully Operational Space Station*). | *(Arrastra aquí la imagen 6)* |
| **07** | Prueba E2E: Disparo de la automatización y publicación en **Chatter**. | *(Arrastra aquí la imagen 7)* |
| **08** | Validación de lógica de negocio y automatizaciones en Trailhead (+100 pts). | *(Arrastra aquí la imagen 8)* |
| **09** | Creación y ejecución del reporte analítico **Supplies**. | *(Arrastra aquí la imagen 9)* |
| **10** | Configuración del panel de control gráfico **Dashboard** (*Construction Supplies*). | *(Arrastra aquí la imagen 10)* |
| **11** | Notificación de logro: ¡Obtención de la insignia oficial! | *(Arrastra aquí la imagen 11)* |
| **12** | Registro de la racha semanal de aprendizaje en Trailhead (*1 Week Streak*). | *(Arrastra aquí la imagen 12)* |
| **13** | Estado del proyecto al 100% completado en Trailhead (+500 pts). | *(Arrastra aquí la imagen 13)* |
| **14** | Ficha técnica de la insignia ganada **Build a Space Station App**. | *(Arrastra aquí la imagen 14)* |

---

## 🏆 Insignia Obtenida

> **Build a Space Station App** — *Build a project management app to construct a galactic Space Station. No code required.*
> * **Completado:** 5/5 Módulos finalizados.
> * **Puntos ganados:** +500 pts.
> * **Fecha:** 4 de Octubre de 2026.
> 
> 

---

## 👩‍💻 Desarrolladora

* **Nombre:** Carolina Lopez
* **Perfil Trailblazer:** [salesforce.com/trailblazer/lopezcarolina](https://www.salesforce.com/trailblazer/lopezcarolina)
* **Rango Trailhead:** Mountaineer
* **Especialidades:** Flow Builder, Data Modeling, Validation Rules, Reports & Dashboards.

```

```

 
