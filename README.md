# Quantitative Finance and Algorithmic Trading in Python

This repository contains my own implementation of concepts and strategies from the course **Quantitative Finance and Algorithmic Trading in Python** on Udemy. It builds upon the materials presented in the course, adding personalized approaches, optimizations, and additional strategies.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Setup and Installation](#setup-and-installation)
4. [Folder Structure](#folder-structure)
5. [How to Use](#how-to-use)
6. [Topics Covered](#topics-covered)
7. [Contributing](#contributing)
8. [License](#license)

---

## Project Overview

This project explores:

- Fundamentals of quantitative finance
- Custom algorithmic trading strategies
- Implementation of financial models in Python with a focus on personalization and experimentation

By working on this project, I aim to:

- Deepen my understanding of quantitative finance.
- Develop and optimize Python scripts for backtesting trading strategies.
- Build robust and reproducible algorithmic trading systems based on real-world scenarios.

## Features

- **Pure Python Files**: Implementation of all models and strategies in Python scripts.
- **Custom Strategies**: Implementation of unique strategies inspired by real-world finance.
- **Backtesting Framework**: Enhanced backtesting system for strategy evaluation.
- **Optimization**: Experiment with parameter tuning and machine learning enhancements.

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Folder Structure

```plaintext
📁 repo-root/
├── 📁 data/                  # Datasets used in the project
├── 📁 scripts/               # Python scripts for models and strategies
├── 📄 requirements.txt       # Required Python packages
└── 📄 README.md              # Project overview (this file)
```

## How to Use

1. **Run Scripts:** Navigate to the `scripts/` folder and execute the Python files for different models and strategies. For example:

   ```bash
   python scripts/black_scholes.py
   ```

2. **Analyze Results:** Check the console output or generated files for performance metrics and insights.

## Topics Covered

- **Bonds:** Pricing, yield, and duration analysis.
- **Black-Scholes (BS):** Option pricing and Greeks calculation.
- **Markowitz Portfolio Theory:** Portfolio optimization using risk and return.
- **Capital Asset Pricing Model (CAPM):** Estimating expected returns and market risk.
- **Value at Risk (VaR):** Quantifying portfolio risk under different scenarios.
- **Vasicek Model:** Modeling interest rates for bond pricing and risk management.

## Contributing

Contributions are welcome! If you have suggestions or find areas for improvement:

1. Fork the repository.
2. Create a new branch for your changes:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Commit your changes and open a pull request.

## License

This repository is for personal and educational purposes. Unauthorized redistribution is prohibited.

