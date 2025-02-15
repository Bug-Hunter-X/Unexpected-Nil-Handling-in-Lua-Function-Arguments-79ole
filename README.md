# Lua Nil Handling Bug

This repository demonstrates a common, yet subtle, bug related to nil handling in Lua function arguments.  The `foo` function attempts to handle `nil` arguments gracefully but reveals an area where unexpected behavior can arise, particularly when both arguments are `nil`.

The `bug.lua` file contains the buggy code.  The `bugSolution.lua` file provides a corrected version.

This example highlights the importance of explicitly checking for `nil` values when dealing with optional function parameters in Lua.