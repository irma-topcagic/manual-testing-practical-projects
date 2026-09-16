# To Do List — Manual Testing

Testing of a simple To Do List app ([todolist.james.am](http://todolist.james.am)) where users can add tasks, mark them as done, edit them, delete them, and filter by All/Active/Completed.

Tool used: Trello.

## What was tested

Covered the core CRUD flow — Create, Read, Update, Delete — plus filtering and basic cross-browser checks.

- 36 test scenarios written and executed
- 3 bugs found
- Browsers tested: Chrome, Firefox, Edge 

## Bugs found

1. **Tasks count off by one** — after checking all tasks as done, the "items left" counter shows -1 instead of 0
2. **Toggle-all arrow needs 3 clicks instead of 2** — the second click does nothing
3. **Page doesn't scroll to top when applying a filter**

Full details (steps, expected/actual, screenshots) are in the `bugs/` folder.

## Files

- `test-scenarios.md` — all scenarios by category (Create/Read/Update/Delete)
- `bugs/` — bug reports
- `screenshots/` — supporting screenshots for each bug