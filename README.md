As conexións entre os nodos cos custos de ir de un a outro son os seguintes :
![Mapa](https://github.com/RPereiro/Ourense-Calatayud-Busqueda-por-costo-unniforme/assets/152397748/f2ac038e-f33e-4227-a536-1c51e07de2a1)

- Agora vemos como se van extendendo os nodos acorde ó o algoritmo de búsqueda empregado neste exercicio:
  
  Cando un nodo xa está no conxunto de nodos explorados, xa non se amosa como unha posíbel rama ao extender os nodos, así descartamos ir cun custo maior a un nodo xa explorado. 
  Tamén se para a busca nunha rama cando hai outra que leva ó mesmo nodo cun custo menor.

![Arbol](https://github.com/RPereiro/Ourense-Calatayud-Busqueda-por-costo-unniforme/assets/152397748/74dda5a1-f50d-43e9-b2e5-6624e3d64e52)

- Desenvolvemento do problema:
  
  Á dereita aparecen os nodos explorados indicando con que custo se chegou a cada un.

![Desarrollo_algoritmo _00](https://github.com/RPereiro/Ourense-Calatayud-Busqueda-por-costo-unniforme/assets/152397748/bf80d210-db3d-4603-8bc8-8a061a44edfd)
![Desarrollo_algoritmo _01](https://github.com/RPereiro/Ourense-Calatayud-Busqueda-por-costo-unniforme/assets/152397748/c0244849-aed0-4437-8c05-b6c3f24237ae)
