# Chapter 1: Engagement Lifecycle & Penetration Testing Frameworks

> **For CREST CPSA Certification Study Guide**
> 
> A comprehensive guide to understanding penetration testing programs, business value, and CREST framework.

---

## Who Is This Chapter For?

This chapter is aimed at five main groups, each with different learning goals and time commitments:

### CREST CPSA Exam Candidates
Security professionals preparing for CPSA certification will need around **2-3 hours** to master this material. This chapter provides exam-focused coverage of Skills A1 (Engagement Lifecycle) and A3 (Scoping).

### IT and Security Professionals
System administrators and security analysts moving into penetration testing roles can complete this in a similar timeframe and can skip some basic sections if needed.

### Managers and CISOs
Those involved in planning PT programs or making investment decisions can use the executive overview, taking about **1-1.5 hours**.

### Executives and Compliance Stakeholders
Board members, risk managers, and compliance officers can get a high-level understanding in about **45 minutes to 1 hour**.

### Students and Career Changers
Those looking to switch careers into cybersecurity can go through the full content over **2-3 hours** for a complete learning experience.

---

## Learning Objectives

After completing Chapter 1, you can:

- Define and contextualize penetration testing
- Explain the CREST penetration testing programme framework
- Recognize legal and compliance considerations
- Understand stakeholder roles and communication
- Relate penetration testing to organizational risk management

---

## Exam Objectives (CPSA Syllabus v2.5)

| Skill ID | Skill Name | Coverage | Depth | Exam % |
|----------|-----------|----------|-------|--------|
| **A1** | Engagement Lifecycle | FULL | Comprehensive | 15-20% |
| **A3** | Scoping | FULL | Comprehensive | 5-10% |

**Total Chapter 1 Exam Coverage: 20-25%**

---

## What Penetration Testing Is

**Penetration Testing (PT)**, also known as *Pen Test*, can be defined as a form of security assessment in which assessors emulate real-world adversaries to identify and exploit vulnerabilities in applications, systems, or networks.

The necessity for penetration testing stems from fundamental requirements related to:
- Quantifying exposure
- Fulfilling legal and regulatory duties
- Independently verifying defensive capabilities

Penetration testing is considered a cybersecurity best practice that involves actively probing an IT environment to discover weaknesses before they can be exploited by real attackers.

The primary reasons organizations need penetration testing are:
1. **Risk identification** - Discover vulnerabilities before attackers do
2. **Regulatory compliance** - Meet mandatory testing requirements
3. **Security validation** - Prove defensive systems actually work

As a cybersecurity practitioner preparing for CREST CPSA certification, it is important to understand not only the penetration testing methodologies but also its contribution to business processes. 

**Key Insight:** Penetration testing delivers both **strategic business value** (by quantifying risk and demonstrating governance) and **technical value** (by validating defensive controls and exposing exploitability).

---

## Business Values of Penetration Testing

The business values of penetration testing extend beyond identifying technical weaknesses. It directly supports risk management, regulatory compliance, and strategic investment decisions that align with an organization's governance and resilience objectives.

### Business Risk Identification and Quantification

The core function of penetration testing is to actively seek out and demonstrate exploitability, thereby translating abstract security weaknesses into quantifiable business risks.

Penetration testing goes beyond simple scanning to actively analyze the system for potential vulnerabilities. It is a structured process designed to simulate real attacks to assess the risk associated with potential security breaches.

To quantify risks in IT infrastructures, networks, and business applications, testers conduct various tasks such as:
- Vulnerability scanning
- Adversary simulation
- Exploitation
- Impact assessment
- Risk identification

**Key Benefit:** The final report generated from a penetration test connects technical findings to business risk. It helps assess the probability of a security weakness being exposed or maliciously exploited to ensure that the resulting risk level is acceptable to the business.

The report typically includes a **Risk/Exposure section** that provides a **quantitative description of the risk discovered**, estimating the loss if the identified vulnerabilities were exploited.

### Compliance and Legal Necessity

Another major driver for penetration testing is the growing number of regulatory and compliance obligations requiring demonstrable assurance of security controls. Organizations in regulated sectors often perform testing primarily due to these requirements.

Penetration testing is required to demonstrate adherence to numerous national and international security standards:

| Standard | Requirement |
|----------|-------------|
| **PCI-DSS** | Requires periodic penetration testing, particularly for environments handling sensitive cardholder data |
| **GDPR** | Article 32 requires "regular testing" of security measures |
| **HIPAA** | Healthcare data protection requires security testing |
| **ISO 27001** | Information security management mandates testing |
| **NIST CSF** | Cybersecurity framework recommends regular assessment |

**UK Context:** For critical national infrastructures and financial services, the regulatory approach moves beyond checklist compliance toward testing real-world threats. For example, in the financial sector, frameworks such as **CBEST** promote intelligence-led assessments executed by CREST-accredited providers.

**Key Benefit:** Conducting regular PT demonstrates due diligence and reasonable precautions against compromise, which is valuable in limiting legal liability and helps organizations demonstrate they have taken reasonable precautions against compromise, important in the event of a security incident or court case.

### Return on Investment (ROI) and Cost Reduction

Penetration testing is not merely a compliance exercise—it is a financially justified practice that reduces long-term operational and remediation costs:

1. **Early Vulnerability Detection** - Identifying vulnerabilities earlier in the Software Development Life Cycle (SDLC), especially via white-box or code-assisted testing, significantly reduces remediation complexity and cost.

2. **Informed Spending** - PT data empowers CIOs and CISOs to perform cost-benefit analyses, calculate security ROI, and prioritize security spending based on verified risks.

3. **Operational Savings** - Effective PT reduces overall ICT operational costs, minimizes breach likelihood, and improves technical reliability, indirectly cutting costs such as downtime and support calls.

---

## Technical Value of Penetration Testing

