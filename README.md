# Parentis

Parentis is a language that is being created following the excellent book "Build Your Own Lisp".

## Requisites

- [MPC](https://github.com/orangeduck/mpc)
- libedit

## Compilation

```bash
$ gcc -std=c99 -Wall parentis.c mpc.c -ledit -lm -o parentis
```
