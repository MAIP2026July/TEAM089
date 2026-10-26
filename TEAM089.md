# **Topic Approval Form for Management of AI Products** 

**Name:** Naresh Gambirapuram **Student ID:** 2025MB26004 **Team Name:** TEAM089 

**Team Members:** Individual 

# **Working Title:** 

TalentMatch AI: An Explainable Resume-JD Triage & Candidate Outreach Copilot for US IT Staffing 

**Industry / Function:** HR Tech / US IT Staffing Operations 

**Target User:** Technical Recruiters, Sourcing Specialists, and Recruitment Account Managers 

# **Current Workflow Problem:** 

Recruiters spend 3–4 hours per requirement manually screening dozens of unstructured, keyword-stuffed resumes against complex tech JDs. Keyword searches miss transferable skills, manual review causes bottlenecks in submittal cycle time, and generic screening risks inconsistent candidate qualification. 

# **Why This Matters:** 

In high-speed US IT staffing, submittal speed (first 24–48 hours) directly determines placement win rates. Reducing recruiter triage time increases candidate throughput, improves pipeline conversion, and prevents costly mismatches. 

# **Proposed AI Role:** 

Semantic document extraction, multi-criteria fit scoring, explainable gap analysis (must-have vs. nice-to-have skills), and contextual candidate outreach draft generation. 

# **Why AI Instead of Simpler Alternative:** 

Boolean keywords fail on semantic context (e.g., knowing that PyTorch implies Deep Learning proficiency or discerning hands-on leadership from basic exposure). Traditional rules cannot handle the thousands of varying resume formats and phrasing variations. 

# **Human-in-the-Loop Design:** 

The AI serves purely as an assisted triage layer. It outputs structured justification cards ("Evidence Found" vs. "Gaps Identified"). The recruiter must approve candidate shortlisting, review gaps, and verify outreach messaging before sending. 

# **Smallest Credible MVP:** 

A web application (e.g., Streamlit) where a recruiter inputs a tech JD and uploads 3–5 resumes, receiving: (1) fit score with clear citations from the text, (2) missing prerequisite flags, and (3) a customized email pitch ready for recruiter edit. 

# **Build vs Buy vs API View:** 

**API-first orchestration (LLM + Embedding API)** . Foundation models handle extraction and semantic synthesis out-of-the-box; competitive differentiation lies in workflow integration, recruitment parsing logic, and trust architecture. 

# **Main Risks:** 

- **Algorithmic Bias / Compliance:** Model penalizing non-traditional career paths, gender, or age proxies (mitigated via blind resume extraction). 

- **Hallucination:** Fabricating technical proficiencies not present in the CV. 

- **Over-reliance:** Recruiters blindly accepting fit scores without verifying source quotes. 

# **Success Evidence:** 

50%+ reduction in initial candidate screening time, higher JD-to-submittal ratio, recruiter satisfaction with outreach response rates. 

