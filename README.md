 **General**
- [ ] Are all variables used properly?
- [ ] Do the variables have properly cased, and meaningful names?
- [ ] Style looks appropriate
- [ ] No unnecessarily duplicated logic
- [ ] Code intent is clear upon initial reading
- [ ] Any code that isn't clear, but is needed, has an effective comment
- [ ] Are method calls or attribute lookups every called on entities that could be undefined/null?
- [ ] The functions can appropriately handle unexpected inputs.
- [ ] Commented *code* has been removed (comments themselves are fine).
- [ ] There are tests for the proposed functionality (if not, there's a good reason)
- [ ] You've actually read the tests, and have a sense of what's being tested and what isn't. (or this is n/a)

**Angular Specific**

- [ ] No DOM manipulation is happening inside controllers
- [ ] View logic is non-existant or minimal
- [ ] Among the rendering logic, there are no good candidates to be extracted into a filter
- [ ] Among the controller logic, there are no good candidates to be extracted into a service
- [ ] Among all the logic, there are no good candidates to be extracted into a directive
- [ ] Among the partials, there are no good candidates for extraction into an ng-include
- [ ] No unneeded controllers were created.

**Final Checks**
- [ ] It has indeed passed build tests before getting merged
- [ ] It does what the description says it does
- [ ] Any technical debt has been added to the log.
