# Description
<!--
1. Include a summary of the change.
2. Motivation for the change
3. Explain more complex topics in a subsection
-->


# Project Planning Tool User Story / Defect Number | Issue #
<!--
Include what project planning item was completed (or partially completed) by this PR
-->


# Verification
<!--
Verification is about testing that the changes match intent (i.e., requirements).
-->
## Unit Tests
<!--
All changes must be accompanied by unit tests. This shall be enforced with a CI pipeline quality gate.
-->

## HIL Tests (if applicable)
<!--
If applicable, a HIL automated test would be great to mention here.
-->

## System Tests
<!--
Unit tests test a module in isolation. System tests test a module in the system it interacts wit.
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
Ideally, any changes will also have been tested by end-users
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
Mono-repos have the potential to be unweildly, and I prefer to have the pieces of my software split up and isolated.
Mention any upstream or downstream dependencies that were updated for this particular set of changes.
-->


# Requirements
<!--
Reference the requirements that led to this change. If there were none, there need to be!
-->


# Miscellaneous Checklist
<!--
Make sure all the items below are checked off. If an item is not applicable, remove it from the PR description.
-->
- [ ] Ensure the package version changed appropriately according to semantic versioning.
- [ ] The `CHANGELOG.md` has been updated
- [ ] The `README.md` has been updated if applicable
- [ ] All compiler, linker, and static analysis warnings have been resolved / supressed-if-justified
- [ ] The MISRA C 2023 coding _directives_ have been followed (static analysis can enforce rules but not directives)
