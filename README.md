# The Bard's Bytecode – LNMIIT CTF

This repository contains a web + file based CTF challenge themed around the **Shakespeare Programming Language (SPL)**.[page:1]

## Challenge Summary

- You are given a Shakespeare-style script, `bard.spl`.
- The script is also a valid SPL program.
- When run with a suitable SPL translator, it prints a single line: a flag in the format `LNM{...}`.
- Your job is to obtain that flag.

## Files

- `index.html` – Challenge landing page (for GitHub Pages).
- `bard.spl` – Shakespeare program that encodes and prints the flag.
- `DEPLOYMENT.md` – Instructions for deploying this repo as a GitHub Pages site.

## Skills Tested

- Working with esoteric languages (Shakespeare Programming Language).
- Understanding / researching language specs and running a custom interpreter.
- Recognizing ASCII output via `speak your mind` and integer values.[page:1]

The actual flag phrase can be adjusted inside `bard.spl` by changing the arithmetic that leads to each printed character.
