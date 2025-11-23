## Who is this chapter for? 

This chapter is for CREST CPSA candidates, cybersecurity practitioners,
and junior penetration testers who need to understand the legal,
regulatory, and compliance requirements for penetration testing in the
UK. It provides essential knowledge for those preparing for the CPSA
exam. The chapter explains how Acts, Regulations, Standards, Policies,
Procedures, and Compliance frameworks define what testers can legally
do. It also covers how to secure authorization and what safeguards to
follow to avoid criminal liability. Anyone starting a career in
penetration testing, moving from IT to security assessment, or looking
to follow CREST best practices will find this chapter\'s clear overview
of the UK\'s legal structure useful. It shows how these laws directly
influence lawful, ethical, and compliant penetration testing activities.

## Learning Objectives 

By the end of this chapter, the learner should be able to:

- Understand the core legal frameworks governing UK penetration testing,
  including the Computer Misuse Act, Data Protection Act/UK GDPR, and
  relevant sector regulations.

- Identify the role and importance of authorization, scoping, and Rules
  of Engagement in ensuring legally compliant security testing.

- Distinguish between organizational documents, Acts, Regulations,
  Standards, Policies, and Procedures, and explain how each shapes
  testing activities.

- Recognize how regulatory requirements (such as NIS Regulations and PCI
  DSS) influence security testing obligations and reporting
  expectations.

- Apply legal and compliance principles to real-world penetration
  testing scenarios commonly assessed in the CPSA exam.

- Evaluate the risks of non-compliance and articulate how improper
  testing may lead to legal, operational, and reputational consequences.

## Exam Objectives

  ----------------------------------------------------------------------------
  **Skill   **Skill Name**        **Coverage**   **Depth**            **Exam
  ID**                                                                %**
  --------- --------------------- -------------- -------------------- --------
  A2        Law and Compliance    ✅ FULL        Comprehensive        15-20%

  ----------------------------------------------------------------------------

## Law and Compliance 

The legal and compliance hierarchy outlined by the UK government is a
structured system developed to define the scope of organizational
behaviour, protect public interests, and preserve national security. It
is crucial for every cybersecurity professional, especially CREST
Approved members, to understand the levels of this hierarchy because the
rules that govern how security testing is authorized and performed are
established by laws, regulations, and standards that define the scope of
each level's jurisdiction. Depending on the level of authority, the
legal position, enforcement power, and compliance requirements are
different.

There is no single official ranking of legal instruments created by the
UK government or CREST. However, the legal framework in the UK and CREST
guidance stress that Acts and Regulations have primary legal authority.
Acts rank highest, followed by Regulations. Organizational policies,
standards, procedures, and guidelines have different levels of
bindingness and legal weight. Figure 1 shows different legal instruments
that penetration testers should be aware of.

![Figure 1 -- Legal
Instruments](media/image1.png){width="5.923509405074365in"
height="5.1875in"}

### Act 

An Act, also referred to as Primary Legislation, is a formal law enacted
by the UK Parliament, which includes the House of Commons and the House
of Lords, and signed into law by the Monarch, known as Royal Assent.
Acts are the highest legal authority in the UK and the basis of all
subsequent regulations, statutory instruments, and compliance codes.
They are created following a rigorous process in which they are read,
debated, reviewed by committees, and modified to be approved. Acts are
legally binding and actionable, meaning that those who violate them can
be penalized or imprisoned criminally or civilly. Because they are the
basis that defines the scope for all activities in the UK, changes to
Acts must occur through new laws, which are presented and passed through
a formal process. Figure 2 presents 27 cybersecurity acts imposed by UK
government for protecting and preserving national cybersecurity.

![Figure 2 -- UK Cybersecurity
Legislations](media/image2.png){width="6.5in"
height="5.831944444444445in"}

For CREST CPSA candidates, understanding relevant Acts is critical, as
they establish the legal framework within which penetration testing must
operate. Several UK Acts influence the cybersecurity legislation and
penetration tests directly. CREST advises candidates to pay special
attention to the following: that Acts establish the boundaries where
security testing is legal and where it is a crime, define the necessity
of the conducting party to be authorized, and test under the legislation
respecting people's privacy and data protection. UK Acts mentioned in
CPSA Syllabus are:

- Computer Misuse Act 1990

- Human Rights Act 1998

- Data Protection Act 1998

- Police and Justice Act 2006

### Regulations

A Regulation, also known as a Statutory Instrument (SI), is a legally
binding rule formulated by a Government Minister, agency, or approved
body to whom powers to create it have been formally delegated by an Act
of Parliament. Regulations are used to provide this specific level of
operational detail needed to implement and enforce the underlying
principles set out by an Act, explaining how the law should be enacted
in practice. Although they may have slightly less authority than an Act,
Regulations remain of the highest legal authority and are fully
enforceable, with infringement typically punished by civil or criminal
means. As they may be created and changed faster than Acts, Regulations
allow the government to adjust requirements and address fast-developing
dangers and trends without the need for a lengthy parliamentary process.
Regulation is crucial in that it transmutes legislative intentions into
actionable technical and procedural requirements. Examples of UK
Cybersecurity Regulations are:

- **Network and Information Systems Regulations 2018 (NIS 1)** --
  Critical infrastructure security

- **General Data Protection Regulation (UK GDPR)** -- Data protection
  detailed rules

- **PCI DSS Requirement 11.3** -- Penetration testing requirement for
  payment systems

- **NHS Data Security Standard 9** -- Healthcare pentesting mandate

- **Telecommunications (Security) Act 2021 Regulations** -- Telecom
  security requirements

### Standards 

Standards are organized collections of technical specifications,
protocols, and performance requirements used to maintain consistency,
dependability, and excellence in cybersecurity operations. CREST CPSA
applicants are advised to grasp the majority of standards since they
define "good security" in governance and technical assurance. In most
cases, standards are created by international bodies, such as ISO,
government offices, and trade organizations. They may be either
normatively binding when contested as rule or recommendatory directives
in the form of "how something should be done" in the dedication to
compliance and improvement. Most standards follow a consistent structure
that includes baseline requirements (minimum acceptable controls), best
practices (recommended methods for enhanced security), implementation
guidance (how to meet the standard), assessment criteria (how compliance
is verified), and certification processes (formal recognition of
compliance). For example, PCI-DSS Requirement 11.3 specifically mandates
penetration testing as part of compliance for payment systems. There are
three main categories of standards:

