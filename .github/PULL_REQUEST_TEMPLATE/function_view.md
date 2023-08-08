### Description

All views with the project are replaced with their class-based analogues.

### Available URL patterns

- `/about/`
  is a static project information page.
- `/<int:param>/`
  serves requests for ... and accept `param` argument (dynamic URL portion).
  Type converter is set to `int`.
- ...

### Checklist before requesting a review

- [ ] Pull request has a descriptive name
- [ ] Django project is running without errors
- [ ] All views listed above are available
- [ ] All views work as they expected
