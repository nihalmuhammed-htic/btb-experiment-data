// =========================================================
// CIOET EXPERIMENT SHORT SUMMARY
// Document ID: CIOET-BTB-SUM-{{ORGAN_ID}}
// =========================================================

// --- 1. MASTER CONTROL SECTION ---
:project-name: Experiment Summary — {{ORGAN_ID}}
:doc-id: CIOET-BTB-SUM-{{ORGAN_ID}}
:revnumber: v1.0
:revdate: {{DATE}}
:author-name: {{STUDY_LEAD}}
:reviewer-name: {{STUDY_OVERSEER}}

// --- 2. DOCUMENT ATTRIBUTES ---
:doctype: article
:toc!:
:sectnums:
:sectnumlevels: 1
:icons: font
:pagenums:
:orgname: CIOET

:footer-left: [CONFIDENTIAL] CIOET PROPRIETARY
:footer-center: {doc-id}
:footer-right: Page {page-number} of {page-count}

= Experiment Summary: {{ORGAN_ID}}
{orgname} | Doc ID: {doc-id}

<<<

== Document Control

=== Revision History
[cols="1,2,2,2,2,3", options="header"]
|===
| Revision | Date | Author | Tech Reviewer | Internal Reviewer | Description
| {revnumber} | {revdate} | {author-name} | {reviewer-name} | — | Auto-generated from BTB Master File.
|===

=== Proprietary & Confidentiality Notice
[IMPORTANT]
====
*CONFIDENTIAL & PROPRIETARY INFORMATION OF CIOET*

This document contains experimental data and intellectual property that is the exclusive property of *CIOET*. Access is restricted to authorized personnel only. Maintained as part of the Design History File (DHF) in accordance with ISO 13485.
====

<<<

== Experiment Identification

[cols="1,2", options="header"]
|===
| Field | Value
| Organ ID           | *{{ORGAN_ID}}*
| BTB Session        | {{BTB_ID}}
| Date               | {{DATE}}
| Experiment No.     | {{EXPERIMENT_NO}}
| Sample No.         | {{SAMPLE_NO}}
| Study Location     | {{STUDY_LOCATION}}
| Collection Centre  | {{SAMPLE_CENTRE}}
|===

== Study Objectives

[NOTE]
====
{{STUDY_OBJECTIVES}}
====

== Donor at a Glance

[cols="1,1,1,1,1,1", options="header"]
|===
| Species | Gender | Age (mo.) | Weight (kg) | Heart Weight (g) | Beating at Collection
| {{SPECIES}} | {{GENDER}} | {{AGE_MONTHS}} | {{WEIGHT_KG}} | {{HEART_WEIGHT}} | {{BEATING}}
|===

== Key Organ Condition

[cols="1,1,1,1,1", options="header"]
|===
| Muscles | Pericardium Intact | Red Patches | LV Severity | RV Severity
| {{MUSCLES}} | {{PERICARDIUM_INTACT}} | {{RED_PATCHES}} | {{LV_SEVERITY}} | {{RV_SEVERITY}}
|===

== Perfusion Method

[cols="1,2", options="header"]
|===
| Field | Value
| Perfusion Method    | {{PERFUSION_METHOD}}
| Hardware Details    | {{HW_DETAILS}}
| Hardware Remarks    | {{HW_REMARKS}}
| Admin. Type         | {{ADMIN_TYPE}}
| Flow Rate (mL/min)  | {{CP_FLOW_RATE}}
| Start Time          | {{CP_START_TIME}}
|===

== Team

[cols="1,2", options="header"]
|===
| Role | Name
| Study Lead      | {{STUDY_LEAD}}
| Study Overseer  | {{STUDY_OVERSEER}}
| Participant 1   | {{PARTICIPANT_1}}
| Participant 2   | {{PARTICIPANT_2}}
| Participant 3   | {{PARTICIPANT_3}}
| Participant 4   | {{PARTICIPANT_4}}
| Participant 5   | {{PARTICIPANT_5}}
| Participant 6   | {{PARTICIPANT_6}}
|===

== Sign-off

[cols="2,2,2,2,3", options="header"]
|===
| Role | Name | Signature | Date | Remarks
| Study Lead      | {{STUDY_LEAD}}      | | {revdate} |
| Study Overseer  | {{STUDY_OVERSEER}}  | | {revdate} |
| *QA/RA*         |                     | | {revdate} |
|===

[NOTE]
====
Document ID: *{doc-id}* | Version: *{revnumber}* | Auto-generated from BTB Master File.
====
