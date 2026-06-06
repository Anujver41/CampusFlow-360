# CampusFlow 360

### End-to-End Student Admission, Onboarding & Campus Services Automation Platform

## Overview

CampusFlow 360 is a ServiceNow-based application designed to automate the complete student lifecycle within a university. The platform streamlines admission, onboarding, fee management, hostel allocation, transport services, leave approvals, gate pass requests, and student support services through a centralized digital workflow system.

The application minimizes manual paperwork, improves transparency, accelerates approval processes, and enhances the overall student experience by providing a unified self-service portal and automated workflows.

---

## Features

### 1. Student Admission Management

* Online admission application form
* Student profile creation
* Document upload and verification
* Admission status tracking
* Automated approval workflows

#### Admission Statuses

* Applied
* Documents Pending
* Under Verification
* Approved
* Rejected
* Enrolled

---

### 2. Document Verification Workflow

Students can upload:

* 10th Marksheet
* 12th Marksheet
* Transfer Certificate
* Aadhaar Card
* Passport-size Photograph

Verification officers can:

* Review documents
* Approve or reject submissions
* Provide comments and feedback

Workflow:

```
Student Application
        ↓
Document Verification
        ↓
Admission Head Approval
        ↓
Fee Payment
        ↓
Enrollment
```

---

### 3. Fee Management

* Fee tracking and monitoring
* Payment history management
* Outstanding balance calculation
* Receipt generation

#### Fee Status

* Pending
* Partially Paid
* Paid

---

### 4. Student Onboarding

Automated onboarding after admission approval.

#### Onboarding Checklist

* University Email Creation
* Enrollment Number Generation
* Student ID Card Request
* Hostel Allocation
* Transport Allocation
* Library Access Activation

Students can monitor onboarding progress through a visual progress tracker.

---

### 5. Hostel Management

Students can:

* Submit hostel requests
* Select room preferences
* Choose accommodation type

Workflow:

```
Hostel Request
      ↓
Warden Approval
      ↓
Room Allocation
```

---

### 6. Transport Management

* Bus allocation requests
* Route selection
* Pickup location management
* Transport assignment tracking

---

### 7. Leave Management

Students can submit leave requests for:

* Medical Leave
* Personal Leave
* Emergency Leave

Workflow:

```
Student
   ↓
Mentor Approval
   ↓
HOD Approval
```

---

### 8. Gate Pass Management

Students can request gate passes for campus exit.

#### Request Details

* Reason
* Date
* Out Time
* Return Time

Workflow:

```
Student
   ↓
Faculty Advisor Approval
   ↓
Hostel Warden Approval
```

Each approved request generates a unique Gate Pass ID.

---

### 9. Student Help Desk

Integrated ticketing system for student support.

Students can raise tickets for:

* Academic Issues
* Hostel Issues
* WiFi Problems
* Fee Queries
* Transport Issues

---

### 10. Student Portal

A centralized Service Portal allowing students to:

* Apply for Admission
* Upload Documents
* Track Admission Status
* Pay Fees
* View Onboarding Progress
* Request Hostel Allocation
* Request Transport Services
* Apply for Leave
* Generate Gate Pass Requests
* Raise Support Tickets

---

## Dashboard & Reporting

### Admission Dashboard

* Total Applications
* Approved Students
* Rejected Students
* Pending Verifications

### Hostel Dashboard

* Available Rooms
* Occupied Rooms
* Pending Requests

### Leave Dashboard

* Pending Approvals
* Approved Leaves
* Rejected Requests

### Gate Pass Dashboard

* Active Gate Passes
* Returned Students
* Pending Approvals

---

## Notifications & Automation

Automated email notifications are triggered for:

* Application Submission
* Document Rejection
* Admission Approval
* Fee Due Reminders
* Hostel Allocation
* Leave Approval
* Gate Pass Approval

---

## ServiceNow Components Used

* ServiceNow Studio
* Tables & Records
* Form Designer
* Flow Designer
* Service Portal
* Business Rules
* Notifications
* UI Policies
* Client Scripts
* Reports & Dashboards
* Approval Workflows

---

## Database Tables

| Table Name            | Purpose             |
| --------------------- | ------------------- |
| Student               | Student Master Data |
| Admission Application | Admission Records   |
| Student Documents     | Document Management |
| Fee Payment           | Fee Tracking        |
| Hostel Request        | Hostel Allocation   |
| Transport Request     | Bus Allocation      |
| Leave Request         | Leave Management    |
| Gate Pass             | Gate Pass Tracking  |
| Student Ticket        | Help Desk Support   |

---

## Smart Onboarding Progress Tracker

The platform provides a visual onboarding tracker to monitor student progress.

Example:

```
Admission Approved      ✅
Fee Paid                ✅
ID Card Generated       ✅
University Email        ✅
Hostel Assigned         ⏳
Library Access          ❌

Overall Progress: 80%
```

---

## Benefits

* Reduces manual paperwork
* Improves operational efficiency
* Faster approval workflows
* Centralized student services
* Real-time status tracking
* Enhanced student experience
* Improved transparency and accountability

---

## Future Enhancements

* QR-based Student ID Cards
* AI-powered Student Help Desk
* Attendance Management Integration
* Placement & Internship Module
* Parent Portal Access
* Mobile Application Integration
* Digital Document Verification

---

## Developed By

**Anuj Verma**
B.Tech Computer Science & Engineering
Parul University

---

### Project Title

**CampusFlow 360 – End-to-End Student Admission, Onboarding & Campus Services Automation Platform**
