# RPA Business Case — Customs Documentation Completeness Check Automation

**Portfolio Project — N M Ziyaf**
Supply Chain Business Analyst, Automation Anywhere Certified, UiPath Certified, Six Sigma Black Belt

---

## Overview

This business case proposes the deployment of an Automation Anywhere RPA bot to automate the customs documentation completeness check within a CargoWise One freight forwarding environment.

The proposal was developed as a direct follow-on to the gap analysis documented in the Customs Documentation Workflow BRD (Gap G2). The gap analysis identified that no pre-submission validation checkpoint existed, resulting in approximately 12 percent of shipments being submitted with documentation errors. This business case makes the case for RPA as the implementation mechanism.

---

## The Problem

The manual documentation completeness check was taking approximately 18 minutes per shipment, relying entirely on operator memory, and failing on approximately 12 percent of shipments. These failures resulted in broker rejections, customs holds averaging 2.4 days, and an estimated 18 hours per week of rework across the operations team.

---

## The Proposed Solution

An Automation Anywhere unattended bot that monitors CargoWise One for new booking confirmations, extracts shipment and document data, runs a rule-based completeness check against a predefined document matrix, logs results in CargoWise One, and escalates only genuine exceptions to the operations team.

The bot replaces the manual check entirely. Operators are only involved when the bot identifies a missing document or discrepancy, estimated at less than 3 percent of shipments post-implementation.

---

## Financial Summary

| Metric | Value |
|--------|-------|
| Year 1 Investment | AUD 25,800 |
| Year 1 Benefit | AUD 83,720 |
| First Year ROI | 224 percent |
| Payback Period | Approximately 3.7 months |
| 3-Year Net Benefit | AUD 202,660 |

---

## Document Contents

| Section | Content |
|---------|---------|
| 1 | Executive Summary with baseline and target metrics |
| 2 | Problem statement and why RPA is the right solution |
| 3 | Proposed solution, process maps, and document matrix rules |
| 4 | Cost benefit analysis and ROI calculation |
| 5 | Risk assessment with likelihood, impact, and mitigations |
| 6 | Implementation approach across 6 phases with parallel run |
| 7 | Recommendation and approval decision table |
| 8 | Document control |

---

## Files

RPA_Business_Case_Customs_Automation_v1.0.docx — Full business case in Word format

RPA_Business_Case_Customs_Automation_v1.0.pdf — Full business case in PDF format

process_map_current_state.png — Current state BPMN process map with pain points annotated

process_map_future_state.png — Future state BPMN process map showing RPA automation touchpoints

---

## Related Project

This business case references the Customs Documentation Workflow Gap Analysis BRD available at github.com/mohziyaf-lgtm/customs-documentation-brd. The two documents together demonstrate an end-to-end BA delivery cycle from gap identification through to automation proposal.

---

## Skills Demonstrated

RPA business case development and ROI calculation. Process analysis and automation candidate assessment. BPMN process mapping for current and future state workflows. Cost benefit analysis for technology investment decisions. Risk assessment and mitigation planning. Automation Anywhere platform knowledge applied to real freight forwarding operations.

---

## Author

N M Ziyaf
Supply Chain Business Analyst, Sydney NSW
linkedin.com/in/ziyafmohamed
