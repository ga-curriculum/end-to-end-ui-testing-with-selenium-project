<h1>
  <span class="headline">End-to-End UI Testing with Selenium Project</span>
  <span class="subhead">Step By Step Project Build</span>
</h1>

# Project Instructions

In this project, you’ll build a small full-stack web application that includes a FastAPI backend and a static HTML frontend. You will design and implement a complete test suite using **pytest** for backend logic and **Selenium** for browser-based UI interactions.

The project emphasizes **testing coverage and test strategy**. You'll demonstrate your ability to test multiple layers of a web application — from isolated logic (unit tests), to interacting services (integration tests), to full end-to-end user flows (Selenium).

## What You'll Learn

By completing this project, you’ll:

- Write and organize a **test suite that includes unit, integration, and end-to-end tests**.
- Build a **modular full-stack app** using FastAPI and a static HTML frontend.
- Use **Selenium WebDriver** to simulate user actions like clicking buttons, filling forms, and checking UI output.
- Structure code and tests using common conventions and tooling in modern Python development.

## Getting Started

You’ll be working **individually** to create a small but complete application and test suite. Your instructor will review your repo, assess your test coverage and strategy, and ensure your application runs locally using the steps you provide in your README.

## 1. Plan Your App

First, decide on a simple app idea. The concept can be anything — a to-do tracker, e-commerce, travel booking, finance app, recipe manager, quote viewer, book catalog, etc.... Keep it small and focused.

**Your app must:**

- Include **a FastAPI backend** with **at least 3 routes**.
- Serve a **static HTML frontend** that interacts with those routes using JavaScript (ex: `fetch`).
- Contain **a minimum of 7 automated tests**:
  - ✅ **3 unit or integration tests**
  - ✅ **4 Selenium end-to-end tests**

## 2. Set Up Your Project

Organize your codebase in a clean, modular way. Here’s a suggested structure:

```text
/your-project/
├── app/
│   ├── main.py
│   ├── routes.py
│   └── static/
│       └── index.html
├── tests/
│   ├── test_unit.py
│   ├── test_integration.py
│   └── test_e2e.py
├── requirements.txt
└── README.md
```

### Recommended Tools and Libraries

Install these in a virtual environment (`venv`):

```bash
pip install fastapi uvicorn
pip install pytest httpx
pip install selenium
```

If needed, include setup steps for chromedriver in your README.

## 3. Build Your App

### Backend (FastAPI)

You should:

- Create **at least 3 API routes**, such as:
  - `GET /items`
  - `POST /items`
  - `DELETE /items/{id}`
- Avoid complex features like databases or authentication unless you're comfortable adding them.
- Store data in memory using Python dictionaries or lists — that’s enough for this project!

### Frontend (Static HTML)

You should:

- Create an `index.html` that interacts with your backend using `fetch` or basic forms.
- Add simple UI features that a Selenium test can interact with:
  - Buttons
  - Forms
  - List items
  - Text updates

## 4. Write Tests

Organize your tests clearly:

### ✅ Unit Test

- Test an isolated function (ex: input validation or formatting logic).

### ✅ Integration Test

- Test how multiple components interact (ex: a test that sends a request to an actual route and verifies the full response).

### ✅ End-to-End Tests (Selenium)

Write at least 4 Selenium tests that interact with the frontend like a real user:

- Click a button and verify the DOM updates
- Fill out and submit a form
- Navigate or scroll to a section
- Confirm data appears from the backend

## 5. Run and Document Everything

Make sure:

- All tests can be run using `pytest`
- You include a working `README.md` with:
  - App description
  - Setup instructions
  - How to run the app and the tests
  - Technologies used

## Tips

- Use simple data structures (no need for a database unless you want to try).
- Build your backend first, then create a basic UI to support testing.
- Keep Selenium tests small — one clear user interaction per test is enough.
- Prioritize passing tests and working features over visual polish.
- Ask for instructor feedback early if you're unsure about scope or direction.
