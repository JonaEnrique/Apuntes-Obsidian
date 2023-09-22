**Definición:** 

Una dependencia funcional es una restricción entre dos conjuntos de atributos de una relación. Sea R un esquema de relación, sea r una instancia cualquiera de R y sean X e Y dos subconjuntos de R. La dependencia funcional X → Y (léase X determina a Y) se cumple si y sólo si para cualesquiera dos tuplas t1 y t2 de r, tales que: 

t1[X] = t2[X], entonces necesariamente t1[Y] = t2[Y]

Es decir, si dos tuplas cualesquiera tienen igual valor en X, deben tener igual valor en Y, para que se cumpla la dependencia funcional. 

Esto significa que los valores componentes de Y de una tupla de r dependen de los valores del componente X, o están determinados por ellos; o bien, que los valores del componente X de una tupla determinan de manera única los valores del componente Y.

![[Pasted image 20230918224328.png]]

![[Pasted image 20230918224702.png]]

Dependencia funcional [[Trivial]]
[[Clave y Superclave]]
[[Axiomas de Armstrong]]
