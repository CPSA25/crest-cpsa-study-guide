**Who is this chapter for?**

This chapter is designed for the five main groups that work with or rely
on penetration testing reports. First, it helps CREST CPSA candidates
understand the report structure, how to assess severity, and how to
communicate effectively based on their audience to meet exam
requirements. They can complete the chapter in about two hours. It also
benefits security professionals, system administrators, and penetration
testers looking to enhance their reporting skills, especially in
translating technical findings into business-related risk insights. They
can skip the introductory context if they prefer. Managers, CISOs, and
project leads will find value in the strategic overview of reporting
needs, workflows for interim versus final reports, and risk-based
decision-making, which they can learn in about an hour. Additionally,
the chapter aids executives, auditors, and compliance stakeholders
seeking a clear understanding of reporting formats, regulatory
alignment, and how severity scores relate to organizational risk. They
can grasp this in roughly 45 minutes. Lastly, students and career
changers entering cybersecurity can use this chapter as an introduction
to professional reporting standards, audience expectations, and
UK-specific compliance requirements, taking two to three hours to
complete.

**Learning Objectives**

By the end of this chapter, the learner should be able to:

- Explain the three core audiences for penetration testing reports

- Maintain an unbroken chain of custody throughout an engagement

- Document technical findings with evidence suitable for remediation

- Create an executive summary that translates technical risk to business
  impact

- Ensure reporting compliance with UK GDPR, DPA 2018, and Computer
  Misuse Act

- Produce CVSS-scored findings that prioritise remediation effectively

**Exam Objectives**

  ---------------------------------------------------------------------------
  **Skill   **Skill Name**        **Coverage**   **Depth**         **Exam %**
  ID**                                                             
  --------- --------------------- -------------- ----------------- ----------
  A5        Record Keeping,       ✅ FULL        Comprehensive     5-10%
            Interim Reporting &                                    
            Final Results                                          

  ---------------------------------------------------------------------------

## Understanding Reporting Requirements 

A thorough penetration testing report is crucial. This report serves as
the essential final product. It turns complex technical findings into
clear, actionable information for different groups, including executive
management, technical teams, and external auditors. Good reporting helps
organisations improve their security posture and reduce the risk of
cyberattacks. It also records the methods used and the overall quality
of the technical tests conducted. A primary goal of the report is to
show security weaknesses clearly. It assigns severity scores to help
prioritise steps to fix issues and provides detailed guidance for
technical staff to address and correct the problems. In the end, a
well-organised report helps make informed risk decisions. It provides
documented proof for stakeholders, justifies security spending, and
promotes ongoing security improvement within the organisation.

## Core Audiences and Objectives 

A successful report must address the distinct needs of both strategic,
non-technical stakeholders and operational technical teams. Relying on a
single output format risks either overwhelming management with jargon or
underserving engineers with insufficient detail. There are three main
target audience groups in a penetration test report.

### Executive Management

Executive Management, comprising company executives and senior leaders,
is the primary audience for the penetration testing report. They are
responsible for managing the organisation, approving budgets, and
establishing the risk management strategy. Since their focus is on
strategic matters, they require clear, actionable insights into the
overall risk ranking and the potential business impact of critical
findings, such as compliance issues or financial and reputational harm,
along with the goals of the assessment. To address their needs, the
report should primarily serve this audience with an Executive Summary,
discussed later in this chapter.

🎯 **CPSA EXAM TIP 1**

You must be able to articulate the distinction between the two core
components of the final report and their respective audiences. Relying
on a single output format risks either overwhelming strategic
stakeholders or underserving operational teams.

### Technical Teams (Developers and Engineers)

Technical teams, including developers, engineers, and security analysts,
are a key audience for the Penetration Test report. Their primary role
is to fix identified vulnerabilities and verify that implemented fixes
work, thereby improving the organisation\'s security. They specifically
focus on the Technical Report section, discussed later in this chapter.
Therefore, the report must include sufficient technical detail,
including command outputs and configuration guidance. This information
enables technical staff to understand the root cause of the
vulnerability and to effectively address issues by applying specific
fixes, such as patches or code updates.

### Auditors & Compliance Teams

Auditors and Compliance Teams play a crucial role in reviewing the
penetration testing report. Their primary responsibility is to ensure
that the organisation's security controls and operational practices
comply with specific external regulations, laws, and industry standards,
such as PCI DSS, ISO 27001, and SOC 2. They focus on the test\'s scope,
the methods used, the assigned risks (often using CVSS), and the
evidence demonstrating whether compliance with requirements for external
testing and code reviews was achieved. Therefore, the report should
include explicit references to compliance and link the findings to
relevant standards. It should also explicitly state any scope
limitations and the methods used to guarantee the findings are credible
and useful for regulatory purposes.