**1. Internationally Recognised Standards**

- **ISO 27001** -- Information security management

- **ISO 27002** -- Information security controls

- **NIST SP 800-115** -- US federal security testing standard

- **OWASP Top 10** -- Web application security risks

**2. Industry-Specific Standards**

- **PCI-DSS** -- Payment Card Industry (13 requirements)

- **HIPAA** -- Healthcare data protection (US)

- **SOC 2** -- Service Organization Controls

**3. UK Government Standards**

- **CREST Framework** -- UK penetration testing standard

- **NHS Digital Standards** -- Healthcare security

- **Cyber Essentials** -- UK baseline cybersecurity

### Policies

Policies are high-level statements of intent and direction that allocate
an organization or government's approach to a specific thematic area of
governance, such as cybersecurity, data protection, or risk management.
As such, they define "what" and "why" -- what the organization or
government is looking to achieve, and why does the policy exist. They do
not delve into the "how"; that is left to lower-level documents such as
procedures, standards, or guidelines. Policies are approved by senior
management or departmental leadership and have specific and binding
authority within the organization. They are typically brief high-level
documents that cover the policy's need, scope, responsibilities,
obligations, and penalties for non-compliance. Effective policies also
have a review schedule to ensure their relevance in light of changing
threats, technologies, and legal frameworks. Mainly, there are two types
of policies:

**1. Government Policies**

- Cyber Security Strategy

- Data Protection Policy

- Incident Response Policy

- Risk Management Policy

**2. Organizational Policies (Examples)**

- Penetration Testing Policy -- \"We will conduct authorized pentesting
  to identify vulnerabilities\"

- Data Protection Policy -- \"All personal data will be protected per
  GDPR\"

- Security Policy -- \"All systems will undergo regular security
  testing\"

- Access Control Policy -- \"Access granted on least-privilege basis\"

### Procedures 

Procedures are the detailed, step-by-step operational instructions that
define how specific security tasks are to be performed. They translate
high-level policies into actionable, repeatable processes, ensuring that
organizational security activities are executed consistently,
accurately, and in compliance with defined standards or regulatory
requirements. Typically developed by technical teams or operational
management, procedures are binding within the organization but are not
legally enforceable outside of it. They focus narrowly on specific
activities, such as conducting a vulnerability scan, performing a
penetration test, managing incident response, or applying system
patches, providing precise, task-level guidance to ensure uniform
execution. Because they address day-to-day operations, procedures are
frequently updated to reflect new technologies, tools, or workflow
changes.

### Compliance 

Compliance refers to following relevant laws, regulations, standards,
and organizational policies. It involves putting legal and regulatory
requirements into practice to ensure that both individuals and
organizations stay within set limits. In short, compliance means acting
according to rules and expectations set by external authorities and
internal governance.

Key aspects of compliance include shared responsibility; both
individuals and organizations are responsible for maintaining it.
Verification usually happens through audits, assessments, inspections,
and testing to ensure adherence. The consequences of not complying can
be serious, including fines, imprisonment, or losing licenses or
certifications. Importantly, compliance is an ongoing process, not a
one-time task. It requires continuous monitoring and improvement. In the
context of the CREST CPSA, compliance is crucial since CPSA practices
rely on lawful, ethical, and standards-driven assessment activities.

There are three main levels of compliance.

**Level 1:** Legal Compliance involves following laws and regulations.
If a company fails to comply, it might face criminal or civil
prosecution. Examples include getting authorization under the Computer
Misuse Act (CMA) or managing personal data according to the General Data
Protection Regulation (GDPR).

**Level 2:** Regulatory Compliance focuses on meeting industry standards
and guidelines. Non-compliance can lead to losing certifications or
licenses. Typical examples include following PCI-DSS standards for
payment systems or the NIS Directive for protecting critical
infrastructure.

**Level 3:** Organizational Compliance relates to following internal
policies and procedures. Violations can lead to disciplinary actions or
contractual issues. Examples include sticking to a company's penetration
testing policy or internal approval processes.

🎯 **CPSA EXAM TIP 1**

Be prepared to connect legal duties with broader regulatory and industry
frameworks, including NIS Regulations and PCI DSS requirements. The CPSA
syllabus evaluates whether candidates can show how penetration testing
contributes to compliance, risk reduction, and assurance obligations
across regulated sectors. Demonstrating awareness of how testing aligns
with organizational governance and regulatory reporting expectations
strengthens your exam responses.

## Acts and Regulations Applied to Penetration Testing 

In the UK, penetration testing is governed by a strict set of legal
rules, mandatory regulations, industry standards, and internal
documents. As a CREST approved cybersecurity practitioner, you must be
aware that pentesting simulates illegal attacks. Its legitimacy depends
entirely on clear, written permission and strict adherence to legal and
ethical guidelines.

### Computer Misuse Act 1990

The most important legal rule for penetration testing is the Computer
Misuse Act 1990 (CMA). Since penetration testing mimics criminal
activities, its legality depends on getting clear, written permission.
The very first section of the CMA 1990 states: "*A person is guilty of
an offence if he causes a computer to perform any function with intent
to secure access to any program or data held in any computer, with
intent to commit an offence to which this section applies\..."*
Therefore, the CMA defines the actions testers take as criminal,
including trying to access computer materials. In section 17 (2), it
states, \"*A person secures access to any program or data held in a
computer if by causing a computer to perform any function he... (a)
alters or erases the program or data; (b) copies or moves it to any
storage medium other than that in which it is held or to a different
location in the storage medium in which it is held; (c) use it; or (d)
has it output from the computer in which it is held (whether by having
it displayed or in any other manner);*\" Any access is considered
unauthorized if the person \"*does not have consent to access from any
person who is so entitled.*\" Therefore, the signed Rules of Engagement
(ROE) must clearly authorize the actions to give the tester a legal
defence against the CMA.

