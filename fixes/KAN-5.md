# Add button label is unclear and not blue in color

## Issue summary

The button currently used to add tasks is not labeled as 'Add Task' and does not have a blue color, leading to potential confusion for users.

## Suggested fix

**Suggestion:**  
Update the add button so its label reads "Add Task" and apply a blue color (e.g., via a CSS class or inline style).

```jsx
<button style={{ backgroundColor: '#007bff', color: 'white' }}>
  Add Task
</button>
```
Or, if using a CSS class:

```jsx
<button className="btn btn-primary">
  Add Task
</button>
```

Make sure "Add Task" is the visible text and the button uses your app's blue button styling for consistency.
