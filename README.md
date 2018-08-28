# sort
javascript实现各种排序算法，并直观比较。


"debug": "node --nolazy --debug-brk=5858 build/test.js"
"debug": "node --nolazy --inspect-brk=5858 build/test.js abc"        最新版node

"configurations": [
    {
      "type": "node",
      "request": "launch",
      "name": "test",
      "program": "${workspaceFolder}/build/test.js"
    },
    {
      "name": "Launch via NPM",
      "type": "node",
      "request": "launch",
      "cwd": "${workspaceRoot}",
      "runtimeExecutable": "npm",
      "runtimeArgs": [
        "run-script",
        "debug"
      ],
      "port": 5858
    }
  ]
