# testing-ruby
Testing software, mostly using Ruby. Initially started as a companion repo to  Effective Testing with RSpec 3.

## Kinds of Tests

* _Acceptance_: Does the whole system work? Useful for big refactors.  These increase your ability to refactor application logic. End-to-end testing provide the best refactoring support. "Because they use your code's public interfaces, they don't depend on implementation details."
* _Unit_: Do our objects do the right thing? Are they convenient to work with? Focused on very specific parts of the code, cheap, and helpful for providing design feedback on code. Easy to make, easy to throw away.
* _Integration_: Does our code work against code we can't change, i.e. external services and dependencies? You must take care when testing these, e.g. rollback any changes you make.  While more difficult to write, these help you keep interfaces to external resources small and well-defined.


## Benefits of Testing
