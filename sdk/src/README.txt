# How to build

set OPT=--max-allocs-per-node 100000

sdcc -o PIPlib.rel -c -mz80 %OPT% --peep-file peep-rules.txt --reserve-regs-iy PIPlib.c
@if %errorlevel% NEQ 0 goto :EOF

sdar r PIPlib.lib PIPlib.rel
@if %errorlevel% NEQ 0 goto :EOF