🎯 **CPSA EXAM TIP 2**

**Distinguish Authorization Under CMA from Contractual Agreement**: The
CMA 1990 makes the core actions of penetration testing criminal
offences, such as securing access to any program or data. The tester's
only legal defence against the CMA is clear, written permission from the
person entitled to consent. Common CPSA exam trap: Confusing
\'authorization under CMA\' with \'contractual agreement.\' You can have
a commercial contract for services, but still lack CMA authorization if
the ROE are missing or if the tester exceeds the agreed limits. The ROE
is the specific contractual and legal document that grants the assessor
legal immunity for authorized actions; testing outside this boundary is
a criminal offence under the CMA Section 1 or Section 3.

### Human Rights Act (HRA) 1998

The Human Rights Act (HRA) 1998 significantly dictates how penetration
testing must be conducted in the UK. The cornerstone of personal
protection is **Article 8** of the HRA, which guarantees the right to
respect for private and family life, home, and correspondence. For
cybersecurity professionals, this directly correlates with the data
protection requirement to maintain the confidentiality, integrity, and
availability of personal data. The implication is profound: when a
tester gains access to a system, they are often accessing individuals\'
private information. Consequently, testing activities, especially
intrusive ones, must be lawful, necessary, and proportionate to achieve
the security goal, while minimising the impact on the individual\'s
rights. Practically, this dictates that testers must obtain explicit,
robust permission before commencing, and strictly adhere to data
handling procedures, such as encrypting all gathered data, never
retaining Personally Identifiable Information (PII) or Personal Health
Information (PHI), and providing only \"proof of access\" (e.g.,
database schema screenshots or file counts) rather than the sensitive
content itself.

The professional obligations are further complicated by **Article 10**
(Freedom of expression), which protects the right to impart information.
Penetration testing results inevitably involve disclosure, of
vulnerabilities, system weaknesses, and sensitive configurations. This
function can raise concerns if the disclosure, even within the bounds of
the test report, is seen as unlawful, particularly regarding the release
of information that might infringe on others\' data rights (Article 8)
or classified information. In balancing these rights, UK legislation
(the Data Protection Act 2018) acknowledges that processing data for
\"special purposes,\" such as journalism or research, sometimes requires
exemptions to reconcile with freedom of expression. However, the core
practical impact for a CREST candidate remains unwavering: testers must
operate under strict non-disclosure agreements and formal Rules of
Engagement, ensuring that the necessary disclosure of security risk is
sanitized, securely transferred, and confined to authorized parties,
thereby ensuring technical assurance without legal transgression.

### Data Protection Act 2018 (DPA 2018)

The Data Protection Act 2018 (DPA 2018) is the UK domestic law that
supplements the principles set out in the UK General Data Protection
Regulation (UK GDPR), requiring penetration testers to comply with both
frameworks simultaneously. The foundational impact lies in the UK GDPR's
\"security principle,\" which mandates that processing systems must
employ \'appropriate technical and organisational measures\' to ensure a
level of security appropriate to the risk. This obligation is reinforced
by UK GDPR **\"Article 32,\"** which requires controllers and processors
to have a formalized \"process for regularly testing, assessing and
evaluating the effectiveness of technical and organisational measures\".
Penetration testing and vulnerability scanning are explicitly relied
upon to fulfil this duty, acting as stress tests to confirm the ongoing
confidentiality, integrity, availability, and resilience of processing
systems. Consequently, the test scope must be rigorously defined to
cover critical systems and comply with the principle of necessity and
proportionality; testing that risks exposing sensitive Personally
Identifiable Information (PII) or causing system disruption
(recklessness under other laws) should be restricted, often requiring
non-production systems or test data to mitigate high impact risks.

The DPA 2018 introduces stringent criminal liabilities that govern the
tester's activities and post-test conduct. Crucially, **Section 170**
makes it an offence to knowingly or recklessly \"*to obtain or disclose
personal data without the consent of the controller*,\" or to \"*retain
it without the consent of the controller*\". This statutory risk
elevates the \"Permission to Test\" document (ROE) to a critical legal
shield, which must define not just the scope but unambiguous
requirements for data handling, storage, and destruction. As a direct
result of these constraints, testers must adhere to data minimisation
principles, ensuring that if sensitive data (such as Cardholder Data) is
encountered, it is not downloaded and stored on the tester\'s systems;
instead, non-content evidence (sanitised screenshots or record counts)
must be used as proof of concept. Furthermore, the DPA 2018 requires
that all data gathered must be encrypted on the tester\'s systems, and
securely destroyed upon the client\'s acceptance of the final report,
thereby ensuring professional conduct and eliminating legal exposure
related to unauthorised retention.

🎯 **CPSA EXAM TIP 3**

**Recognize the Criminality of Data Retention (DPA S.170):** While the
CMA governs the *act* of unauthorized access, the Data Protection Act
2018 (DPA 2018) governs the ethical and secure handling of data after
access is secured. The DPA 2018 establishes stringent criminal
liabilities, notably Section 170, which makes it an offence to knowingly
or recklessly \"retain\" personal data without the controller\'s
consent. Therefore, if a tester fails to securely destroy PII
(Personally Identifiable Information) or sensitive data from their
systems after the project concludes, they violate this criminal
provision. The ROE must specify unambiguous secure destruction
protocols. Testers must use sanitized, non-content evidence (e.g.,
schema screenshots or record counts) rather than the sensitive content
itself as proof of concept (PoC).

### Police and Justice Act (PJA) 2006 

The Police and Justice Act (PJA) 2006 was an important law meant to
update the UK\'s legal system for cybercrime, especially through
specific changes to the Computer Misuse Act 1990. PJA 2006 Section 35
focused on the main CMA offence, which is unauthorized access to
computer material (CMA Section 1). It expanded the definition to include
actions taken with the intent to allow unauthorized access. However, the
most significant change for aggravated offences came from PJA 2006
Section 36. This section replaced the old Section 3 of the CMA with a
new offence that covers \"unauthorized acts with intent to impair, or
with recklessness as to impairing, operation of a computer, etc.\" This
change raised the maximum penalty for these acts from a previous maximum
of five years to ten years in prison. The new Section 3 made it illegal
not only to intentionally impair but also to be reckless about whether
an act would prevent or hinder access to any program or data. As a
result, it covers many unintentional outcomes of destructive testing.

