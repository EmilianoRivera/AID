# Directorio de Expedientes NNA (Niñas, Niños y Adolescentes)
> **Desarrollador:** Rivera Segura Jose Emiliano  
> **Institución:** Instituto Politécnico Nacional - ESCOM  
> **Materia:** Análisis y Diseño de Sistemas 
> **Grupo:** 4BV1

## 📌 Descripción del Proyecto
Este primer programa está enfocada a agregar, actualizar, eliminar o buscar expedientes de niñas, niños y adolescentes, por lo que es un una primera idea de diseñado para la gestión de expedientes de menores. Para el manejo de la información se utiliza una estructura de **Pilas o Stack** implementada usando **Listas Enlazadas** en C.

## 🛠️ Funcionalidades
* **Agregar Expediente:** Se capturan los datos de identificación del menor como: CURP, Nombre, Edad e información para la elaboración del reporte.
* **Modificar:** Permite la actualización de Domicilio, Edad y Descripción Física.
* **Buscar:** Funcionalidad para extraer toda la información del expediente que se quiera usando el CURP.
* **Listar:** Se visualizan todos los datos de los expedientes.
* **Eliminar:** Se borra el expediente requerido, siguiento también las reglas de la estructura de **Pila**.

## 📂 Estructura del Código
El programa consta de una plantilla de estructuras que representan al NNA, posteriormente el flujo que esta en la función main y finalmente las funciones:
* `main.c`: Código principal del programa.
  
## 🚀 Para Compilar
Para compilar el proyecto correctamente, se puede correr desde el editor de texto **VS Code ** o usar el siguiente comando:
```bash
gcc main.c implementacion.c -o main.c


