# Retirement Simulator 🧓
Simulating investment returns based on the SPDR S&P 500 Trust ETF, or better known as SPY!

Mean and standard deviation of YOY change is collected from Date A to Date B.

This data is used to create a Gaussian Random Walk many years out.

**A valid Kaggle API is needed since that is where data is pulled.**

# Configuration (Python + Windows Git Bash)
New environment:
```
$ python -m venv venv
```
Activate:
```
$ source venv/Scripts/activate
```
Add packages:
```
$ python -m pip install -r requirements.txt
```
Deactivate:
```
$ deactivate
```