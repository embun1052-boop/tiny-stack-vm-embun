# tiny-stack-vm

A faithful interpreter of make.fun's tiny stack ISA (see the kit's
`generator/subject/ISA.md`): 32-bit wrapping arithmetic, a 256-value
stack, a 64-deep call stack, 256 words of memory, and traps 2..11
with their own exit codes.

Run locally on the practice set:

```
mkdir -p out && MAKEFUN_INPUT_DIR=practice/input MAKEFUN_OUTPUT_DIR=out node main.ts
```
