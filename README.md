# Groovy Map sum() Method Issue

This example demonstrates a common issue encountered when using the `sum()` method in Groovy with Maps.  The `sum()` method is designed to operate on collections of numbers (like Lists), not Maps.  Attempting to directly call `sum()` on a map results in a `MissingMethodException`.

The solution shows how to correctly calculate the sum of values within a Groovy Map using the `values()` method to access the numerical values and then applying the `sum()` method to that resulting collection.

## How to Reproduce

1.  Save the code in `GroovyMapSumBug.groovy`.
2.  Run the script using the Groovy interpreter.

You'll observe the `MissingMethodException`.

## Solution

The solution is provided in `GroovyMapSumSolution.groovy`.