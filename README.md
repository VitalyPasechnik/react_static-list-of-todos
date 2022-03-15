# React static list of TODOs
- Replace `<your_account>` with your Github username in the
  [DEMO LINK](https://<your_account>.github.io/react_static-list-of-todos/)
- Follow the [React task guideline](https://github.com/mate-academy/react_task-guideline#react-tasks-guideline)

## Task
Import `todos` and `users`, add a user to each todo and render them in the 
list.

1. Create a `preparedTodos` array basing on `todos`. Each prepared todo should
   have a `user` property with a link to a user from `users` array or `null`if
   we can't find a use by `userId`. It should be stored in the `App`.
2. Create a `TodoList` component accepting an array of `preparedTodos` and 
   rendering them as a list
3. Create a `UserInfo` component accepting a `user` object and use it to render
   a `todo.user` in the list with some styling. (Show at least a `name` and an
   `email` of the `user`)
4. Create a `TodoInfo` component accepting a `todo` object and use it in the 
   list to render `title`, `completed` status and `User`

Hint: You can add only the props you use to the `User` interface. `Todo` 
interface should have a `user` property that could be a `User` or `null`. 

Импортируйте задачи и пользователей,
добавьте пользователя в каждую задачу и отобразите их в списке.

1. Создайте подготовленный массив Todos на основе todos. 
Каждое подготовленное задание должно иметь
- пользовательское свойство со ссылкой на пользователя из массива пользователей 
- ілі null, если мы не можем найти применение по userId. Он должен храниться в приложении.
2. Создайте компонент TodoList, 
принимающий массив подготовленных задач и отображающий их в виде списка.
3. Создайте компонент UserInfo, 
принимающий объект пользователя, и используйте его для отображения 
- todo.user в списке с некоторым стилем. (Покажите хотя бы имя и адрес электронной почты пользователя)
4. Создайте компонент TodoInfo, принимающий объект todo, и используйте его в списке для отображения 
- заголовка, 
- завершенного статуса и пользователя.

Подсказка: вы можете добавить в пользовательский интерфейс только те реквизиты, которые используете. 
Интерфейс Todo должен иметь пользовательское свойство, которое может быть User или null.