From a technical standpoint, penetration testing provides independent, adversarial validation of a system's security posture. It simulates real-world attacks to verify control effectiveness and uncover vulnerabilities that automated tools alone cannot detect.

### Comprehensive Vulnerability Validation

PT goes beyond vulnerability scanning. It verifies exploitability and demonstrates real-world attack potential. While vulnerability scanners identify known weaknesses, PT confirms exploitability and impact, delivering more accurate and actionable results.

Penetration testers apply a blend of manual and automated methods to emulate various attack scenarios. Different testing styles such as **White Box**, **Black Box**, and **Grey Box** testing are employed to achieve full coverage.

**Key Insight:** Skilled testers can correlate findings and chain multiple weaknesses across applications, systems, or networks to demonstrate critical business impact—something automated tools often overlook.

### Validation of Defensive Controls and Security Posture

Penetration testing provides essential technical security assurance by independently validating that defensive controls are correctly implemented, configured, and operating effectively against actual threats.

**Three Key Achievements:**

1. **Effectiveness of Security Controls** - PT is an ethical attack simulation intended to demonstrate or validate the effectiveness of security controls in a particular environment.

2. **Integrated Testing** - Employing a mix of techniques ensures comprehensive security validation. For example, a White Box approach ensures the underlying source code is reviewed for sound practices, while Black Box confirms the software works correctly from the end-user's viewpoint against external attacks.

3. **Improving Measurement** - Regular testing provides an industry benchmark against which improvements in the technical security environment can be measured.

### Validation of Incident Response

For sophisticated organizations, testing extends beyond preventive controls to assessing the capability of internal defenders (often referred to as Blue Teams) to detect and prevent attacks.

**Red Team Exercises** provide:
- Balanced view of security performance
- Advanced attacker simulation
- Critical metrics such as **Time-To-Detect (TTD)** and **Time-To-Mitigate (TTM)**
- Proof of how well the security program is running

---

## 🎓 CPSA EXAM TIP #1

**Question:** In what way does penetration testing contribute to strategic business value, rather than just technical findings?

**Focus Area:** Penetration testing delivers strategic business value by **translating abstract security weaknesses into quantifiable business risks**. This enables:
- Risk quantification and visualization in business terms
- Informed decision-making on security investments
- Alignment of security spending with operational objectives

---

## Penetration Testing Programme: The CREST Framework

CREST stresses the importance of **structured testing governance** rather than just exploitation skills. Candidates need to understand how different stages in the framework fit into an ongoing security assurance process.

The penetration testing program promotes:
- Consistency
- Traceability
- Accountability

These are key principles of CREST's technical and ethical testing standards.

According to CREST's penetration testing guidance, the best approach combines **governance**, **process management**, and the technical standards of **PTES** and **NIST SP 800-115**.

### The Three-Phase Model

This guide presents **three main phases** of any penetration testing program:

1. **Preparation** - Establish scope and authorization
2. **Testing** - Execute active assessment
3. **Follow-Up** - Remediate and improve

Together, these phases create a systematic, legally authorized, technically solid, and risk-focused method for effective penetration testing.

---

## PHASE A: PREPARATION (Weeks 1-2)

### Overview

The preparation phase aligns with **PTES pre-engagement interactions** and the **CBEST initiation stage**. The preparation phase defines the strategic and governance foundations for penetration testing.

The client organization takes the lead here. This phase should answer three questions:
- **Why test?** - Business drivers
- **What test?** - Scope definition
- **Who test?** - Resource planning

### A1: Maintain Technical Security Assurance Framework

The main task in this step is to ensure that the organization follows a clear and approved framework to protect its most important information and systems.

This framework must include:
- Creating different environments for thorough testing (development, staging, live)
- Defining necessary security setup
- Offering ongoing security monitoring services (e.g., Security Operations Centre)
- Ensuring balanced range of technical security services

**Critical:** This technical security framework needs **formal review and approval from business and IT management**. It must also receive adequate support through budgets, trained staff, proper processes, tools, and technology.

### A2: Establish Penetration Testing Governance

The main task is to put in place a suitable governance structure, usually a joint management and technical team with authority to oversee and coordinate a consistent, company-wide penetration testing programme.

This governance structure is responsible for:
- Defining the program's scope (covering all major systems, focusing on critical assets)
- Defining methods for protecting sensitive information
- Defining repeatable penetration testing processes and methodologies
- Criteria for selecting suppliers
- General management assurance framework

**Critical:** The whole structure and the defined program must get **formal approval from senior business and IT management**. This approval gives the team necessary control and authority to improve overall security plans.

### A3: Evaluate Drivers for Conducting Penetration Tests

This step requires the organization to clearly define the context and purpose for conducting penetration testing as part of the larger technical assurance program.

Key factors include:
- Increasing need for compliance with regulatory or legal requirements
- Possible effects of serious cyber-attacks seen in similar organizations
- Introduction of new or significant changes to crucial operational processes or IT infrastructure
- Changes in the perceived threat landscape

The evaluation should also include findings from:
- Existing risk assessments
- Audits
- Lessons learned from previous penetration tests

**CREST Emphasis:** Penetration testing should focus on **risk**, rather than just meeting compliance. Grasping these drivers helps ensure that the test delivers business value.

### A4: Identify Target Environments

This step requires clearly defining the penetration testing scope, which identifies specific systems and components that need penetration testing.

The organization must carefully consider testing on:
- Important Business Services (IBSs)
- Critical web applications
- Key IT infrastructure (major data centre, corporate network)
- Specialized equipment (mobile devices, process control systems)
- Relevant system development lifecycles

**Key Factors:**
- Actual importance of the system (determined through criticality/business impact assessment)
- Adherence to specific regulatory and compliance requirements (PCI-DSS, etc.)
- Major changes in business or IT

### A5: Define Purpose of Penetration Tests

This step requires the organization to state the clear goals and expected benefits of the security assessments in its penetration testing program.

