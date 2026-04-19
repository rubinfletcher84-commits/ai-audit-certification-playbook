# Mock Case Study: AI Audit of a Mid-Sized Enterprise

## Scenario
A mid-sized company has adopted several AI tools across the business:
- an internal HR assistant
- a customer support copilot
- a resume screening model
- a security alert triage assistant
- a marketing content generator

The organization has no central AI governance committee, inconsistent vendor reviews, and limited post-deployment monitoring.

## Audit objective
Assess the organization’s AI governance maturity and certification readiness using the AI Audit Checklist & Certification Playbook.

## Key observations
- AI tools are deployed across multiple business units
- No complete central AI inventory exists
- High-impact systems are in use, including HR-related decision support
- Vendor terms for some tools do not clearly restrict customer-data use
- Monitoring exists for system uptime but not for harmful outputs or model drift
- Human oversight is defined inconsistently

## Sample findings
### F-01: Incomplete AI inventory
The organization cannot produce a full list of AI systems in use across departments.

**Risk:** Untracked AI use creates blind spots in governance, risk review, and certification readiness.  
**Severity:** High

### F-02: Weak vendor data-use controls
One generative AI vendor contract does not clearly restrict data retention or model-improvement use.

**Risk:** Sensitive organizational or customer data may be used outside approved boundaries.  
**Severity:** High

### F-03: No formal post-launch harm review
The HR assistant has no documented ongoing review for harmful outputs, accuracy drift, or escalation failures.

**Risk:** High-impact AI decisions may be influenced by unmonitored outputs.  
**Severity:** Critical

### F-04: Governance reviews not performed on schedule
AI policy exists, but there is no evidence of regular governance review meetings.

**Risk:** Controls may exist on paper without real oversight.  
**Severity:** Medium

## Sample maturity assessment
- Governance and accountability: 2 / 5
- Inventory and classification: 1 / 5
- Risk and impact assessment: 2 / 5
- Data governance and privacy: 2 / 5
- Security and resilience: 3 / 5
- Human oversight: 2 / 5
- Monitoring and incident response: 1 / 5
- Vendor assurance: 2 / 5

## 30 / 60 / 90 day actions
### 0–30 days
- Name an accountable AI governance owner
- Freeze unapproved high-risk AI use cases
- Build a central AI inventory
- Issue interim AI acceptable-use guidance

### 31–60 days
- Perform risk and impact reviews for high-impact systems
- Update vendor contracts and data-use terms
- Define human oversight criteria
- Implement AI-related logging and monitoring

### 61–90 days
- Perform internal audit validation
- Hold management review
- Track corrective actions to closure
- Prepare certification-readiness documentation