These aggravated offences have serious implications for professional
penetration testers. They need to be extremely careful and strictly
follow established ROE. Penetration testing involves simulating real
attacks and exploiting vulnerabilities. If testing crosses into
aggravated actions, it involves anything that can intentionally or
recklessly harm computer operations or block legitimate access. For
example, certain techniques used in active penetration testing, like
running resource-heavy exploits, denial of service (DoS) style tests, or
using vulnerability scanners too aggressively, can lead to degradation,
loss of services, or even system restarts. These outcomes can meet the
recklessness criteria under CMA Section 3. The risk increases when
testing critical infrastructure or live environments, such as
Operational Technology (OT) or systems that support essential services
under the NIS Regulations. Disruption in these areas could cause serious
economic or social harm. Therefore, testers must obtain clear legal
authorization to protect themselves against potential system
instability. They should also document all their actions carefully and
avoid making any changes to critical services unless previously agreed
upon. This helps reduce exposure to the stricter penalties associated
with these aggravated offences.

### Network and Information Systems (NIS) Regulations 2018

For critical infrastructure, the Network and Information Systems
Regulations 2018 represent a cornerstone of the UK's approach to
managing cyber risk within crucial services, designed to boost the
overall level of security of these systems. The scope of the regulations
applies predominantly to Operators of Essential Services (OESs) and
Relevant Digital Service Providers (RDSPs). OESs are defined as entities
providing services critical for the maintenance of societal or economic
activities, specifically mandated across the sectors of energy, water
supply and distribution, health, transport, and digital infrastructure.
A penetration tester is highly likely to encounter environments
regulated by NIS, as organisations in these sectors frequently procure
testing services to validate controls against evolving cyber threats,
often driven by legal or regulatory requirements. OESs have a legal duty
under **Regulation 10(1) and (2)** to implement appropriate and
proportionate technical and organisational measures to manage and
minimise risks to their essential services. This is essential because
the failure or compromise of networks and information systems in these
sectors poses a systemic risk to the services they provide, contributing
to the overarching goal of ensuring the UK is the safest place to be
online.

The strict definition underpinning these legal duties, found in
Regulation 2(3)(g), is the security of network and information systems,
defined as \"*the ability of network and information systems to resist,
at a given level of confidence, any action that compromises the
availability, authenticity, integrity or confidentiality of stored or
transmitted or processed data or the related services offered by, or
accessible via, those network and information systems*\". The practical
impact for the CPSA tester is focusing their methodology not just on
confidentiality (data theft) but critically on availability (service
disruption). For example, when testing a water utility\'s SCADA network
(falling under the water sector OES), the testing scope must be strictly
controlled to prevent system failure or interference, as integrity and
availability are paramount. Failure by an OES or RDSP to fulfil these
security duties can result in severe financial penalties levied by the
Competent Authority. These penalties are tiered, ranging up to a maximum
of **£17 million** for material contraventions that result in an
immediate threat to life or a significant adverse impact on the United
Kingdom economy. This rigorous enforcement regime underscores the
imperative for precision and caution when performing security
assessments in NIS-regulated environments.

Note: The UK Government is consulting on updating NIS Regulations to
align with the EU NIS 2.0 Directive. CPSA candidates should be aware
that enhanced requirements for asset owners and critical infrastructure
are evolving. As of October 2025, CPSA exams reference NIS 2018, but
updates may follow.

### PCI DSS Penetration Testing Guidance

The PCI Data Security Standard (PCI DSS) requires specific security
assessments to protect the Cardholder Data Environment (CDE). This is
mainly outlined in Requirement 11.3. This requirement states that
penetration testing must be done at least once a year, and also after
any major changes to the infrastructure or application that could impact
network security or provide access to cardholder data. The scope of the
PCI DSS penetration test is broad. It includes the entire CDE perimeter
and all-important systems that store, process, or transmit cardholder
data. The CDE perimeter consists of both external (public-facing attack
surfaces) and internal (LAN-LAN attack surfaces) segments. Therefore,
the testing must include both External Penetration Tests, which simulate
an outside attacker against perimeter defences and remote access points
like VPNs, and Internal Penetration Tests, which simulate an attack from
within the internal network to evaluate lateral movement and access
controls. The assessment must consider both application-layer and
network-layer security issues.

The CPSA candidate must understand that PCI DSS stresses strictly
approved scopes and methods to ensure thoroughness and coverage.
Penetration tests must specifically validate segmentation controls to
confirm that they work, are effective, and separate all out-of-scope
systems from the CDE. The choice of methodologies is important: PCI DSS
tests are usually performed as Grey-Box or White-Box assessments. These
approaches use partial or full knowledge of the system, such as network
diagrams or source code. They provide more reliable results and better
verification of security than purely Black-Box tests. Ultimately, the
organization being assessed must define the scope of the CDE and
critical systems. The test plan, which includes the ROE, must be
officially agreed upon and documented before starting. This formal
agreement authorizes the tester to perform the tasks while managing
risks related to system disruption or the exposure of sensitive data.
Any cardholder data accessed during the test must be reported
immediately and handled securely according to PCI DSS requirements.

### NHS Data Security Standard 9 (DSS 9) 

The DSS 9 comes from the National Data Guardian's recommendations and is
a mandatory security requirement for the UK health sector. CPSA
penetration testers need a strong understanding of DSS 9 because it is a
vital part of the \"Data Security and Protection Toolkit\" (DSPT). This
requirement applies to organizations like NHS Trusts, Integrated Care
Boards, and related IT suppliers. The standard states that a penetration
test must occur at least once a year, with the main goal being to
protect IT systems from cyber threats based on a proven security
framework. To ensure quality, NHS organizations are advised to choose
commercial partners that are CREST UK Approved Member Companies or to
hire testers who are CREST/Tiger Scheme qualified. This shows a clear
link between the regulatory requirement and the CREST professional
standards. Additionally, the Senior Information Risk Owner (SIRO) must
be actively involved and must approve the scope of all testing plans.

