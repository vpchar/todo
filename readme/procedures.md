# (1) Create top-level folders

```bash
mkdir todo
mkdir readme
```

# (2) Create draft readme files (rules and this file)

Top level README.md

/readme/rules.md - general rules for the hole coding

/readme/procedures.md - description of tasks for humans

# (3) Create FOLDER STRUCTURE to start development
The folder structure is simple, nested categories for structural support

```
root
root/product
root/product/project
root/product/project/src 
root/product/project/src/backend (we'll put anything important here; server)
root/product/project/src/frontend (client side; CLI or web apps...)
root/product/project/dist
...
```

# (4) Create github repository

# (5) Git init, initial commit, push
```
git remote add origin git@github.com:vpchar/todo.git
git branch -M main
git push -u origin main
```