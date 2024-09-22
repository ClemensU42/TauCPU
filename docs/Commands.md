# Commands
## Command layout:

|byte|   0  |  1  |  2 |  3 |
|----|------|-----|----|----|
|type|cmd id|flags|arg1|arg2|
|----|------|-----|----|----|

## List of all commands:
#### Memory commands:
- ld
    - Load
- st
    - Store
- swpr
    - Swap Registers
#### Arrithmetic Operations:
- add
    - Add
- sub
    - Subtract
- shftl
    - Shift Left
- shftr
    - Shift Right
- and
    - And
- or
    - Or
- xor
    - Xor
- not
    - Not
#### Conditions Operations:
- cmp
    - Compare
- jmp
    - Jump
- jne
    - Jump if not equal
- jeq
    - Jump if equal
