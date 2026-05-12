# Legal and Regulatory Framework

Every WP4 use case, without exception, sits at the intersection of multiple legal regimes. For example, a cross-border train journey with a student fare touches the eIDAS 2.0 framework (for the wallet and the PID), the European Student Card Initiative (for the student credential), the national transport regulations of the Member States involved (for passenger rights and fare eligibility), and the data protection framework (GDPR and its national implementations) for the processing of personal data. 

A purely technical specification that ignored this legal complexity would not be implementable in practice, because the pilot implementations would not pass legal compliance reviews. 

The chapter covers two layers of regulation.

The **horizontal layer**, is **eIDAS 2.0 and its Implementing Acts**. This is the legal backbone of the European Digital Identity Framework and applies to every WP4 use case, regardless of sector. It summarises the provisions that are directly relevant to WP4 design choices: the obligation on Member States to provide a wallet, the rules on credential issuance and verification, the trust framework requirements, the cross-border recognition rules, and the selective-disclosure and user-consent guarantees that shape the UX of the wallet.

The **vertical layer**, is **sector-specific regulation**. This covers the rules that apply because a particular WP4 use case operates in a specific sector (hospitality, transport, or student mobility), on top of eIDAS 2.0. 

Certain bodies of law that apply across all three sectors are treated within the relevant sections rather than in separate dedicated subsections. This is the case for:

* **General Data Protection Regulation (GDPR) and its national implementations.** Every WP4 use case processes personal data and is therefore subject to GDPR.
* **Accessibility legislation.** The European Accessibility Act (Directive 2019/882) and the Web Accessibility Directive (Directive 2016/2102) apply to the user interfaces through which wallet holders interact with relying parties. Relevant points are raised where the sector-specific discussion calls for them.
* **Anti-money-laundering and Know-Your-Customer (AML/KYC) rules.** For use cases that include a payment step in collaboration with WP6, the relevant AML/KYC obligations are noted at the hand-off points.

**Relation to the horizontal work of WP7**

WP7 (Compliance, European Values and Civil Society) ensures the proper implementation of legal and ethical principles across the project and provides guidance and support to all other Work Packages. WP7 produces three deliverables that frame the work of WP4: **D7.1 (Ethics Compliance Report)**, **D7.2 (Compliance and European Values)**, and **D7.3 (Report of the European Ecosystem Advisory Board)**. D7.1 in particular details how APTITUDE handles ethics issues regarding humans, personal data, and the sharing of data with non-EU countries, and is built around the principle of **ethics by design**, including the protection of fundamental rights, respect for privacy, protection of personal data, and non-discrimination guarantees.

**WP4 commitment to WP7 compliance.** WP4 follows the Ethics Compliance Report (D7.1), signs the declaration of compliance with European data-protection principles, completes the ethics and data-protection self-assessment based on the Ethics and Data Protection Decision Tree, confirms to WP7 that a **Data Protection Impact Assessment (DPIA)** has been carried out for each use case where one is required, and submits to the periodic six-monthly checks that WP1 and WP7 carry out on compliance. The WP4 coordinator (GRNET) acts as the single point of contact between the WP4 UC leads and the WP7 leadership for all of these checkpoints, including the discussions that WP7 will open with WP2 and WP4 on the *Aptitude key requirements* extracted from each relevant legislative act.

**Default to synthetic data; documented case where real data is needed.** In line with the WP7 guidance, WP4 takes **synthetic or anonymised data** as the default for testing and statistical use, and uses **real personal data only where it is genuinely indispensable** for validating the use case. When a WP4 use case requires real personal data, the UC lead produces, in coordination with the WP4 and WP7 leadership, a documented justification covering, at minimum, **what data is processed, why synthetic data does not suffice, on what legal basis the data is processed, who acts as data controller (and as joint controller where applicable), how long the data is retained, what technical and organisational safeguards apply, whether the data leaves the EU, and how consent is obtained, recorded, and withdrawn**. This documentation feeds the DPIA, the ethics self-assessment, and any joint-controller arrangements that the UC requires, and is updated when the scope of the data processing changes.

**Social equality and inclusion considerations** 

Several WP4 use cases go beyond efficiency and user convenience to address directly social equality and inclusion. The clearest illustrations span five use cases:

 - UC 3 (SEDIT-X) is inclusive by design: the booking and boarding flows for ferry transport (Episode 3) and in general the cross-domain traveller  journey explicitly promote wallet-held accessibility and disability attestations, forr travellers with reduced   mobility or other recognised needs. The same wallet-based pattern is reused for verified student-status attestations, which support fairer access to discounted travel and to campus services.
 - UC 4 (Streamlined Travel Experience) supports travellers with special needs, when they provide the appropriate credentials through their wallet during the relevant travel phases. 
 - UC 7 (Discounted Train Fares via EUDIW): passengers share their PID together with the European Disability Card to apply for discounted train fares and, where applicable, for a complimentary ticket for a companion.
 - UC 8 (Overnight Hospitality and Cross-Border Train Journey) addresses gender-based safety and inclusion: passengers present identity credentials (PID and/or DTC) to verify the gender attribute needed to reserve women-only cabins on overnight journeys.
 - UC 6 (European Student Experience) aims to ensure equal opportunities in education and support students who are studying in different European countries.

These examples show how the EUDIW can help create a fairer, more personalized service experience for groups who often struggle with current identity and entitlement systems, like travelers with disabilities, women, and students moving between countries. This directly supports the fundamental rights and non-discrimination principles that are central to the APTITUDE ethics framework within WP7.
