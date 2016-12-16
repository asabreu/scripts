# scripts
Useful scripts and snippets of code

| File | Type | Description |
|:------------- |:--------------- |:------------- |
| colors16.sh | Bash | This file echoes a bunch of ANSI color codes to the terminal to demonstrate what's available. Each line is the color code of one forground color, out of 17 (default + 16 escapes), followed by a test use of that color on all nine background colors (default + 8 escapes) |
| colors256.sh | Bash | Generates an 8 bit color table (xterm-256 colors) for reference, using the ANSI CSI+SGR ``\033[48;5;${val}m`` for background and ``\033[38;5;${val}m`` for text (see [ANSI Code](http://en.wikipedia.org/wiki/ANSI_escape_code) on Wikipedia) |
| translatecolor.py | Python | Convert values between RGB hex codes and xterm-256 color codes. Provides listing of all 256 colors and their codes. Useful for developing console color themes, or even script output schemes |