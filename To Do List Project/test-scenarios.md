# To Do List — Test Scenarios

Application under test: [todolist.james.am](http://todolist.james.am)

## Create

- [x] Validate creating a task with valid alphabetic text
- [x] Validate creating a task with alphanumeric text
- [x] Validate creating a task with special characters
- [x] Validate creating multiple tasks sequentially
- [x] Validate creating a task with maximum allowed character length
- [x] Validate that an empty task cannot be created
- [x] Validate that a task with only whitespaces cannot be created
- [x] Validate creating a task with only numeric values
- [x] Validate creating a task with SQL injection input

## Read

- [x] Validate that all created tasks are displayed correctly in the list
- [x] Validate that all active tasks are displayed
- [x] Validate that all completed tasks are displayed
- [x] Validate that task order matches the order in which they were created
- [x] Validate that new tasks display immediately without refresh
- [x] Validate that refreshing the page does not lose or duplicate existing tasks
- [x] Validate that a very high number of tasks does not break the list rendering or cause performance issues
- [x] Validate that number of tasks is correct

## Update

- [x] Validate that double-clicking a task allows editing
- [x] Validate that an edited task saves the new text correctly
- [x] Validate that a task can be marked as complete via checkbox
- [x] Validate that a task can be marked as incomplete (unchecked) after being completed
- [x] Validate that pressing Enter after editing saves the changes
- [x] Validate that editing a task updates the display immediately without refresh
- [x] Validate that pressing "Escape" during edit cancels changes without saving
- [x] Validate updating a task with only whitespaces
- [x] Validate updating a task with only numeric values
- [x] Validate updating a task with SQL injection input
- [x] Validate updating a task exceeding the maximum character limit

## Delete

- [x] Validate that a task can be successfully deleted
- [x] Validate that deleting a task updates the list immediately without refresh
- [x] Validate that deleting a task does not affect other existing tasks
- [x] Validate that deleting the last remaining task results in an empty list
- [x] Validate that a completed (checked) task can be deleted
- [x] Validate that multiple tasks can be deleted sequentially
- [x] Validate that deleting a task while it is being edited does not cause unexpected behavior
- [x] Validate that clicking Clear deletes only completed tasks

## Summary

| Category | Total | Executed |
|---|---|---|
| Create | 9 | 9 (100%) |
| Read | 8 | 8 (100%) |
| Update | 11 | 11 (100%) |
| Delete | 8 | 8 (100%) |
| **Total** | **36** | **36 (100%)** |