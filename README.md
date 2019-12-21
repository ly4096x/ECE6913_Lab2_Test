# ECE6913_Lab2_Test

Run with `./branchsimulator.out <config_file> <trace_input_file>`

Compare result with `diff -wq <trace_output.out> <trace_answer.out>`

### Debug Info Format

```
b77b5c4d   [col]   3           [row]  00000c4d     [bhr] 000000/11   [cv] 3           [act] 1                           [ret] 1
^-------         ^--                  ^                  ^----- ^-        ^                 ^                                 ^
|                |                    |                  |      |         |                 |                                 |
Branch_PC        Matching PHT column  PHT row number     Ignore BHR       Counter value     Actual branch taken or not        Prediction
```

Note:
PHT column number is actually equal to BHR value in decimal.
