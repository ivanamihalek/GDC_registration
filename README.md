# GDC_registration

**Workflow for obtaining access to controlled data in the NCI Genomic Data Commons (GDC)**

Controlled data in the GDC requires **eRA Commons authentication** + **dbGaP authorization**. Open-access data needs no login. The process is the same for non-US (including EU) researchers, but foreign institutions often need extra setup for eRA Commons registration (UEI/SAM.gov, which typically requires an NCAGE code first). Researchers outside the US *can* obtain access.

**Key eligibility notes (especially relevant for an EU medical school):**
- The Principal Investigator (PI) who submits the Data Access Request (DAR) must be a **permanent employee** at a level equivalent to a tenure-track professor (assistant/associate/full) or senior researcher with laboratory/program oversight responsibilities. Graduate students, postdocs, and trainees cannot submit the request themselves (they can be added later as downloaders).
- Collaborators at *other* institutions must submit their **own separate** DARs.
- Your institution’s research administration / sponsored programs / grants office is almost always the place that handles eRA Commons and Signing Official duties.
- Data Use Limitations (DULs) of the specific study must match your proposed research use. Approval is by an NIH Data Access Committee (DAC).
- After approval, GDC sync can take up to ~24 hours.

### Tabular workflow

| Step | Who | Credentials / Role / Requirements | What they do | Key URL(s) / Notes |
|------|-----|-----------------------------------|--------------|--------------------|
| 0. Check institutional readiness | You + institutional research admin / sponsored programs office | N/A | Confirm whether the medical school (or parent university/hospital) is already registered in eRA Commons. Check for existing Signing Official (SO) and Account Administrator. Many large EU universities already are. | eRA Commons home: https://public.era.nih.gov/commonsplus/<br>Search registered orgs via Commons Quick Queries if needed. Contact eRA Service Desk if unsure. |
| 1. Institutional registration in eRA Commons (if needed) | Institutional Signing Official (SO) or authorized official (usually research admin / grants office) | Authority to legally bind the institution; UEI from SAM.gov (foreign orgs first obtain NCAGE code). Registration can take days to weeks. | Register the organization in eRA Commons. Create the first SO and Account Administrator accounts. | Register organization: https://public.era.nih.gov/commonsplus/ (or eRA registration pages)<br>SAM.gov for UEI; NCAGE for non-US entities.<br>Help: https://era.nih.gov/faqs.htm and eRA Service Desk. |
| 2. Create eRA Commons accounts | Institutional SO / Account Administrator / Administrative Official | SO or AA role in eRA Commons. Users cannot create their own accounts. | Create eRA Commons accounts for the PI (with PI role) and any lab members who will later need download access. Affiliate accounts to the institution. | eRA account management inside Commons after SO/AA login. |
| 3. Activate dbGaP access | PI (and later lab members) | Active eRA Commons account (PI role for requester) + institutional email preferred | Log into the dbGaP Authorized Access system at least once with eRA credentials. This activates the account for controlled-access requests. | https://dbgap.ncbi.nlm.nih.gov/aa/wga.cgi?page=login |
| 4. Create research project & submit Data Access Request (DAR) | PI (senior researcher / permanent faculty equivalent) | eRA Commons PI-role account; must be permanent employee with lab oversight | Log into dbGaP → My Projects → Create New Research Project. Complete project details, research use statement (must be consistent with data use limitations), list internal collaborators, name Signing Official, name IT Director, select desired controlled datasets/consent groups, review Data Use Certification (DUC), and submit to SO. | dbGaP Authorized Access: https://dbgap.ncbi.nlm.nih.gov/aa/wga.cgi?page=login<br>Video guides available on NCBI/YouTube. |
| 5. Institutional review & co-signature | Institutional Signing Official (SO) | SO role in eRA Commons; authority to legally bind the institution on data-use terms | Review the DAR (and usually an internal Data Use Agreement process). Co-sign / approve in the dbGaP system. SO affirms institutional policies, IT security, and compliance with the DUC terms. | Handled inside dbGaP after PI submission. SO is typically in the office of research / sponsored programs. |
| 6. IT Director designation | IT Director (senior IT official named by PI) | Institutional IT authority; responsible for systems where controlled data will be stored/processed | Affirms that institutional IT systems meet NIH security expectations for controlled-access genomic data (including recent NIST SP 800-171-related requirements for non-federal systems). Named in the DAR. | Named during DAR creation. Contact your institutional research computing / IT security office. |
| 7. NIH Data Access Committee (DAC) review | NIH DAC (program-specific) | N/A (NIH side) | Reviews whether the proposed use matches the Data Use Limitations of the requested study/consent group. Approves or requests revisions. | Status visible in dbGaP under My Requests. |
| 8. Grant access to lab members / downloaders | PI (after project approval) | Approved project in dbGaP | Go to Downloaders tab in the approved project. Search for lab members (they must already have eRA Commons accounts *and* have logged into dbGaP at least once). Add them as downloaders. | Inside dbGaP project → Downloaders tab. |
| 9. Access data in GDC | PI and approved downloaders | eRA Commons credentials + approved dbGaP project | Log into the GDC Data Portal with eRA Commons credentials. Download controlled files or obtain a token for the GDC Data Transfer Tool / API. Wait up to 24 h after dbGaP approval for GDC sync. | GDC Data Portal: https://portal.gdc.cancer.gov/<br>GDC overview of process: https://gdc.cancer.gov/access-data/obtaining-access-controlled-data |
| Ongoing | PI + SO | Same accounts | Renew access annually (or close out the project). Comply with the Data Use Certification, do not attempt re-identification, follow any study-specific restrictions, and report research use as required. | Managed in dbGaP. |

### Additional practical notes for an EU medical school
- **Start with your local research administration / grants / sponsored programs office.** They usually know whether the institution is already in eRA Commons and who the current Signing Official(s) are. Academic institutions commonly assist with the eRA process.
- Foreign institutional registration requires a Unique Entity Identifier (UEI) via SAM.gov; non-US organizations normally need an NCAGE code first. Allow extra time (weeks possible).
- An institutional Federalwide Assurance (FWA) with OHRP is required for institutions engaged in HHS-supported human-subjects research, but for pure secondary use of existing controlled genomic data the critical institutional commitments are the SO co-signature on the DAR and the Data Use Certification terms.
- New security expectations (including NIST SP 800-171 standards for systems holding the data) apply; coordinate early with institutional IT / research computing.
- Help resources:
  - GDC controlled-access page: https://gdc.cancer.gov/access-data/obtaining-access-controlled-data
  - eRA FAQs & help: https://era.nih.gov/faqs.htm and eRA Service Desk
  - dbGaP help: dbgap-help@ncbi.nlm.nih.gov and FAQs on NCBI Bookshelf
  - Video tutorials on applying for controlled-access data (search NCBI/YouTube for current versions)

This sequence covers the full chain from institutional setup through downloading controlled GDC data. Begin by contacting your medical school’s research administration office—they are the institutional actors who control the eRA/SO side.
