# Directorio de Expedientes NNA (Niñas, Niños y Adolescentes)
> **Desarrollador:** Rivera Segura Jose Emiliano  
> **Institución:** Instituto Politécnico Nacional - ESCOM  
> **Materia:** Estructuras de Datos  
> **Grupo:** 4BV1

## 📌 Descripción del Proyecto
Este programa es un CRUD (Create, Read, Update, Delete) diseñado para gestionar expedientes de menores en el marco de la **Ley General de los Derechos de Niñas, Niños y Adolescentes**. Utiliza una estructura de **Pila (Stack)** implementada mediante **Listas Enlazadas** en lenguaje C.

## 🛠️ Funcionalidades
* **Agregar Expediente:** Captura datos de identificación (CURP, Nombre, Edad) y del reporte inicial.
* **Modificar:** Permite la actualización selectiva de Domicilio, Edad y Descripción Física.
* **Buscar:** Localización inmediata de expedientes mediante la CURP.
* **Listar:** Visualización de todos los registros almacenados en la memoria dinámica.
* **Eliminar:** Borrado seguro de nodos y liberación de memoria física.

## 📂 Estructura del Código
El proyecto está modularizado para separar la lógica de los datos:
* `main.c`: Manejo del menú e interfaz de usuario.
* `plantillas.h`: Definición de estructuras (`DatosNNA`, `DatosReporte`) y prototipos.
* `implementacion.c`: Lógica de punteros y gestión de la lista enlazada.

## 🚀 Instrucciones de Compilación
Para compilar el proyecto correctamente, utiliza el siguiente comando en tu terminal:
```bash
gcc main.c implementacion.c -o programa_nna
