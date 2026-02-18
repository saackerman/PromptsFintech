# Risk Assessment Prompts

This directory contains prompts for testing AI's ability to evaluate and analyze financial risks.

## Prompts in this Category

1. [Credit Risk Evaluation](#1-credit-risk-evaluation)
2. [Market Risk Analysis](#2-market-risk-analysis)
3. [Operational Risk Assessment](#3-operational-risk-assessment)

---

## 1. Credit Risk Evaluation

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
A small business is applying for a $500,000 loan. Evaluate their credit risk based on the following information:

Company Profile:
- Industry: Restaurant (Fast Casual)
- Years in business: 3 years
- Annual Revenue: $800,000
- Annual Expenses: $720,000
- Current Debt: $150,000 (equipment loan)
- Employees: 12

Financial Metrics:
- Debt-to-Income Ratio: 18.75%
- Current Ratio: 1.2
- Cash on Hand: $50,000
- Accounts Receivable: $20,000
- Inventory: $15,000

Additional Information:
- Owner's credit score: 680
- 2 late payments in past year on existing loan
- Business operates in a competitive area with 8 similar restaurants within 2 miles
- Lease expires in 18 months
- Purpose of loan: Expansion to second location

Provide:
1. Overall risk assessment (Low/Medium/High)
2. Key risk factors
3. Mitigating factors
4. Loan recommendation (Approve/Decline/Conditional)
5. If conditional, what terms or requirements would you suggest?
```

### Expected Evaluation Points

1. **Risk Factors**: Identifies competitive market, lease expiration, past late payments
2. **Financial Analysis**: Evaluates thin profit margin, adequate liquidity
3. **Industry Knowledge**: Recognizes restaurant industry challenges
4. **Balanced Assessment**: Considers both risks and positive factors
5. **Practical Recommendation**: Provides clear reasoning for decision

### Key Concepts Tested

- Credit risk analysis
- Financial ratio interpretation
- Industry-specific risks
- Loan underwriting
- Risk mitigation strategies

---

## 2. Market Risk Analysis

**Difficulty Level**: Advanced

**Estimated Response Time**: Detailed

### The Prompt

```
An investment portfolio consists of:

- 40% U.S. Large Cap Stocks (S&P 500 index fund)
- 20% International Developed Markets Stocks
- 15% Emerging Markets Stocks
- 15% Corporate Bonds (Investment Grade)
- 10% Cash/Money Market

Client Profile:
- Age: 45
- Retirement goal: Age 65 (20 years)
- Risk tolerance: Moderate
- Current portfolio value: $500,000
- Annual contributions: $25,000
- No planned withdrawals before retirement

Market Conditions:
- Current interest rates rising (Federal Reserve hiking cycle)
- Inflation at 4% annually
- U.S. stock market at all-time highs
- Emerging markets showing volatility
- Corporate bond spreads widening

Assess:
1. What market risks does this portfolio face?
2. How might rising interest rates impact each asset class?
3. Is the portfolio appropriately allocated for the client's profile?
4. What adjustments, if any, would you recommend?
5. How should the client prepare for a potential market downturn?
```

### Expected Evaluation Points

1. **Risk Identification**: Interest rate risk, equity risk, currency risk, inflation risk
2. **Asset Impact Analysis**: Understands bond duration risk, equity volatility
3. **Suitability**: Evaluates if allocation matches moderate risk profile
4. **Recommendations**: Balanced suggestions considering time horizon
5. **Downside Protection**: Strategies for managing market downturn

### Key Concepts Tested

- Market risk types
- Asset allocation principles
- Interest rate impact
- Portfolio construction
- Risk-adjusted returns

---

## 3. Operational Risk Assessment

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
A fintech company is launching a new peer-to-peer payment application. Identify and assess the operational risks:

Company Details:
- Startup with 2 years operating history
- 15 employees (5 developers, 3 support, 7 admin/business)
- Expected user base: 100,000 in first year
- Average transaction value: $150
- Expected monthly volume: $15 million

Technology Infrastructure:
- Cloud-based architecture (AWS)
- Third-party payment processor integration
- In-house developed mobile app (iOS and Android)
- Customer data stored in encrypted database
- Single data center region
- Disaster recovery plan: Untested backup system

Compliance & Security:
- No dedicated compliance officer
- Basic cybersecurity measures in place
- No penetration testing performed
- AML/KYC procedures documented but not fully implemented
- Customer service team has access to sensitive data
- No formal incident response plan

What are the key operational risks? Prioritize them and recommend mitigation strategies.
```

### Expected Evaluation Points

1. **Risk Identification**: Cybersecurity, compliance, technology, people, process risks
2. **Prioritization**: Ranks risks by severity and likelihood
3. **Regulatory Awareness**: Recognizes compliance gaps (AML/KYC)
4. **Technical Risks**: Identifies single point of failure, untested DR
5. **Mitigation**: Practical and specific recommendations

### Key Concepts Tested

- Operational risk categories
- Fintech regulatory requirements
- Business continuity planning
- Security best practices
- Scalability concerns

---

## Using These Prompts

Test AI systems on their ability to:
- Identify multiple risk types
- Balance quantitative and qualitative factors
- Provide actionable recommendations
- Consider regulatory and compliance aspects
- Think through real-world scenarios