You must:
- Define the purpose of the tests
- Evaluate the potential advantages they will offer the organization
- Assess whether tests can effectively help meet security needs
- Consider any testing limitations or challenges

### A6: Produce Requirements Specifications

This step involves formally documenting all testing criteria in a dedicated specification document.

This formal document combines:
- Objectives
- Testing style
- Scope boundaries
- Deliverables
- Constraints
- Timeframes
- Legal authorization
- Evidence handling rules
- Reporting expectations
- Communication protocols

**Critical Requirement:** The document must state that testers will ensure the test is legal and will not violate data protection rules.

This documented requirement must be:
1. Created and reviewed by skilled technical experts and business management
2. Approved by senior management before testing begins

**Key Documents Created:**
- **Rules of Engagement (RoE)** - Legal authorization and scope
- **Statement of Work (SOW)** - Detailed engagement terms

Together, these documents define what will be tested and how the test will be carried out. They ensure the engagement proceeds in a controlled, authorized, and accountable way.

### A7: Select Suitable Suppliers

This step requires the organization to officially appoint suitable third-party suppliers (PTSPs) to conduct independent penetration testing of the target environment.

The procurement process must include:
- Clearly defined requirements
- Evaluation of benefits
- Set criteria for selecting suppliers

**Selection Criteria Should Ensure:**
- High-quality, cost-effective services
- Strong ethical reputation
- Skill through recognized professional accreditation

**Ideal:** Suppliers should be **CREST-accredited member organizations** with well-qualified technical testers.

**Critical:** Verify the supplier's ability to meet specific requirements and ensure all necessary legal contracts are in place, including confidentiality and non-disclosure clauses.

---

## 🎓 CPSA EXAM TIP #2

**Question:** What is the PRIMARY legal requirement for penetration testing authorization?

**Answer:** Written, signed **Rules of Engagement (RoE)** demonstrating CMA 1990 compliance.

**Why This Matters:** Shows understanding of legal framework beyond just memorizing Acts. Without RoE, testing is unauthorized access—a crime. With RoE, it's legitimate security testing.

---

## PHASE B: TESTING EXECUTION (Weeks 3-4)

### Overview

The PenTest team executes the engagement in accordance with agreed requirements, using structured management controls and ethical practices.

This phase should answer two main questions:
- **How exploit?** - Testing techniques
- **Where vulnerable?** - Vulnerability identification

### B1: Agree Testing Style and Type

This step requires identifying the exact method and technical expertise needed for the penetration test.

This involves defining:
- **Testing style** (affects information given to the penetration tester): Black Box, Grey Box, or White Box
- **Specific type** of testing: Critical web applications, IT infrastructure, mobile devices, or specialized equipment

**Best Practice:** Conducting the test in a live environment provides the best results. However, if disruptive or destructive testing is necessary, a very similar test environment should be agreed upon to prevent business impact while ensuring the test meets its goals.

### B2: Identify Testing Constraints

This step requires clearly identifying and acknowledging all limitations related to the planned penetration testing. This ensures that the engagement stays feasible, safe, and legal.

Constraints often come from three main areas:
1. **Operational and technical issues** that prevent testing certain parts of the business
2. **Legal restrictions** like the Computer Misuse Act
3. **Limits due to insufficient time and resources** for the continuous testing program

**Best Practice:** 
- Testing should mimic live conditions as closely as possible
- Schedule activities outside of normal business hours
- Explicitly leave out sensitive external parties (business partners, customers)

### B3: Produce Scope Statements

This step involves creating a clear, written statement that defines the parameters of the penetration test. All relevant parties must sign off on it before any activities begin.

This document should clearly outline:
- Target environment
- Necessary resources and liabilities
- Official authorization to carry out specific tasks
- Legal disclaimer
- Reporting needs (detailed technical report + executive summary)

### B4: Establish Management Assurance Framework

The main goal is to create a clear structure that governs all parts of the penetration test.

This framework is important because just defining scope and depending on the supplier without ongoing client oversight can cause issues if problems arise or results are not satisfactory.

The management assurance framework is responsible for:
- Implementing a process to oversee the testing
- Monitoring the supplier's performance against documented requirements
- Making sure proper corrective actions are taken during the engagement

### B5: Implement Management Control Processes

This step requires the use of effective risk, change, and problem management processes that apply to all parts of the penetration test.

To ensure safety and reduce risks:
- Maintain detailed planning
- Keep clear definition of scope
- Follow predefined escalation procedures

**Key Processes:**
- **Change Management** - Control changes to scope or adjustments in testing personnel
- **Problem Management** - Address issues like test failures, system problems caused by testing, or contract violations

### B6: Use Effective Testing Methodology

The CREST penetration testing guide and related frameworks like PTES state that penetration tests must be carried out using a clear, organized method.

This method should:
- Rely on proven practices
- Reference reliable, publicly available sources (e.g., Open-Source Security Testing Methodology)
- Detail specific evaluation criteria
- Use common language and scope for security evaluations
- Outline required steps for all stages of thorough penetration testing

The selected method ensures all tests proceed logically through defined phases:
- Planning
- Conducting research
- Identifying vulnerabilities
- Exploiting weaknesses
- Reporting findings
- Fixing issues

### B7: Conduct Sufficient Research and Planning

This step involves thorough research and planning, which is crucial for preparing the technical execution of the test.

**Two Main Outputs:**

1. **Detailed Planning** - Clear, agreed-upon test plans that outline exactly what activities will take place. Must be flexible enough to handle priority changes and receive approval from all relevant parties before testing begins.

2. **Thorough Research** - Extensive research aimed at mimicking the reconnaissance activities a potential attacker would perform:
   - Collecting, organizing, and reviewing data from public sources and threat intelligence
   - Conducting reconnaissance to confirm system configurations
   - Performing network scanning to identify possible points of access

### B8: Identify and Exploit Vulnerabilities

