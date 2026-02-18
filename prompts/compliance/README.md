# Compliance & Regulations Prompts

This directory contains prompts for testing AI's knowledge of financial regulations and compliance requirements.

## Prompts in this Category

1. [KYC/AML Compliance](#1-kycaml-compliance)
2. [Data Privacy Compliance](#2-data-privacy-compliance)
3. [Regulatory Reporting](#3-regulatory-reporting)

---

## 1. KYC/AML Compliance

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
A digital bank's compliance team is reviewing a new customer application:

Customer Information:
- Name: John Smith
- Age: 32
- Occupation: "Business Consultant"
- Stated Annual Income: $150,000
- Source of Funds: "Consulting fees from various international clients"

Initial Activity (First 30 Days):
- Opening deposit: $50,000 (wire from offshore account in Cayman Islands)
- Multiple wire transfers received: Total $200,000 from 15 different countries
- Multiple wire transfers sent: Total $180,000 to various recipients
- Cash deposits: $30,000 across multiple branches
- Account balance fluctuates between $5,000 and $80,000

Additional Red Flags:
- Customer provided minimal documentation about business
- Email domain is generic (@gmail.com), not business email
- Listed business address is a residential property
- Reluctant to provide client references
- Requests for documentation met with delays
- When questioned about transaction purposes: "business expenses" without detail

Current Situation:
- Customer is requesting to increase daily wire transfer limit from $10,000 to $50,000
- Just attempted a $75,000 wire transfer to an account in a high-risk jurisdiction

Questions:
1. What AML/KYC red flags are present?
2. What should the compliance team do immediately?
3. What additional information should be requested?
4. Should a Suspicious Activity Report (SAR) be filed?
5. What ongoing monitoring should be implemented?
```

### Expected Evaluation Points

1. **Red Flag Identification**: Lists multiple concerning indicators (offshore accounts, high velocity, vague business, etc.)
2. **Immediate Actions**: Block the $75,000 transfer, freeze account, escalate to compliance officer
3. **Information Needed**: Business registration, client contracts, source of funds documentation
4. **SAR Requirement**: Correctly identifies this meets SAR filing criteria
5. **Enhanced Due Diligence**: Recommends EDD process and ongoing monitoring

### Key Concepts Tested

- AML/KYC regulations
- Red flag recognition
- Suspicious activity reporting
- Enhanced due diligence
- Risk-based compliance

---

## 2. Data Privacy Compliance

**Difficulty Level**: Advanced

**Estimated Response Time**: Detailed

### The Prompt

```
A fintech company operates in multiple jurisdictions and faces the following data privacy scenario:

Company Profile:
- Mobile banking app available in US, UK, and EU
- 500,000 users globally
- Processes payments, stores financial data, and offers credit scoring
- Uses AI/ML for fraud detection and credit decisions

Data Handling:
- Customer data stored on cloud servers in US
- Third-party analytics tools integrated
- Marketing emails sent to all users
- Data shared with credit bureaus
- Customer service outsourced to offshore provider
- Mobile app collects device information and location data

Recent Incident:
- Customer in Germany requests complete data deletion (GDPR "Right to be Forgotten")
- Customer has an outstanding loan balance of €5,000
- Customer previously opted into marketing communications
- Customer's data has been shared with 3 credit bureaus
- Transaction history includes payments to other users
- Fraud detection system has flagged historical transactions

Complications:
- Legal requirement to retain certain financial records for 7 years
- Credit bureau contracts require data retention during active loan
- Other users' transaction records reference this customer
- Fraud investigation team needs historical data for ongoing case

Questions:
1. Can the company fully comply with the deletion request? Why or why not?
2. What data can be deleted immediately?
3. What data must be retained and under what legal basis?
4. What process should the company follow?
5. What policies should be updated to prevent similar issues?
6. Are there other compliance violations evident in the data handling practices?
```

### Expected Evaluation Points

1. **GDPR Understanding**: Recognizes right to erasure vs. legal retention requirements
2. **Data Categorization**: Distinguishes between deletable and non-deletable data
3. **Legal Basis**: Identifies legitimate grounds for retention (legal obligation, contract)
4. **Process**: Proper verification, documentation, and response timeline
5. **Broader Issues**: Identifies potential consent, transfer, and minimization issues
6. **Privacy by Design**: Recommendations for systemic improvements

### Key Concepts Tested

- GDPR compliance
- Data subject rights
- Legal basis for processing
- Cross-border data transfers
- Privacy by design
- Data retention policies

---

## 3. Regulatory Reporting

**Difficulty Level**: Intermediate

**Estimated Response Time**: Moderate

### The Prompt

```
A cryptocurrency exchange must file various regulatory reports:

Transaction Data (Q4 2023):
- Total trades executed: 1,250,000
- Total trading volume: $2.5 billion
- Number of active users: 85,000
- New account openings: 15,000
- Average transaction size: $2,000

Reportable Transactions Identified:
- 1,200 transactions over $10,000 (CTR threshold)
- 45 transactions with incomplete customer information
- 12 transactions flagged by AML system for unusual patterns
- 8 customers from OFAC sanctioned countries attempted transactions
- 3 transactions potentially linked to ransomware payments
- Customer complaints: 150 (mostly about delayed withdrawals)

Regulatory Requirements:
- Currency Transaction Reports (CTR) for transactions >$10,000
- Suspicious Activity Reports (SAR) when appropriate
- OFAC compliance reporting
- State money transmitter license renewals (in 45 states)
- FinCEN registration updates
- Customer complaint logs for regulatory examination

Issues:
- AML Officer position vacant for 2 months
- Some CTRs from previous quarter filed late
- Customer identification program has gaps
- 3 state licenses expired and awaiting renewal
- Board of Directors hasn't reviewed AML program in 18 months

What are the immediate compliance priorities and required actions?
```

### Expected Evaluation Points

1. **Reporting Requirements**: Identifies CTR, SAR, OFAC obligations
2. **Immediate Actions**: File overdue reports, address sanctioned country transactions, appoint interim AML officer
3. **Compliance Gaps**: Recognizes staffing, program review, licensing issues
4. **Risk Assessment**: Prioritizes high-risk items (OFAC, SARs, expired licenses)
5. **Remediation Plan**: Systematic approach to address all issues

### Key Concepts Tested

- Regulatory reporting obligations
- BSA/AML compliance
- OFAC sanctions compliance
- Licensing requirements
- Compliance program governance

---

## Using These Prompts

Test AI knowledge of:
- Specific regulations (GDPR, BSA/AML, etc.)
- Practical application of rules
- Risk-based decision making
- Compliance program elements
- Regulatory priorities
