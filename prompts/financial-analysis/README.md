# Financial Analysis Prompts

This directory contains prompts for testing AI's ability to analyze financial statements, metrics, and business performance.

## Prompts in this Category

1. [Financial Statement Analysis](#1-financial-statement-analysis)
2. [Cash Flow Analysis](#2-cash-flow-analysis)
3. [Valuation Analysis](#3-valuation-analysis)

---

## 1. Financial Statement Analysis

**Difficulty Level**: Intermediate

**Estimated Response Time**: Detailed

### The Prompt

```
Analyze the following financial statements for TechStart Inc., a B2B SaaS company:

Income Statement (Year Ended Dec 31, 2023):
Revenue: $10,000,000
Cost of Revenue: $2,000,000
Gross Profit: $8,000,000
Operating Expenses:
  - Sales & Marketing: $4,500,000
  - Research & Development: $2,000,000
  - General & Administrative: $1,200,000
Operating Income: $300,000
Interest Expense: $100,000
Net Income: $200,000

Balance Sheet (As of Dec 31, 2023):
Assets:
  - Cash: $3,000,000
  - Accounts Receivable: $2,500,000
  - Other Current Assets: $500,000
  - Property & Equipment: $1,000,000
  - Intangible Assets: $2,000,000
Total Assets: $9,000,000

Liabilities:
  - Accounts Payable: $1,000,000
  - Deferred Revenue: $3,500,000
  - Long-term Debt: $2,000,000
Total Liabilities: $6,500,000

Equity: $2,500,000

Additional Metrics:
- Customer Acquisition Cost (CAC): $1,200
- Customer Lifetime Value (LTV): $8,000
- Monthly Recurring Revenue (MRR): $750,000
- Annual Recurring Revenue (ARR): $9,000,000
- Churn Rate: 5% annually
- Number of Customers: 500

Previous Year (2022):
- Revenue: $6,000,000
- Net Income: -$500,000
- ARR: $5,400,000

Provide:
1. Key financial ratios and what they indicate
2. Analysis of the company's profitability and growth
3. Assessment of financial health
4. Red flags or concerns
5. Positive indicators
```

### Expected Evaluation Points

1. **Ratio Analysis**: Calculates and interprets relevant ratios (margins, liquidity, etc.)
2. **Growth Assessment**: Recognizes strong revenue growth (67% YoY)
3. **SaaS Metrics**: Understands LTV/CAC ratio, ARR growth, churn impact
4. **Concerns**: Identifies high S&M spend, deferred revenue implications
5. **Overall Assessment**: Balanced view of growth vs. profitability

### Key Concepts Tested

- Financial statement interpretation
- SaaS-specific metrics
- Ratio analysis
- Trend analysis
- Business model understanding

---

## 2. Cash Flow Analysis

**Difficulty Level**: Basic

**Estimated Response Time**: Moderate

### The Prompt

```
Review this company's cash flow situation:

Monthly Cash Flow Statement:
Beginning Cash Balance: $100,000

Cash Inflows:
- Customer payments received: $180,000
- New loan proceeds: $50,000
Total Inflows: $230,000

Cash Outflows:
- Payroll: $120,000
- Rent: $15,000
- Suppliers/Inventory: $80,000
- Loan payment: $10,000
- Marketing: $25,000
- Utilities: $5,000
- Other expenses: $15,000
Total Outflows: $270,000

Ending Cash Balance: $60,000

Additional Information:
- Accounts Receivable: $150,000 (60-90 days outstanding)
- Accounts Payable: $90,000 (currently 45 days past due)
- Upcoming expenses: $50,000 equipment purchase needed next month
- Revenue is seasonal - next month expected to be 30% lower

Questions:
1. What is the company's cash position?
2. What problems do you identify?
3. What immediate actions should management take?
4. What long-term improvements are needed?
```

### Expected Evaluation Points

1. **Cash Position**: Recognizes deteriorating cash balance and negative cash flow
2. **Problem Identification**: Late payables, slow receivables, seasonal risk
3. **Immediate Actions**: Accelerate collections, delay equipment purchase, negotiate with suppliers
4. **Long-term Solutions**: Improve collections process, build cash reserves, manage seasonality

### Key Concepts Tested

- Cash flow analysis
- Working capital management
- Liquidity assessment
- Short-term financial planning

---

## 3. Valuation Analysis

**Difficulty Level**: Advanced

**Estimated Response Time**: Detailed

### The Prompt

```
You're evaluating an acquisition opportunity. The target company has:

Financial Performance (Last 12 Months):
- Revenue: $5,000,000
- EBITDA: $1,250,000
- Net Income: $750,000
- Free Cash Flow: $900,000

Growth History:
- 3-year Revenue CAGR: 25%
- EBITDA margin improving from 20% to 25%

Market Information:
- Industry: E-commerce (Fashion)
- Comparable companies trade at 12-15x EBITDA
- Recent similar acquisition: 14x EBITDA multiple
- Market is growing at 10% annually

Target Company Specifics:
- Strong brand recognition in niche market
- 60% revenue from repeat customers
- Proprietary technology platform
- Key person dependency (founder CEO)
- 3-year supplier contracts in place
- Customer concentration: Top 10 customers = 40% of revenue

Synergies Expected:
- Cost savings: $200,000 annually
- Revenue synergies: $300,000 annually (realistic estimate)

Using multiple valuation methods:
1. What is a fair valuation range for this company?
2. What are the key value drivers?
3. What are the main risks to value?
4. What due diligence items are critical?
5. What deal structure would you recommend?
```

### Expected Evaluation Points

1. **Multiple Methods**: Uses EBITDA multiple, DCF considerations, comparable analysis
2. **Valuation Range**: Reasonable range considering market multiples and synergies
3. **Value Drivers**: Identifies recurring revenue, growth, margins, synergies
4. **Risk Assessment**: Key person risk, customer concentration, market conditions
5. **Deal Structure**: Considers earnouts, risk mitigation in structure

### Key Concepts Tested

- Business valuation methods
- M&A analysis
- Risk assessment in valuation
- Synergy evaluation
- Deal structuring

---

## Using These Prompts

These prompts test AI's ability to:
- Perform financial calculations accurately
- Interpret financial data in business context
- Identify both strengths and weaknesses
- Provide actionable recommendations
- Understand industry-specific metrics
