---
sidebar_position: 1
---

# Code of Conduct

## Principles

At Critique, we uphold the following principles in our software development process:

1. **Test-Driven Development (TDD):** Prioritize writing automated tests before implementing new features or making changes to existing code. TDD ensures reliability, maintainability, and adherence to requirements.

2. **Code Readability:** Emphasize code that is easy to understand and maintain. Use clear and descriptive variable names, even if it means using longer names.

3. **Minimal Comments:** Limit comments to complex logic or algorithms. Strive to write self-explanatory and expressive code that reduces the need for excessive comments.

4. **Comprehensive README:** Include a detailed README file in every project, providing essential setup, installation, and running instructions. 

5. **Centralized Documentation:** All development-related documentation should be consolidated in the `ct-dev-docs` repository. Covering each project's purpose, architecture, and other relevant details.

## Best Practices

### Version Control

At Critique, we follow GitHub Flow as our version control workflow. GitHub Flow is a lightweight and flexible approach to collaboration and code deployment. For a detailed explanation, you can refer to [this blog post by Scott Chacon](https://scottchacon.com/2011/08/31/github-flow.html).

Here's an overview of how GitHub Flow works:

1. **Main Branch is Always Deployable:** The `main` branch serves as the production-ready branch, and all code pushed to it should be deployable at any time.

2. **Create Feature Branches:** When working on a new feature or fixing a bug, create a new branch off `main` with a descriptive name (e.g., new-oauth2-scopes).

3. **Local Commits and Pushes:** Regularly commit your changes locally and push your work to the branch with the same name on the server.

4. **Pull Requests:** When the feature or fix is ready for feedback or merging, open a pull request. Request reviews from other team members to ensure code quality and correctness.

5. **Review and Approval:** After someone else has reviewed and signed off on the changes, merge the branch into `main`.

6. **Immediate Deployment:** Once the changes are merged and pushed to `main`, promptly deploy the updated code.

### Coding Standards

1. **Language Conventions:** Adhere to the official style guidelines and conventions of the chosen programming language to maintain consistency.

2. **Code Reviews:** Conduct code reviews to ensure code quality, identify issues, and share knowledge among team members.

### Testing

1. **Test Coverage:** Aim for comprehensive test coverage to minimize regressions and ensure code reliability.

2. **Continuous Integration (CI):** Integrate projects with a CI/CD pipeline for automated testing, builds, and deployments.

### Security

1. **Secure Coding:** Prioritize security by avoiding common vulnerabilities and following best practices for data handling, authentication, and authorization.

2. **Dependency Management:** Regularly update and monitor project dependencies to address security vulnerabilities and maintain stability.

### Performance

1. **Efficient Algorithms:** Optimize algorithms and data structures for better performance.

2. **Profiling and Monitoring:** Use profiling tools and application monitoring to identify and address performance bottlenecks.

## Inclusivity and Collaboration

1. **Respectful Communication:** Foster a positive and inclusive environment, respecting diverse opinions and backgrounds. Encourage open discussions and active listening.

2. **Knowledge Sharing:** Promote knowledge sharing through documentation, code reviews, and team discussions. Encourage mentorship and pair programming to facilitate learning.

3. **Supportive Collaboration:** Build a supportive and encouraging atmosphere that values creativity and innovation. Emphasize learning from failures rather than shaming, and see them as opportunities for growth.

4. **Forgiving Environment:** Create a forgiving environment where team members feel comfortable taking risks and trying new approaches. Recognize that mistakes are part of the learning process and should not be met with harsh criticism.

5. **Diverse Perspectives:** Embrace and celebrate diversity in all its forms. Encourage diverse perspectives and ideas, as they enrich our solutions and make us a stronger team.

## Licensing

Ensure that all projects adhere to appropriate licensing requirements, with clear indications in the project's README or LICENSE file.

By following this code of conduct, we aim to create an environment that promotes excellence, collaboration, and continuous improvement in our software development endeavors.