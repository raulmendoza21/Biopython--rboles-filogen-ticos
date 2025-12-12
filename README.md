# PRACTICA 1 - ARBOLES FILOGENETICOS CON BIOPYTHON

**Asignatura:** Bioinformatica  
**Grado:** Bioinformatica / Ciencia e Ingenieria de Datos  
**Universidad:** Universidad de Las Palmas de Gran Canaria (ULPGC)

**Autores:**  
- Raul Mendoza  
- Adrian Ojeda  

---

## DESCRIPCION GENERAL

En esta practica se trabaja con arboles filogeneticos utilizando la libreria
BioPython, concretamente el modulo `Bio.Phylo`. El objetivo principal es aprender
a leer, analizar y modificar arboles filogeneticos en formato **Newick**, que es
uno de los formatos estandar mas utilizados en bioinformatica.

La practica se divide en dos ejercicios principales:

1. Analisis de un arbol filogenetico.  
2. Modificacion y representacion visual del arbol.

Todo el trabajo se ha realizado en un cuaderno Jupyter (`.ipynb`) para facilitar
la ejecucion paso a paso y la comprension del proceso.

---

## REQUISITOS

Para poder ejecutar la practica es necesario disponer de:

- Python 3.9 o superior  
- BioPython  
- matplotlib  
- Jupyter Notebook  

Las dependencias pueden instalarse con:

```bash
pip install biopython matplotlib
```

---

## EJERCICIO 1: LECTURA Y ANALISIS DE UN ARBOL NEWICK

En este ejercicio se carga un arbol filogenetico en formato Newick. En nuestro
caso se utiliza un arbol de ejemplo definido directamente en el codigo para
asegurar que el notebook sea reproducible.

A partir del arbol se realizan las siguientes tareas:

- Lectura del arbol usando `Phylo.read()`.
- Visualizacion basica del arbol.
- Obtencion del numero total de clados.
- Calculo del numero de nodos internos.
- Identificacion del numero de terminales (hojas).
- Listado de los nombres de todas las especies.
- Analisis de las longitudes de las ramas.
- Calculo de la distancia acumulada desde la raiz a cada terminal.
- Identificacion del clado interno con mayor numero de terminales.

Este ejercicio permite entender la estructura interna de un arbol
filogenetico y como acceder a su informacion de forma programatica.

---

## EJERCICIO 2: MODIFICACION DEL ARBOL FILOGENETICO

En el segundo ejercicio se realizan cambios sobre el arbol cargado en el
ejercicio anterior. El objetivo es comprobar que el arbol no es solo una
estructura estatica, sino que puede modificarse facilmente.

Las modificaciones realizadas son:

- Cambio del nombre de una especie.
- Modificacion de la longitud de una rama concreta.
- Coloreado de una rama para destacarla visualmente.

Tras aplicar los cambios, el arbol se vuelve a representar graficamente para
verificar que las modificaciones se han aplicado correctamente.

Finalmente, el arbol modificado se guarda de nuevo en formato Newick para
poder reutilizarlo o entregarlo.

---

## ESTRUCTURA DEL PROYECTO

- `Bioinformatica_ULPGC_Sesion05_Arboles_Filogeneticos.ipynb`  
  Cuaderno principal con el desarrollo completo de la practica.

- `arbol_modificado.nwk`  
  Arbol resultante tras aplicar las modificaciones del ejercicio 2.

---

## CONCLUSIONES

Esta practica sirve como una primera toma de contacto con el manejo de
arboles filogeneticos mediante codigo. Se ha aprendido a:

- Interpretar el formato Newick.
- Trabajar con clados y terminales.
- Analizar distancias evolutivas.
- Modificar y exportar arboles filogeneticos.

Los conocimientos adquiridos en esta practica son fundamentales para
trabajos posteriores relacionados con evolucion, comparacion de especies
y analisis filogenetico mas avanzado.
