# Ben Felix's 5% Rule: Buy vs Rent Calculator

## Overview

This notebook calculates the breakeven monthly rent using Ben Felix's 5% Rule, which compares the unrecoverable costs of renting a home to buying one. The 5% Rule provides a quick heuristic for individuals to evaluate whether buying a home is financially advantageous compared to renting.

## Requirements

- Python 3.x
- pandas
- numpy_financial
- matplotlib
- seaborn

## How to Use

1. **Import Libraries**: Run the cell that imports the necessary Python libraries.
2. **Set Parameters**: 
    - `home_price`: The price of the home you are considering buying.
    - `tax_rate`: The property tax rate in your jurisdiction.
    - `mortgage_rate`: The mortgage rate for a 30-year fixed-rate mortgage.
    - `years`: The length of the mortgage in years (usually 30).
    
    Fill in these parameters in the designated code cells.
    
3. **Run Cells**: Execute the remaining cells to calculate and display the unrecoverable costs and breakeven rent.

## What it Calculates


- **Maintenance Cost**: Assumed to be 1% of the home price per year.
- **Cost of Capital**: 
    - **Cost of Debt**: Monthly mortgage payment based on the mortgage rate and home price.
    - **Cost of Equity**: Opportunity cost of using your down payment to buy the home instead of investing it elsewhere.
- **Breakeven Rent**: Sum of all the above costs. If you can rent for less than this amount, renting may be the more cost-effective choice.

## Outputs

- **Cost Summary Table**: A table summarizing all the calculated costs and the breakeven rent.

## Source

The methodology is based on the ideas presented by Ben Felix in his video: [The 5% Rule of Buying vs. Renting a Home](https://www.youtube.com/watch?v=Uwl3-jBNEd4).

## Disclaimer

This is a simplified model and should not be used as the sole basis for any financial decisions. Always consult with a financial advisor for personalized advice.
