
cmd-shift-f: `[^_]print_obligation`


`normalize_expr` - vieta, kur parse'ina ATP/SMT output'ą atgal į TLA?

`src/backend/prep.ml:1408` -  This function is called on every obligation in the range selected by the user. It produces a [Schedule.t] that represents the job of proving this obligation.


```
EIO_TRACING=stdout tlapm $(pwd)/Bubblesort/Bubblesort.tla --toolbox 66 67 --toolbox-vsn 2 --printallobs --prefer-stdlib -C --nofp -v --debug=verbose4,tempfiles,test_print
```

```
EIO_TRACING=stdout dune exec tlapm -- $(pwd)/examples_test/Bubblesort.tla --toolbox 66 67 --
toolbox-vsn 2 --printallobs --prefer-stdlib -C --nofp -v --debug=verbose4,tempfiles
```