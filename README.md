# budgetview

## Launch (Windows-tested only)

Install as a package
```sh
uv pip install -e .
```

Run from terminal
```sh
budgetview
```

Run from vscode debugger
```js
{
   "name": "budgetview",
   "type": "debugpy",
   "request": "launch",
   "module": "budgetview",
   "cwd": "${workspaceFolder}",
   "justMyCode": false,
}
```

## Build (Windows-tested only)
