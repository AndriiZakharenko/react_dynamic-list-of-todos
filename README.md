# React dynamic list of TODOs

You are given the markup for the `App`, `TodosList`, `TodoFilter`, `TodoModal`
and `Loader` components. Load data from the API and show it using the given components.

1. Load [the todos](https://mate-academy.github.io/react_dynamic-list-of-todos/api/todos.json) when the `App` is
loaded and show them using `TodoList` (check the code in the `api.ts`);
1. Show the `Loader` when waiting any data from the server (check the `components` folder);
1. Check how the `wait` function is used in the `api.ts` to ensure that `Loader` works as expected;
1. When the `Show` button is clicked open the `TodoModal` with a selected `todo`;
1. Don't forget to load [user details](https://mate-academy.github.io/react_dynamic-list-of-todos/api/users/1.json) (replace `1` with the actual `userId`);
1. Show the Loader while waiting for the user;
1. `x` button should close the modal;
1. The `select` should filter todos by the `completed` status: `all`, `completed` and `active`(not completed) todos;
1. Use the `input` in the `TodoFilter` to filter the `todos` by `title`;
    - show the `x` button when the `query` is entered;
    - the `x` button should clear the `query` and reset the todos;
  
## Demo Links

- [DEMO LINK](https://AndriiZakharenko.github.io/react_dynamic-list-of-todos/)
