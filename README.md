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



<svg width="512" height="512" xmlns="http://www.w3.org/2000/svg">
 <title/>

 <g>
  <title>background</title>
  <rect fill="none" id="canvas_background" height="402" width="582" y="-1" x="-1"/>
 </g>
 <g>
  <title>Layer 1</title>
  <g id="icomoon-ignore"/>
  <path stroke="null" id="svg_1" d="m497.999984,128.743203c-86.285511,-0.600366 -460.325521,-0.474763 -492.999984,0c0.962888,220.717251 1.155465,238.779093 0.962888,242.256785c93.400394,0 398.636711,-1.738846 492.037096,-1.738846c0,-77.088744 0,-163.429195 0,-240.517939zm-471.187485,222.549886c-0.333333,-68.008118 -1.666667,-137.016236 -2,-205.024355c146.458329,0 306.916657,1 453.374986,1c-0.531787,7.784035 3.70716,145.062116 2.303263,202.446124l-442.678249,1.578231z"/>
 </g>
</svg>
