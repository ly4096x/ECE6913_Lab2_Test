# ECE6913_Lab2_Test

Run with `./branchsimulator.out <config_file> <trace_input_file>`

Compare result with `diff -wq <trace_output.out> <trace_answer.out>`

### Debug Info Format

```
b77b5c4d   [col]   3                 [bhr] 000000/11 [act] 1                           [ret] 1
^-------         ^--                       ^----- ^-       ^                                 ^
|                |                         |      |        |                                 |
Branch_PC        Matching PHT column       Ignore BHR      Actual branch taken or not        Prediction
```