![Figure 1 - Report Audience
Hierarchy](media/image1.jpeg){width="4.214352580927384in"
height="4.046242344706911in"}

## Interim Reporting 

Interim reporting is a crucial communication process during active
penetration testing. It usually involves frequent, often informal status
updates, such as daily meetings or encrypted messages, to the Control
Group (CG) and technical operational teams. The aim is to maintain
operational stability and ensure quick risk containment. This reporting
is continuous, with immediate alerts needed for critical vulnerabilities
or active compromises, allowing relevant stakeholders to act swiftly.
The focus is on providing updates and alerts about progress through
testing phases and documenting key compromise actions, rather than
detailed risk analysis or long-term remediation plans. The primary
audience includes technical teams responsible for vulnerability fixes,
project managers (CG/Project Manager), and those liaising with
regulators. Due to its urgent nature, the format is typically brief,
like emails or verbal updates during daily meetings, highlighting
essential technical details and context rather than the formal structure
of a final report.

## Final Reporting

The final report is the formal, detailed document delivered after the
engagement concludes, summarising the structured security assessment and
serving as a critical interface for strategic risk management and
continuous security improvement. This report is pivotal for guiding the
organisation to strengthen its security posture and reduce the risk of
cyberattacks. It is explicitly structured for a bifurcated audience,
featuring a concise, non-technical **executive summary** alongside a
detailed **technical report**. The core purpose is to communicate
findings and insights clearly, identifying the methodologies employed,
the weaknesses discovered, their potential impact, and clear remediation
steps. Key content must include a comprehensive list of findings (Test
Results), assigned standardized severity ratings or Risk Scores (e.g.,
CVSS) for prioritization, technical vulnerability details, and concrete
remediation recommendations for all affected systems.

  ----------------------------------------------------------------------------
  **Aspect**   **Interim Reporting**          **Final Report**
  ------------ ------------------------------ --------------------------------
  **When**     During active testing          Upon completion of the
               (Daily/Weekly/Immediate)       engagement

  **Primary    Operational stability,         Strategic risk management,
  Goal**       immediate risk containment     complete compliance record,
                                              long-term improvement roadmap

  **Key        Status updates, critical       Executive Summary, Technical
  Output**     alerts, evidence of immediate  Findings, Strategic
               compromise                     Recommendations, Methodology
                                              Review

  **Format**   Often informal, rapid,         Formal, structured document,
               encrypted communication        clearly separated sections
                                              (Executive vs. Technical)

  **Risk       May use quick classifications  Mandates industry-standard
  Scoring**    (e.g., Critical/High)          metrics (e.g., CVSS)
  ----------------------------------------------------------------------------

  : Table 1 -- Key Differences of Interim Reporting and Final Reporting

## The Executive Summary

The executive summary is an integral part of a penetration testing
report. It serves as a straightforward briefing intended for executive
management and senior non-technical stakeholders who need a quick,
strategic understanding of the engagement\'s value and risk. The summary
must concisely present the assessment\'s overall findings, scope, and
purpose. It functions as the \"elevator pitch\" of the report, ideally
fitting onto one page and delivered in clear, non-technical language
free of jargon. It should highlight key findings and their possible
consequences, such as compliance issues or financial losses. Therefore,
it must clearly identify the overall risk ranking, score, or profile of
the environment. Additionally, it should offer strategic recommendations
that act as a guide for improving security at the business level while
avoiding technical jargon and negative speculation.

## The Technical Report 

The technical report, or findings section, is the detailed and
action-oriented part of the penetration test report. It mainly targets
technical teams, like developers and engineers, as well as auditors and
compliance staff. Its importance lies in turning the high-level risks
identified in the executive summary into precise, technical data needed
for effective fixes. The main goal is to provide all the information
necessary to replicate, understand, and resolve each identified security
flaw. Key content should include a summary list of findings, which
typically consists of a severity rating or a standardised score, such as
CVSS, to help prioritise issues. It must also include precise technical
descriptions, clear steps to reproduce the vulnerability (the Proof of
Concept, or PoC), supporting evidence (such as screenshots or code
outputs), and detailed, actionable guidance on how to resolve the
underlying issue.

🎯 **CPSA EXAM TIP 2**

The actual value of a penetration test is not merely identifying
vulnerabilities, but ensuring their permanent removal. Candidates must
demonstrate they understand the full lifecycle, from diagnosis to
successful validation.

## Structured Record-Keeping During Engagements