Implementing DSS 9 requires specific planning beyond a general security
assessment. The main requirement for the penetration test states that it
must include all web servers used by the organization, detailed
vulnerability scans, and checks to ensure that default passwords for
network components have been changed. This test should cover the
organization's entire critical network structure, such as server farms.
While annual testing is the minimum, the approach supports ongoing
verification and improvement, following a Plan, Do, Check, Act model. If
an organization undergoes an equivalent security onsite assessment, this
may fulfil the annual penetration testing requirement, as long as it
includes the necessary checks of web servers and default passwords, and
the scope is officially approved by the SIRO. Importantly, any critical
or high-risk vulnerabilities found during the assessment must be fixed
within 14 days. If these vulnerabilities are not addressed, the SIRO
must formally document and accept the risk.

### Policies and Procedures (Internal Governance) 

Internal governance translates external requirements into practical
steps. High-level Policies define strategic intent. For example, Recital
78 of the UK GDPR states that to show compliance, *"The controller
should adopt internal policies and implement measures which meet in
particular the principles of data protection by design and data
protection by default\".* The specific Procedure for managing the
technical aspects of penetration testing is the ROE.

To sum up, UK legislation collectively transforms penetration testing
into a regulated, legally accountable practice that prioritizes
authorization, data protection, and critical infrastructure assurance.
The **CMA** **1990** mandates explicit written consent before any
testing, ensuring all simulated access remains lawful. The **DPA 2018**
and **UK GDPR** extend this framework by enforcing ethical handling of
personal and sensitive data, requiring that any information accessed
during testing be securely managed, used only as proof of concept, and
destroyed after project completion. The **NIS Regulations 2018** further
elevate penetration testing requirements for essential service
operators, making security validation a legal duty and attaching
significant financial penalties for non-compliance. Together, these laws
ensure that penetration testing in the UK is conducted responsibly, with
clear authorization, strong data governance, and accountability to
national cybersecurity standards.

## How Legal Requirements Shape Penetration Testing Decisions

1.  **Scoping Impact: How Legal Constraints Force Testing Boundaries**

The law directly determines the boundaries of a penetration test,
transforming technical possibility into legal constraint. The scope must
explicitly define what systems are included and excluded from testing.

- **CMA 1990 Defining Access Limits:** The Computer Misuse Act 1990
  criminalises unauthorised access to computer material (Section 1) and
  unauthorised acts intended or reckless as to impairing computer
  operation (Section 3). Therefore, legal scoping is essential because
  testing any system or performing any action outside the boundaries
  defined in the ROE constitutes a criminal offence under the CMA 1990.
  This is particularly critical when dealing with third-party hosted
  services; client permission alone is insufficient, and separate
  authorisation must be obtained from the hosting provider.

- **GDPR \"Article 32\" (Appropriate Level of Security):** The UK GDPR
  imposes a duty on controllers and processors to implement appropriate
  technical and organisational measures to ensure a level of security
  appropriate to the risk (Article 32). This legal mandate requires
  assurance that all critical components are adequately secured. This
  duty impacts scope definition by mandating that critical systems,
  systems that store, process, or transmit sensitive data (like the
  Cardholder Data Environment under PCI DSS), and boundary controls
  (like network segmentation) are included in the assessment to ensure
  the overall resilience of the system.

- **Data Protection by Design Influencing Methodology:** The principle
  of Data Protection by Design requires that security is integrated
  early into the system development lifecycle (SDLC). This influences
  testing methodology, favouring techniques like White Box testing
  (which involves access to source code for in-depth review) and source
  code analysis to find logic flaws and weaknesses early, thereby
  incorporating security safeguards *into* the design, rather than
  relying solely on late-stage Black Box testing.

  1.  **Authorization Impact: Why Written Consent is Non-Negotiable**

Explicit, written authorisation is the professional penetration tester's
core defence against prosecution under the CMA 1990 and is required to
manage the risks inherent in intrusive testing.

- **Necessity of Rules of Engagement (ROE):** The ROE is a contractual
  and legal document that defines *how* testing will be conducted and
  grants the assessor legal immunity for authorized actions. Crucially,
  the ROE must indemnify the tester against liabilities associated with
  potential system failure or exposure of sensitive data resulting from
  authorised testing activity.

- **Breaching CMA without Explicit ROE:** Without a signed ROE clearly
  defining the methods, timings, and extent of penetration, a tester
  risks committing a CMA offence even if they have general permission to
  access the system. For instance, accessing systems or data explicitly
  denied by the employer, even by an employee or a contracted tester,
  can be considered \"unauthorised access\" under CMA Section 1 if the
  limits of authority are clearly defined. If the tester exceeds the
  agreed scope by, for example, causing a service disruption, they could
  recklessly impair the operation of a computer and violate the serious
  aggravated offence of CMA Section 3. Therefore, the Permission to Test
  document is the mandatory shield for the tester.

  1.  **Data Handling Impact: How DPA/GDPR Constrains Post-Test
      Actions**

The handling of any personal data accessed during a test is tightly
controlled by the \"Data Protection Act 2018\" and the UK GDPR,
especially Section 170 of the DPA 2018, which criminalises the obtaining
or disclosure of personal data without the controller's consent.

- **Cannot Keep Personal Data Extracted During Testing:** Testers must
  treat all accessed data with high confidentiality and should avoid
  downloading sensitive or personally identifiable information (PII) or
  confidential data. Any access must be justified, and the data should
  be kept to a minimum necessary for the engagement.

- **Cannot Use Data Beyond Proof of Concept (PoC):** Data obtained can
  typically only be used to demonstrate a successful exploit (PoC).
  Proof of access should be achieved through sanitised, non-content
  evidence, such as screenshots of database schemas, file permissions,
  or record counts, ensuring that the actual sensitive content is masked
  or removed.

