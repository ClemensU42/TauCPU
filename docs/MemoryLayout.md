## Hardware Specifics:
Memory lanes: 24
Total accessible memory: 2^24 bytes = 16MB
Data RAM is memory banked

### Layout:
0-8MB:  Data RAM
8-16MB: Program Memory

### Memory Banks:
Data RAM seperated into sections of 1MB with each section having 8 banks, so a total of 64MB of RAM is accessible.
The bank address is specified by the command flags by ld and st commands.
