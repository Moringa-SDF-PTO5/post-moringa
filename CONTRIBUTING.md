# Contributing to Project

We appreciate your interest in contributing to this project! Here are some guidelines to help you get started.

## How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## Coding Standards

- Follow PEP 8 for Python code.
- Follow the Airbnb style guide for JavaScript/React code.
- Write tests for your code.
- Ensure all tests pass before submitting a PR.
- Use linting tools (`flake8` for Python and `eslint` for JavaScript/React).

## Commit Messages

Commit messages should be clear, concise, and descriptive. Follow these rules for making elaborate commits:

1. **Separate subject from body with a blank line**  
   Example:

```
Add user login feature

Implemented user authentication using JWT.
Updated user model to include password hashing.
Added tests for user login and registration.
```

2. **Limit the subject line to 50 characters**  
Keep the subject concise and to the point.

3. **Capitalize the subject line**  
Example: `Add user login feature`

4. **Do not end the subject line with a period**  
Example: `Add user login feature`

5. **Use the imperative mood in the subject line**  
Example: `Fix bug in user authentication`

6. **Wrap the body at 72 characters**  
This helps maintain readability in various interfaces.

7. **Use the body to explain what and why vs. how**  
Example:

```
Refactor user authentication module

Moved authentication logic to a separate service.
Updated tests to mock the new service.
This improves code maintainability and separation of concerns.
```


## Pull Request Checklist:

- [ ] My code follows the style guidelines of this project.
- [ ] I have performed a self-review of my own code.
- [ ] I have commented my code, particularly in hard-to-understand areas.
- [ ] I have made corresponding changes to the documentation.
- [ ] My changes generate no new warnings.
- [ ] I have added tests that prove my fix is effective or that my feature works.
- [ ] New and existing unit tests pass locally with my changes.
- [ ] Any dependent changes have been merged and published in downstream modules.

Thank you for contributing!