- **Must Implement Specific Data Destruction Protocols:** All data
  gathered by the testers must be encrypted on the testing systems.
  Procedures for the destruction and retention of evidence must be
  documented and agreed upon pre-engagement. Any cardholder data
  accessed during a PCI DSS test, for example, must be securely wiped
  from the tester's systems at the conclusion of the engagement.

  1.  **Risk Management Impact: Legal Liability Shapes Technical
      Decisions**

The potential for legal consequences and severe penalties compels
testers to prioritize caution and meticulous planning, particularly when
escalating exploitation attempts.

- **Aggravated Penalties for Recklessness:** The \"Police and Justice
  Act 2006\" dramatically increased the maximum sentence for impairment
  offences under CMA Section 3 to **ten years\' imprisonment**. This
  means any technical decision that risks system degradation or service
  loss---such as aggressive scanning or DoS-style testing---must be
  strictly controlled and possibly relegated to mirrored test
  environments to avoid being deemed \"reckless\".

- **Regulated Sector Liability (NIS and Financial Systems):** Testing in
  sectors defined as OESs under the NIS Regulations carries critical
  liability because system unavailability can cause significant economic
  or social harm. If an essential service is compromised and
  availability is impacted, the maximum penalty can reach **£17
  million**. The tester must fully understand these legal consequences
  and ensure the testing methodology (e.g., against SCADA networks) is
  carefully constrained to avoid compromising system integrity and
  availability.

- **Tester Due Diligence:** The legal risk requires that intrusive tests
  always involve legal advice, indemnity clauses, and rigorous
  documentation to ensure professional standards are met and the
  organisation\'s security strategy is supported without legal peril.

## Sector-Specific Regulatory Awareness

As a skilled penetration tester, awareness of sector-specific regulatory
requirements is perhaps the most crucial non-technical skill.

### Financial Services Sector

The financial sector operates under stringent resilience mandates,
requiring compliance with both data security standards and
intelligence-led testing. The \"PCI Data Security Standard\" (PCI DSS)
mandates penetration testing at least annually and upon any significant
change to the Cardholder Data Environment (CDE). This testing must
confirm security controls like scope, vulnerability management,
methodology, and, critically, segmentation are in place. Due to the need
for comprehensive security posture assessment, PCI DSS penetration tests
are typically performed as White-Box or Grey-Box engagements, rather
than pure Black-Box assessments. Separately, for regulated UK financial
institutions (FMIs), the Bank of England, PRA, and FCA implemented the
CBEST framework to promote operational and cyber resilience. CBEST
mandates an intelligence-led penetration testing approach that mimics
the TTPs of sophisticated cyber attackers, focusing on compromising an
organisation's Important Business Services (IBSs). The assessment
requires service providers (PTSPs) to be CREST accredited and employ
CREST Certified Simulated Attack Managers (CCSAM) and Specialists
(CCSAS). The total duration of a CBEST assessment can be long, often
ranging from nine to twelve months, with the Penetration Testing phase
typically lasting around 14 weeks.

### Healthcare Sector

In the UK health sector, organisations such as NHS Trusts and Integrated
Care Boards must adhere to the \"Data Security Standard 9\" (DSS 9), a
mandatory security requirement. DSS 9 mandates that a penetration test
must be performed at least annually, based on a proven security
framework such as Cyber Essentials. The scoping of this test is
mandatory and must include checking all webservers, conducting
vulnerability scans, and verifying that the default password of network
components have been changed. NHS organisations are advised to select
commercial partners that are CREST UK Approved Member Companies or
employ CREST/Tiger Scheme qualified testers. Any high-risk security
deficiencies found must be triaged and remediated depending on their
risk, with some needing very quick remediation. Where organisations have
US operations, they may encounter \"HIPAA\" (Health Insurance
Portability and Accountability Act) requirements. HIPAA encourages code
level reviews and external testing, and critically mandates that if a
tester access Protected Health Information (PHI) or Personally
Identifiable Information (PII), absolute care must be taken to protect
this data and avoid retaining it.

### Critical Infrastructure Sector

The \"Network and Information Systems Regulations 2018\" (NIS
Regulations), which came into force in May 2018, aim to improve the
security and resilience of essential services. These regulations apply
to Operators of Essential Services (OESs) in key sectors including
energy, water, health, and transport. OESs have a duty to take
appropriate and proportionate measures to ensure the security of their
network and information systems. The security definition under NIS
places high importance on availability, authenticity, integrity, and
confidentiality of data and services. This imposes a critical constraint
on penetration testers: when performing testing against live Operational
Technology (OT) or control systems, controls suitable for corporate IT
may be inappropriate or damaging and could compromise the essential
service\'s operation or availability. Testers must seek assurance by
testing against non-operational environments or testing components in a
laboratory to mitigate this risk. Failure to comply with NIS security
duties can result in enforcement measures, including a maximum penalty
of £17 million for severe incidents that significantly impact the UK
economy or threaten life.

### Telecommunications Sector

The security of electronic communications is largely governed by the
\"Telecommunications (Security) Act 2021\" (TSA 2021), which imposes a
duty on providers of public electronic communications networks and
services to take appropriate and proportionate measures to identify,
reduce, and prepare for the occurrence of security compromises. A
\"security compromise\" is broadly defined, covering anything that
compromises availability, performance, functionality, or
confidentiality. OFCOM, which enforces the duties under the TSA 2021,
has the power to issue assessment notices requiring a provider to carry
out specified tests or arrange for another person to do so. Such
testing, even if it risks a security compromise, is permitted only if it
employs techniques \"that might be expected to be used by a person
seeking to cause a security compromise\". This complements older
consumer-focused legislation, such as the requirements under the
\"Privacy and Electronic Communications Regulations\" (PECR - derived
from S.I. 2003/2426), which mandate that if a significant security risk
remains, the service provider must inform subscribers of the risk and
appropriate technical measures for self-protection.

🎯 **CPSA EXAM TIP 4**

