# Tarea--Uso-de-la-clase-Vector-en-C-
Tarea 1 de Lógica de Programación (UCE) - Implementación del Ejercicio Propuesto 2 sobre el uso de std::vector de objetos (struct) en C++. Incluye compilación y pruebas de ejecución.

Figura 1: Ejecución del programa de Vectores Paralelos (Ejercicio Propuesto 1).
Se muestra el flujo completo del sistema: la inserción de 6 productos usando push_back(), la impresión del inventario formateado a dos decimales, la eliminación exitosa del producto "Lápiz" mediante erase() con validación previa, el cálculo del precio promedio del inventario ($194.80) y la identificación automática de la "Mochila" como el artículo de mayor precio.
<img width="1902" height="987" alt="Screenshot 2026-08-12 205343_edited" src="https://github.com/user-attachments/assets/b80f2862-97a4-4ea8-b925-4b5df29bc78b" />

Figura 2: Ejecución del programa con Vector de Objetos (Ejercicio Propuesto 2).
Se muestra el flujo del programa en consola dividido en 4 secciones clave: la impresión del inventario inicial cargado con struct Producto y push_back(), la modificación directa del precio del "Lápiz" a $15.00 accediendo por índice (inventario[i].precio), el cálculo del precio promedio ($233.88) y la demostración del acceso seguro con at(), mostrando una lectura correcta y la captura de la excepción out_of_range al consultar el índice inválido 10.

<img width="1920" height="1026" alt="Screenshot 2026-08-12 210016_edited" src="https://github.com/user-attachments/assets/ae3f9e51-0429-44ca-ae53-3e09b5cf8d8f" />

## Tecnologías y Herramientas Utilizadas
- **Lenguaje:** C++ (Estándar C++17)
- **Biblioteca Estándar (STL):** `<vector>`, `<string>`, `<algorithm>`, `<iostream>`, `<iomanip>`, `<stdexcept>`
- **Entorno de Desarrollo / Compilador:** OnlineGDB / GCC
- **Control de Versiones:** Git & GitHub
