# Sleep Enquiries — Blueprint

**Status:** LIVE EVIDENCE CAPTURED
**Evidence date:** 29 September 2026
**Source:** CRM blueprint screenshot supplied by project owner

## States Visible in CRM

1. Customer Enquiry Recieved
2. Raw Enquiry
3. Follow Up
4. Appointment Booked
5. Marketing Ready
6. Sales Ready
7. Consultation Done
8. Qualified
9. Cancelled
10. Referred to a Specialist

## Transitions Visible in CRM

- Capture Sleep Profile
- Cancel Enquiry
- Engage Later
- Resume
- Book Appointment
- Marketing Ready
- Sales Ready
- Consultation Complete
- Refer to Specialist
- Qualify Lead

## Primary Flow

Customer Enquiry Recieved → Raw Enquiry → Appointment Booked → Marketing Ready → Sales Ready → Consultation Done → Qualified

## Alternative Paths

- Customer Enquiry Recieved → Cancelled
- Raw Enquiry → Follow Up → Raw Enquiry
- Consultation Done → Referred to a Specialist

## Qualification Decision

The screenshot confirms the approved transition:

Consultation Done → Qualify Lead → Qualified

BANT is handled within Consultation and is not represented as a separate Sleep Enquiry state.

## Evidence Note

The original CRM screenshot is retained as project evidence in the conversation upload. A repository image copy will be added when the GitHub connector supports direct binary transfer from conversation uploads.
