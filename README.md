# VHDL Counter Bug: Integer Range Issue

This repository demonstrates an uncommon bug in VHDL related to the handling of integer ranges within a counter. The original code (`buggy_counter.vhdl`) incorrectly manages the integer range, leading to unexpected behavior when the counter reaches its maximum value. The corrected code (`fixed_counter.vhdl`) addresses this issue.

## Bug Description

The `buggy_counter.vhdl` code implements a simple counter. However, due to an oversight in handling the integer range, the counter does not reset correctly when it reaches the maximum value.  This can lead to unpredictable results or simulation errors.

## Solution

The `fixed_counter.vhdl` file provides the corrected code. The solution ensures that the counter properly resets to 0 when reaching its maximum value, eliminating the unexpected behavior.

## How to Reproduce the Bug

1. Simulate `buggy_counter.vhdl`. 
2. Observe the counter's behavior when it should wrap around from 15 to 0. You will see unexpected behavior.

## How to Run the Solution

1. Simulate `fixed_counter.vhdl`.
2. Verify that the counter correctly wraps around from 15 to 0.
