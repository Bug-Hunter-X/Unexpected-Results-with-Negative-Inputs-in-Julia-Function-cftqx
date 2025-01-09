This repository demonstrates a common error in Julia involving unexpected results when dealing with negative numbers in a conditional statement. The issue arises from the interplay of operator precedence and missing parentheses, leading to incorrect calculations.

The file `bug.jl` contains the original buggy code. The file `bugSolution.jl` provides a corrected version with the necessary parentheses to ensure the desired behavior.

The solution emphasizes understanding Julia's operator precedence rules and properly using parentheses to enforce the intended order of operations, especially when working with negative numbers and exponents.