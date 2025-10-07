# Proyecto ISABEL

Holaaa!
Este es el repositorio de **Isabel**, donde enviaremos los datos del **ESP32** y los muestra a través de una interfaz sencilla.  
Este README te explica **qué es cada parte** del proyecto y **cómo trabajar con él paso a paso**, igual ya sabes que si surge duda entre todos lo checamos.  

---

## I. ¿Qué es este proyecto?

El proyecto se divide en 3 partes principales:

1. **Frontend**  
   - Es la parte visual (la página web).  
   - Aquí está el código HTML, CSS y JavaScript que verán los usuarios en el navegador.

2. **Backend (Java)**  
   - Es el “cerebro” del sistema.  
   - Aquí se manejan las peticiones, se guardan datos y se conecta con la base de datos.

3. **Base de datos (SQL Server)**  
   - Aquí se almacenan los datos que envía el microcontrolador (por ejemplo, lecturas de sensores).  
   - Usamos **SQL Server** como motor de base de datos.

---

## 🧭 2. Estructura del proyecto

ISABEL/
├─ backend/ → Código en Java (servidor/API)
├─ frontend/ → Archivos HTML, CSS y JS (interfaz web)
├─ sql/ → Scripts de base de datos (tablas, datos de prueba)
├─ docs/ → Documentación técnica (API, arquitectura)
└─ README.md → Este archivo

