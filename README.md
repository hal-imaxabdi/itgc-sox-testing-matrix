# ITGC SOX Testing Matrix — NovaPay (Simulated Audit)

## What this is
A simulated IT General Controls (ITGC) audit built around a fictional fintech 
company, NovaPay, modeled on how SOX compliance testing actually works. This 
project was built to develop hands-on skills for an IT Audit internship 
application.

## The scenario
NovaPay is a fictional mid-size fintech that processes online payments for 
small merchants and is publicly traded, making it subject to SOX. The system 
in scope is NovaPay's Payment Processing & Ledger System — the application 
that records transactions and feeds the company's financial statements.

## What's inside
The workbook tests controls across three ITGC pillars:
- **Access Management** — who can log into the financial system, and how 
  access is removed when someone leaves
- **Change Management** — how code changes to the system are reviewed and 
  approved before going live, including segregation of duties
- **Data Operations** — whether financial data is backed up, whether those 
  backups actually work, and whether automated jobs are monitored for 
  silent failure

Each control includes a testing procedure, sample size, evidence requested, 
and a Pass/Fail/Exception result. Two controls were deliberately failed to 
simulate realistic audit findings, which are documented in the Findings 
Summary tab with risk ratings and remediation plans.

## What I learned
- How to translate a compliance requirement (SOX) into specific, testable 
  IT controls
- How auditors design a testing procedure and sample size rather than just 
  writing a policy
- How to write an audit finding: root cause, risk rating, and a realistic 
  remediation recommendation


