#### 2. a- Pourquoi `UpdateBookAuthor` possède uniquement l’identifiant de `CrupdateBook` et l’identifiant de Author, mais sans les autres propriétés telles que bookName et authorName comme dans leur composant respectif ?
Car ici c'est juste pour lier un `book` et un `author` ainsi leurs identifiants seuls suffit d'éffectuer cette tâche.

#### 2. b- Dans quel cas, UpdateBookAuthor devrait avoir les propriétés de `CrupdateBook` et de Author
Dans le cas où ces `book` et `author` sont des ressources qui ne sont pas encore enregistrées dans le server.

#### 3. a- Pourquoi les paginations sont-elles nécessaires ?
Car ça permet de gérer de manière efficace de grandes quantités de données, améliore les performances et l’utilisation des ressources.	

#### 4. a- Est ce qu’on peut gérer la pagination à travers les entêtes de la requête ?
Oui. Car on peut filter des données à travers des paths parameters même si ce n'est pas très faisable comme avec ce `GET /authors`.

#### 4. b-  Est ce qu’on doit gérer la pagination à travers les entêtes de la requête ?
Non. Car les entêtes de la requête sont pour identifier une ressource et non pas faire des filtres