This step requires penetration testers to systematically identify a range of possible vulnerabilities in the target system, then try to exploit these weaknesses in a controlled and precise way.

This careful process involves:
- Examining technical system, network, and application vulnerabilities
- Using mix of automated scanning methods and thorough manual testing
- Ethically exploiting weaknesses to gain unauthorized access

**Key Focus:**
- Not just confirming presence of vulnerabilities (OWASP Top Ten)
- But ethically exploiting weaknesses using exploitation frameworks or customized methods
- Showing **post-exploitation capabilities** (escalation, lateral movement)

This approach fully demonstrates the true business risk and impact of the vulnerability across the environment.

### B9: Report Key Findings

This step requires that the main findings from the penetration test be formally presented to the organization by the suppliers.

The report must provide:
- Detailed information about discovered vulnerabilities
- Possible effects
- Level of risk to the business
- Needed remediation advice

**Key Elements:**
- Agreed format within a formal report
- Suitable for both technical audiences and senior management
- Narrative explaining the testing process
- Solid test evidence (tool results, screenshots of successful exploits)
- Specific details about technical risks and mitigation advice
- Remediation activities and root causes
- Sharing with all stakeholders
- Debriefing sessions to ensure appropriate action

---

## PHASE C: FOLLOW-UP & CLOSURE (Weeks 5-8)

### Overview

The follow-up phase ensures accountability, validates remediation efforts, and fosters continuous security improvement following testing completion.

This phase should answer three main questions:
- **What fix?** - Remediation planning
- **Did it work?** - Validation and retesting
- **What's next?** - Continuous improvement

### C1: Remediate Weaknesses

This step is a crucial follow-up activity that involves implementing a formal remediation process to reduce the risk of vulnerabilities found during testing from being exploited again.

Key actions include:
- Applying immediate or short-term solutions (patching systems, closing ports, blocking traffic)
- Using technical data to replicate the penetration test results
- Setting priorities based on risk ratings, especially for critical assets
- Leading to longer-term solutions (updated patch management strategies)
- Reporting weaknesses to relevant third-party organizations (CERTs, BUGTRAQ)
- Formal agreement for conducting short-term retesting to confirm fixes work

### C2: Address Root Causes of Weaknesses

This step enforces thorough examination of the security weaknesses found during the penetration test. The goal is to address the core problems instead of just treating the symptoms of the attack.

This process is essential for improving security long-term. It involves:
- Finding the true root causes of vulnerabilities
- Assessing how these issues could affect the business
- Requiring skilled and experienced security professionals to outline needed corrective actions
- Focusing on broader issues (updating entire patch management system) rather than just resolving specific problems (applying one missing patch)

**Key Principle:** Address systemic problems, not just tactical symptoms.

### C3: Initiate Improvement Programme

This step requires the formal launch of a structured improvement program right after completing penetration tests.

This important initiative aims to:
- Ensure ongoing security improvements
- Turn tactical findings into strategic, organization-wide actions
- Address root causes of security weaknesses
- Carefully evaluate overall effectiveness of the penetration testing
- Identify and include lessons learned
- Ensure good security practices are consistently applied organization-wide
- Create and monitor action plans
- Agree on necessary approaches for future testing exercises

### C4: Evaluate Penetration Testing Effectiveness

This step mandates the organization to carry out careful evaluation of whether the security assessment activities met the intended goals and provided value for money.

This evaluation involves:
- Confirming if original testing objectives were met
- Checking if enough weaknesses were found within reasonable timeframe
- Reviewing exploitations carried out (usually on sample basis)
- Comparing overall test results to established industry standards

**Optional Tool:** CREST penetration testing maturity assessment suite to evaluate effectiveness and maturity (Level 1 least effective to Level 5 most effective).

### C5: Build on Lessons Learned

This step is crucial to the follow-up phase. It requires the organization to identify, record, analyze, and act on all lessons learned from the penetration testing process.

The main goal is to ensure that **best practices and fixes discovered during testing are applied consistently and effectively across other environments** in the organization.

This approach aims to address root causes throughout the system and includes:
- Improving future testing plans
- Giving constructive feedback to service providers
- Evaluating long-term effectiveness of past remediation efforts
- Supporting development of thorough, integrated security program

### C6: Create and Monitor Action Plans

This step necessitates the formal creation and careful oversight of detailed action plans right after completing the follow-up activities.

These plans must:
- Outline all actions to prevent recurrence of identified vulnerabilities
- Improve the overall information security program
- Be documented, created by qualified technical experts
- Be reviewed by business management
- Be approved by senior management
- Include details: priorities, categories, responsible individuals, target completion dates
- Proceed effectively within set timeframes with regular monitoring
- Track progress and reassess risk level

---

## 🎓 CPSA EXAM TIP #3

**Question:** What is the primary objective of addressing root causes (C2) during the Follow-Up Phase?

**Focus Area:** The goal is to address the **core problems instead of just treating the symptoms** of the attack. This leads to long-term security improvement and prevents recurrence of similar vulnerabilities.

---

## Scoping: The Essential Foundation

Scoping is the essential foundation of any successful penetration testing program. It mainly falls within the **Preparation (A)** and **Testing (B)** phases of the CREST framework.

Scoping involves:
- Clearly defining boundaries
- Defining objectives
- Defining legal limits of the security assessment
- Specifying what will be tested
- Defining how testing will be conducted (Rules of Engagement)
- Detailing necessary resources and deliverables

**Key Documents:** The formal Scope Statement (B3) and Rules of Engagement (RoE) must be signed off by all involved parties to provide legal authorization for tests to begin.

### Why Scoping Matters

The need for scoping arises from:

1. **Legal Requirements** - Ensures test is legal and complies with data protection standards
2. **Risk Management** - Reduces risk of scope creep, system disruption, or legal issues
3. **Value Assurance** - Keeps exercise focused and goal-oriented

