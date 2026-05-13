# Práctica de Estructuras de Datos - Árboles

<div align="center">

Universidad Técnica de Ambato |
Ingeniería en Sistemas, Electrónica e Industrial |
Software - Tercero 

</div>
Nombre: Monserrath Medina

---

##  Objetivos

### General
Desarrollar habilidades en el trabajo con árboles.

### Específicos
1. Implementar operaciones fundamentales sobre árboles N-arios y árboles binarios utilizando recursividad.
2. Aplicar recorridos (In-Order) y transformaciones (inversión) para manipular la estructura de árboles.
3. Diferenciar el comportamiento y aplicación de árboles N-arios vs Árboles Binarios de Búsqueda (BST).

---
##  Descripción

Este repositorio contiene la solución completa de **5 ejercicios prácticos** sobre árboles, desarrollados en **C++** y **Java**. Cada ejercicio implementa operaciones fundamentales para trabajar con estructuras jerárquicas:

- Árboles **N-arios**
- Árboles **Binarios** y **Árboles Binarios de Búsqueda (BST)**
- Recorridos **(In-Order)**
- Transformaciones **(Inversión/Árbol espejo)**

---

##  Estado del Proyecto

| Estado | Compleción |
|--------|-------------|
|  **COMPLETADO** | 5/5 ejercicios (C++ + Java) |

---

## Estructura del Repositorio

- 📂 Guia_Ape3_Arboles
  - 📂 C++
    - 📄 Ejercicio1_Basico.cpp
    - 📄 Ejercicio2_Binario.cpp
    - 📄 Ejercicio3_Binario.cpp
    - 📄 Ejercicio4_Recorridos.cpp
    - 📄 Ejercicio5_Transformacion.cpp
  - 📂 Java
    - 📄 Ejercicio1_Basico.java
    - 📄 Ejercicio2_Binario.java
    - 📄 Ejercicio3_Binario2.java
    - 📄 RecorridoInOrder.java
    - 📄 Ejercicio5_Transformacion.java
  - 📄 Informe.pdf
  - 📄 README.md


## 📊 Ejercicios Implementados en Java y C++

| # | Ejercicio | Concepto |
|---|-----------|----------|
| 1 | Conteo de nodos | Árbol N-ario + Recursividad 
| 2 | Inserción en BST | Árbol Binario de Búsqueda
| 3 | Cálculo de altura | Profundidad máxima 
| 4 | Recorrido In-Order | Izquierda → Nodo → Derecha
| 5 | Inversión del árbol | Árbol espejo 
---
## Analisis de Resultados
Los 5 ejercicios fueron implementados exitosamente tanto en C++ como en Java. Se desarrollaron habilidades fundamentales en el trabajo con arboles:
- **Recursividad:** Todos los ejercicios utilizaron recursion como tecnica principal para recorrer y transformar los arboles, demostrando que es la aproximacion mas natural para estructuras jerarquicas.

- **Arboles N-arios vs Binarios:** Se evidencio la diferencia estructural fundamental:
  - Arbol N-ario: cada nodo contiene un vector de hijos
  - Arbol binario: cada nodo tiene maximo 2 hijos (izquierdo y derecho)

- **Propiedad BST:** La insercion en BST respeta la propiedad de orden, permitiendo busquedas eficientes en O(log n).

- **Recorrido In-Order:** Sobre un BST produce automaticamente una secuencia ordenada de menor a mayor.

- **Transformacion estructural:** La inversion modifica completamente la forma del arbol intercambiando recursivamente los punteros de los hijos.

## Conclusiones del análisis 
La implementación de los cuatro recorridos en ambos lenguajes permitió comprender las ventajas y desventajas de cada uno. C++ ofrece mayor control y rendimiento, mientras que Java facilita la implementación con su gestión automática de memoria. Los resultados obtenidos coinciden con los valores teóricos esperados, validando la correcta implementación de los algoritmos recursivos y el uso de la cola para BFS. La aplicación al caso del sistema web demostró la utilidad práctica de los recorridos en escenarios reales de desarrollo de software.

## Referencias Bibliograficas

[1] L. Joyanes Aguilar, Estructuras de datos en C++, 2nd ed. Mexico D.F.: McGraw-Hill, 2005, pp. 256-280.

[2] M. A. Weiss, Estructuras de datos y algoritmos, 2nd ed. Madrid: Pearson Educacion, 2007, pp. 112-135.

[3] J. J. Rodriguez Vega, "Implementacion de Recorridos en Arboles Binarios," Revista Tecnologica ESPOL, vol. 28, no. 5, pp. 45-53, Dec. 2015.

[4] F. J. Garcia Izquierdo, Algoritmos y estructuras de datos en Java. Madrid: RA-MA Editorial, 2018, pp. 189-210.

[5] R. Sedgewick and K. Wayne, Algoritmos, 4th ed. Barcelona: Addison-Wesley, 2012, pp. 78-94.

## Comparacion entre Java y C++

| Aspecto | C++ | Java |
|---------|-----|------|
| Manejo de memoria | Manual con new y delete | Automatico con Garbage Collector |
| Punteros vs Referencias | Usa punteros (*) y referencias (&) | Solo referencias |
| Paso de parametros | Por valor, puntero o referencia | Siempre por valor |
| Verificacion de nulos | nullptr (C++11) o NULL | null |
| Sobrecarga de operadores | Permitida | No permitida |
| Librerias para listas | vector<> de STL | ArrayList<> |
| Funciones matematicas | max() de algorithm | Math.max() |
| Compilacion | Fuente -> objeto -> ejecutable | Fuente -> bytecode -> JVM |
| Velocidad | Generalmente mas rapido | Mas lento por JVM |
| Portabilidad | Depende del compilador y SO | Multiplataforma |

# Compilación y ejecución (C++)
# Compilar
g++ -std=c++11 Ejercicio1_Basico.cpp -o ejercicio1
# Ejecutar
./ejercicio1

# Compilación y ejecución (java)
# Compilar
javac Ejercicio1_Basico.java

# Ejecutar
java Ejercicio1_Basico



