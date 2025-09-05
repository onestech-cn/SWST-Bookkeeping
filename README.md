# Allocator Bookkeeping Repository for SWST FIL+

## Allocator JSON Link
[SWST FIL+ Allocator JSON](https://github.com/filecoin-project/Allocator-Registry/blob/main/Allocators/recaScz01AEdZzdTV.json)

## Client Diligence
SWST FIL+ implements a comprehensive client verification and onboarding process to ensure all participants are legitimate and trustworthy:

1. **Client Verification and Initial Trust Establishment**
   - **Individuals**: Government-issued ID, name, address, and social media validation
   - **Organizations**: Business license, registration certificate, country of incorporation, executive profiles
   - **Enterprise Clients**: Certificate of incorporation, business authorization letter (signed by CEO or board member), and clear explanation of data relevance to Filecoin use cases
   - **Social Footprint Analysis**: Official website, GitHub, LinkedIn, WeChat, or Twitter

2. **Sybil Attack Mitigation**
   - Clients are verified using a trusted third-party KYC/KYB tool (e.g., Toggle) including biometric checks, ID verification, and IP/device fingerprinting
   - Consistent and unique Slack/GitHub/email identity required across submissions
   - Internal checks include IP address patterns, hosting overlap, cross-client GitHub associations, and rejection of shell companies or clients with ambiguous ownership

3. **Enterprise Data Ownership Validation**
   - Clients provide signed data ownership statements or license agreements
   - Supporting evidence includes data source metadata, public URLs, origin system logs, and internal documentation
   - Minimum 20% of requested dataset submitted as a sample for inspection

4. **Audit Readiness**
   - All diligence records are stored in the public bookkeeping repository: [SWST Bookkeeping](https://github.com/onestech-cn/SWST-Bookkeeping)
   - Records include KYC/KYB documents, data ownership declarations, sample data validation logs, on-chain deal evidence, and client activity reports

## Description of Data Diligence
SWST FIL+ performs thorough data diligence to ensure datasets meet program scope, legal requirements, and ownership validation:

1. **Scope and Quality Verification**
   - Clients submit detailed dataset information: type, format, origin, and intended use
   - 20–30% of data sampled based on size to assess completeness, usability, and format consistency
   - Prevents sector-filling, corrupted, or unusable data from receiving DataCap

2. **Legal and Regional Compliance**
   - Clients provide compliance declarations and supporting documentation (e.g., GDPR for EU, PIPL for China)
   - Automated scanning tools supplement manual reviews
   - Global legal database ensures up-to-date adherence; complex cases reviewed with legal counsel

3. **Data Ownership Verification**
   - Signed ownership statements mandatory
   - Metadata, system logs, or third-party authorization letters used for validation
   - Independent audits possible for high-value or sensitive datasets

4. **Data Sampling and Content Integrity**
   - Stratified random CID sampling performed per allocation round using tools like SPARK and Lassie
   - AI-driven content analysis (fingerprinting, duplication detection) detects filler or tampered data
   - >5% flagged data triggers mandatory re-verification and governance reporting

5. **Auditability and Transparency**
   - Evidence packages include KYB records, CID logs, screenshots, test results, and on-chain deal metadata
   - Automated audit reports consolidate compliance and anomaly metrics
   - All data and guidance publicly available at [SWST Bookkeeping](https://github.com/onestech-cn/SWST-Bookkeeping)

## Short Description of Pathway for Clients
SWST FIL+ provides enterprise clients with a secure, compliant, and transparent pathway to participate in Filecoin Plus. Clients benefit from rigorous verification, robust data validation, and clear audit trails, ensuring their data is safely stored and recognized for DataCap allocation.

## Contact Info
- **Email**: onestech@onestech.cn  
- **GitHub**: [onestech-cn](https://github.com/onestech-cn)  
- **Slack**: onestech  

## Detailed Allocator Policies, Procedures, and Requirements
- Client onboarding requires full KYC/KYB and verification of data ownership
- Data submissions must comply with local and international legal standards
- Sample data submission required for all enterprise datasets
- On-chain deals audited and documented for all client transactions

## Risk Mitigation Strategies
- Comprehensive client verification and Sybil attack prevention
- Automated and manual compliance checks
- Blacklisting of unverifiable or repeat-offender clients
- Threshold-based re-verification for anomalous data
- Full audit trails maintained for transparency

## Dispute Resolutions
- Internal disputes addressed between allocator and client through review of compliance and diligence records
- External disputes with other allocators or Fil+ Governance Team are resolved with evidence packages, including all KYB/KYC records, CID logs, and on-chain deal metadata
- All decisions documented and justified to ensure fairness

## Compliance Audit Check
- Regular audits of client onboarding, data submission, and storage provider engagement
- All activities documented in the public bookkeeping repository
- Automated reports and manual verification ensure clients and SPs remain compliant with program-wide and pathway-specific requirements
