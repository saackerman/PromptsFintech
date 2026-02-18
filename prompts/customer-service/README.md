# Customer Service Prompts

This directory contains prompts for testing AI's ability to handle customer service scenarios in financial services.

## Prompts in this Category

1. [Disputed Transaction](#1-disputed-transaction)
2. [Account Access Issues](#2-account-access-issues)
3. [Fee Complaint Resolution](#3-fee-complaint-resolution)

---

## 1. Disputed Transaction

**Difficulty Level**: Basic

**Estimated Response Time**: Quick

### The Prompt

```
You are a customer service representative for a digital bank. Handle this customer interaction:

Customer Message:
"I see a charge for $847.99 from 'AMZN MKTP US' on my credit card from yesterday, but I never made this purchase! I've never spent that much on Amazon. This is fraud! I want my money back immediately and I'm going to close my account if you don't fix this right now. This is ridiculous!"

Account Information:
- Customer: Sarah Johnson
- Account in good standing for 3 years
- No previous disputes
- Transaction date: Yesterday, 3:47 PM
- Merchant: Amazon Marketplace
- Amount: $847.99
- Transaction status: Posted

Additional Context:
- Customer has Amazon Prime linked to this card
- Customer made 15 Amazon purchases in past 3 months (avg $45 each)
- IP address for transaction matches customer's home address
- Same device used as previous Amazon purchases

How should you respond to this customer?
```

### Expected Evaluation Points

1. **Empathy**: Acknowledges customer's concern and frustration
2. **Investigation**: Asks clarifying questions before assuming fraud
3. **Information Gathering**: Suggests checking Amazon order history
4. **Process Explanation**: Explains dispute process if truly fraudulent
5. **Account Security**: Recommends security measures regardless
6. **Tone**: Professional, helpful, not accusatory

### Key Concepts Tested

- Customer service communication
- Dispute handling procedures
- Fraud vs. forgotten purchase investigation
- De-escalation techniques
- Security awareness

---

## 2. Account Access Issues

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
Customer calls with this situation:

Customer: "I can't access my account! I've been trying for 2 hours. I need to pay my rent TODAY and the payment is due in 3 hours. Your app keeps saying my password is wrong, but I know my password! I tried to reset it but I'm not getting the email. I'm going to be charged a late fee if I can't pay my landlord. This is YOUR fault!"

Account Research Shows:
- Customer: Michael Chen
- Account balance: $2,800
- Rent payment history: $1,500 monthly, always on 1st of month
- Today is the 1st
- Last successful login: 3 days ago
- Failed login attempts: 12 in past 2 hours (triggered security lock)
- Password reset email sent to: m***@yahoo.com
- Email on file: mchen2023@yahoo.com (verified 8 months ago)
- Phone number on file: (555) 123-4567
- Security questions: Set up 2 years ago

Additional Information:
- Customer claims he's calling from (555) 123-4567 (matches record)
- Landlord account for bill pay is set up and verified
- No fraud alerts on account
- Yahoo experiencing email delivery delays (per tech team alert)

The customer is very upset and stressed. How do you handle this?
```

### Expected Evaluation Points

1. **Empathy & Urgency**: Acknowledges stress and time sensitivity
2. **Security Balance**: Verifies identity while helping quickly
3. **Alternative Solutions**: Offers phone banking, temporary unlock, or manual payment processing
4. **Clear Communication**: Explains account lock reason and resolution steps
5. **Problem Solving**: Addresses both immediate need (rent payment) and longer-term (account access)
6. **Follow-up**: Ensures customer can prevent this in future

### Key Concepts Tested

- Crisis management in customer service
- Security vs. convenience balance
- Identity verification procedures
- Alternative service channels
- Problem-solving under pressure

---

## 3. Fee Complaint Resolution

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
Customer submits this complaint:

"I just noticed I was charged $150 in overdraft fees this month! This is highway robbery. I never opted into overdraft protection. I only overdrafted by $12 once, and you charged me $35. Then you charged me FOUR more times for the same thing! I want all these fees refunded. I've been a customer for 10 years and this is how you treat me?"

Account Analysis:
- Customer: Patricia Rodriguez
- Customer since: 2013 (10 years)
- Average monthly balance: $800
- Overdraft protection: Opted IN (checked at account opening, 2013)

Transaction History (This Month):
- Oct 1: Balance $245
- Oct 2: Debit $50 (Coffee shop) - Approved
- Oct 3: Debit $180 (Grocery) - Approved, balance now $15
- Oct 4: Debit $27 (Gas station) - OVERDRAFT, fee $35, balance now -$47
- Oct 5: Debit $22 (Restaurant) - OVERDRAFT, fee $35, balance now -$104
- Oct 6: Debit $18 (Pharmacy) - OVERDRAFT, fee $35, balance now -$157
- Oct 7: Debit $31 (Grocery) - OVERDRAFT, fee $35, balance now -$223
- Oct 8: Debit $15 (Streaming service) - OVERDRAFT, fee $35, balance now -$273
- Oct 10: Deposit $400 (paycheck), balance now $127

Policy Information:
- Overdraft fee: $35 per transaction
- Maximum 5 overdraft fees per day
- Fee waiver: Manager can waive up to 2 fees per year for good customers
- Customer's fee waiver history: 0 waivers used in past 12 months

Previous Account History:
- 2 overdrafts in past 10 years (both over 5 years ago)
- No previous fee complaints
- Generally responsible account management

How should you respond?
```

### Expected Evaluation Points

1. **Facts First**: Reviews actual transaction history with customer
2. **Education**: Explains overdraft protection vs. decline option
3. **Empathy**: Acknowledges frustration and long relationship
4. **Policy Application**: Explains fee structure clearly
5. **Goodwill Consideration**: Considers fee waiver based on account history
6. **Future Prevention**: Offers solutions (alerts, overdraft protection opt-out, balance monitoring)
7. **Fair Resolution**: Balances policy with customer retention

### Key Concepts Tested

- Fee policy explanation
- Customer retention strategies
- Complaint resolution
- Financial education
- Service recovery
- Regulatory compliance (opt-in requirements)

---

## Using These Prompts

Evaluate AI responses on:
- Professionalism and tone
- Problem-solving approach
- Policy knowledge
- Customer empathy
- Practical solutions
- Conflict resolution skills
