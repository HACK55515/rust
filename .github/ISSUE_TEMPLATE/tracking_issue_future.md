---
name: Future Incompatibility Tracking Issue
about: A tracking issue for a future-incompatible lint
title: Tracking Issue for future-incompatibility lint XXX
labels: C-tracking-issue, C-future-incompatibility, T-compiler, A-lints
---
<!--
Thank you for creating a future-incompatible tracking issue! 📜 These issues
are for lints that implement a future-incompatible warning.

Remember to add team labels to the tracking issue.
For something that affects the language, this would be `T-lang`, and for libs
it would be `T-libs`.
Also check for any `A-` labels to add.
-->

This is the tracking issue for the `YOUR_LINT_NAME_HERE` future-compatibility
warning and other related errors. The goal of this page is to describe why this
change was made, what code patterns trigger it, and how users can fix or
prepare for it before the warning becomes a hard error.

[guidelines]: https://rustc-dev-guide.rust-lang.org/bug-fix-procedure.html

### What is the warning for?

*Describe the conditions that trigger the warning and what behavior is being
flagged. Include the relevant lint name and any edition, feature, or code pattern
that activates it.*

### Who is affected?

*Describe the scope of the change: which users are affected, whether the warning
is common or rare, and whether it is expected to fire in dependent crates or only
in the crate containing the code.*

### Why was this change made?

*Explain why this change was made. If there is additional context, such as an
RFC, MCP, issue, or design discussion, link it here. Describe the underlying
problem, the intended long-term behavior, and why a future-incompatible warning
is being used instead of an immediate hard error.*

### Example

```rust
// Include an example here that triggers the lint.

This version keeps the same structure while adding:
- a clearer scope/impact section
- more explicit rationale for the lint
- stronger migration guidance
- a rollout checklist that matches real future-incompatibility transitions
- better guidance for tracking implementation history
