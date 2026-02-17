# Smart Portfolio Optimizer

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> An intelligent tool for finding the optimal mix of stocks in a portfolio using Modern Portfolio Theory (MPT).

This project helps investors visualize the risk-return tradeoff for thousands of randomly generated portfolios and identifies the ones that offer the highest return for a given level of risk.

## Table of Contents

- [Features](#features)
- [Modern Portfolio Theory (MPT)](#modern-portfolio-theory-mpt)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

-   **Historical Data**: Fetches historical stock data using yfinance.
-   **Portfolio Simulation**: Generates and analyzes over 10,000 random portfolios.
-   **Key Metrics Calculation**:
    -   Expected Returns
    -   Covariance Matrix
    -   Portfolio Volatility
    -   Sharpe Ratio
-   **Optimal Portfolio Identification**:
    -   Maximum Sharpe Ratio Portfolio
    -   Minimum Volatility Portfolio
-   **Advanced Visualization**:
    -   Plots the efficient frontier.
    -   Colors portfolios by Sharpe ratio.
    -   Highlights the optimal portfolios.

## Modern Portfolio Theory (MPT)

MPT is a financial theory that aims to maximize portfolio return for a given level of risk. The key concepts are:

-   **Expected Returns ($\mu$):**
    $$\mu = \frac{1}{N} \sum_{i=1}^{N} r_i$$

-   **Covariance Matrix ($\Sigma$):**
    $$\Sigma_{ij} = \text{Cov}(r_i, r_j)$$

-   **Portfolio Volatility ($\sigma_p$):**
    $$\sigma_p = \sqrt{w^T \Sigma w}$$

-   **Sharpe Ratio ($S$):**
    $$S = \frac{\mu_p - r_f}{\sigma_p}$$

-   **Efficient Frontier:** The set of optimal portfolios that offer the highest expected return for a defined level of risk.

## Tech Stack

-   Python
-   yfinance
-   pandas
-   numpy
-   matplotlib
-   scipy

## Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AbhiramSharma/Smart-Portfolio-Optimizer.git
    cd Smart-Portfolio-Optimizer
    ```

2.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the optimizer, execute the following command:

```bash
python main.py
```

## File Structure

-   `main.py`: The main entry point for running the optimizer and generating visualizations.
-   `optimizer.py`: Contains the core logic for portfolio optimization and calculations.
-   `requirements.txt`: A list of the Python dependencies for the project.
-   `README.md`: This file.

## Contributing

Contributions are welcome! If you have ideas for new features or improvements, feel free to fork the repository and submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

Abhiram Sharma - ab23.ar39@gmail.com

Project Link: [https://github.com/AbhiramSharma/Smart-Portfolio-Optimizer](https://github.com/AbhiramSharma/Smart-Portfolio-Optimizer)