By outlining the depth and breadth of the test beforehand, the organization can:
- Avoid unintended damage to critical, sensitive, or delicate systems (e.g., legacy equipment)
- Avoid systems linked to external partners
- Keep the exercise focused on achieving specific business objectives
- Identify risks that could negatively affect the organization's mission

**For Regulated Environments:** Proper scoping ensures all necessary controls (e.g., segmentation, CDE perimeter access points) are explicitly tested.

### Understanding Client Requirements

Understanding client requirements is the groundwork for preparation, particularly covered in Step A6 (Produce requirements specifications).

This stage sets the purpose and scale of the testing based on systematic assessment of various factors:
- **Mandatory compliance** - ISO 27001, PCI-DSS, NIS Regulations
- **Business impact** - Repercussions of serious cyber incidents on similar organizations
- **Infrastructure changes** - Significant changes to business applications or IT infrastructure

**Key Point:** Requirements must take into account the impact on:
- Important business applications
- Key IT structures
- Confidential data

Criticality and impact assessments drive this process, ensuring that testing resources concentrate on high-risk assets.

**Documentation:** These requirements must be:
1. Formally documented
2. Collaboratively developed
3. Reviewed by qualified technical experts and business management
4. Receive senior management sign-off to confirm corporate commitment

### Accurate Timescale Scoping

Accurate timescale scoping is vital for:
- Managing client expectations
- Ensuring profitability
- Avoiding scope creep

Time estimates are often linked to:
- The tester's experience in that specific area
- The technical complexity defined in the scope

**Best Practice:** Add **15-20% padding/consultant overhead** to the initial time estimate to accommodate:
- Unavoidable interruptions
- Logistical issues
- Unexpected complexities that arise during the test

**Critical:** The scope must clearly state:
- Definite start and end dates
- Manage client expectations
- Tie deliverables to payment terms
- Especially important for retesting efforts (common area for scope creep)

### Resource Planning

Resource planning is closely connected to scoping and determines the needed human and technological capabilities.

The scope documentation (B3) must outline:
- Roles, skills, experience, and qualifications of testers
- Necessary expertise (CREST certification, etc.)

**Verification:** Confirmed during formal supplier selection process (A7).

**Additional Planning:**
- **Logistical details** - Days needed, testing location (on-site or remote)
- **Client facilities** - Private secure room, technical access
- **Technical tools** - Automated scanners, Burp Suite, Metasploit
- **Tool policies** - All parties follow usage policies and legal restrictions

---

## 🎓 CPSA EXAM TIP #4

**Question:** How does Scoping relate to the earlier Preparation phases in the CREST framework?

**Focus Area:** Remember that **Scoping (B3)** is the formal documented output of the earlier thinking stages **(A3, A4, A5, A6, B1, B2)**.

Understanding this relationship is crucial for exam success. Scoping is not a standalone activity—it's the formalization of all the preparation decisions made in Phase A.

---

## Testing Styles: Black Box vs. Grey Box vs. White Box

### Overview

Penetration testing comes in three flavors based on the **knowledge level and starting position** of the tester:

| Testing Style | Knowledge Level | Simulates | Timeline |
|---|---|---|---|
| **Black Box** | Zero knowledge | External attacker | Longest (reconnaissance-heavy) |
| **Grey Box** | Limited knowledge | Compromised insider | Balanced |
| **White Box** | Full knowledge | Developer/architect | Shortest (most efficient) |

---

### Black Box Testing: The Realistic Approach

**What tester receives:**
- Public company name
- Public website(s)
- General industry knowledge

**What tester does NOT receive:**
- Network diagrams
- System inventory
- Credentials
- Source code
- Documentation

**Typical Timeline:**

```
Week 1-2: Reconnaissance (30% of time)
├─ OSINT (public records, social media, Google)
├─ DNS enumeration
├─ Network scanning
└─ Port discovery

Week 3-4: Vulnerability identification (40% of time)
├─ Service enumeration
├─ Version discovery
├─ Known vulnerability checks
└─ Custom vulnerability testing

Week 4-6: Exploitation (30% of time)
├─ Confirm vulnerabilities exploitable
├─ Demonstrate impact
└─ Post-exploitation
```

**Why Black Box takes longest:** Tester must discover everything. No shortcuts. Very realistic.

