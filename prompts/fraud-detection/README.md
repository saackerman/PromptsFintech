# Fraud Detection Prompts

This directory contains prompts for testing AI's ability to identify and analyze fraudulent activities in financial systems.

## Prompts in this Category

1. [Suspicious Transaction Pattern](#1-suspicious-transaction-pattern)
2. [Credit Card Fraud Detection](#2-credit-card-fraud-detection)
3. [Account Takeover Scenario](#3-account-takeover-scenario)

---

## 1. Suspicious Transaction Pattern

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
A customer's bank account shows the following transaction pattern over the past 7 days:

Day 1: $50 purchase at local grocery store
Day 2: $1,200 wire transfer to an international account
Day 3: $3,500 wire transfer to same international account
Day 4: $75 gas station purchase
Day 5: $8,000 wire transfer to a different international account
Day 6: $2,500 cash withdrawal from ATM in different state
Day 7: Multiple small purchases totaling $200 at various online retailers

The customer typically has:
- Monthly deposits of $4,000 (salary)
- Regular expenses: rent ($1,500), utilities ($200), groceries ($400-600)
- Average transaction value: $50-150
- No history of international transfers
- No previous out-of-state ATM usage

Analyze this pattern and:
1. Identify potential fraud indicators
2. Determine the risk level (Low/Medium/High)
3. Recommend specific actions to take
4. Suggest preventive measures for the future
```

### Expected Evaluation Points

1. **Pattern Recognition**: Identifies unusual international transfers and large withdrawals
2. **Risk Assessment**: Properly evaluates the severity (should flag as High risk)
3. **Action Items**: Recommends immediate account freeze and customer contact
4. **Preventive Measures**: Suggests transaction limits, alerts, and verification steps

### Key Concepts Tested

- Anomaly detection
- Behavioral analysis
- Risk scoring
- Fraud prevention strategies

### Red Flags in Responses

- Failing to recognize the sudden change in transaction behavior
- Not considering the international transfer aspect
- Recommending minor actions for clearly suspicious activity
- Ignoring the out-of-state ATM withdrawal pattern

---

## 2. Credit Card Fraud Detection

**Difficulty Level**: Basic

**Estimated Response Time**: Quick

### The Prompt

```
A credit card shows these transactions within a 2-hour window:

12:00 PM - $85 at McDonald's in New York, NY
12:15 PM - $1,500 at Best Buy in Los Angeles, CA
12:30 PM - $200 at Shell Gas Station in Chicago, IL
12:45 PM - $2,500 at jewelry store in Miami, FL
1:00 PM - $50 at Starbucks in Seattle, WA
1:30 PM - Online purchase $3,000 from electronics website (IP in Romania)

What fraud indicators are present? Should the card be blocked? What should the fraud team do immediately?
```

### Expected Evaluation Points

1. **Geographic Impossibility**: Recognizes impossible travel distances in short timeframes
2. **Transaction Pattern**: Identifies escalating purchase amounts
3. **International Element**: Notes suspicious international online purchase
4. **Immediate Action**: Recommends immediate card block

### Key Concepts Tested

- Geographic velocity checking
- Transaction pattern analysis
- Real-time fraud detection
- Incident response

### Red Flags in Responses

- Not recognizing the geographic impossibility
- Suggesting to "monitor" rather than immediately block
- Missing the IP location mismatch

---

## 3. Account Takeover Scenario

**Difficulty Level**: Advanced

**Estimated Response Time**: Detailed

### The Prompt

```
A financial institution's security system logs the following activities for a customer account:

Timeline:
- Monday 2:00 AM: Login attempt from new device (iPhone, IP from Russia) - Failed (wrong password)
- Monday 2:05 AM: 4 more failed login attempts from same IP
- Monday 2:15 AM: Successful password reset using recovery email
- Monday 2:20 AM: Successful login from Russian IP
- Monday 2:25 AM: Email address changed
- Monday 2:30 AM: Phone number changed
- Monday 2:35 AM: $5,000 wire transfer initiated to overseas account
- Monday 2:40 AM: Transfer limit increase requested and approved via automated system
- Monday 2:45 AM: Additional $15,000 wire transfer initiated
- Monday 8:00 AM: Legitimate customer calls from their usual location (California) reporting locked account

Additional context:
- Account has been active for 5 years
- Customer typically logs in during business hours from California
- No previous international access
- No previous changes to contact information
- Automated system approved limit increase based on account history

Analyze this incident:
1. What type of attack occurred?
2. What security controls failed?
3. What should have triggered alerts?
4. How should the institution respond?
5. What preventive measures should be implemented?
```

### Expected Evaluation Points

1. **Attack Classification**: Correctly identifies as account takeover (ATO)
2. **Security Failures**: Points out weak password reset process, automated approval issues
3. **Alert Triggers**: Lists all the red flags that should have triggered alerts
4. **Response Plan**: Comprehensive incident response steps
5. **Prevention**: Multi-factor authentication, behavioral analytics, geographic controls

### Key Concepts Tested

- Account takeover detection
- Security control evaluation
- Incident response planning
- Multi-layered security
- Authentication best practices

### Red Flags in Responses

- Not identifying the password reset as the breach point
- Missing the automated approval system vulnerability
- Failing to recommend MFA implementation
- Not addressing the need for behavioral analytics

---

## Using These Prompts

1. Copy the prompt text exactly as written
2. Present it to different AI systems
3. Compare responses against the evaluation points
4. Rate each AI's performance on accuracy, completeness, and practical recommendations
