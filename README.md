# Diagramme de classe

![Classes](uml/classes.png)

## Vrai ou faux

Etant donné le diagramme de domaine ci-dessus, les assertions suivantes sont-elles vraies ou fausses ?

- Etudiant est une classe d’association **F**
- Un étudiant peut participer à autant de cours qu’il veut. **V**
- Plusieurs professeurs peuvent enseigner la même discipline. **F**
- Un professeur peut enseigner plusieurs disciplines. **V**
- Un cours peut être enseigner à 2 étudiants. **F**
- Un cours peut être enseigner à 20 étudiants. **V**

## Question ouverte

Représentez la même association avec la notation UML « petit losange »

- Quelles informations perd-on par rapport au diagramme ci-dessus ?

1. Un cours est forcément lié à un professeur et à une discipline. Hors, maintenant il se peut qu'un cours n'ait pas de discipline.
1. On n'arrive plus à déduire le fait qu'un professeur puisse enseigner à plus de 30 étudiants (cours différents)
