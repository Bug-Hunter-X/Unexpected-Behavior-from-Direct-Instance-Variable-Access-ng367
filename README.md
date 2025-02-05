# Ruby Bug: Unexpected Behavior from Direct Instance Variable Access

This repository demonstrates a common, yet subtle bug in Ruby related to directly accessing instance variables using `instance_variable_get` and `instance_variable_set`.  While technically functional, this practice is strongly discouraged and can lead to unexpected behavior and reduced code maintainability.

The `bug.rb` file showcases the issue. The `bugSolution.rb` file shows the improved approach using getter and setter methods.

## Key Points
* **Avoid direct instance variable access:** Favor getter and setter methods for controlled access to internal state.
* **Maintainability:** Using methods promotes cleaner, more maintainable code.
* **Encapsulation:** Getter and setter methods help encapsulate data and enforce object-oriented principles.
