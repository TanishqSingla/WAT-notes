# Function Overhead

This page discusses about the function import/export overhead in websassembly or in other words it discusses about when to call a function.

## Exporting a function

Whenever JS calls a function exoprted by WASM incurs a overhead cost, which is why:

- Don't make WASM functions which perform small task as the overhead cost maybe more than the performance achieved. Use JS for them
- WAT functions that loop are better suited in that situation.
