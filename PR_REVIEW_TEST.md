# PR Review Workflow Test Fixture

This standalone fixture is included to exercise the repository's pull-request review workflow. It demonstrates appointment-date validation and a submission confirmation state.

## Review target

The date picker has an intentionally seeded defect: it blocks same-day appointments even though the helper text says same-day booking is allowed. Please treat that as a test finding, not production behavior.

Open `pr-review-demo.html` in a browser to inspect the fixture.
