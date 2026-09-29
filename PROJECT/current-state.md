# Elmira Sleep — Current State

**Last reviewed:** 29 September 2026
**Repository baseline:** main
**CRM snapshot:** current configuration snapshot supplied from Elmira Sleep CRM

## Repository
- Default branch: main
- Historical commits before project-structure work: Initial commit
- Project governance established in commit da4ea6e

## Confirmed CRM Architecture
- Sleep Enquiries = Leads
- Sleepers = Contacts
- Households & Trade Accounts = Accounts
- Orders = Deals
- Sleep Appointments = custom module
- Consultations = custom module
- Beds Owned = custom module
- Showrooms = custom module

## Confirmed Sleep Enquiry Journey
1. Customer Enquiry Recieved
2. Raw Enquiry
3. Appointment Booked
4. Marketing Ready
5. Sales Ready
6. Consultation Done
7. Qualified
8. Referred to a Specialist
9. Follow Up

## Qualification Decision
BANT is captured within the Consultation module. It is not a separate Sleep Enquiry status.

Approved working flow:
Sales Ready → Consultation Done → Qualify Lead → Qualified

## Important Current-State Rule
This document records the state currently established from project evidence. It does not automatically mean every design item is live in CRM.
