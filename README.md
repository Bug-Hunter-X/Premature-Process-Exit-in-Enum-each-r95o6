# Elixir Enum.each and Process Termination

This example showcases a potential pitfall when using `Enum.each` in Elixir and handling process termination.

The `bug.ex` file contains code that exits the process when a specific condition is met within the `Enum.each` loop.  This leads to incomplete processing of the list.

The `bugSolution.ex` file demonstrates a solution for this problem, showing how to properly handle termination and continue processing when possible.