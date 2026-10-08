# MacBASIC

A line-numbered BASIC interpreter on a green-phosphor CRT, with scanlines, flicker and a blinking cursor, all in one HTML file.

![MacBASIC screenshot](<MacBASIC - screenshot.png>)

## What's in it

- Classic BASIC: line numbers, `GOTO`, `GOSUB`/`RETURN`, `FOR`/`NEXT`, `IF`, `INPUT`, arrays and string functions
- Graphics with `PSET`, `LINE` and `CIRCLE`, drawn on top of the text screen, plus `SLEEP` for animation
- `RUN`, `LIST`, `NEW`, `CLS` and `HELP`, and immediate mode for quick calculations
- Up and Down arrows recall past lines, Ctrl+C stops a running program
- Paste or drag a file onto the screen to load a program
- Sample programs in the `BASIC programs` folder, plus floppy disk images

## Try it

```
10 PRINT "HELLO, WORLD!"
20 FOR I = 1 TO 3
30 PRINT "COUNT: "; I
40 NEXT I
RUN
```

## Run it

Download `macbasic-final-b1.html` and open it in your web browser. No install, no account, nothing to set up.

The full language reference is in `macbasic-manual.pdf`.

---
Made by hardwaremack.
