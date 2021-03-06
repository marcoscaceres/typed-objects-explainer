# Typed Objects Explainer

This is an effort to pull together and explain the various typed
objects spec in an informal fashion. The expanations are divided into
groups:

- [Core](core.md) defines the core typed objects proposal.
- [Value types](valuetypes.md) defines an extension to the core
  proposal to support new kinds of values, akin to numbers and
  strings.
- [SIMD](simd.md) defines how the proposed SIMD spec fits into all this.
- [OO types](ootypes.md) defines an extesion to allow
  typed objects to (more) accurately describe the kinds of
  things one can describe in Java or C#.
- [Class syntax](classsyntax.md) explores integration of typed objects
  with ES6 class syntax and modules.
- [Operator overloading](overloading.md) describes a mechanism for
  operator overloading that integrates with the
  [value types](valuetypes.md) proposal.

**Caveat:** This set of explainers is **very much** a work in
  progress. The further down that list you go, the less consensus
  exists on the design.
