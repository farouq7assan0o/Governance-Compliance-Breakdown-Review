# Governance & Compliance Breakdown Review (ISO 27014, PDPL, PCI DSS)**.

**Author:** Farouq Hassan
**Organization:** BazaarJo
**Frameworks Analyzed:**

* ISO/IEC 27014 (Information Security Governance)
* PDPL (Personal Data Protection Law)
* PCI DSS

---

# 1️⃣ Objective

Conduct a governance and compliance gap assessment following the BazaarJo data breach.

Focus areas:

* Leadership accountability
* Regulatory alignment
* Policy maturity
* Risk governance
* Vendor oversight
* Segregation of duties (SoD)

The goal was to:

* Identify governance failures
* Prioritize regulatory exposure
* Build a remediation roadmap
* Prepare an executive-level board briefing

📄 Source: 

---

# 2️⃣ Identified Governance & Compliance Gaps

The assessment identified seven major governance failures.

---

## 1. Lack of Segregation of Duties (SoD)

**Issue:**
Developers were able to deploy code without independent approval.

**Risk:**

* Malicious insider deployment
* Unreviewed production changes
* Increased likelihood of supply-chain compromise

**Framework Impact:**

* ISO 27014 governance failure
* PCI DSS change control violation

---

## 2. Undefined CISO Accountability

**Issue:**
Security leadership lacked clear reporting lines.

**Impact:**

* Delayed escalation
* Slow incident decision-making
* Governance confusion

**Framework Impact:**

* ISO 27014 role clarity violation

---

## 3. No Formal Breach Notification Policy

**Issue:**
No documented disclosure process aligned with PDPL.

**Risk:**

* Delayed reporting
* Regulatory penalties
* Legal liability

**Framework Impact:**

* PDPL violation risk
* PCI DSS incident response gaps

---

## 4. No Board-Level Risk Appetite

**Issue:**
Executive leadership did not define acceptable security risk.

**Impact:**

* Misaligned investments
* Inconsistent security decisions
* Lack of executive oversight

**Framework Impact:**

* ISO 27014 governance maturity gap

---

## 5. Weak Vendor Security Oversight

**Issue:**
Third-party vendors were not contractually bound to security standards.

**Risk:**

* Supply-chain compromise
* Shared responsibility failures
* Compliance cascade risk

**Framework Impact:**

* PCI DSS vendor compliance issue
* PDPL third-party data handling risk

---

## 6. Missing PDPL-Aligned Privacy Policy

**Issue:**
Customer data handling obligations were unclear.

**Impact:**

* Data protection non-compliance
* Regulatory exposure
* Customer trust erosion

---

## 7. No Periodic Policy Review Cycle

**Issue:**
Policies were outdated and not formally reviewed.

**Impact:**

* Controls not aligned to evolving threats
* Compliance drift
* Governance stagnation

---

# 3️⃣ Gap Prioritization (Impact vs Regulatory Risk)

Based on business and regulatory exposure:

| Gap                           | Business Impact | Regulatory Risk | Priority Window        |
| ----------------------------- | --------------- | --------------- | ---------------------- |
| SoD absence                   | High            | High            | Immediate (0–3 months) |
| No breach notification policy | High            | High            | Immediate (0–3 months) |
| Undefined CISO accountability | High            | Medium          | High (3–6 months)      |
| No board risk appetite        | Medium          | Medium          | High (3–6 months)      |
| Vendor oversight gaps         | Medium          | High            | Medium (6–9 months)    |
| Missing PDPL privacy policy   | Medium          | High            | Medium (6–9 months)    |
| No policy review cycle        | Low             | Medium          | Low (9–12 months)      |

📄 Source: 

---

# 4️⃣ Remediation Roadmap — Top 3 Critical Gaps

The top three priorities were selected based on combined operational and regulatory impact.

---

## Gap 1 — Enforce Segregation of Duties

**Owner:** Head of Engineering / CISO

### Milestones

1. Define SoD model (dev vs approval vs deployment)
2. Update CI/CD pipeline controls
3. Implement mandatory dual approval for production
4. Audit enforcement mechanisms

### Required Resources

* DevSecOps tooling enhancements
* 1 FTE security engineer

### KPI

```
100% of production deployments require dual approval
```

---

## Gap 2 — Establish Breach Notification Policy

**Owner:** Legal / Compliance

### Milestones

1. Draft PDPL-aligned notification policy
2. Obtain board approval
3. Conduct staff awareness training
4. Define regulator notification timeline

### Resources

* Legal advisory budget

### KPI

```
Breach notification executed within PDPL-mandated timeframe
```

---

## Gap 3 — Formalize CISO Accountability

**Owner:** CEO / Board

### Milestones

1. Update organizational chart
2. Define CISO authority & mandate
3. Establish reporting cadence
4. Quarterly security board briefings

### Resources

* Governance restructuring only

### KPI

```
Quarterly board-level security reporting established
```

📄 Source: 

---

# 5️⃣ Executive Board Brief — Governance Recovery Summary

The breach was driven primarily by governance and compliance failures, not just technical misconfiguration.

### Root Causes

* Absence of enforced SoD
* Unclear security leadership
* Missing breach notification process
* Lack of PDPL-aligned data protection governance

### Business Impact

* Delayed response
* Increased regulatory exposure
* Reputational damage
* Customer trust erosion

---

## Top Remediation Actions (Board-Level Summary)

1. Enforce segregation of duties in CI/CD
2. Approve formal breach notification policy
3. Formalize CISO authority & reporting structure

### Estimated Timeline

* 3–6 months implementation
* Moderate cost
* Primarily process redesign + limited tooling

---

## Strategic Recommendation

The Board should immediately endorse the remediation roadmap to:

* Demonstrate regulatory due diligence
* Reduce PDPL & PCI DSS exposure
* Align with ISO 27014 governance principles
* Restore stakeholder confidence

📄 Source: 

---

# 6️⃣ Governance Maturity Improvement Themes

| Governance Domain    | Improvement                       |
| -------------------- | --------------------------------- |
| Leadership           | Defined CISO mandate              |
| Risk Oversight       | Board risk appetite               |
| Change Management    | Enforced SoD                      |
| Regulatory Alignment | PDPL breach notification          |
| Vendor Governance    | Contractual security requirements |
| Policy Lifecycle     | Scheduled review cycle            |

---

# 7️⃣ Framework Alignment Summary

### ISO/IEC 27014

* Governance accountability clarified
* Board oversight formalized
* Security integrated into enterprise risk management

### PDPL

* Formal breach notification policy
* Privacy policy modernization
* Third-party data governance

### PCI DSS

* Change control improvement (SoD)
* Incident response formalization
* Vendor compliance strengthening

---

# 8️⃣ Skills Demonstrated

* Governance gap analysis
* Regulatory risk prioritization
* ISO 27014 mapping
* PDPL impact assessment
* PCI DSS alignment evaluation
* Executive-level reporting
* Roadmap creation
* KPI definition
* Risk-based prioritization
* Board communication drafting

---

# 🔐 Final Determination

BazaarJo’s breach was enabled by governance breakdown, not solely technical weakness.

By addressing:

* Segregation of duties
* Leadership accountability
* Formal breach notification

The organization can:

* Reduce regulatory exposure
* Improve incident response speed
* Align with global governance best practices
* Strengthen long-term cyber resilience

