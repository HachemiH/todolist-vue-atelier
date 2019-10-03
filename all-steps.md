# Toutes les étapes pour créer une Todo Liste sous Vue JS

1. Création du projet `vue create todolist`
2. Nettoyage du boilerplate (suppression des composants, nettoyage de `App.vue`)
3. Installation de [Bulma](https://bulma.io/)
4. Création du composant `TodoList.vue`
5. Câbler le composant `TodoList.vue`  vers `App.vue` (import)
6. Création du composant `TodoInputText.vue`
7. Câbler le composant `TodoInputText.vue` vers `TodoList.vue` (export, import)
8. Insérer un `input` de `Bulma` dans le composant `TodoInputText.vue`
9. Ajouter de la `data` dans le composant `TodoList.vue`
10. Création du composant `TodoListItem.vue`
11. Câbler le composant `TodoListItem.vue` vers `TodoList.vue` (export, import, props)
  11.1 `ul` dans `TodoList.vue` et `li` dans `TodoListItem.vue`
  11.2 `props` dans `TodoListItem.vue`
12. Brancher un `v-model` sur la balise `TodoInputText` dans `TodoList.vue`
13. Brancher un écouteur de la touche `enter` pour déclencher la méthode `addTodo` dans la balise `TodoInputText` dans `TodoList.vue`
14. Créer la méthode `addTodo`
15. Créer un compteur `nextTodoId` en variable globale
16. Ajouter une propriété `id` pour chaque item dans la `data`
17. Ajouter un écouteur `remove` dans la balise `TodoListItem` dans `TodoList.vue` pour enclencher la méthode `removeTodo`
18. Créer la méhtode `removeTodo`
19. Ajouter un bouton de suppression dans le `li` dans `TodoListItem.vue` qui déclence un évènement `remove` et qui prend un argument `todo.id`