The integrity of any penetration testing engagement relies fundamentally
on meticulous, structured record-keeping. This process, often referred
to as maintaining the **Chain of Custody (CoC)** in digital forensics,
is the meticulous, chronological documentation process that tracks every
interaction with digital evidence from the point of seizure through to
its final disposition. Understanding this structured methodology is
paramount, as failure to maintain an unbroken, detailed record can
render crucial findings unreliable and inadmissible for risk remediation
or legal purposes. In the following discussion, we specify the essential
elements of structured record keeping, specifying what, when, and how
technical documentation must be compiled throughout an engagement.

🎯 **CPSA EXAM TIP 3**

Meticulous, structured record-keeping is fundamental to the integrity of
the engagement, as failure to maintain an unbroken, detailed record can
render crucial findings unreliable. Expect questions requiring you to
identify the essential elements of this forensic methodology (CoC).

### What to Document: The Comprehensive Data Set

Structured record keeping requires capturing all details related to the
assessment\'s integrity, execution, and findings. This goes beyond
simply listing vulnerabilities to include administrative,
methodological, and forensic specifics.

**Administrative and Foundational Data**

This information establishes the context and authorisation of the
assessment:

- **Scope and Methodology:** Define the boundaries of the engagement,
  the agreed-upon penetration testing style (e.g., black box, grey box,
  white box), tools employed (e.g., scanning software, exploit
  framework), and adherence to industry frameworks (e.g., OWASP, NIST,
  PTES).

- **Personnel and Custody:** Record the full names and credentials of
  all team members and relevant client staff involved. Every handler of
  digital evidence must be logged chronologically to maintain
  accountability.

- **Engagement Timeline:** Record the precise duration of the
  engagement, including start and end dates/times, and details of any
  limitations or constraints encountered (e.g., lack of access, broken
  functionality, time restrictions).

**Technical Execution and Evidence (The Audit Trail)**

The core evidence captured during active testing must be sufficiently
detailed to allow technical teams to verify the findings and auditors to
assess the methodology:

- **Steps to Reproduce (Exploitation Vector):** For every confirmed
  vulnerability or misconfiguration, meticulous, step-by-step
  instructions documenting the exploitation path must be recorded.

- **Proof and Artifacts:** Collect and keep strong evidence that proves
  the compromise. This includes command outputs, request/response data
  (HTTP headers, payloads), configuration files, logs, and sensitive
  data accessed (properly masked or sampled). Screenshots must be
  included, clearly labelled, and redacted to safeguard sensitive
  information.

- **System Identification:** Record the affected hosts, specific URLs,
  ports, parameters manipulated, and application versions targeted.

