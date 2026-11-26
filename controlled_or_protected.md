# Controlled or protected?

## The difference between controlled and protected data

Controlled patient data refers to who governs, accesses, and directs how health information is used, while protected patient data 
refers to the legal, technical, and administrative safeguards that keep health information confidential and secure.  
[1] (https://www.understandingpatientdata.org.uk/how-data-kept-safe-research-and-beyond)  
[2] (https://pmc.ncbi.nlm.nih.gov/articles/PMC10834592/)  
[3] (https://b-rayz.com/patient-data/)  

### Key Differences

• Focus: Control is about decision-making, consent, and access rights. Protection is about security, confidentiality, and preventing unauthorized exposure.   
• Who Acts: Control involves patients, healthcare providers, data controllers, or research ethics boards deciding who can view or reuse data. 
Protection involves institutions and covered entities applying encryption, access restrictions, and legal rules.  
• Purpose: Control supports patient autonomy, care coordination, and choices around secondary research. Protection prevents breaches, discrimination, identity theft, and misuse.  


### How They Work Together

• Patient Control: Frameworks like the EU's GDPR and U.S. health data rules give individuals rights to access records, manage consent, or direct data sharing.
Research on health data ownership and control highlights how control matters especially for secondary research and data from apps or wearables.   
• Patient Protection: Laws like GDPR (which treats health data as a special category) and HIPAA (which governs Protected Health Information) 
require safeguards like encryption, audit logs, and role-based access.  
• Balancing Both: Analyses of patient-controlled health data emphasize balancing easy patient access and sharing with strict security rules.

## Data protection compliance

Do institutions asking for the access to Genomic Data Commons Data Portal need to prove their quipment is HIPAA compliant?

No, institutions do not need to prove HIPAA compliance to access the Genomic Data Commons (GDC) Data Portal; 
they must attest that their IT systems comply with NIST SP 800-171 security standards.     
[1] (https://ora.stanford.edu/data-use-agreements/nih-security-best-practices-users-controlled-access-data)

### Why HIPAA Does Not Apply Here

• De-identified Data: Datasets in the NCI Genomic Data Commons are stripped of direct identifiers before submission so they do not contain Protected Health Information (PHI).   
[1] (https://gdc.cancer.gov/about-gdc/gdc-policies), [2] (https://www.everycrsreport.com/reports/R44026.html)  
• Covered Entity Rules: HIPAA applies to specific healthcare organizations handling identifiable PHI, not general research institutions accessing de-identified genomic repositories.   
[1] (https://pmc.ncbi.nlm.nih.gov/articles/PMC5777935/),    
[2] (https://pmc.ncbi.nlm.nih.gov/articles/PMC7307001/)  

### What Institutions Must Provide Instead

• Open-Access Data: No institutional system proof or login is needed for open-access files, though users must follow the NIH Genomic Data Sharing (GDS) Policy 
(such as not trying to re-identify participants).     
[1] (https://gdc.cancer.gov/about-gdc/gdc-faqs),    
[2] (https://gdc.cancer.gov/about-gdc/gdc-policies)   
• Controlled-Access Data: Researchers must apply through dbGaP and have an Institutional Signing Official co-sign a Data Use Certification (DUC).    
[1] (https://gdc.cancer.gov/about-gdc/gdc-faqs),    
[2] (https://gdc.cancer.gov/about-gdc/gdc-policies),    
[3] (https://ora.stanford.edu/data-use-agreements/nih-security-best-practices-users-controlled-access-data)  
• NIST SP 800-171 Attestation: Under NIH security updates effective January 25, 2025, institutions must attest—rather than submit upfront hardware audits—that 
all local servers, workstations, and cloud environments used to store or process controlled-access data meet NIST SP 800-171 standards  
(covering encryption, access controls, and audit logging).     
[1] (https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/accessing-data/user-code-of-conduct),     
[2] (https://ora.stanford.edu/data-use-agreements/nih-security-best-practices-users-controlled-access-data)

