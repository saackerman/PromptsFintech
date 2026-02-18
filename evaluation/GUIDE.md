# Evaluation Guide for AI Responses

This guide helps you systematically evaluate and compare AI responses to fintech prompts.

## Evaluation Framework

### 1. Technical Accuracy (0-10 points)

**What to evaluate:**
- Correctness of financial calculations
- Proper use of industry terminology
- Accuracy of regulatory/compliance knowledge
- Sound financial principles

**Scoring:**
- 9-10: Completely accurate, no errors
- 7-8: Mostly accurate, minor errors that don't affect core advice
- 5-6: Some significant errors but general direction correct
- 3-4: Multiple errors, questionable advice
- 0-2: Fundamentally incorrect or dangerous advice

### 2. Completeness (0-10 points)

**What to evaluate:**
- Addresses all parts of the prompt
- Considers multiple perspectives
- Identifies both risks and opportunities
- Provides comprehensive analysis

**Scoring:**
- 9-10: Thoroughly addresses all aspects
- 7-8: Covers most points, minor gaps
- 5-6: Addresses main issues but misses important details
- 3-4: Incomplete, misses several key points
- 0-2: Superficial, misses most important aspects

### 3. Practical Applicability (0-10 points)

**What to evaluate:**
- Real-world feasibility of recommendations
- Actionable and specific advice
- Considers implementation challenges
- Balances ideal vs. practical solutions

**Scoring:**
- 9-10: Highly practical and immediately actionable
- 7-8: Mostly practical with minor impractical elements
- 5-6: Mix of practical and theoretical
- 3-4: Mostly theoretical, hard to implement
- 0-2: Impractical or unrealistic recommendations

### 4. Risk Awareness (0-10 points)

**What to evaluate:**
- Identifies potential risks and downsides
- Addresses compliance and regulatory concerns
- Considers ethical implications
- Acknowledges limitations and uncertainties

**Scoring:**
- 9-10: Comprehensive risk identification and mitigation
- 7-8: Identifies major risks, minor gaps
- 5-6: Identifies some risks but misses important ones
- 3-4: Minimal risk awareness
- 0-2: Ignores or downplays significant risks

### 5. Communication Quality (0-10 points)

**What to evaluate:**
- Clarity and organization
- Appropriate level of explanation
- Professional tone
- Proper use of examples

**Scoring:**
- 9-10: Exceptionally clear and well-organized
- 7-8: Clear and professional
- 5-6: Understandable but could be clearer
- 3-4: Confusing or poorly organized
- 0-2: Unclear or unprofessional

## Comparison Matrix Template

Use this template when comparing multiple AI systems:

```markdown
### Prompt: [Prompt Title]

| Criterion | AI #1 | AI #2 | AI #3 | Notes |
|-----------|-------|-------|-------|-------|
| Technical Accuracy | X/10 | X/10 | X/10 | |
| Completeness | X/10 | X/10 | X/10 | |
| Practical Applicability | X/10 | X/10 | X/10 | |
| Risk Awareness | X/10 | X/10 | X/10 | |
| Communication Quality | X/10 | X/10 | X/10 | |
| **Total** | **X/50** | **X/50** | **X/50** | |

#### Key Differences:
- [Notable difference 1]
- [Notable difference 2]

#### Best Response: [AI name]
**Reason:** [Brief explanation]

#### Areas Where Each AI Excelled:
- AI #1: [Strength]
- AI #2: [Strength]
- AI #3: [Strength]
```

## Category-Specific Evaluation Criteria

### Fraud Detection Prompts

Additional evaluation points:
- Speed of pattern recognition
- Ability to distinguish false positives
- Understanding of fraud typologies
- Knowledge of prevention tools
- Incident response quality

### Risk Assessment Prompts

Additional evaluation points:
- Risk quantification ability
- Balance of quantitative vs qualitative factors
- Industry-specific knowledge
- Scenario analysis depth
- Mitigation strategy quality

### Financial Analysis Prompts

Additional evaluation points:
- Calculation accuracy
- Ratio interpretation
- Trend analysis
- Comparative analysis (when applicable)
- Business context understanding

### Compliance Prompts

Additional evaluation points:
- Regulatory knowledge accuracy
- Understanding of enforcement priorities
- Documentation requirements
- Process recommendations
- Ethical considerations

### Customer Service Prompts

Additional evaluation points:
- Empathy and tone
- De-escalation techniques
- Policy vs customer balance
- Problem-solving approach
- Follow-up recommendations

### Investment Advice Prompts

Additional evaluation points:
- Tax efficiency awareness
- Time horizon considerations
- Risk-adjusted thinking
- Diversification principles
- Disclosure of limitations

### Payment Processing Prompts

Additional evaluation points:
- Technical infrastructure knowledge
- Payment flow understanding
- International payment expertise
- Fee structure knowledge
- Modern payment solutions awareness

### Credit Scoring Prompts

Additional evaluation points:
- Credit score factor knowledge
- Fair lending awareness
- Alternative data understanding
- Realistic timeline expectations
- Educational value for consumers

## Red Flags to Watch For

### Critical Issues (Automatic failing grade)
- Illegal or unethical recommendations
- Advice that violates regulations
- Recommendations that could cause financial harm
- Discriminatory suggestions
- Claiming certainty where none exists
- Providing specific investment picks without disclaimers

### Significant Concerns (Major point deductions)
- Math errors in calculations
- Misunderstanding core concepts
- Ignoring stated constraints in prompt
- Overly generic advice
- Missing critical risk factors
- Incomplete compliance considerations

### Minor Issues (Small point deductions)
- Typos or formatting issues
- Slightly imprecise terminology
- Over-explanation of basic concepts
- Missing minor details
- Slightly off calculations (if method is correct)

## Best Practices for Testing

1. **Consistency Testing**: Use the same prompt multiple times to check for consistency

2. **Follow-up Questions**: Test how AI handles clarifying questions or challenges

3. **Edge Cases**: Try variations with unusual or edge case scenarios

4. **Time Sensitivity**: Note if responses consider current market/regulatory environment

5. **Bias Testing**: Look for potential biases in credit, hiring, or risk decisions

6. **Hallucination Check**: Verify that AI doesn't cite non-existent regulations or data

## Sample Evaluation Report

```markdown
# AI Comparison Report: Fintech Prompts

**Test Date:** [Date]
**AI Systems Tested:** [List]
**Number of Prompts:** [Number]

## Overall Results

| AI System | Average Score | Strengths | Weaknesses |
|-----------|---------------|-----------|------------|
| AI #1 | X/50 | [List] | [List] |
| AI #2 | X/50 | [List] | [List] |
| AI #3 | X/50 | [List] | [List] |

## Category Performance

### Fraud Detection
[Results and analysis]

### Risk Assessment
[Results and analysis]

[Continue for each category...]

## Key Findings

1. [Finding 1]
2. [Finding 2]
3. [Finding 3]

## Recommendations

**Best Overall:** [AI name]
**Best for [specific use case]:** [AI name]
**Most Improved Needed:** [AI name in specific area]

## Detailed Results

[Include detailed scoring for each prompt]
```

## Continuous Improvement

- Keep detailed logs of all evaluations
- Track how AI systems improve over time
- Update prompts based on changing regulations
- Add new categories as fintech evolves
- Share findings with the community

Remember: The goal is not just to rank AIs, but to understand their strengths and limitations for different fintech applications.
