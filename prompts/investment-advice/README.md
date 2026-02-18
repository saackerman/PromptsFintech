# Investment Advice Prompts

This directory contains prompts for testing AI's ability to provide investment analysis and recommendations.

## Prompts in this Category

1. [Portfolio Rebalancing](#1-portfolio-rebalancing)
2. [Retirement Planning](#2-retirement-planning)
3. [Tax-Loss Harvesting](#3-tax-loss-harvesting)

---

## 1. Portfolio Rebalancing

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
A client's portfolio has drifted from target allocation due to market performance:

Target Allocation (Set 1 year ago):
- 60% Stocks (30% US, 20% International, 10% Emerging Markets)
- 30% Bonds (20% Investment Grade, 10% High Yield)
- 10% Alternative Investments (REITs, Commodities)

Current Allocation (After 1 year):
- 68% Stocks (35% US, 22% International, 11% Emerging Markets)
- 24% Bonds (17% Investment Grade, 7% High Yield)
- 8% Alternative Investments (5% REITs, 3% Commodities)

Portfolio Value: $1,000,000
Client Profile:
- Age: 52
- Risk Tolerance: Moderate
- Time Horizon: 13 years to retirement
- Tax Situation: High income bracket, taxable account
- No immediate liquidity needs

Market Context:
- Stocks have outperformed bonds significantly
- REITs underperformed due to rising interest rates
- Client has $50,000 in realized gains this year
- No tax-loss harvesting opportunities currently

Questions:
1. Should the portfolio be rebalanced? Why or why not?
2. If rebalancing, what trades are needed?
3. What tax implications should be considered?
4. Are there alternatives to selling winners?
5. How should future contributions be allocated?
```

### Expected Evaluation Points

1. **Rebalancing Decision**: Recognizes significant drift warrants rebalancing
2. **Tax Awareness**: Considers tax implications of selling appreciated assets
3. **Trade Calculation**: Accurately determines rebalancing trades needed
4. **Alternative Strategies**: Suggests directing new contributions, tax-efficient methods
5. **Risk Assessment**: Evaluates if current allocation still appropriate for age/goals

### Key Concepts Tested

- Portfolio rebalancing
- Asset allocation
- Tax-efficient investing
- Risk management
- Investment policy adherence

---

## 2. Retirement Planning

**Difficulty Level**: Advanced

**Estimated Response Time**: Detailed

### The Prompt

```
Create a retirement analysis for this client:

Client Information:
- Current Age: 58
- Desired Retirement Age: 67
- Life Expectancy Planning: Age 95
- Current Income: $180,000/year
- Spouse Income: $120,000/year (Spouse age 56)

Current Savings:
- 401(k): $850,000 (client)
- 401(k): $520,000 (spouse)
- Traditional IRA: $200,000 (client)
- Roth IRA: $150,000 (client)
- Taxable Brokerage: $300,000 (joint)
- Cash/Emergency Fund: $75,000
- Home Equity: $400,000 (paid off)
Total: $2,495,000

Retirement Contributions:
- Client 401(k): $25,000/year (includes employer match)
- Spouse 401(k): $18,000/year (includes employer match)
- Roth IRA: $7,000/year (client, catch-up contribution)

Expected Expenses in Retirement:
- Basic living expenses: $90,000/year
- Healthcare (pre-Medicare): $20,000/year
- Healthcare (post-Medicare): $12,000/year
- Travel/discretionary: $25,000/year
- Total: $115,000-$127,000/year (depending on healthcare)

Income Sources in Retirement:
- Social Security (client at 67): $36,000/year
- Social Security (spouse at 67): $28,000/year
- No pension

Additional Considerations:
- Inflation assumed at 3%
- Investment return assumed at 7% pre-retirement, 6% post-retirement
- Plan to help grandchildren with college: $100,000 total
- Want to leave estate of at least $500,000

Provide:
1. Will they have enough for retirement?
2. What is their projected portfolio value at retirement?
3. What withdrawal rate would they need?
4. Is this sustainable for 28 years of retirement?
5. What risks should they plan for?
6. What recommendations would you make?
```

### Expected Evaluation Points

1. **Calculations**: Projects future value of savings, accounts for contributions
2. **Income Gap**: Identifies difference between expenses and Social Security
3. **Withdrawal Rate**: Calculates sustainable withdrawal rate
4. **Longevity Planning**: Considers 28-year retirement period
5. **Risk Factors**: Healthcare costs, inflation, sequence of returns, longevity
6. **Recommendations**: Specific, actionable advice on savings, allocation, timing

### Key Concepts Tested

- Retirement planning calculations
- Time value of money
- Withdrawal rate strategies
- Social Security optimization
- Healthcare cost planning
- Estate planning considerations

---

## 3. Tax-Loss Harvesting

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
A client's taxable investment account has the following positions:

Current Holdings (December 15):
1. Vanguard S&P 500 ETF (VOO)
   - Shares: 500
   - Cost Basis: $400/share
   - Current Price: $450/share
   - Unrealized Gain: $25,000

2. Tech Growth Fund (ABC)
   - Shares: 1,000
   - Cost Basis: $80/share
   - Current Price: $65/share
   - Unrealized Loss: -$15,000

3. International Stock Fund (XYZ)
   - Shares: 2,000
   - Cost Basis: $30/share
   - Current Price: $25/share
   - Unrealized Loss: -$10,000

4. Corporate Bond Fund (BOND)
   - Shares: 800
   - Cost Basis: $100/share
   - Current Price: $95/share
   - Unrealized Loss: -$4,000

5. Small Cap Value Fund (SCV)
   - Shares: 600
   - Cost Basis: $70/share
   - Current Price: $72/share
   - Unrealized Gain: $1,200

Client Situation:
- Tax bracket: 32% federal, 5% state
- Already has $40,000 in realized short-term capital gains this year
- No realized losses this year yet
- Wants to maintain similar market exposure
- Account total value: $440,000

Questions:
1. What tax-loss harvesting opportunities exist?
2. What is the total tax benefit available?
3. What are the wash sale rule implications?
4. What replacement securities would you suggest?
5. Should all losses be harvested now, or is there a better strategy?
6. What should happen with the harvested losses?
```

### Expected Evaluation Points

1. **Loss Identification**: Identifies $29,000 in harvestable losses
2. **Tax Benefit**: Calculates offset to capital gains (37% total tax rate)
3. **Wash Sale Awareness**: Explains 30-day rule and substantially identical securities
4. **Replacement Strategy**: Suggests similar but not identical funds
5. **Timing Consideration**: Discusses year-end timing and carryforward rules
6. **Strategic Planning**: Considers future tax situations and rebalancing opportunities

### Key Concepts Tested

- Tax-loss harvesting mechanics
- Wash sale rules
- Capital gains offset strategies
- Investment similarity and substitution
- Tax planning timing
- Portfolio management during tax harvesting

---

## Using These Prompts

Evaluate AI responses on:
- Technical accuracy of calculations
- Understanding of tax implications
- Practical investment knowledge
- Risk awareness
- Personalization to client situation
- Regulatory and fiduciary considerations

**Important**: AI should acknowledge when advice requires licensed professional input.
