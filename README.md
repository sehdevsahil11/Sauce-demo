# SauceDemo E-Commerce Automation Project

This is a UI test automation project for [SauceDemo](https://www.saucedemo.com/), built using Python, Selenium, and PyTest.

---

## ✅ Features Covered

- User Login (valid & invalid)
- Product Listing
- Product Filtering (by name, price)
- Product Details Page
- Cart Functionality (add, remove, verify)
- Checkout Flow (with field validations)

---

## 🧪 Test Strategy

The overall testing strategy including scope, types of testing, tools, and environments is documented in [`TEST-STRATEGY`](./TEST-STRATEGY). In summary:

- Focus on end-to-end user flows and edge cases
- Automated via Selenium WebDriver + PyTest
- Structured using Page Object Model (POM)

---

## 📝 Test Plan

Detailed test plans for each feature are included in [`TEST-PLANS`](./TEST-PLANS), outlining:

- Test objectives
- Scenarios and steps
- Entry/exit criteria
- Data requirements

---

## ⚙️ Framework Choice: PyTest

**Why PyTest?**
- Easy syntax, great for writing concise tests
- Fixture support for reusable setup/teardown
- Strong community and plugin support (e.g. `pytest-html`, `allure`)

---

## 🪲 Bug Reporting

All reported issues are included in [`BUGREPORT-1.MD`](./BUGREPORT-1.MD) and follow this format:
- Clear title and reproduction steps
- Expected vs actual result
- Severity and Priority

---

## 📦 Installation Instructions

```bash
# Clone the repository
git clone <repo-url>
cd saucedemo_automation

# Setup virtual environment
python -m venv venv
source venv/bin/activate  # or venv\\Scripts\\activate on Windows

# Install dependencies
pip install -r requirements.txt
