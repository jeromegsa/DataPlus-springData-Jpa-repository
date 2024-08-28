## Reposository
Un repository estr un composant de votre application qui gère les opérations de persistence (CRUD ) sur les entités dans un BDD. En gros c'rest la couche qui nous permet de parler à la BDD sans se soucier des détails.

## Annotation @Repository

Elle sert à marquer une classe comme étant un repository, c'est-à dire un endroit où vous allez interagir avec une BDD.

### Est-ce obligatoire ?

NOn ! Quand on implémente déjà une interface comme `JpaRepostory `,Spring détecte automatiquement toute les repository.