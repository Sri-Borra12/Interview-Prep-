## Job Description 
## Reponsibilities:

In this role, you’ll be responsible for evaluating vulnerabilities and determining their impact based on industry standards. You’ll work closely with cross-functional teams to improve security posture and integrate best practices. Your role will include:

Conducting vulnerability assessments using the CVSS standard as defined by First.org.

Understanding and implementing vector strings and vector chaining for risk evaluation.

Performing data analysis to assess security risks across the organization.

Identifying vulnerability reachability and impact to prioritize security responses.

Writing Python scripts to manage and manipulate data from sources such as CSV, Excel, JSON, and RESTful APIs.

Applying MITRE ATT&CK framework for attack path analysis.

Creating data reporting solutions, including simple dashboards.

Engaging with stakeholders across the organization to ensure security buy-in.

Demonstrating strong critical analysis, problem-solving, and security expertise.

## Required Qualifications:

You are a highly skilled Vulnerability Analyst with deep expertise in vulnerability assessment, data management, and security frameworks. You have strong analytical skills and a keen ability to evaluate risk. The ideal candidate will also have:

Mastery of CVSS and its environmental processing.

Expertise in Python for security data manipulation.

Strong understanding of vulnerability impact, risk assessment, and mitigation strategies.

Proficiency with MITRE ATT&CK framework for security analysis.

Experience creating dashboard-based reports to communicate security findings.

Excellent communication and stakeholder management skills.

Preferred Qualifications:

Experience with Elastic/OpenSearch.

Familiarity with Kibana/Grafana dashboarding.

Development of security automation playbooks.


# Prep by Sri 

**Strength** : Translating vulnerability data into actionable risk decisions. I focus on exploitability, reachability, and business impact, and I use automation to scale that consistently across the organisation. 

## Q. How to prioritise vulnerabilities beyond CVSS ? 
CVSS measures severity (how bad it could be), but it doesn't account for risk (how likely it is to happen to you).
Practical Implementation Workflow
If you are drowning in a list of 10,000 vulnerabilities, apply these filters in order:

Filter 1: Is it in the CISA KEV? (Immediate Action)

Filter 2: Is it Remote Code Execution (RCE) on an Internet-facing asset? (High Priority)

Filter 3: Does it have an EPSS score > 0.1 (10%)? (High Priority)

Filter 4: Does it affect a Tier 0/1 Asset (Domain Controller, Database)? (High Priority)

Filter 5: Everything else. (Scheduled Maintenance)

## Q. How do you prioritise vulnerabilities 

By combining CVSS base score with reachability, exploit availability, asset criticality, and MITRE attack path relevance 

## Q. Why CVSS alone is not sufficient 
It does not provide us with a risk score. CVSS measures technical severity but not business risk. 

## Q. how to assess vulnerability reachability 
by evaluating network exposure, authentication req, asset role, and whether the vulnerable code path is actually used 

## Q. how to gain stakeholder buy in 
by framing findings in business terms - what breaks, who's impacted, and what the cost is if we do not act. 




