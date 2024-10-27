# Commands
## Command layout:

|byte|   0  |  1  |  2 |  3 |
|----|------|-----|----|----|
|type|opcode|flags|arg1|arg2|
|----|------|-----|----|----|

## List of all commands:
#### Memory commands:
- ld
    - Load
- st
    - Store
- swpr
    - Swap Registers
- push
    - push to stack
- pop
    - pop from stack
- pout
    - put value from register into specific port
- pin
    - read value from specific port into register
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
#### Condition & Branch Operations:
- cmp
    - Compare
- jmp
    - Jump
- jne
    - Jump if not equal
- jeq
    - Jump if equal
- jgr
    - Jump if greater
- jle
    - Jump if less
- jcr
    - Jump if carry
- call
    - Calls a function, pushing the current value in program counter register onto stack
- ret
    - Returns from a function, poping the top value from stack into program counter

