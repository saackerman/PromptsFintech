# Payment Processing Prompts

This directory contains prompts for testing AI's understanding of payment systems and transaction processing.

## Prompts in this Category

1. [Payment Gateway Integration](#1-payment-gateway-integration)
2. [Chargeback Management](#2-chargeback-management)
3. [Cross-Border Payment Issues](#3-cross-border-payment-issues)

---

## 1. Payment Gateway Integration

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
An e-commerce company is experiencing payment processing issues:

Business Profile:
- Online retailer selling electronics
- Average order value: $350
- Monthly transactions: 12,000
- Monthly volume: $4.2 million
- Operating in US, Canada, and UK

Current Problem:
- Payment success rate dropped from 94% to 78% over past week
- Customer complaints increased 300%
- Shopping cart abandonment up 45%

Transaction Failure Breakdown:
- "Declined - Insufficient Funds": 15% of failures
- "Declined - Do Not Honor": 35% of failures
- "Card Verification Failed": 25% of failures
- "Transaction Timeout": 20% of failures
- "Unknown Error": 5% of failures

Additional Details:
- Issue started after switching to new payment gateway
- Previous gateway: 2.9% + $0.30 per transaction
- New gateway: 2.5% + $0.25 per transaction (cost savings motivation)
- New gateway response time: 8-12 seconds (vs 2-3 seconds previously)
- 3D Secure authentication now required for all transactions
- Mobile app users most affected (65% failure rate)

Business Impact:
- Estimated lost revenue: $800,000/week
- Customer service calls up 500%
- Social media complaints increasing
- Some customers threatening to stop using the service

Questions:
1. What are the likely causes of the payment failures?
2. Which issues should be addressed first?
3. What immediate actions should be taken?
4. What testing should have been done before the switch?
5. How should the company communicate with customers?
6. What metrics should be monitored going forward?
```

### Expected Evaluation Points

1. **Root Cause Analysis**: Identifies timeout issues, 3D Secure friction, configuration problems
2. **Prioritization**: Focus on technical timeouts and mobile app issues first
3. **Immediate Actions**: Rollback consideration, parallel processing, gateway support escalation
4. **Prevention**: Proper testing protocols, gradual rollout, A/B testing
5. **Communication**: Proactive customer updates, clear error messages
6. **Monitoring**: Success rates, response times, error types, customer experience metrics

### Key Concepts Tested

- Payment gateway functionality
- Transaction processing troubleshooting
- Business impact analysis
- Change management
- Customer experience in payments

---

## 2. Chargeback Management

**Difficulty Level**: Advanced

**Estimated Response Time**: Detailed

### The Prompt

```
A subscription-based software company faces increasing chargebacks:

Company Details:
- SaaS product: $99/month subscription
- 8,000 active subscribers
- Monthly recurring revenue: $792,000
- Been in business 18 months

Chargeback Situation:
Current Month Chargebacks: 156
Previous Month: 89
Three Months Ago: 45
Chargeback Rate: 1.95% (industry average: 0.5-0.7%)

Chargeback Reason Codes:
- "Fraudulent Transaction" (10.4): 45 cases
- "Subscription Cancelled" (13.2): 38 cases
- "Product Not Received/Not As Described" (13.1): 28 cases
- "Credit Not Processed" (13.3): 25 cases
- "Duplicate Processing": 12 cases
- "Other": 8 cases

Investigation Reveals:
- 60% of "fraudulent" claims are from legitimate customers who forgot about subscription
- Cancellation process requires 3 steps and email confirmation
- No clear billing descriptor (shows as "TechSoft LLC" vs product name)
- Auto-renewal happens without advance notice to customers
- Refund requests take 7-10 business days to process
- Customer service response time: 48-72 hours
- No clear cancellation link in emails
- Free trial converts to paid automatically

Financial Impact:
- Chargeback fees: $25 per case = $3,900/month
- Lost revenue from chargebacks: $15,444/month
- Risk of payment processor termination (threshold: 1% rate)
- Stripe threatening to increase processing fees or terminate account

Questions:
1. Why is the chargeback rate so high?
2. What immediate changes are needed?
3. How should each chargeback category be addressed?
4. What policies should be updated?
5. How can the company reduce "friendly fraud"?
6. What documentation is needed to fight chargebacks?
7. What preventive measures should be implemented?
```

### Expected Evaluation Points

1. **Root Cause**: Poor customer experience, unclear billing, difficult cancellation
2. **Urgent Actions**: Improve billing descriptor, simplify cancellation, add renewal notifications
3. **Category-Specific**: Different approaches for fraud, cancellation, and refund issues
4. **Policy Changes**: Clear refund policy, proactive cancellation options, better communication
5. **Friendly Fraud**: Better receipts, pre-charge notifications, clear product naming
6. **Documentation**: Service logs, proof of delivery, clear ToS, communication records
7. **Prevention**: Better onboarding, clear billing cycle info, easy customer service access

### Key Concepts Tested

- Chargeback management
- Dispute resolution
- Customer experience optimization
- Subscription billing best practices
- Payment processor relationships
- Fraud prevention

---

## 3. Cross-Border Payment Issues

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
A freelance marketplace is expanding internationally and encountering payment challenges:

Platform Details:
- Connects clients with freelancers globally
- Processes payments in USD, EUR, GBP, CAD, AUD
- Takes 15% commission on transactions
- Pays out freelancers weekly

Current Problem Scenarios:

Scenario 1 - Currency Conversion:
- Client in US pays $1,000 for project
- Freelancer in India wants payment in INR
- Platform's bank charges 3.5% FX markup
- Freelancer receives ₹68,500 (expected ₹72,000)
- Freelancer complains about "hidden fees"

Scenario 2 - Payment Delays:
- European client pays on Monday
- Canadian freelancer should receive payment Friday
- Payment still not arrived the following Wednesday
- SWIFT transfer stuck in correspondent bank
- Freelancer has bills to pay and is upset

Scenario 3 - Compliance Issue:
- Large payment ($25,000) from UAE client to Pakistani freelancer
- Payment blocked by intermediary bank
- Request for additional documentation
- Client frustrated, freelancer concerned about being flagged
- Neither party understands what's needed

Scenario 4 - High Fees:
- Small payment: $150 project
- Wire transfer fee: $45
- FX conversion: $8
- Freelancer receives $97 (after fees and commission)
- Freelancer refuses to accept projects under $500

Platform Statistics:
- 40% of transactions are cross-border
- Average delay for international payments: 3-5 days
- Fee complaints increased 200% since international launch
- 15% of freelancers switched to competitors with better payment options

Questions:
1. What are the main issues with the current payment approach?
2. What alternatives should the platform consider?
3. How should FX fees be handled more transparently?
4. What compliance requirements need to be addressed?
5. How can payment speed be improved?
6. What communication improvements are needed?
```

### Expected Evaluation Points

1. **Problem Identification**: High fees, slow transfers, poor transparency, compliance gaps
2. **Alternative Solutions**: Payment aggregators, crypto, local bank accounts, Wise/Payoneer
3. **Transparency**: Clear fee disclosure, real-time FX rates, all-in pricing
4. **Compliance**: KYC/AML for high-value transfers, OFAC screening, documentation requirements
5. **Speed Improvements**: Real-time payment systems, local payment methods, blockchain options
6. **Communication**: Upfront fee calculator, payment status tracking, clear policies

### Key Concepts Tested

- International payment systems
- Foreign exchange management
- Cross-border compliance
- Payment infrastructure
- Fee structures and transparency
- Alternative payment methods

---

## Using These Prompts

Test AI understanding of:
- Payment technology and infrastructure
- Troubleshooting payment issues
- Compliance and regulatory aspects
- Customer experience in payments
- Business impact of payment problems
- Modern payment solutions
