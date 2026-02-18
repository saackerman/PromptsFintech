# Credit Scoring Prompts

This directory contains prompts for testing AI's understanding of credit evaluation and lending decisions.

## Prompts in this Category

1. [Personal Credit Evaluation](#1-personal-credit-evaluation)
2. [Alternative Credit Scoring](#2-alternative-credit-scoring)
3. [Credit Score Improvement Advice](#3-credit-score-improvement-advice)

---

## 1. Personal Credit Evaluation

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
Evaluate this loan application:

Applicant Information:
- Name: Jennifer Martinez
- Age: 29
- Employment: Registered Nurse, 4 years at current hospital
- Annual Income: $78,000
- Requested Loan: $25,000 (debt consolidation)
- Requested Term: 5 years

Credit Report:
- Credit Score: 660 (FICO)
- Payment History:
  * Auto loan: 48 payments, 2 late payments (30 days, over 2 years ago)
  * Credit Card #1: $8,000 balance, $10,000 limit, always pays minimum
  * Credit Card #2: $3,500 balance, $5,000 limit, occasional late payments
  * Credit Card #3: $2,200 balance, $3,000 limit, recent (6 months old)
  * Student Loans: $42,000 balance, in good standing, $380/month
  * No collections, no bankruptcies, no foreclosures

Credit Utilization: 74%
Credit History Length: 7 years
Recent Hard Inquiries: 3 (in past 6 months)
New Accounts: 2 (in past year)

Debt-to-Income Calculation:
Monthly Income: $6,500
Current Debt Payments:
- Student Loans: $380
- Auto Loan: $420
- Credit Card Minimums: $350
Total: $1,150
DTI: 17.7%

Additional Information:
- Rent: $1,400/month (not included in DTI)
- Savings: $2,500
- 401(k): $15,000
- No other assets
- Purpose: Pay off credit cards to reduce interest
- Current avg credit card APR: 22%
- Proposed loan APR: 12%

Questions:
1. Should this loan be approved?
2. What are the positive factors?
3. What are the risk factors?
4. What loan terms would you recommend?
5. What alternative solutions might be better?
```

### Expected Evaluation Points

1. **Approval Decision**: Likely approve with conditions or reduced amount
2. **Positive Factors**: Stable employment, improving payment history, debt consolidation purpose makes sense
3. **Risk Factors**: High credit utilization, recent credit seeking, borderline credit score
4. **Terms**: Possibly approve $20,000 instead of $25,000, or require higher rate
5. **Alternatives**: Balance transfer card, secured loan, credit counseling

### Key Concepts Tested

- Credit analysis
- Risk assessment
- Debt-to-income calculation
- Credit report interpretation
- Lending decision factors
- Alternative financial solutions

---

## 2. Alternative Credit Scoring

**Difficulty Level**: Advanced

**Estimated Response Time**: Detailed

### The Prompt

```
A fintech lender is developing an alternative credit scoring model for underbanked populations:

Traditional Applicant Profile:
- No traditional credit score (credit invisible)
- Age: 34
- Recent immigrant (3 years in country)
- Employment: Restaurant manager, 2 years at current job
- Annual Income: $45,000
- Requesting: $5,000 personal loan

Alternative Data Available:
- Bank Account History (24 months):
  * Regular deposits matching salary
  * Average balance: $1,200
  * 3 overdrafts in 24 months (all covered within 3 days)
  * Consistent bill payments (rent, utilities, phone)
  * Monthly surplus: ~$300 after expenses

- Rental Payment History:
  * 24 months of on-time rent payments ($900/month)
  * Verified through property management system
  * No evictions or disputes

- Utility Payments:
  * Electric, gas, internet paid on time 90% of time
  * Average monthly: $180
  * 2 late payments (within 15 days)

- Employment Verification:
  * 2 years continuous employment
  * Started at $38,000, now at $45,000
  * Employer confirms reliable employee

- Education:
  * Business management degree from home country
  * Currently taking online courses (paid consistently)

- Mobile Phone:
  * 30 months of service
  * Paid on time 95% of time
  * $80/month plan

- Cash Flow Analysis:
  * Consistent income
  * Spending patterns stable
  * Occasional money transfers to family ($200-300/month)
  * Small emergency savings ($2,000)

Questions:
1. How would you assess creditworthiness without traditional credit score?
2. What risk factors are present in the alternative data?
3. What positive indicators exist?
4. Should the loan be approved? At what rate?
5. What additional data would strengthen the assessment?
6. How does this compare to traditional credit scoring?
7. What are the risks of using alternative data?
```

### Expected Evaluation Points

1. **Alternative Assessment**: Values behavioral patterns, cash flow stability, rental history
2. **Risk Factors**: Credit invisibility, international money transfers (cultural, not risk), thin file
3. **Positive Indicators**: Strong rent history, employment stability, positive cash flow
4. **Lending Decision**: Approve with slightly higher rate to account for uncertainty
5. **Additional Data**: References, savings rate, longer transaction history, social validation
6. **Comparison**: More holistic but less predictive than FICO, includes behavioral finance
7. **Alternative Data Risks**: Privacy, disparate impact, data quality, regulatory compliance

### Key Concepts Tested

- Alternative credit scoring methods
- Financial inclusion
- Risk assessment without traditional credit
- Behavioral finance indicators
- Regulatory considerations (Fair Lending)
- Data ethics and bias

---

## 3. Credit Score Improvement Advice

**Difficulty Level**: Basic

**Estimated Response Time**: Moderate

### The Prompt

```
A customer asks for help improving their credit score:

Current Situation:
- Credit Score: 585 (Poor)
- Goal: Reach 700+ within 18 months (for mortgage application)

Credit Report Details:

Negative Items:
- 1 Collection: Medical bill $850 (2 years old, unpaid)
- 2 Charge-offs: Credit cards totaling $3,200 (3 years old, unpaid)
- Late Payments: 8 in past 24 months (various accounts)
- Bankruptcy: None
- Foreclosure: None

Current Accounts:
- Credit Card #1: $450 balance / $500 limit (90% utilization)
- Credit Card #2: $1,800 balance / $2,000 limit (90% utilization)
- Auto Loan: $8,500 balance, $285/month, current (no late payments in 12 months)
- Store Credit Card: $300 balance / $500 limit (60% utilization)

Credit Mix: 4 accounts
Average Age of Accounts: 4 years
Recent Inquiries: 5 (in past year)

Financial Capacity:
- Monthly Income: $3,800
- Monthly Expenses: $2,900
- Available to pay down debt: $900/month
- Emergency Savings: $1,000

Customer Questions:
1. What steps should I take to improve my score?
2. Should I pay off collections/charge-offs?
3. How should I prioritize my debts?
4. Should I close any accounts?
5. What about the high utilization?
6. Can I reach 700 in 18 months?
7. Should I get a secured credit card?

Provide a realistic action plan with priorities and timeline.
```

### Expected Evaluation Points

1. **Immediate Actions**: Pay down utilization (biggest quick impact), stop new inquiries
2. **Collection Strategy**: Negotiate pay-for-delete on collection, consider settling charge-offs
3. **Debt Priority**: High-utilization cards first, maintain auto loan payments
4. **Account Management**: Keep accounts open (average age), use them lightly
5. **Utilization Plan**: Get below 30%, ideally below 10%
6. **Timeline Reality**: 700 is possible but aggressive; 650-680 more realistic in 18 months
7. **Secured Card**: Yes, if responsible use to build positive history

### Key Concepts Tested

- Credit score factors and weights
- Credit repair strategies
- Debt payoff optimization
- Credit utilization impact
- Realistic timeline expectations
- Financial counseling
- Credit building techniques

---

## Using These Prompts

Evaluate AI on:
- Credit industry knowledge
- Risk assessment capability
- Practical financial advice
- Regulatory awareness (Fair Lending, ECOA)
- Ethical considerations in lending
- Customer education quality
