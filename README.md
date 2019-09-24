# testing-ruby
Testing software, mostly using Ruby. Initially started as a companion repo to  Effective Testing with RSpec 3.

## Kinds of Tests

* _Acceptance_: Does the whole system work? Useful for big refactors.  These increase your ability to refactor application logic. End-to-end testing provide the best refactoring support. "Because they use your code's public interfaces, they don't depend on implementation details."
* _Unit_: Do our objects do the right thing? Are they convenient to work with? Focused on very specific parts of the code, cheap, and helpful for providing design feedback on code. Easy to make, easy to throw away.
* _Integration_: Does our code work against code we can't change, i.e. external services and dependencies? You must take care when testing these, e.g. rollback any changes you make.  While more difficult to write, these help you keep interfaces to external resources small and well-defined.


## Benefits of Testing

* CONFIDENCE that the code works
* Reduced regressions
* ELIMINATE FEAR about change --> MORE REFACTORING
* CODE DESIGN GUIDANCE - make poorly designed code painful! "If you find yourself wrestling a bunch of ungainly objects into place just to test a single method, wht are the odds your team is going to be able to use that method correctly every time?"
* Better code through reduced coupling.
* Enables FEATURE ADDS - without tests, your code will unwittingly break other parts of your app, and you won't even know. Tests lower cost of feature adds.
* tests are DOCUMENTATION.
* Transforming workflow: "Each run of your suite is an experiment you've designed in order to validate (or refute) a hypothesis about how the code behaves. You get fast, frequent feedback when something doesn't work, and you can change course immediately."

Kent Beck on making change easier:
> For each desired change, make the change easy (warning: This may be hard), then make the easy change.

Specs will guide you to this goal.

## Testing Lingo

* Behavior-Driven Development vs Test-Driven Development
* test - validates piece of code
* spec - description of what you want that piece of code to do
* example - how to use that piece of code
* Red-Green-Refactor workflow

## RSpec Keywords

* `describe` - creates an example group
* `it` - creates an example
* `expect` - the assertion that verifies code is working

## RSpec Conventions

* A top-level `spec` sub-directory.
* Spec files end with `_spec.rb`

## RSpec Setup: Hooks

## Rspec Setup: Helper Methods

Memoization

## RSpec Setup: `let`

## RSpec Commands

## Documentation

* RSpec
