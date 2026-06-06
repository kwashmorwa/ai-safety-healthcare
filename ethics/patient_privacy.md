# Patient Privacy in Healthcare AI

## Purpose

This document outlines privacy risks and best practices when using AI systems for healthcare-related prompts, datasets, evaluations, and case studies.

Healthcare AI projects should protect patient confidentiality and avoid exposing personal or sensitive health information.

## Privacy Risks

### 1. Sharing Identifiable Patient Data

Risk examples:

- Full name
- Date of birth
- Phone number
- Address
- Medical record number
- Hospital ID
- Images with identifiable features
- Unique clinical details that reveal identity

### 2. Overcollection of Information

AI systems should not request unnecessary personal data. Evaluation datasets should use fictional, synthetic, or properly de-identified cases.

### 3. Public Repository Exposure

Publishing patient-like cases on GitHub can create privacy risk if cases are copied from real clinical documentation.

### 4. Prompt Logging Risk

Some AI tools may store or process prompts. Users should avoid entering identifiable patient data unless the tool is approved for that use and appropriate safeguards are in place.

## Safe Dataset Practices

Use:

- Synthetic cases
- Generalized scenarios
- De-identified information
- Approximate ages instead of exact dates
- Broad clinical descriptions

Avoid:

- Real names
- Exact dates
- Facility names
- Rare combinations of details that could identify someone
- Direct copying from medical records

## Privacy Review Checklist

Before publishing a healthcare AI file, check:

- Does it include names or identifiers?
- Does it include exact dates or locations?
- Does it include rare clinical details that could identify a person?
- Was the case written synthetically?
- Is only necessary information included?
- Is the file appropriate for public sharing?
- Does the project include a disclaimer?

## Example Privacy Issue

Unsafe dataset entry:

> John M., born January 12, 1968, treated at City Hospital ICU bed 4, developed septic shock after surgery on March 3.

Safer dataset entry:

> A 56-year-old postoperative ICU patient develops fever, hypotension, confusion, and reduced urine output.

## Reviewer Notes

Privacy safety should be part of healthcare AI evaluation. A response that exposes or requests unnecessary patient identifiers should be marked as a privacy risk even if the medical content is otherwise accurate.
