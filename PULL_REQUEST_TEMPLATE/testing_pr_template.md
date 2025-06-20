<!--- TESTING PR -->

## Tests adding/updating scope

<!--- Explanation of the tests' purpose.
If JIRA ticket covers these well, it's enough to link to that. -->

## Tests list

<!--- List the added/updated test names. 
If the test was updated, describe the reason for the update -->

## Additional Notes

<!--- Any additional information or context relevant to this PR. -->

## Reviewer Checklist  

- [ ] **Test names are clear** Test name is similar to bug name - should be clear and short at the same time.

- [ ] **Each test is checking one thing.** There can be exclusions for e2e or time consuming tests.

- [ ] **There are no `only` annotations.** There shouldn't be any `test.only` or `test.describe.only`. Having `only` annotation will prevent tests from running in GHA. 

- [ ] **Test annotations are correct.** If any test or test set (`test.describe`) has `fail` or `skip` annotation, it should be clear why the test fails or is skipped. Commonly a TODO comment should be written for such tests/test sets.

- [ ] **Tickets created for remaining gaps.** If the scope is for creating smoke tests only, or in case of any other gaps, tasks for creating comprehensive testing should be created and linked.