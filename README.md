# Demonstration of pre-push not working

This is a very simple test for husky pre-commit and pre-push hooks and demonstrate that pre-push does not work.

## Steps

- Clone this repository.
- Make a change to one of the files and save.
- Commit and push the change.

## Expected

- pre-commit should write "pre-commit" to the console.
- pre-push should write "pre-push" to the console.

## Actual

- pre-commit writes "pre-commit" to the console.
- pre-push doesn't write anything to the console.

---

Test test