**When to use Black Box:**
- ✅ First security test (organization doesn't know their posture)
- ✅ You want most realistic assessment
- ✅ You want external security validation
- ✅ You want to test incident detection systems

**When NOT to use Black Box:**
- ❌ You have limited budget for extensive reconnaissance
- ❌ You want specific internal vulnerability testing
- ❌ You want rapid results

---

### Grey Box Testing: The Balanced Approach

**What tester receives:**
- Employee credentials (low-privilege user)
- Basic network documentation
- Some system information
- Maybe list of internal servers

**What tester does NOT receive:**
- Administrative access
- Source code
- Complete architecture

**What tester simulates:**
- Compromised employee
- Insider with limited privileges
- Disgruntled staff member
- Lateral movement threat

**Typical Timeline:**

```
Day 1-2: Access validation (10% of time)
└─ Confirm low-privilege credentials work
└─ Map internal network from insider perspective

Week 1-2: Privilege escalation (50% of time)
├─ Find ways to escalate from user to admin
├─ Test network segmentation
├─ Discover internal vulnerabilities
└─ Find local privilege escalation vectors

Week 3-4: Lateral movement & impact (40% of time)
├─ Move from initial system to targets
├─ Access restricted resources
├─ Demonstrate business impact
└─ Show data theft potential
```

**Why Grey Box is most commonly used:**
- ✅ Cost-effective
- ✅ Efficient
- ✅ Realistic threat simulation
- ✅ Tests both external AND insider scenarios

**When to use Grey Box:**
- ✅ Testing insider threat scenarios
- ✅ Testing network segmentation
- ✅ Testing privilege escalation
- ✅ Testing lateral movement
- ✅ Budget is moderate
- ✅ You want practical, balanced assessment

**When NOT to use Grey Box:**
- ❌ You want only external security validation
- ❌ You want only code review
- ❌ You want comprehensive organizational security (use both Grey and White)

---

### White Box Testing: The Thorough Approach

**What tester receives:**
- Complete source code
- Network diagrams
- System architecture
- Database schema
- Admin credentials
- Security control documentation
- Configuration files

**What tester simulates:**
- Developer reviewing code
- Architect knowing all systems
- Insider with full access

**Typical Timeline:**

```
Week 1: Code review (40% of time)
├─ Static code analysis
├─ Architecture review
├─ Design flaw identification
└─ Logic issue discovery

Week 2: Manual verification (30% of time)
├─ Confirm code review findings
├─ Test discovered vulnerabilities
└─ Verify security controls

Week 3: Advanced exploitation (30% of time)
├─ Exploit design flaws
├─ Bypass security mechanisms
└─ Demonstrate business impact
```

**Why White Box is most efficient (time-wise):** Full knowledge means no reconnaissance needed. Testers focus immediately on vulnerabilities.

**When to use White Box:**
- ✅ Application security before deployment
- ✅ Identifying design flaws
- ✅ Code review and logic testing
- ✅ Finding complex vulnerabilities
- ✅ Time constraints
- ✅ Most comprehensive technical assessment

**When NOT to use White Box:**
- ❌ You want to validate external security (attackers don't have source code)
- ❌ You want to test incident detection
- ❌ You want realistic threat simulation

---

### Choosing the Right Style: Decision Framework

**Question 1: What's the primary objective?**
- External security posture? → **BLACK BOX**
- Insider threat simulation? → **GREY BOX**
- Code review before deployment? → **WHITE BOX**
- Combination? → **Consider multiple styles**

**Question 2: How much budget and time?**
- Limited budget, quick results? → **GREY BOX**
- Comprehensive assessment? → **BLACK BOX (time)** or **WHITE BOX (code focus)**
- Balanced? → **GREY BOX (most cost-effective)**

**Question 3: What's being tested?**
- External website/API → **BLACK BOX**
- Internal network → **GREY BOX**
- Application before deployment → **WHITE BOX**
- Entire organization → **Multiple styles**

### Real-World Combinations

**Financial services:**
- BLACK BOX + GREY BOX
- Test external threat AND insider threat

**Software company:**
- WHITE BOX (code review) + BLACK BOX (deployed app)

**Healthcare:**
- BLACK BOX + GREY BOX
- Test external threat AND insider accessing patient data

**Retail:**
- GREY BOX only
- Focus on insider threat to payment systems

---

## 🎓 CPSA EXAM TIP #5

**Question:** You must be able to distinguish the three testing styles (Black Box, Grey Box, White Box) based on the information provided to the tester, as this affects time, cost, and the type of simulation (external vs. insider threat).

**Focus Area:** 
- **Black Box** = Most realistic external threat simulation, most time-consuming
- **Grey Box** = Most commonly used, balanced cost/realism, insider threat focus
- **White Box** = Most thorough code review, most efficient timeline

Clearly identifying constraints (B2) is vital for managing real-world risk during the assessment phase.

---

## Project Closure and Debrief

The closure and debrief of a penetration testing project are the most crucial deliverables from the penetration testing team to the management team, serving as the bridge between technical findings and strategic business action.

The penetration testing report serves as the official record of the engagement, capturing the entire process from scoping to exploitation, and must provide maximum value to the customer.

> **Note:** We will discuss more about reporting in Chapter 3 (Reporting & Documentation)

---

## Common Mistakes

### The Legal Mistake

**Mistake:** Commencing any assessment activity, including reconnaissance or scanning, without securing the necessary legal authorization.

**Consequence:** The tester risks violating the Computer Misuse Act (CMA) 1990. This failure in governance can lead to legal liability for the organization and the testing team. Furthermore, without authorization, the entire engagement lacks the legally controlled, accountable way required by the CREST framework.

**How to Avoid:**
1. Obtain **Written, Signed Rules of Engagement (RoE)** and a **Statement of Work (SOW)**
2. RoE must be signed by a person with legal authority (Director/C-level)
3. Clearly define the specific scope (IP ranges, domains, dates, times)
4. List exclusions (systems NOT permitted for testing)
5. This formal documentation provides the legal basis and authorization for tests to begin

---

### The Scoping Mistake

**Mistake:** Failing to define clear boundaries or testing systems that fall outside the agreed-upon scope (scope creep) or neglecting to account for known system vulnerabilities or constraints.

**Consequence:** This increases the risk of system disruption or unintended damage to critical, sensitive, or delicate systems (e.g., legacy equipment). It can also lead to legal issues for both client and tester. If constraints are ignored, the engagement may not be feasible, safe, or legal.

**How to Avoid:**
1. Identify and acknowledge all limitations (B2) related to:
   - Technical issues
   - Operational constraints
   - Legal restrictions (e.g., CMA)
2. Produce a formal **Scope Statement (B3)** that clearly outlines:
   - Target environment
   - Resources and liabilities
   - Official authorization
3. Ensure it is **signed off by all relevant parties** before activities begin

---

### The Methodology Mistake

**Mistake:** Conducting the test without a clear, organized methodology (B6) or failing to perform sufficient research and planning (B7) prior to execution.

**Consequence:** Testing lacks consistency, traceability, and accountability. It may fail to progress logically through defined phases, potentially missing critical business impact by failing to correlate findings or chain multiple weaknesses across systems.

**How to Avoid:**
1. Use a clear, organized method relying on proven practices
2. Reference reliable, publicly available sources such as **PTES** and **NIST SP 800-115**
3. Conduct thorough research and planning (B7) aimed at mimicking reconnaissance activities a potential attacker would perform
4. Gather information about the target environment and its setup

---

### The Reporting Mistake

**Mistake:** Delivering a final report that only focuses on technical findings (e.g., SQL injection confirmed) without translating those results into quantifiable business risks.

**Consequence:** The report fails to provide strategic business value. Senior decision-makers (CIOs/CISOs) cannot make informed strategic investment decisions or align security spending with operational objectives because the abstract security weakness is not linked to potential loss or business exposure.

**How to Avoid:**
1. Ensure the final report (B9) **connects technical findings to business risk**
2. Include a **Risk/Exposure section** that provides:
   - Quantitative description of the risk discovered
   - Estimation of potential loss if vulnerabilities were exploited
3. Make the report suitable for:
   - Technical audiences (technical terminology)
   - Senior management (plain language explanations)

---

### The Follow-Up Mistake

**Mistake:** Focusing solely on applying immediate, short-term remediation fixes (C1), such as patching one system, without performing thorough examination (C2) of the underlying root causes.

**Consequence:** The organization fails to achieve long-term security improvement. Tactical findings do not evolve into strategic, organization-wide actions. This leads to recurrence of identified vulnerabilities—the same types of problems will surface in future tests.

**How to Avoid:**
1. Enforce thorough examination of security weaknesses found (C2)
2. Address the **core problems** instead of just treating symptoms
3. Corrective actions must focus on broader issues:
   - Updating entire patch management system (not just one patch)
   - Changing development processes
   - Implementing training programs
4. This requires skilled professionals to outline future improvement plans
5. Ensure the formal **Improvement Programme (C3)** is launched

---

## Legal Compliance Checklist

### Before Any Penetration Test

#### 1. AUTHORIZATION
- [ ] Written Rules of Engagement (RoE) obtained
- [ ] RoE signed by a person with legal authority (Director/C-level)
- [ ] RoE defines the specific scope (IP ranges, domains, dates, times)
- [ ] RoE lists exclusions (systems NOT permitted for testing)
- [ ] RoE is dated and stored securely (recommended 3-year retention)

#### 2. THIRD-PARTY VERIFICATION
- [ ] Confirm ownership of all IP addresses, systems, and assets in scope
- [ ] If cloud/ISP-hosted systems are included: explicit written permission obtained
- [ ] For NHS or Critical National Infrastructure: appropriate regulator consulted

#### 3. SCOPE DEFINITION
- [ ] Formal Scope Statement (B3) produced and signed off
- [ ] Testing constraints (B2) identified and documented
- [ ] Testing windows (dates/times) agreed and documented
- [ ] Emergency contact procedures defined

#### 4. DATA HANDLING
- [ ] Data protection impact assessment completed (if handling sensitive data)
- [ ] Evidence collection procedures agreed (what CAN be captured)
- [ ] Secure evidence destruction process defined
- [ ] GDPR/DPA compliance confirmed

#### 5. INSURANCE & LIABILITY
- [ ] PTSP professional liability insurance confirmed
- [ ] Coverage adequate for scope and risk
- [ ] Liability terms documented in contract
- [ ] Dispute resolution process defined

---

## Quick Reference: CREST PT Programme

| Phase | Duration | Primary Purpose | Key Deliverable | Gateway Question |
|-------|----------|---|---|---|
| **A: Preparation** | 1-2 weeks | Define WHY, WHAT, WHO | Signed RoE, Scope Spec | "Requirements approved?" |
| **B: Testing** | 2-6 weeks | Execute HOW, WHERE | Draft PT Report, Evidence | "Critical findings escalated?" |
| **C: Follow-Up** | 2-8 weeks | Fix, Validate, Improve | Remediation Plan, Closure | "Root causes addressed?" |

### Phase A Steps (A1-A7)

1. **A1:** Maintain Technical Security Framework
2. **A2:** Establish PT Governance
3. **A3:** Evaluate Testing Drivers
4. **A4:** Identify Target Environments
5. **A5:** Define Purpose
6. **A6:** Produce Requirements Specification
7. **A7:** Select Suitable Suppliers

### Phase B Steps (B1-B9)

1. **B1:** Agree Testing Style/Type
2. **B2:** Identify Testing Constraints
3. **B3:** Produce Scope Statements
4. **B4:** Establish Management Assurance
5. **B5:** Implement Management Control Processes
6. **B6:** Use Effective Testing Methodology
7. **B7:** Conduct Research & Planning
8. **B8:** Identify and Exploit Vulnerabilities
9. **B9:** Report Key Findings

### Phase C Steps (C1-C6)

1. **C1:** Remediate Weaknesses
2. **C2:** Address Root Causes
3. **C3:** Initiate Improvement Programme
4. **C4:** Evaluate PT Effectiveness
5. **C5:** Build on Lessons Learned
6. **C6:** Create and Monitor Action Plans

---

## Chapter Summary

This chapter offers a clear introduction to penetration testing from both business and technical viewpoints. It aligns well with the CREST CPSA syllabus.

**Key Concepts Covered:**

- **What PT is** - Security assessment emulating real-world adversaries
- **Why organizations perform it** - Risk identification, compliance, validation
- **How it provides value** - Business value through risk quantification and governance; technical value through control validation
- **Business value** - Governance assurance, risk reduction, cost justification, incident response validation
- **Technical value** - Vulnerability validation, control effectiveness, measurement, incident response capability

**The CREST Penetration Testing Programme:**

Three phases provide a systematic, legally authorized, technically solid approach:
- **Phase A: Preparation** - Governance, purpose, scope, authorization
- **Phase B: Testing** - Methodology, research, exploitation, reporting
- **Phase C: Follow-Up** - Remediation, validation, improvement

**Scoping Importance:**

Proper scoping ensures:
- Legal compliance
- Budget management
- Realistic timelines
- Appropriate resource allocation
- Operational feasibility

**Key Success Factors:**

1. Written legal authorization (RoE)
2. Clear scope boundaries
3. Defined constraints
4. Appropriate testing style
5. Professional methodology
6. Business-aligned reporting
7. Root cause remediation
8. Continuous improvement

---

## Review Questions

**1. What is the PRIMARY legal requirement for initiating penetration testing authorization, ensuring compliance with the Computer Misuse Act (CMA 1990)?**

A. Written, signed Rules of Engagement (RoE) demonstrating CMA 1990 compliance  
B. Approval from the Chief Information Security Officer (CISO) and a successful vulnerability scan  
C. A high-level Memorandum of Understanding (MoU) and insurance documentation  
D. Proof of CREST accreditation for the testing supplier  

---

**2. According to the Testing phase (Phase B), what is the primary rationale for clearly identifying testing constraints (B2)?**

A. To minimize the need for external third-party verification (A7)  
B. To implement 15 to 20% padding/consultant overhead in budgeting  
C. To ensure the engagement stays feasible, safe, and legal by acknowledging operational, technical, or legal limitations  
D. To define the official format for the Final Report (B9) and the Executive Summary  

---

**3. Who must provide formal review and final approval for the documented Requirements Specifications (A6) before a penetration test legally begins?**

A. The Penetration Testing Team lead (Pen Test Team)  
B. Senior Management, following creation and review by skilled technical experts and business management  
C. External compliance auditors (e.g., PCI-DSS QSA)  
D. The designated Incident Response Team  

---

**4. Which of the following activities best exemplifies the strategic business value provided by penetration testing, as opposed to its technical value?**

A. Comprehensive vulnerability validation by confirming exploitability and demonstrating post-exploitation capabilities (B8)  
B. Translating abstract security weaknesses into quantifiable business risks to inform strategic investment decisions  
C. Achieving validation of defensive controls and measuring metrics like Time-To-Detect (TTD)  
D. Using proven methodology that relies on publicly available sources like PTES and NIST SP 800-115 (B6)  

---

**5. During the Follow-Up Phase (C), the goal of Step C2 (Address Root Causes of Weaknesses) is essential for long-term improvement. What does this process prioritize?**

A. Applying immediate, short-term remediation fixes, such as patching one missing system (C1)  
B. Launching the formal Improvement Programme (C3) without management approval  
C. Focusing on addressing the core systemic problems, such as updating the entire patch management system, rather than just treating symptoms  
D. Conducting retesting activities to confirm that the remediation fixes work (C1)  

---

**6. According to the CREST framework, what essential information must the Risk/Exposure section of the final report (B9) provide to senior management?**

A. A quantitative description of the risk discovered, estimating the potential loss if the identified vulnerabilities were exploited  
B. A complete narrative of the methodology used, referencing all publicly available testing tools  
C. Screenshots of all successful exploits (B8), required only for technical audiences  
D. A comparison of the organization's security posture against similar organizations in the same sector (C4)  

---

**7. If a penetration tester is provided with network diagrams, access to source code, and user credentials before starting the engagement, which testing style is being utilized?**

A. Black Box  
B. White Box  
C. Grey Box  
D. Adversarial Goal-Based Assessment (Red Teaming)  

---

**8. What is the recommended range of padding/consultant overhead that should be added to initial time estimates to accommodate unavoidable interruptions or unexpected complexities during the engagement?**

A. 5% to 10%  
B. 15% to 20%  
C. 25% to 30%  
D. 0% - timescale must be fixed as per the SOW  

---

**9. What is the main requirement for the Technical Security Assurance Framework (A1) regarding testing environments?**

A. It must rely solely on automated vulnerability scanning tools  
B. It must be approved only by the Penetration Testing Team (A7)  
C. It must receive formal review and approval from business and IT management  
D. It must define the program's scope to cover only external, customer-facing systems  

---

**10. What is the main objective of the C5 (Build on Lessons Learned) step within the Follow-Up Phase?**

A. To confirm that the original testing objectives were met and provided value for money (C4)  
B. To ensure that best practices and fixes discovered during testing in a specific environment are applied consistently and effectively across other environments in the organization  
C. To set strict target completion dates for all identified action items (C6)  
D. To report weaknesses to relevant third-party organizations, such as CERTs or BUGTRAQ (C1)  

---

## Answer Key

1. **A** - Written, signed Rules of Engagement (RoE)
2. **C** - Ensure feasibility, safety, and legality
3. **B** - Senior Management approval
4. **B** - Translating to quantifiable business risks
5. **C** - Addressing core systemic problems
6. **A** - Quantitative risk description with estimated loss
7. **B** - White Box (full knowledge)
8. **B** - 15% to 20%
9. **C** - Formal approval from business and IT management
10. **B** - Apply lessons learned across the organization

---

## References & Resources

### Official CREST Documentation
- CREST Penetration Testing Guide (v1.0 and latest)
- CREST Technical Syllabus v2.5

### Industry Standards & Frameworks
- PTES (Penetration Testing Execution Standard)
- NIST SP 800-115 (Technical Security Testing)
- OWASP Top 10 / OWASP Testing Guide
- ISO 27001 Information Security Management
- CBEST Framework (UK Financial Services)

### Regulatory Compliance
- Computer Misuse Act 1990 (UK)
- GDPR Article 32 (Data Protection)
- PCI-DSS v3.2.1 (Payment Card Security)
- HIPAA (Healthcare)
- NIS Regulations (Critical Infrastructure)

### Useful Tools & Resources
- Metasploit Framework
- Burp Suite Professional
- OWASP ZAP
- Nmap
- Kali Linux

---

**Document Version:** 1.0  
**Last Updated:** November 18, 2025  
**CPSA Syllabus Alignment:** v2.5  
**Skills Covered:** A1 (Full), A3 (Full)

---

*This Markdown document is ready for GitHub publication. Copy and save as `Chapter-01.md` in your repository.*
