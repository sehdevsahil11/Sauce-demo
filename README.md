# SauceDemo Automation Suite

## Features Covered
- Login
- Product listing
- Filtering
- Cart
- Checkout

## Setup Instructions
```bash
git clone <repo>
cd saucedemo_automation
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pytest
```

## Run All Tests
```bash
pytest
```

## Run With HTML Report
```bash
pytest --html=reports/report.html
```
