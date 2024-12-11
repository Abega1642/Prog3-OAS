### 2. a- Pourquoi `UpdateBookAuthor` possède uniquement l’identifiant de `CrupdateBook` et l’identifiant de Author, mais sans les autres propriétés telles que bookName et authorName comme dans leur composant respectif ?
Car ici c'est juste pour lier un `book` et un `author` ainsi leurs identifiants seuls suffit d'éffectuer cette tâche.

### 2. b- Dans quel cas, UpdateBookAuthor devrait avoir les propriétés de `CrupdateBook` et de Author
Dans le cas où ces `book` et `author` sont des ressources qui ne sont pas encore enregistrées dans le server.