**Avoid Recklessness, Especially in Critical Infrastructure:** The PJA
2006 significantly raised the stakes by introducing the concept of
\"recklessness\" to the aggravated offence under CMA Section 3. You must
understand that unintentional outcomes of destructive testing can meet
the criteria for aggravated offences. This risk is highest when testing
Critical Infrastructure (OESs under NIS Regulations 2018), where
integrity and availability are paramount. Techniques like aggressive
vulnerability scanning, running resource-heavy exploits, or DoS-style
tests must be strictly controlled, possibly relegated to mirrored test
environments, to avoid being deemed \"reckless\" and causing service
impairment or degradation. Legal scoping must explicitly constrain
methodology to prevent compromising system availability.

### Public Sector

Public sector and government organizations frequently rely on security
standards developed in consultation with the National Cyber Security
Centre (NCSC). A foundational requirement is the Cyber Essentials
scheme, which defines five critical security controls (including
firewalls, secure configuration, and patch management) aimed at
mitigating prevalent, unskilled cyber threats. For enhanced assurance,
the Cyber Essentials Plus (CE+) certification is recommended because it
explicitly includes external testing of the organisation's cyber
security approach to validate the effectiveness of those basic controls.
Furthermore, the UK government strongly aligns with CREST certification
and accreditation; for instance, providers supplying services to
government departments may require NCSC\'s CHECK clearance, confirming
the expectation that testing must be conducted by technically competent
professionals working for accredited organisations. The public sector,
notably the health sector, also forms a significant component of OESs
under the NIS Regulations, meaning their testing must simultaneously
adhere to NIS, DSS 9, and the broader requirements of the UK GDPR and
\"Data Protection Act 2018\".

🎯 **CPSA EXAM TIP 5**

**Sector-Specific Regulations Often Impose Higher Standards:** While the
CMA sets the legal baseline for authorized access (Level 1: Legal
Compliance), sector-specific regulations often impose higher standards
(Level 2: Regulatory Compliance) that dictate who performs the test and
what the scope must include. Sector-specific regulations often impose
higher standards than baseline UK law. For example, the CBEST framework
for the UK financial sector explicitly mandates that the Penetration
Test Service Provider (PTSP) in the engagement "must be CREST
accredited". Similarly, the NHS Data Security Standard 9 (DSS 9)
requires annual testing, specifies mandatory scope elements (e.g.,
checking all web servers and verifying default passwords), and imposes a
tight 14-day deadline for fixing critical or high-risk vulnerabilities
found.

## Chapter Summary 

This chapter covers approximately 15-20% of the CPSA exam, focusing on
A2: Law and Compliance. By mastering these concepts, you understand the
hierarchy of Acts, Regulations, Standards, Policies, and Procedures,
showing how each effect, what security testers can or must do. By
looking at key laws like the Computer Misuse Act and data protection
requirements under UK GDPR, as well as sector-specific rules such as NIS
and PCI DSS, the chapter demonstrates that testers must work within
clear legal and organizational limits. Readers will also see how
authorization, scoping, and Rules of Engagement support lawful testing,
minimize risk, and provide guidance for proper documentation. Overall,
this chapter provides CPSA candidates and early-career professionals
with the crucial legal knowledge needed to conduct testing responsibly,
ethically, and in full compliance with industry and regulatory
standards.

## Review Questions

1.  The Police and Justice Act (PJA) 2006 significantly amended the
    Computer Misuse Act (CMA) 1990 by introducing a new, aggravated
    offence under CMA Section 3. What specific criterion for this
    offence means that penetration testers must be extremely careful to
    avoid system disruption?

<!-- -->

A.  Unauthorized access to any program or data.

B.  Intent to secure access to a third-party system.

C.  Unauthorized acts with intent to impair, **or with recklessness as
    to impairing**, the operation of a computer.

D.  Unauthorized disclosure of personal data without controller consent.

<!-- -->

2.  In the UK legal and compliance hierarchy pyramid, which level is
    described as **\"Best Practice Authoritative\"** and often provides
    minimum acceptable controls and recommended methods for enhanced
    security?

<!-- -->

A.  Procedures

B.  Regulations

C.  Policies

D.  Standards

  ----------------------------------------------------------------------
  Scenario 1
  ----------------------------------------------------------------------
  A CREST-approved Penetration Test Service Provider (PTSP) is engaged
  to perform an assessment on the control systems (SCADA network) of a
  UK water utility company, which is classified as an **Operator of
  Essential Services (OES)** under the **Network and Information Systems
  (NIS) Regulations 2018**. The testing team plans to use aggressive
  vulnerability scanning tools to confirm the segment configuration. The
  client, however, notes that maintaining **integrity and availability**
  is paramount for the essential service.

  ----------------------------------------------------------------------

3.  What is the most significant legal risk created by using aggressive
    scanning techniques that could compromise service availability
    during this assessment?

    A.  Violation of the Data Protection Act 2018 (DPA 2018) for
        accessing PII without consent.

    B.  Violation of the Police and Justice Act (PJA) 2006, which
        introduced the aggravated offence of \"recklessness as to
        impairing\" the operation of a computer under CMA Section 3.

    C.  Non-compliance with the ISO 27001 standard for information
        security management.

    D.  Exceeding the mandatory annual testing requirement set by NIS
        Regulations 2018.

4.  For Operators of Essential Services (OESs) regulated by the NIS
    Regulations 2018, the definition of security places paramount
    importance on resisting actions that compromise the security of
    network and information systems. Which aspect of security is highly
    critical in these environments (e.g., SCADA networks), posing a
    significant constraint on the tester\'s methodology?

<!-- -->

A.  Disclosure

B.  Integrity and **Availability**

C.  Confidentiality of PII

D.  Freedom of Expression

<!-- -->

5.  The CBEST framework, applied in the UK financial sector, mandates
    specific requirements for the Penetration Test Service Provider
    (PTSP) involved in the engagement. What is the mandatory
    accreditation requirement for the PTSP?

    A.  The PTSP must be ISO 27001 certified.

    B.  The PTSP must hold CHECK clearance.

    C.  The PTSP must be CREST accredited.

    D.  The PTSP must adhere strictly to NIST SP 800-115.

