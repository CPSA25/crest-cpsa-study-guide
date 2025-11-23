# CREST CPSA Certification Study Guide

🎓 **A comprehensive, exam-aligned study guide for CREST CPSA certification candidates**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CPSA Aligned](https://img.shields.io/badge/CPSA%20Aligned-v2.5-blue)](https://www.crest-approved.org/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-Nov%202025-green)](https://github.com/yourusername/CPSA-Study-Guide)

---

## 📚 About This Guide

This repository contains a **professional-grade, comprehensive study guide** for the **CREST Practitioner Security Analyst (CPSA)** certification. Designed by a PhD researcher in cybersecurity at Newcastle University, this guide bridges the gap between academic knowledge and practical penetration testing frameworks.

### 🎯 What This Is

- ✅ **Exam-Aligned:** Covers CPSA Syllabus v2.5 in detail
- ✅ **Comprehensive:** 10+ chapters covering all major skills
- ✅ **Practical:** Real-world examples from UK financial services and healthcare contexts
- ✅ **Professional:** Written by active cybersecurity researchers
- ✅ **Open Source:** Free for educational use (MIT License)
- ✅ **Community-Driven:** Feedback and contributions welcome

### 🚀 What This Isn't

- ❌ Not a replacement for official CREST materials
- ❌ Not a guarantee of exam pass (but significantly improves preparation)
- ❌ Not an official CREST publication
- ❌ Not a substitute for hands-on penetration testing experience

---

# Chapter 2: Law and Compliance (A2)

## About This Chapter

**Exam Coverage**: 15-20% of CPSA exam  
**Skill ID**: A2 (Law and Compliance)  
**Difficulty Level**: Intermediate  
**Estimated Study Time**: 4-5 hours  
**Prerequisites**: Basic understanding of cybersecurity and IT infrastructure

---

## Overview

This chapter provides a comprehensive guide to the legal, regulatory, and compliance frameworks governing penetration testing in the UK. As a CREST CPSA candidate, understanding the "why" behind authorization, scoping, and Rules of Engagement is essential—these concepts account for **15-20% of your exam** and directly impact your career as an ethical security professional.

**Key Insight**: Penetration testing itself mimics criminal activity. Its legitimacy depends entirely on **clear, written authorization** and strict adherence to legal frameworks.

---

## Who Is This Chapter For?

- **CREST CPSA Candidates** preparing for the A2: Law and Compliance exam objective
- **Cybersecurity Practitioners** transitioning into penetration testing
- **Junior Penetration Testers** building their legal and compliance foundation
- **IT Professionals** moving from general IT security to authorized security testing
- **Security Assessment Teams** needing to understand UK legal constraints

---

## Learning Objectives

By the end of this chapter, you will be able to:

- ✅ **Understand** the core legal frameworks governing UK penetration testing, including the Computer Misuse Act 1990, Data Protection Act 2018/UK GDPR, Human Rights Act 1998, and Police and Justice Act 2006
- ✅ **Identify** the role and importance of authorization, scoping, and Rules of Engagement (ROE) in ensuring legally compliant security testing
- ✅ **Distinguish** between organizational documents (Acts, Regulations, Standards, Policies, Procedures) and explain how each shapes penetration testing activities
- ✅ **Recognize** how regulatory requirements (NIS Regulations, PCI DSS, DSS 9, CBEST) influence security testing obligations and reporting expectations
- ✅ **Apply** legal and compliance principles to real-world penetration testing scenarios commonly assessed in the CPSA exam
- ✅ **Evaluate** the risks of non-compliance and articulate how improper testing may lead to legal, operational, and reputational consequences

---

## Exam Objectives

| **Skill ID** | **Skill Name** | **Coverage** | **Depth** | **Exam %** |
|---|---|---|---|---|
| **A2** | Law and Compliance | ✅ FULL | Comprehensive | 15-20% |

---

## Key Concepts at a Glance

### The Legal Hierarchy

```
ACTS (Primary Legislation)
    ↓
REGULATIONS (Statutory Instruments)
    ↓
STANDARDS (Best Practice & Technical Requirements)
    ↓
POLICIES (Organizational Intent & Direction)
    ↓
PROCEDURES (Step-by-Step Operational Instructions)
    ↓
COMPLIANCE (Following all levels)
```

### The Four Mandated UK Acts

| **Act** | **Key Impact on Pentesting** | **Maximum Penalty** | **Exam Weight** |
|---|---|---|---|
| **Computer Misuse Act 1990** | Defines "unauthorized access" as criminal | 10 years imprisonment | 25% |
| **Human Rights Act 1998** | Protects privacy (Article 8) during testing | Civil/Administrative remedies | 20% |
| **Data Protection Act 2018** | Criminalizes data retention (Section 170) | Criminal prosecution | 25% |
| **Police & Justice Act 2006** | Introduces "recklessness" as aggravated offense (CMA Section 3) | 10 years imprisonment | 30% |

---

## Chapter Contents

### 1. **Understanding the Legal Hierarchy**
- What is the UK legal and compliance hierarchy?
- Acts (Primary Legislation)
- Regulations (Statutory Instruments)
- Standards (Best Practice & Technical Requirements)
- Policies (Organizational Intent)
- Procedures (Step-by-Step Operations)
- Compliance (Three Levels: Legal, Regulatory, Organizational)

### 2. **The Four UK Acts Governing Penetration Testing**
- **Computer Misuse Act 1990**
  - Section 1: Unauthorized access (basic offense)
  - Section 2: Unauthorized access with intent to commit further crime (aggravated)
  - Section 3: Unauthorized modification of computer material
  - Why ROE (Rules of Engagement) is your legal defense
  
- **Human Rights Act 1998**
  - Article 8: Right to privacy
  - Article 10: Freedom of expression
  - Practical implications for data handling
  
- **Data Protection Act 2018**
  - Relationship to UK GDPR
  - Section 170: Criminal liability for unauthorized data retention
  - Data minimization principles
  
- **Police and Justice Act 2006**
  - Introduction of "recklessness" as a criterion
  - CMA Section 3: Aggravated offenses
  - Impact on critical infrastructure testing

### 3. **Regulations & Sector-Specific Requirements**
- **Network and Information Systems (NIS) Regulations 2018**
  - Operators of Essential Services (OES)
  - £17 million penalty threshold
  
- **PCI DSS Requirement 11.3**
  - Annual penetration testing mandate
  - Cardholder Data Environment (CDE) scope
  
- **NHS Data Security Standard 9 (DSS 9)**
  - Healthcare penetration testing requirement
  - 14-day remediation timeline for critical vulnerabilities
  
- **CBEST Framework (Financial Services)**
  - CREST accreditation requirement
  - Bank of England/FCA alignment
  
- **Telecommunications Security Act 2021**
  - PECR regulations
  - OFCOM enforcement

### 4. **How Legal Requirements Shape Penetration Testing Decisions**
- **Scoping Impact**: How CMA defines testing boundaries
- **Authorization Impact**: ROE as your legal shield
- **Data Handling Impact**: DPA Section 170 constraints
- **Risk Management Impact**: Legal liability assessment

### 5. **Rules of Engagement (ROE): The Operational Legal Framework**
- What is an ROE?
- Mandatory ROE Components
  - Responsible signatories
  - In-scope vs. out-of-scope systems
  - Testing windows (dates, times, blackout periods)
  - Attack types (permitted/prohibited)
  - Credentials provision
  - Escalation contacts
  - Data handling & destruction protocols
  - Liability & indemnification

### 6. **Review Questions & Exam Practice**
- 10 scenario-based review questions
- Detailed answer keys with legal references
- Real-world exam-style questions covering all four acts
- Sector-specific scenarios (financial, healthcare, critical infrastructure)

---

## Study Tips

### For Understanding & Retention

1. **Connect Legal Concepts to Real Testing**
   - Don't memorize acts in isolation
   - Ask: "How does this law impact what I can do during a penetration test?"
   
2. **Master the Act Distinctions**
   - CMA 1990 = Authorization requirement
   - DPA 2018 = Data handling requirement
   - HRA 1998 = Privacy protection requirement
   - PJA 2006 = Recklessness avoidance requirement

3. **Understand ROE as Your Legal Defense**
   - ROE ≠ Contract
   - ROE = Criminal law defense + contractual agreement
   - Missing ROE = Criminal liability even with contract

4. **Focus on Sector Differences**
   - Financial (CBEST) = CREST accreditation required
   - Healthcare (DSS 9) = Annual testing + 14-day remediation
   - Critical Infrastructure (NIS) = OES classification + £17M penalties

### For Exam Preparation

- [ ] Read sections on the four acts (Computer Misuse, HRA, DPA, PJA)
- [ ] Study the legal hierarchy diagram (Figure 1)
- [ ] Review the 27 UK cybersecurity legislations (Figure 2)
- [ ] Complete all 10 review questions
- [ ] Focus on scenario-based questions (Q3, Q7, Q8, Q10)
- [ ] Memorize key terms: CMA, ROE, DPA S.170, PJA recklessness, OES, CDE, DSS 9
- [ ] Create flashcards for act penalties and key dates

---

## Common CPSA Exam Traps

### ⚠️ Trap 1: Authorization Under CMA vs. Contractual Agreement
❌ **Wrong**: "I have a contract, so I have CMA authorization"  
✅ **Correct**: "I have a signed ROE explicitly defining scope and legal immunity"

### ⚠️ Trap 2: Data Handling Under DPA 2018
❌ **Wrong**: "I can store customer data as proof of concept"  
✅ **Correct**: "I must use sanitized screenshots or record counts; destroy all PII post-engagement"

### ⚠️ Trap 3: Recklessness Under PJA 2006
❌ **Wrong**: "I only get prosecuted if I intentionally crash systems"  
✅ **Correct**: "I get prosecuted if I recklessly cause disruption without authorization"

### ⚠️ Trap 4: Sector-Specific Regulations
❌ **Wrong**: "PCI DSS Requirement 11.3 applies to all companies"  
✅ **Correct**: "PCI DSS applies only to organizations handling cardholder data"

---

## Quick Reference: Acts & Penalties

| **Act** | **Key Section** | **Offense** | **Maximum Penalty** |
|---|---|---|---|
| Computer Misuse Act 1990 | Section 1 | Unauthorized access | 2 years imprisonment |
| Computer Misuse Act 1990 | Section 2 | Unauthorized access + intent | 5 years imprisonment |
| Computer Misuse Act 1990 | Section 3 | Unauthorized modification | 10 years imprisonment |
| Police & Justice Act 2006 | CMA S.3 (amended) | Reckless impairment | 10 years imprisonment |
| Data Protection Act 2018 | Section 170 | Unauthorized data retention | Criminal prosecution + fine |
| Human Rights Act 1998 | Article 8 | Privacy violation | Civil remedies |

---

## Study Timeline Recommendation

### Week 1: Understanding the Hierarchy
- Day 1-2: Read legal hierarchy section & figures
- Day 3-4: Study Acts individually (CMA, HRA)
- Day 5: Study Acts (DPA, PJA)
- Day 6-7: Consolidate & create flashcards

### Week 2: Applying the Knowledge
- Day 8-9: Study regulations & sector-specific requirements
- Day 10-11: Work through scenario-based questions
- Day 12-13: Review weak areas & detailed answer explanations
- Day 14: Take timed practice quiz

### Week 3: Retention & Exam Prep
- Day 15-18: Revisit weak topics & scenarios
- Day 19-20: Explain each act to a colleague (teaching aids retention)
- Day 21: Final review & confidence check

**Total Estimated Time**: 15-20 hours of focused study

---

## Figures & Diagrams

**Figure 1**: Legal Instruments Hierarchy Pyramid  
*Shows the relationship between Acts, Regulations, Standards, Policies, and Procedures*

**Figure 2**: 27 UK Cybersecurity Legislations  
*Comprehensive visual reference of all major UK cybersecurity acts*

---

## Further Resources

### Official Sources
- **CREST CPSA Syllabus (v2.5)** — Official exam objectives and coverage
- **CREST Approved Body Guidance** — Best practices for authorized testing
- **UK Government Cyber Security Strategy** — National cybersecurity framework

### Legislation (Official UK Government Sites)
- Computer Misuse Act 1990: [legislation.gov.uk](https://www.legislation.gov.uk/ukpga/1990/18)
- Data Protection Act 2018: [legislation.gov.uk](https://www.legislation.gov.uk/ukpga/2018/12)
- Human Rights Act 1998: [legislation.gov.uk](https://www.legislation.gov.uk/ukpga/1998/42)
- Police and Justice Act 2006: [legislation.gov.uk](https://www.legislation.gov.uk/ukpga/2006/48)

### Standards & Frameworks
- **PCI Security Standards Council**: [pcisecuritystandards.org](https://www.pcisecuritystandards.org)
- **NIST Cybersecurity Framework**: [nist.gov](https://www.nist.gov/cyberframework)
- **OWASP**: [owasp.org](https://owasp.org)
- **NHS Data Security Standard**: [digital.nhs.uk](https://www.digital.nhs.uk)

### Related CPSA Chapters
- **Chapter 1**: Introduction & Assessment Foundations
- **Chapter 3**: Technical Assessment Foundations
- **Chapter 4**: Testing Methodologies & Scoping

---

## How to Use This Chapter

### For Self-Study
1. Read through each section sequentially
2. Study the diagrams and tables
3. Take notes on key concepts
4. Complete the review questions as you go
5. Check your answers against the detailed answer keys
6. Revisit sections where you scored below 80%

### For Group Study
1. Assign different acts to group members
2. Have each member explain their assigned act to the group
3. Work through scenario-based questions together
4. Discuss real-world pentesting situations and legal implications
5. Quiz each other on key terms and penalties

### For Instructors/Trainers
- Use the learning objectives to structure lessons
- Reference scenarios in live training sessions
- Ask learners to identify legal risks in given testing scenarios
- Use review questions as formative assessment

---

## Feedback & Community

### Found an Issue?
- **Typo or grammar error?** Open a GitHub Issue
- **Factual error?** Provide the official source and correction
- **Unclear explanation?** Suggest how it could be clearer
- **Missing content?** Recommend what should be added

### Want to Contribute?
- Fix typos or improve explanations
- Add new scenarios or examples
- Translate to other languages (e.g., Dari)
- Suggest sector-specific case studies

**See [CONTRIBUTING.md](../CONTRIBUTING.md) for guidelines on submitting issues and pull requests.**

---

## Disclaimer

This study guide is an **independent resource**, not officially endorsed by CREST. While content is aligned with the official CREST CPSA syllabus (v2.5) and verified against UK legislation, readers should:

- Verify all legal references against official UK Government sources
- Check current CREST CPSA syllabus for any updates
- Consult legal professionals for specific legal questions
- Cross-reference with official CREST guidance

---

## Version History

| **Version** | **Date** | **Changes** |
|---|---|---|
| 1.0 | November 2025 | Initial release: Complete A2 coverage with 10 review questions |

---

## Estimated Reading Time by Section

| **Section** | **Reading Time** | **Study Exercises** | **Total Time** |
|---|---|---|---|
| Legal Hierarchy Overview | 30 mins | 15 mins | 45 mins |
| Computer Misuse Act 1990 | 45 mins | 20 mins | 65 mins |
| Human Rights Act 1998 | 30 mins | 15 mins | 45 mins |
| Data Protection Act 2018 | 45 mins | 25 mins | 70 mins |
| Police & Justice Act 2006 | 35 mins | 20 mins | 55 mins |
| Regulations & Sector Requirements | 50 mins | 30 mins | 80 mins |
| How Laws Shape Testing | 40 mins | 25 mins | 65 mins |
| Review Questions & Answers | 60 mins | 60 mins | 120 mins |
| **TOTAL** | **~5.5 hours** | **~3.5 hours** | **~9 hours** |

*Note: Times vary based on prior knowledge and reading speed. Allocate 4-5 hours minimum for focused study.*

---

## Knowledge Checkpoint

**Before moving to the next chapter, ensure you can answer:**

1. What are the four UK Acts governing penetration testing? ✓
2. What is the difference between authorization under CMA and a contractual agreement? ✓
3. Why is a Rules of Engagement (ROE) document legally critical? ✓
4. How does the DPA Section 170 impact your post-test data handling? ✓
5. What makes testing aggressive scanning in a critical infrastructure environment risky under PJA 2006? ✓
6. Which sector requires CREST accreditation for penetration testers? ✓
7. What is the remediation timeline for critical vulnerabilities in NHS DSS 9? ✓
8. How do NIS Regulations define Operators of Essential Services (OES)? ✓

**If you can confidently answer all 8 questions, you're ready for the next chapter!**

---

## Contact & Support

**Questions about this chapter?**
- Open a GitHub Issue with your question
- Start a GitHub Discussion for broader topics
- Check existing issues—your question may already be answered

**Want to suggest improvements?**
- Submit a pull request with your suggestions
- Open an issue tagged with "enhancement"
- Engage respectfully with community feedback

---

**Last Updated**: November 23, 2025  
**Version**: 1.0 | **Status**: Complete & Publication-Ready  
**License**: Creative Commons Attribution 4.0 (CC-BY-4.0)

---

*Made with ❤️ for CREST CPSA candidates worldwide*

**[← Back to Main Repository](../README.md)** | **[Next: Chapter 3 - Technical Assessment Foundations →](#)**
