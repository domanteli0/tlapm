

`src/tlapm_lib.ml:291` (`process_module`) - pažymi modulius `important` ir tik tuos analizuoja???

tlamp_lib.main > Module.Deps.schedule > `/src/module/m_elab.ml`:`let rec normalize`


# Random

`normalize_expr` - vieta, kur parse'ina ATP/SMT output'ą atgal į TLA?

`src/backend/prep.ml:1408` -  This function is called on every obligation in the range selected by the user. It produces a [Schedule.t] that represents the job of proving this obligation.


# Other

cmd-shift-f: `[^_]print_obligation`

# Runnning

```
EIO_TRACING=stdout tlapm $(pwd)/Bubblesort/Bubblesort.tla --toolbox 66 67 --toolbox-vsn 2 --printallobs --prefer-stdlib -C --nofp -v --debug=verbose4,tempfiles,test_print
```

```
EIO_TRACING=stdout dune exec tlapm -- $(pwd)/examples_test/Bubblesort.tla --toolbox 66 67 --toolbox-vsn 2 --printallobs --prefer-stdlib -C --nofp -v --debug=verbose4,tempfiles
```