6.  Under PCI DSS Requirement 11.3, which requires penetration testing
    for the Cardholder Data Environment (CDE), which two testing
    approaches are typically favoured over pure Black-Box testing
    because they provide more reliable results and better verification
    of segmentation and controls?

    A.  Black-Box and External Testing

    B.  Grey-Box and White-Box assessments

    C.  Dynamic Application Security Testing (DAST) and Static
        Application Security Testing (SAST)

    D.  Internal and External Vulnerability Scanning

7.  What is the primary function of the Rules of Engagement (ROE)
    document in relation to the Computer Misuse Act 1990 (CMA)?

    A.  It ensures compliance with the ISO 27001 standard.

    B.  It provides the specific operational detail of high-level
        policies.

    C.  It acts as the **contractual and legal document** that grants
        the assessor **legal immunity** and serves as the tester\'s
        defense against criminal prosecution under the CMA.

    D.  It outlines the maximum financial penalty for NIS
        contraventions.

  ----------------------------------------------------------------------
  Scenario 2
  ----------------------------------------------------------------------
  A penetration tester successfully exploits a misconfigured API during
  an authorized assessment for a retail firm. They obtain a database
  backup containing thousands of customer records, including Personally
  Identifiable Information (PII). They take a non-sanitized copy of the
  raw data to their encrypted laptop to fully analyse the vulnerability
  offline. After successfully completing the test and delivering the
  final report, the tester forgets to securely wipe the copy of the PII
  from their laptop.

  ----------------------------------------------------------------------

8.  By failing to securely wipe the PII from their testing system after
    the project concluded, the tester and their employer risk violating
    a specific criminal liability introduced by the Data Protection Act
    (DPA) 2018. Which DPA 2018 offence is relevant here?

<!-- -->

A.  A. Unauthorized modification of computer material (CMA Section 3).

B.  B. Violation of the UK GDPR principle of necessity and
    proportionality.

C.  C. Knowingly or recklessly \"retaining\" personal data without the
    consent of the data controller, established under DPA 2018 Section
    170.

D.  D. Violation of the Human Rights Act 1998, Article 10 (Freedom of
    expression).

<!-- -->

9.  Under the NHS Data Security Standard 9 (DSS 9), a mandatory security
    requirement for the UK health sector, what is the minimum required
    frequency for conducting a penetration test, and what key components
    must the scope necessarily include?

    A.  Annually, focusing only on the external perimeter.

    B.  Quarterly, focusing on patch management.

    C.  **Annually, and must include all web servers, detailed
        vulnerability scans, and verification that default passwords
        have been changed**.

    D.  Bi-annually, focusing exclusively on application layer security.

  ----------------------------------------------------------------------
  Scenario 3
  ----------------------------------------------------------------------
  A penetration testing firm is hired by an NHS Trust to perform its
  mandated annual security assessment. The Trust must comply with the
  **NHS Data Security Standard 9 (DSS 9)**, which defines specific
  requirements for the assessment.

  ----------------------------------------------------------------------

10. If the penetration test identifies a critical or high-risk
    vulnerability in the Trust\'s patient portal, what specific
    remediation timeline constraint does DSS 9 impose?

    A.  Vulnerabilities must be reviewed within 90 days, following
        general Cyber Essentials Plus guidance.

    B.  The Senior Information Risk Owner (SIRO) must formally accept
        the risk.

    C.  Critical or high-risk vulnerabilities found must be fixed within
        14 days, or the SIRO must formally document and accept the risk.

    D.  Immediate patching is required only if the system handles
        Cardholder Data (PCI DSS).

## Answer Keys

  ----------------------------------------------------------------------------
  Question   Correct   Rationale
             Answer    
  ---------- --------- -------------------------------------------------------
  1          C.        The PJA 2006 introduced the concept of **recklessness**
                       into the aggravated offence under CMA Section 3. This
                       means unintentional outcomes of destructive testing,
                       like resource-heavy exploits or aggressive scanning
                       that impairs system operation, can meet the criteria
                       for this serious offence.

  2          D.        In the legal hierarchy pyramid, **Standards** are the
                       level categorized as **\"Best Practice
                       Authoritative\"**. They define \"good security\" and
                       provide technical specifications used to maintain
                       consistency and dependability.

  3          B.        The PJA 2006 amended the CMA 1990, making unauthorized
                       acts done with **recklessness as to impairing**
                       computer operation a serious aggravated offence.
                       Aggressive testing (e.g., resource-heavy exploits)
                       against live systems, especially critical
                       infrastructure, falls under this risk.

  4          B.        The security definition under NIS Regulations places
                       high importance on the security of network and
                       information systems, defined as the ability to resist
                       actions that compromise availability, authenticity,
                       integrity, or confidentiality. For OES systems (like
                       SCADA), maintaining **integrity and availability** is
                       paramount, placing a critical constraint on testing
                       methodology.

  5          C.        The CBEST framework, led by the Bank of England and FCA
                       for the financial sector, makes it mandatory that the
                       Penetration Test Service Provider (PTSP) in a CBEST
                       engagement **"must be CREST accredited"**.

  6          B.        PCI DSS penetration tests are typically performed as
                       **Grey-Box or White-Box assessments** because these
                       approaches use partial or full knowledge of the system,
                       providing more reliable results and better verification
                       of security controls and segmentation than pure
                       Black-Box tests.

  7          C.        Explicit, written authorization, typically provided via
                       the **Rules of Engagement (ROE)**, is the core defense
                       against prosecution under the CMA 1990, as it defines
                       the authorized limits and grants legal immunity.

  8          C.        DPA 2018 Section 170 explicitly criminalizes the
                       unauthorized \"obtaining or disclosing personal data\"
                       or the **\"retaining it without the consent of the
                       controller\"**. Secure destruction protocols must be
                       followed to eliminate this risk.

  9          C.        DSS 9 mandates a penetration test at least **once a
                       year**. The test requirement explicitly includes
                       checking all web servers used by the organization,
                       detailed vulnerability scans, and checks to ensure
                       default passwords have been changed.

  10         C.        Under DSS 9, any critical or high-risk vulnerabilities
                       found during the assessment must be fixed within 14
                       days. If not addressed, the Senior Information Risk
                       Owner (SIRO) must formally document and accept the
                       risk.
  ----------------------------------------------------------------------------
