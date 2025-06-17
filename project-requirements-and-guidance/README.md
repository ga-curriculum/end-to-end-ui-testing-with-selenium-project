<h1>
  <span class="headline">End-to-End UI Testing with Selenium Project</span>
  <span class="subhead">Project Requirements and Guidance</span>
</h1>

## Overview

### Objective:

Build a simple full stack Python application with both a backend (FastAPI) and a static HTML frontend, and demonstrate your ability to write a complete and well-structured test suite that includes unit, integration, and end-to-end tests using `pytest` and `Selenium`.

### Scope and Complexity:

For your project, you will be building a small, testable web application that includes both backend API routes and a basic frontend UI.

Throughout the course, you've learned how to build Python web apps, test APIs, and automate browser-based user flows. Now, it's your turn to **apply that knowledge** by designing your own minimal app and writing automated tests to validate its behavior from top to bottom.

The project is estimated to take around **10-15 hours** to complete.

**_You will work individually on this project._**

> ❗ **General Assembly has a zero-plagiarism policy.**  
> Your project must be **your own** work. While it’s fine to use libraries or small code snippets to accomplish specific tasks, your project’s core functionality should be implemented by you.

A printable version of the project requirements can be found [here](./assets/project-requirements.pdf).

## Technical Requirements

> ✅ More than **three** incomplete items in this section will result in a failing grade.

Your application must meet the following requirements:

- The project must be committed to a version control system (`Git`) with clear commit messages reflecting progress.

- Your backend must include at least `3 FastAPI routes`.

- You must include at least `1 test per route` using `pytest` (unit or integration).

- You must include at least `1 unit test`, `1 integration test`, and `4 end-to-end Selenium tests`.

- The frontend must be a `static HTML page` that connects to your API and supports the UI flows being tested.

- Your Selenium tests must simulate realistic user interactions (ex: clicking, submitting forms, navigation).

- The application must run locally with clear setup instructions in the `README`.

#### Stretch Goals:

(These are not requirements, only ideas)

- Add basic authentication or sessions.

- Use a database like SQLite for persistent data.

- Implement automated testing in a CI pipeline (e.g., GitHub Actions).

- Create a more dynamic frontend using basic JavaScript or a lightweight framework.

- Track and display test coverage using pytest-cov.

## Code Convention and Design Requirements

> ✅ More than **two** incomplete items in this section will result in a failing grade.

- The code must be well-organized and modular, following FastAPI best practices.

- Error messages should be clear and informative, guiding users to correct their input.

- Code should be free of commented-out blocks or unused imports.

- Files and functions should be appropriately named, with consistent formatting and indentation.

- The test suite should be logically organized, with meaningful test names and grouped by test type.

## README Requirements

> ✅ More than **three** incomplete items in this section will result in a failing grade.

Your project must include a `README.md` file with:

- The **app’s name**.

- A brief **description** of your app and its functionality.

- A **Getting Started** section with instructions on how to install dependencies and run the app locally.

- A **Technologies Used** section listing major frameworks and libraries such as Selenium, pytest, frontend style libraries, etc...

- If applicable, an **Attributions** section crediting external resources or libraries that require acknowledgment.

## Evaluation

Your instructional team will evaluate your project after the due date. They will use the above guidelines to determine whether your project meets the **minimum requirements**.

If there is a specific section of code where you’d like additional feedback, **ask your instructor for a code review**!

## Guidance

### Getting Started

Here are some quick tips to help you plan and execute your project successfully:

- **Discuss your app idea with an instructor** before diving too deep into development.
- **_Keep it simple._** A well-functioning **Minimum Viable Product (MVP)** is better than an unfinished app with unnecessary features.
- **Prioritize core functionality** first. Develop features in a way that allows you to test as you go.
- **Regularly review the project requirements** to stay on track. A printable version of this document is available [here](./assets/project-requirements.pdf).
- **Use clear commit messages** to track your progress.

### Project Assistance

Your instructor team will provide **guidelines for reaching out for help** during the project. Make sure to:

- **Ask specific questions** when seeking assistance.
- **Follow debugging best practices** before reaching out—check error messages and logs!
