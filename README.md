# Rocqing proof theory

Formalisation of proof systems (Hilbert and sequent calculi) for intuitionistic logic. 

## Installation instructions

### Using Opam

#### Coq/Rocq

The development compiles with Rocq `9.3.1`.

If you do not have a suitable version yet, I suggest:

> `opam pin add rocq 9.3.1`

#### External dependencies

If it is the first time you install rocq libraries with `opam`, you will have to run the following command:

> `opam repo add rocq-released https://rocq-prover.org/opam/released`

This work depends on two libraries: `rocq-coinduction` and `rocq-equations`. You can install them by running the following commands. 

> `opam install rocq-stdpp`
> `opam install rocq-equations`

## Compiling

You can run the following command in the main folder:

> `make all`