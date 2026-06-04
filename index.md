<link rel="stylesheet" href="styles.css">

# Isaic Cruse  
<p style="text-align: center;">
    <span id="location"></span> | P: <span id="phone"></span> | 
    <a href="mailto:isaiccruse28@gmail.com">isaiccruse28@gmail.com</a> | 
    <a href="https://github.com/Ahkylez">https://github.com/Ahkylez</a> | 
    <a href="http://www.linkedin.com/in/isaic-cruse">http://www.linkedin.com/in/isaic-cruse</a>
</p>


<script src="config.js"></script>
<script>
    if (typeof config !== 'undefined') {
        document.getElementById('location').innerText = config.LOCATION || "Remote / California";
        document.getElementById('phone').innerText = config.PHONE || "[Hidden]";
    } else {
        document.getElementById('location').innerText = "California";
        document.getElementById('phone').innerText = "[upon request]";
    }
</script>
---

* Applied Mathematics (CS Emphasis) undergraduate with research interest in quantitative finance, stochastic programming, and optimization.   
* First-author on a conference-submitted paper integrating TC-VAE with Vine Copula for stochastic portfolio optimization.   
* Selected as a UROC Research Scholar (5% acceptance rate) using Lean4 to formalize proofs under Prof. Juan Meza. 

## **EDUCATION**

---

<p class="item-header"><strong>University of California, Merced | B.S. in Applied Mathematics (CS Emphasis) | GPA: 3.7 </strong> <span>Expected May 2027</span></p>

**Relevant Coursework:** Mathematical Modeling, Probability & Statistics, Linear Algebra & Differential Equations, Numerical Analysis, Data Structures, Advanced Programming, Algorithm Design & Analysis, Complex Variables, Linear Analysis 

## **RESEARCH EXPERIENCE**

---

<p class="item-header"><strong>Undergraduate Research – Stochastic Programming & Generative Modeling</strong> <span>Merced, CA</span></p>
<p class="item-header">Mentor: Prof. Roummel F. Marcia<span>Oct 2025 – Present</span></p>

* **Conference Paper \- submitted:** Authored "Hybrid Time-Causal Variational Autoencoders with Vine Copula for Scenario Generation in Portfolio Optimization," recently submitted to multiple conferences. The hybrid model achieved a 12.75% total return vs. 10.20% for the ARMA-GARCH Vine Copula baseline over a 52-week out-of-sample backtest.  
* **C++ / Python Optimizer:** Engineered a two-stage stochastic CVaR-minimizing portfolio optimizer in C++ (using Google OR-Tools MPSolver), with Python for data wrangling, scenario generation, and backtesting.  
* **Scenario Generation (TC-VAE):** Implemented a Time-Causal VAE and applied posterior-bootstrapped sampling with a state-conditioned Vine Copula to correct correlation collapse, improving realized 95% CVaR to 5.47% (vs 6.07% baseline).   
* **Risk-Adjusted Performance:** Delivered 0.739 Sharpe and 1.250 Sortino (vs. 0.593/0.839 baseline) and lowered annualized volatility to 18.79% on average.   
* **Backtesting Infrastructure:** Built a dynamic 52-week rolling-window backtesting framework with weekly rebalancing and variable transaction costs, simulating realistic portfolio management at $100,000 initial wealth.  
* **Scientific Communication:** Presented technical research findings via a poster at the Undergraduate Research Opportunity Center (UROC).

<p class="item-header"><strong>UROC Research Scholar</strong> <span>Merced, CA</span></p>
<p class="item-header">Mentor: Prof. Juan Meza<span>June 2026 – Present</span></p>

* **Proofs for Finance:** Utilizing Lean 4 to explore the formal verification of non-linear financial models and optimization algorithms.  
* **Algorithmic Correctness:** Researching methods to prove the mathematical soundness of automated strategies, targeting high-reliability applications in derivatives and options pricing.

## **PROJECTS**

---

<p class="item-header"><strong>Quantitative Risk & MPT Engine | <i>Python, streamlit, Pandas, Numpy</i></strong><span>2025</span></p>

* Analytics Dashboard: Developed a Streamlit app for Modern Portfolio Theory (MPT) asset allocation.   
* Risk Attribution: Engineered modular libraries for automated multi-asset covariance estimation and downside risk metrics.

## **WORK EXPERIENCE**

--- 
<p class="item-header"><strong>UNIVERSITY OF CALIFORNIA, Merced</strong> <span>Merced, CA</span></p>
<p class="item-header">Learning Assistant - Calculus<span>Aug 2024 – Present</span></p>

* Mentored 1,000+ students by translating abstract mathematical concepts into actionable problem-solving techniques during collaborative review sessions. 

## **ADDITIONAL**

---

**Skills:** Python (PyTorch, scikit-learn, pandas, NumPy, Streamlit, Jupyter, Matplotlib, SciPy),  LaTeX, git, CVXPY, HIGHS/LP solver, SQL, Google OR-Tools MP Solver, Vim