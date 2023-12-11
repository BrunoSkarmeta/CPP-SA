# CPP-SA
Simulated Annealing on Chinese Postman Problem

El CPP es un problema $NP$-completo, que dado un grafo $G$ simple, finito y conexo con pesos en sus aristas, buscar un camino cerrado (que empiece y termine en el mismo vértice) de peso mínimo. Para esto, buscaremos soluciones a partir de la técnica Simulated Annealing (recocido simulado).
Esta técnica se basa en que a partir de un grafo donde los nodos son posibles soluciones factibles y las aristas existen cuando hay una relación simétrica entre dos posibles soluciones, se va explorando el grafo a partir de la aleatoriedad, donde la posible solución va cambiando a 
partir de ciertos algoritmos estocásticos. Dependiendo de la construcción de este grafo, su relación de vecinos y sus parámetros, se puede probar teóricamente que converge a una solución óptima.

La construcción del grafo y el acercamiento a la resolución del problema, incluído el algoritmo se encuentran en Modelamiento.md, mientras que el el código aplicado se encuentra en un python notebook, llamado algoritmo.ipynb. En este código, se encuentra resuelto un ejemplo de juguete de grafo completo de 7 nodos, donde la representación de la solución se encuentra en scatter.gif.
