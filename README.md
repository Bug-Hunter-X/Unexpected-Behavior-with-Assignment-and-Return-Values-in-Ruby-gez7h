# Ruby Assignment and Return Value Bug

This repository demonstrates an uncommon but potentially confusing code error related to assignment and return values in Ruby. The code shows a `MyClass` class with a `value` method.  The assignment `my_object.value = 20` not only modifies the object's state but also returns the newly assigned value.  This implicit return can be unexpected and lead to errors if not carefully considered.

The `bug.rb` file contains the problematic code. The `bugSolution.rb` file offers a solution, emphasizing clarity and avoiding unexpected behavior.

This example highlights the importance of understanding Ruby's implicit return behavior to write robust and predictable code.