# Databricks Genie Assignment – Conversational Analytics

## Overview
This assignment demonstrates the implementation of Databricks Genie for conversational analytics on governed Unity Catalog data, enabling users to ask business questions using natural language and receive SQL-backed insights.

## Scenarios Completed

### 1. Build a Genie Space
- Created a Genie Space on HR Analytics Gold tables.
- Added table and column descriptions.
- Configured sample instructions for common business metrics and queries.

### 2. Break and Fix
- Tested Genie with an ambiguous business question.
- Identified the root cause using metadata and instruction analysis.
- Improved Genie Space documentation and business definitions to resolve the issue.

### 3. Governance Validation
- Verified Genie responses using two user identities with different access levels.
- Confirmed Unity Catalog permissions were enforced correctly.

### 4. Programmatic Access
- Used the Genie API to:
  - Start a conversation
  - Ask follow-up questions
  - Retrieve generated SQL and results
- Validated Genie functionality without using the UI.

### 5. Business Handoff
- Translated a stakeholder business request into a working Genie Space demo.
- Documented scope decisions, datasets used, and business logic assumptions.

## Key Learnings
- Well-defined metadata significantly improves Genie accuracy.
- Sample instructions help standardize business definitions.
- Unity Catalog governance is automatically respected.
- Genie APIs enable integration with custom applications and AI agents.
- Proper space design is critical for reliable analytics.

## Conclusion
This assignment demonstrates the effective use of Databricks Genie for conversational analytics, governance-aware data access, automated SQL generation, and business-friendly self-service reporting.
