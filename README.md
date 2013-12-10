What you need to know when building software for UNEP-Live
==============

Main themes:
- Code sharing and version control
- Testing
- Documentation
- Deployment
- Code monitoring and review
- Technology choices

## Code sharing and version control
Principle:  All code is open, public and easily available for anyone to contribute and share.

1. All UNEP-live code is commited to github in a public repository
2. We'll use the shared repository model for updating the code:  [https://help.github.com/articles/using-pull-requests#shared-repository-model](https://help.github.com/articles/using-pull-requests#shared-repository-model)

## Testing
Principle: [Test Driven Development (TDD)](http://en.wikipedia.org/wiki/Test-driven_development) reduces defects and bugs, enables confident refactoring and encourages developers to design code from the outside-in.

1. Before features are implemented, first a failing test case describing the desired behavior must be written. Developers then write code to make the failing tests cases pass.
2. Refactor code where possible, while confirming that no failures are introduced in the tests.
3. Code may only be deployed or released if all tests are passing.

## Documentation
Principle:  All code is documented to a level which would allow a fresh developer with knowledge of the used programming language to be able to contribute to the code and deploy it to production with minimal involvement from the development team.

1. Use a README file to explain the developer set-up 
2. Use the Wiki for deployment instructions.

## Code monitoring and review
Principle: Code reviews are used to reduce defects and improve team members' knowledge of the code-base. 

1. Features are developed on 'feature' branches, which are committed and pushed to regularly.
2. When features are ready for integration to the master branch, a [pull request](https://help.github.com/articles/using-pull-requests) is submitted.
3. Another member of the team reviews the pull request, making comments where necessary.
4. Once the other member of the team is happy with the feature branch, they merge it into master.







