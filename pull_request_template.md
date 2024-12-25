# Description
<!--
1. Include a summary of the change.
2. Motivation for the change
3. Explain more complex topics in a subsection
-->


# Project Planning Tool User Story / Defect Number | Issue #
<!--
Include what project planning item was completed (or partially completed) by this PR.
-->


# Verification
<!--
Verification is about testing that the changes match intent (i.e., requirements).
-->
## Unit Tests
<!--
All changes must be accompanied by unit tests. This shall be enforced by a CI pipeline quality gate.
-->

## HIL Tests (if applicable)
<!--
If applicable, a HIL automated test would be great to mention here.
-->

## System Tests
<!--
Unit tests assess a module in isolation. System tests assess a module in the system it interacts with.
Mention those system tests here. A simulation environment is adequate for this.
-->

## Device Verification
<!--
All changes must be shown to actually work on the device in question!
-->

# Validation
<!--
Validation is about checking if the changes _feel_ right.
-->
## End-User Testing
<!--
Ideally, any changes will also have been evaluated by end-users.
-->


# Statistics
<!--
Changes will typically come with a change in CPU loading, memory usage, communication bus network statistics, etc.
Do mention them here!
-->
### Microcontroller Stats

### Communication Bus Network Stats


# Upstream / Downstream Repositories
<!--
Mono-repos have the potential to be unwieldy, and I prefer to have the pieces of my software split up and isolated.
Mention any upstream or downstream dependencies that were updated for this particular set of changes.
-->


# Requirements
<!--
Reference the requirements that led to this change. If there were none, there need to be!
-->


# Quality Checklist
<!--
Make sure all the items below are checked off. If an item is not applicable, remove it from the PR description.
-->
- [ ] Ensure the package version changed appropriately according to semantic versioning.
- [ ] The `CHANGELOG.md` has been updated
- [ ] The `README.md` has been updated if applicable
- [ ] All compiler, linker, and static analysis warnings have been resolved / suppressed-if-justified
- [ ] MISRA C
   - [ ] Coding directives have been followed where applicable (static analysis can enforce rules but not directives)
   - [ ] Coding rules that are **mandatory** have been complied with
   - [ ] Coding rules that are **required** have been complied with or clearly justified
   - [ ] Coding rules that are _advisory_ have been complied with or clearly justified