- **Severity and Risk:** Assign a consistent, justified risk rating to
  each vulnerability using a standardized framework (see \'Risk Ranking
  and CVSS Scoring\' section below).

**Remediation and Post-Engagement Data**

Documentation must guide future security enhancement:

- **Mitigation Recommendations:** Detailed, technically accurate steps
  explaining how to permanently fix the identified vulnerability,
  focusing on addressing the root cause rather than just the symptom.

- **Environmental Changes/Cleanup:** Any modifications made to the
  target environment during testing (e.g., creation of test accounts,
  file uploads, configuration changes) must be recorded for cleanup
  purposes.

- **Forensic Data:** In cases of assumed or actual breach, acquire
  forensically sound copies of relevant data (e.g., bit-by-bit disk
  images, system memory dumps) while maintaining full CoC over the
  original medium.

🎯 **CPSA EXAM TIP 4**

Understanding the evidence preservation lifecycle is critical. Expect
questions about the difference between working on original media (which
contaminates evidence) and creating forensically sound copies (which
preserve integrity). Remember: Chain of Custody integrity can make or
break the legal defensibility of your findings.

### When to Document: The Engagement Lifecycle

Documentation is not a final step; it is a continuous process integrated
into every phase of the engagement:

- **Initial Collection/Seizure:** Evidence collection must be documented
  immediately upon identification to establish the original state (e.g.,
  date, time, location of system or data).

- **During Execution (Progressive Logging):** Technical staff must
  maintain a real-time audit trail of their actions, noting all commands
  executed, tools run, and the time of execution. This is crucial for
  distinguishing tester activity from malicious acts and for
  troubleshooting unexpected operational impact.

- **Upon Transfer of Custody:** Every time the evidence (digital medium,
  files, or reports) moves from one person or location to another, a
  formal log of the transfer, the purpose, and the acceptance/release
  signatures must be recorded.

- **Post-Execution/Reporting:** Comprehensive reports compiling all
  findings, risk scores, and remediation advice are produced after
  testing concludes.

- **Final Disposition:** Records must be kept detailing the secure
  destruction or long-term retention of test data and evidence, adhering
  to internal policies or regulatory requirements.

### How to Maintain Integrity: Methodology and Tools

The credibility of the findings rests on the strict adherence to
protocols designed to ensure that the evidence has not been tampered
with or contaminated.

- **Use of Digital CoC Systems:** Reliance on dedicated software systems
  for logging and tracking evidence is preferable to manual records, as
  these tools enhance centralization, organization, and reduce human
  error.

- **Verification of Evidence:** When collecting digital data, prioritise
  creating forensically sound copies (such as bit-by-bit images) instead
  of working directly on original media, ensuring the integrity of the
  source data is preserved.

- **Security of Storage:** All collected evidence and draft reports
  containing sensitive system data must be securely stored. Encryption
  (e.g., AES) is required for data at rest and during transmission. If
  physical media is used, it must be sealed and signed across the seal
  to prevent unauthorized access.

- **Reporting Formats:** As we discussed earlier in this chapter, the
  final report should typically be split into an Executive Summary and a
  detailed Technical Report. Reports should be provided in a secure,
  encrypted format.

**Risk Ranking and CVSS Scoring**

The effectiveness of penetration testing relies heavily on translating
complex technical discoveries into clear, measurable metrics that
facilitate informed risk management decisions. The primary purpose of
incorporating detailed metrics is threefold: to clearly identify
security weaknesses, to quantify the potential business impact, and to
prioritise remediation efforts effectively.

**Severity Ratings and Risk Ranking**

The foundation of metric reporting is determining the significance of a
finding. These terms, while related, serve slightly different purposes
in the final report:

- **Severity Rating (Technical Focus):** This provides an objective
  measure of the technical consequence of exploiting a vulnerability.
  Every identified vulnerability must be assigned a reproducible
  severity score, typically categorised as Critical, High, Medium, or
  Low. This categorisation helps technical teams immediately understand
  the required level of urgency and the potential technical depth of the
  flaw.

- **Risk Ranking/Profile (Business Focus):** This translates the
  technical severity into a measurable risk based on the potential
  **business impact**, such as regulatory compliance issues, financial
  losses, or reputational damage, within the specific organisational
  context. As we discussed earlier in this chapter, the Executive
  Summary must present the overall risk score in non-technical language
  relevant to executives and senior stakeholders.

🎯 **CPSA EXAM TIP 5**

In the context of the CPSA, it is vital to use standardised metrics and
understand how technical findings are translated into business risk.
Candidates should clearly define the separate functions of \'Severity\'
and \'Risk\' within the report.

**Common Vulnerability Scoring System (CVSS)**

The CVSS is the industry-standard framework for deriving a consistent,
objective measure of vulnerability severity. It provides a numerical
score (typically 0.0 to 10.0) that quantifies the flaw\'s
characteristics and impacts.

- **Standardisation:** Using CVSS ensures that the scoring is traceable
  and reproducible, moving beyond subjective descriptions.

- **Reporting Requirement:** Each finding\'s severity level, whether
  derived directly from CVSS or an equivalent organizational matrix,
  must be documented in the technical findings section.

- **Prioritisation:** CVSS base scores are essential for remediation
  planning, helping technical teams prioritize tasks based on the
  quantified risk level.

For organizations that handle sensitive data or operate under strict
regulatory standards (e.g., PCI DSS), CVSS is necessary to rank
vulnerabilities identified during security scans. While the score itself
is objective, it is essential to remember that its meaning (the risk
ranking) should include environmental factors specific to the target
application and organization.

## UK-specific compliance in reporting

Reporting a penetration test in the UK is fundamentally governed by
stringent legal and regulatory frameworks, primarily the UK General Data
Protection Regulation (UK GDPR) and the Data Protection Act 2018 (DPA
2018). These frameworks impose specific requirements for handling
personal data identified during testing and set out the obligations of
organisations classified as data controllers or processors. Failure to
adhere to these requirements carries severe statutory consequences,
including substantial fines and reputational damage. UK data protection
law, governed by the UK GDPR and DPA 2018, is unified across the entire
UK. The UK GDPR sets out the principles and rules for processing the
personal data of UK data subjects. The Data Protection Act 2018 (DPA
2018) supplements the UK GDPR and establishes the legal framework for
the processing of personal data, regulated by the Information
Commissioner's Office (ICO). The ICO has the power to carry out
investigations and compulsory data protection audits under Section 146
of the DPA 2018.

### Roles and Responsibilities in Reporting

The report must address the roles defined under the UK GDPR and the DPA
2018, which determine accountability.

- **Controller**: Determines what data is collected, how it is used, and
  how it is processed. Primarily accountable for compliance; must ensure
  the final report reflects risk management decisions, policy adherence,
  and proper handling of PII discovered.

- **Processor**: Processes data strictly under the instructions of a
  Controller. Must provide sufficient guarantees regarding security
  measures, often validated by the Controller through audit and
  inspection clauses. Must immediately notify the Controller of any
  personal data breach discovered.

- **Data Subject**: The living individual to whom the personal data
  relates. The central focus of data protection is safeguarding their
  rights and freedoms against potential compromise, damage, or distress.

### Data Protection Implications in Reporting

A key principle of the UK GDPR is the security principle, which requires
processing personal data securely using appropriate technical and
organisational measures. Penetration test reports are mandatory
documentation of this process and must demonstrate compliance.

1.  **Handling Personal Data (PII)**

Any information collected during a penetration test that can directly or
indirectly identify a living individual is considered Personally
Identifiable Information (PII) and must be securely handled.

- **Evidence Handling:** If the test identifies and exploits a
  vulnerability allowing access to PII (e.g., passwords, customer
  records), the handling of this data must be documented rigorously,
  maintaining the Chain of Custody (CoC) to ensure the evidence\'s
  integrity. The report should detail how any PII obtained was secured,
  encrypted, and destroyed upon completion.

- **Proof of Concept (PoC):** If sensitive data is accessed to provide
  PoC, it must be securely handled, encrypted, and potentially sampled
  or masked to prevent full exposure within the report.

2.  **Incident Notification Duty (The 72-Hour Rule)**

The discovery of a successful compromise during a penetration test
involving PII triggers an obligation under the UK GDPR.

- **Personal Data Breach:** If the Controller becomes aware of a
  personal data breach (accidental or unlawful destruction, loss,
  alteration, unauthorised disclosure of, or access to, personal data),
  the Controller must notify the ICO.

- **Reporting Timeline:** The Controller must notify the ICO without
  undue delay, and where feasible, no later than 72 hours after becoming
  aware of the breach, unless the breach is unlikely to result in a risk
  to the rights and freedoms of individuals.

- **Report Content:** The notification must describe the nature of the
  breach, the contact details of the data protection officer, the likely
  consequences, and the measures taken or proposed to mitigate adverse
  effects.

3.  **Civil and Criminal Liability**

The UK legal framework includes specific criminal offences related to
computer misuse and data handling that are relevant to penetration
testing reports.

- **Computer Misuse Act 1990 (CMA):** Penetration testing simulates
  actions that could be construed as unauthorized access (Section 1) or
  unauthorized modification (Section 3). The reporting must explicitly
  reference the Rules of Engagement (RoE) and the client\'s formal
  permission (or \"get out of jail free card\") to demonstrate that the
  testing activity was authorised and therefore not illegal.

- **DPA 2018 Offences:** It is an offence to unlawfully obtain or
  disclose personal data (Section 170) or knowingly or recklessly
  re-identify de-identified personal data (Section 171). This reinforces
  the need for meticulous handling and masking of PII within the final
  report, even in non-production environments.

4.  **Mandatory Report Components for UK Compliance**

The overall report structure must be highly formal and incorporate
specific documentation to meet transparency and accountability
obligations.

- **Executive Summary**: Communicates overall risk and impact to senior
  management in non-technical, business terms, aiding strategic
  decision-making regarding remediation investment. Must translate
  technical severity ratings (like CVSS) into strategic business risk.

- **Testing Methodology**: Documents the specific methodology (e.g.,
  OWASP, PTES, NIST 800-115) to demonstrate due diligence and scope
  adherence. Include explicit detail on the agreed-upon scope and any
  constraints/limitations.

- **Findings & Risk Scores**: Provides actionable steps for remediation.
  Requires clear severity ratings (e.g., Critical/High/Medium/Low)
  derived from standardized systems (e.g., CVSS) to prioritize fixes.
  Ensure findings include mitigation steps that address the root cause,
  not just the symptom.

- **Data Handling Plan**: Must document the processes for handling
  PII/sensitive data collected, including encryption status, storage,
  and final destruction procedures. This directly addresses the
  confidentiality and integrity principles of the UK GDPR.

## Client Handoff and Debrief Processes

The client handoff and debrief processes represent the critical final
stages of a penetration testing engagement, ensuring that complex
technical findings are formally communicated, understood, and translated
into an actionable risk mitigation strategy for the organisation. These
activities, often managed through formal review workshops and subsequent
planning phases, are essential for maintaining the integrity of the test
and facilitating continuous security improvement, aligning directly with
CREST certification expectations.

### Client Handoff and Report Review (Assessment Phase Closure)

The client handoff involves the formal delivery of the assessment
findings and the initiation of a collaborative review process among the
assessor, the client's designated Control Group (CG), and, where
applicable, regulatory bodies.

- **Draft Report Delivery:** The Penetration Testing Service Provider
  (PTSP) produces a draft Penetration Test Report, which is the output
  of the execution phase. This report typically includes detailed
  results related to PT performance, identified vulnerabilities, and
  preliminary remediation findings.

- **The Review Workshop:** A dedicated review workshop is conducted
  involving the client, the regulator, the PTSP, and sometimes the
  Threat Intelligence Service Provider (TISP). During this critical
  session, the client (CG) is expected to review the draft report and
  identify any inaccuracies that need to be incorporated into the final
  version.

- **Final Report Output:** The output of this review activity is a final
  Penetration Test Report. The PTSP produces this final document for
  delivery to the client organization (Firm/FMI), which then forwards
  the document to the regulator. This definitive report must clearly
  detail the testing approach, tools used, and compliance methodologies
  employed, ensuring the findings are traceable and credible.

### Post-Execution Integrity and Data Handoff

Before full closure, meticulous steps must be taken to ensure the
security and non-repudiation of the assessment environment and the
collected data.

- **Environment Cleanup:** The penetration tester must document and
  reveal to the organization any changes made to the environment during
  the test, such as creating test accounts, modifying configurations, or
  installing tools. This step is necessary to ensure the environment is
  restored to its original secure state.

- **Evidence Destruction/Sanitisation:** All sensitive data or
  Personally Identifiable Information (PII) accessed during the test,
  including forensic material, configuration files, and any samples used
  for proof of concept, must be securely handled, encrypted, and
  destroyed upon completion of the engagement, adhering to security
  policies and legal constraints. This ensures the confidentiality of
  client data is maintained.

### The Debrief and Lessons Learned

The Debrief session occurs typically during the Closure Phase and serves
a distinct purpose separate from the technical findings review:
continuous program improvement.

- **Stakeholder Participation:** The final Debrief session includes all
  key stakeholders, including the firm, the regulator, and the providers
  (TISP and PTSP).

- **Feedback on Process:** The session focuses on reviewing the
  effectiveness of the assessment process, gathering feedback on
  deliverables, and identifying opportunities to improve the overall
  methodology or future engagements. The regulator may explicitly seek
  input on the CBEST execution process.

- **Documenting Improvement:** The outcomes of this session provide
  crucial qualitative data that can inform strategic decisions and
  mature the client's assessment program, feeding lessons learned back
  into future preparation cycles.

### Remediation Planning and Validation

The ultimate purpose of the reporting and handoff phase is to transition
findings into tangible security improvements.

- **Remediation Plan Creation:** The client\'s Control Group prepares
  the draft Remediation Plan. This planning leverages the comprehensive
  findings presented in the final Penetration Test Report. The final
  plan must detail strategic actions covering governance, senior
  management review, and both tactical and strategic technical
  remediation advice.

- **Prioritisation:** Critical or high-risk vulnerabilities must be
  remediated promptly, often specified within short timeframes (e.g., 14
  days). If fixes require longer timeframes (e.g., legacy system
  replacement), they must be documented as actions within the
  organisation's data security improvement plan.

- **Retesting and Validation:** Following the client\'s remediation, the
  penetration tester should conduct a formal retest to verify that the
  implemented changes successfully mitigate the original risk. This step
  provides definitive proof that the security weakness has been
  adequately addressed.

**Report Completion Checklist**

+----------------------------------------------------------------------+
| EXECUTIVE SUMMARY                                                    |
+:=====================================================================+
| ☐ Two pages maximum                                                  |
|                                                                      |
| ☐ No technical jargon                                                |
|                                                                      |
| ☐ Clear risk profile statement                                       |
|                                                                      |
| ☐ 2-3 critical findings summarised                                   |
|                                                                      |
| ☐ Strategic recommendations aligned to business goals                |
+----------------------------------------------------------------------+
| TECHNICAL REPORT                                                     |
+----------------------------------------------------------------------+
| ☐ All findings have unique IDs                                       |
|                                                                      |
| ☐ Each finding includes a CVSS score                                 |
|                                                                      |
| ☐ Steps to reproduce are reproducible by the technical team          |
|                                                                      |
| ☐ Screenshots/PoC are clear and labelled                             |
|                                                                      |
| ☐ Remediation addresses root cause (not symptom)                     |
|                                                                      |
| ☐ Affected systems explicitly listed                                 |
+----------------------------------------------------------------------+
| CHAIN OF CUSTODY                                                     |
+----------------------------------------------------------------------+
| ☐ Personnel signatures logged                                        |
|                                                                      |
| ☐ Transfer timestamps recorded                                       |
|                                                                      |
| ☐ Storage method documented                                          |
|                                                                      |
| ☐ Sensitive data encrypted                                           |
|                                                                      |
| ☐ Destruction procedures detailed                                    |
+----------------------------------------------------------------------+
| UK COMPLIANCE                                                        |
+----------------------------------------------------------------------+
| ☐ Rules of Engagement referenced (Computer Misuse Act defence)       |
|                                                                      |
| ☐ Scope and limitations stated                                       |
|                                                                      |
| ☐ Testing methodology documented (OWASP/PTES)                        |
|                                                                      |
| ☐ PII handling procedures described                                  |
|                                                                      |
| ☐ 72-hour breach notification procedure clarified                    |
+----------------------------------------------------------------------+

1.  What is the primary operational objective of the Technical Report
    section of the penetration test documentation, specifically
    targeting developers and engineers?

    A.  To provide a concise, non-technical overview of the assessment's
        overall risk ranking for senior non-technical stakeholders.

    B.  To detail command outputs, Proof of Concept (PoC) steps, and
        root cause guidance for effective replication and remediation of
        security flaws.

    C.  To formally log every transfer of custody of the collected
        digital evidence with corresponding timestamps and acceptance
        signatures.

    D.  To specify adherence to external regulatory standards, such as
        PCI DSS or ISO 27001, for compliance checks.

  ----------------------------------------------------------------------
  Scenario 1
  ----------------------------------------------------------------------
  A penetration testing firm has concluded a web application assessment
  that resulted in three critical findings related to SQL injection
  vulnerabilities. The firm must now structure the final report for two
  primary audiences: the Chief Executive Officer (CEO) and the technical
  Development Team lead.

  ----------------------------------------------------------------------

2.  Which specific element must the penetration tester ensure is clearly
    communicated in the Executive Summary to meet the needs of the CEO
    and senior non-technical stakeholders?

    A.  Meticulous, step-by-step instructions detailing the exploitation
        path (Proof of Concept) for the SQL injection vulnerability.

    B.  A concise statement of the overall risk profile and strategic
        recommendations for improving security at the business level.

    C.  The full inventory of affected systems, including specific IP
        addresses, URLs, and application versions targeted.

    D.  The chronological log of all evidence transfers and acceptance
        signatures to maintain the Chain of Custody (CoC).

3.  Which component is mandatory for inclusion in the Executive Summary,
    as it is strictly intended for Executive Management and senior
    non-technical stakeholders?

    A.  Meticulous, step-by-step instructions documenting the
        exploitation path for every confirmed vulnerability.

    B.  The numerical Common Vulnerability Scoring System (CVSS) base
        score assigned to each technical finding.

    C.  A concise statement of the overall risk ranking/profile and
        strategic recommendations for improving security at the business
        level.

    D.  Explicit documentation detailing the secure destruction
        procedures for all Personally Identifiable Information (PII)
        collected.

4.  In penetration testing reporting, what is the Common Vulnerability
    Scoring System (CVSS) primarily intended to provide?

    A.  The Risk Ranking, which translates technical severity into the
        potential business impact specific to the organisation.

    B.  The mandatory, quick classifications (e.g., Critical/High) used
        during interim reporting.

    C.  An objective, numerical measure (0.0 to 10.0) of the technical
        severity of a vulnerability, ensuring standardisation and
        traceability.

    D.  The full documentation required by Auditors and Compliance Teams
        to assess regulatory adherence.

  ----------------------------------------------------------------------
  Scenario 2
  ----------------------------------------------------------------------
  During the penetration test, the assessor successfully bypassed
  authentication and retrieved sampled Personally Identifiable
  Information (PII) to serve as irrefutable Proof of Concept. This
  sensitive data is crucial for the report but must be handled according
  to strict forensic and legal standards.

  ----------------------------------------------------------------------

5.  As part of the Chain of Custody (CoC) process, the digital evidence
    (including the PII sample) is moved from the tester's secure
    acquisition machine to the firm's central forensic repository. What
    is the minimum required documentation element for this transfer?

    A.  A full CVSS environmental score to assess the risk of the
        storage medium.

    B.  The explicit detailing of the software patch level of both the
        source and destination storage devices.

    C.  A formal log of the transfer, including the time, date, location
        change, and acceptance/release signatures.

    D.  The precise scope limitations and constraints encountered during
        active testing.

6.  According to structured record-keeping requirements for the Chain of
    Custody (CoC), what protocol is explicitly required to maintain the
    integrity and security of all collected evidence and draft reports
    containing sensitive system data during storage and transmission?

    A.  The creation of bit-by-bit disk images must be acquired from all
        systems accessed during the engagement.

    B.  Evidence must be handled exclusively using forensically sound
        copies rather than working directly on original media.

    C.  Encryption (e.g., AES) is required for data at rest and during
        transmission, and the security of storage must be documented.

    D.  All evidence must be securely destroyed immediately after the
        formal client handoff and review workshop.

7.  Why is it a mandatory component of the final report to explicitly
    reference the Rules of Engagement (RoE) and the client's formal
    permission to test?

    A.  To aid the client's Control Group in preparing the draft
        Remediation Plan.

    B.  To serve as a necessary defence against potential criminal
        charges under the UK's Computer Misuse Act 1990 (CMA).

    C.  To document the methods used to secure, encrypt, and destroy
        Personally Identifiable Information (PII) discovered during the
        assessment.

    D.  To ensure the Controller is aware of the 72-hour timeline for
        notifying the Information Commissioner's Office (ICO) of a
        personal data breach.

8.  What essential action must the penetration tester undertake after
    the client has implemented the fixes detailed in the Remediation
    Plan?

    A.  Provide status updates via frequent, informal encrypted
        communications to the Control Group during active testing.

    B.  Conduct a formal retest and validation to verify that the
        implemented changes successfully mitigate the original security
        risk.

    C.  Document all administrative and foundational data, including the
        precise duration of the engagement and tools employed.

    D.  Collect supporting evidence, such as configuration files and
        request/response data, to prove the compromise.

9.  How does Interim Reporting fundamentally differ from Final Reporting
    regarding its primary goal?

    A.  Interim Reporting requires the mandate of industry-standard
        metrics like CVSS, while Final Reporting may use quick
        classifications.

    B.  Interim Reporting focuses on operational stability and immediate
        risk containment, often through critical alerts and informal
        updates during active testing.

    C.  Interim Reporting is delivered upon the completion of the
        engagement and includes a detailed review of the full
        methodology employed.

    D.  Interim Reporting is targeted primarily at Auditors and
        Compliance Teams to establish a complete compliance record.

  ----------------------------------------------------------------------
  Scenario 3
  ----------------------------------------------------------------------
  A penetration test reveals an outdated server component assigned a
  Critical severity rating (CVSS score of 9.2). The Technical Report
  recommends immediately patching the component and implementing
  automated update processes. The client subsequently implements a
  temporary network filter to block the known exploit vector instead of
  patching the software.

  ----------------------------------------------------------------------

10. In this scenario, what specific function does the assigned CVSS
    score of 9.2 serve for the technical teams reviewing the Technical
    Report?

    A.  It defines the risk ranking based on potential financial or
        reputational harm to the business.

    B.  It acts as an objective, numerical measure of the technical
        severity of the vulnerability, aiding prioritisation.

    C.  It serves as the primary output of interim reporting for
        immediate risk containment.

    D.  It documents any modifications made to the target environment
        during testing for cleanup purposes.

Answer Keys

  ------------------------------------------------------------------------
  Answer   Correct   Rationale
  No.      Answer    
  -------- --------- -----------------------------------------------------
  1        B         The Technical Report's primary goal is to provide all
                     necessary information, including the Proof of Concept
                     (PoC) and detailed guidance, to technical teams to
                     replicate, understand, and resolve the security flaw.

  2        B         The Executive Summary must be concise and
                     non-technical, providing senior stakeholders with an
                     overview of the overall risk profile and strategic
                     recommendations.

  3        C         The Executive Summary is delivered in non-technical
                     language for senior management, focusing on the
                     overall risk profile, scope, and strategic
                     recommendations.

  4        C         The CVSS is the industry-standard framework providing
                     an objective, numerical score (0.0 to 10.0) to
                     measure technical severity for standardisation and
                     prioritisation.

  5        C         Maintaining the Chain of Custody (CoC) requires
                     documenting every transfer of evidence with a formal
                     log that includes timestamps and acceptance/release
                     signatures.

  6        C         The security of storage is critical for evidence
                     integrity, requiring encryption (e.g., AES) for
                     sensitive data in draft reports and evidence, both at
                     rest and during transmission.

  7        B         Penetration testing simulates actions covered by the
                     Computer Misuse Act 1990 (CMA); referencing the RoE
                     explicitly demonstrates client authorisation, serving
                     as a legal defence.

  8        B         The final stage of the remediation lifecycle is the
                     formal retest (validation), conducted by the tester,
                     to verify the client's fixes have successfully and
                     permanently mitigated the identified risk.

  9        B         Interim reporting occurs continuously during active
                     testing, aiming for immediate risk containment and
                     operational stability, often via quick, informal
                     alerts.

  10       B         CVSS provides an objective, numerical measure of the
                     technical severity (0.0 to 10.0), which is essential
                     for technical teams to prioritise remediation
                     efforts.
  ------------------------------------------------------------------------
