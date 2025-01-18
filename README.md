# Unexpected Behavior When Assigning to Getter Method in Ruby

This example demonstrates a common pitfall in Ruby: attempting to modify an instance variable by assigning a value to the result of a getter method.  Unlike some other languages, this does not modify the underlying instance variable. This can lead to unexpected behavior and difficult-to-debug issues.

The `bug.rb` file contains code that showcases this problem.  The solution, found in `bugSolution.rb`, shows the correct approach to modifying the instance variable.