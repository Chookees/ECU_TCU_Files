# BMW E46 330i – ECU/TCU Info & Tools

## Supported ECUs
- MS43
- MS45
- MS45.1

## Tools Required

### Reading/Writing ECU
- **MS4x Flasher** (Windows/Android) (https://www.ms4x.net/)
  - Used to read/write ECU over OBD or bench
  - Supports full flash, partial flash, and recovery

### ECU Editing
- **TunerPro** (https://tunerpro.net/)
  - Used with `.xdf` files to modify `.bin` images
  - Make sure to match ECU version with correct `.xdf`

## Notes
- Always verify ECU compatibility and checksum correction before writing modified files.
- Back up the original file before making any changes.
