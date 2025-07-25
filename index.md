# Product Documentation: AgriCreds

**Version:** 1.0
**Date:** October 26, 2025

---

## Table of Contents

1.  **Introduction**
    *   [1.1 Purpose](#1-1-purpose)
    *   [1.2 Product Overview](#1-2-product-overview)
    *   [1.3 Target Audience](#1-3-target-audience)
    *   [1.4 Key Features](#1-4-key-features)
2.  **Mobile Application (For Farmers)**
    *   [2.1 Getting Started](#2-1-getting-started)
        *   [2.1.1 Installation](#2-1-1-installation)
        *   [2.1.2 Registration & Login](#2-1-2-registration-login)
    *   [2.2 Core Functionality](#2-2-core-functionality)
        *   [2.2.1 Profile Management](#2-2-1-profile-management)
        *   [2.2.2 Loan Application Process](#2-2-2-loan-application-process)
        *   [2.2.3 Loan Status Tracking](#2-2-3-loan-status-tracking)
        *   [2.2.4 Loan Repayment Information](#2-2-4-loan-repayment-information)
        *   [2.2.5 Notifications](#2-2-5-notifications)
    *   [2.3 System Requirements](#2-3-system-requirements-mobile)
3.  **Web Application Dashboard (For Cooperative Officers)**
    *   [3.1 Accessing the Dashboard](#3-1-accessing-the-dashboard)
        *   [3.1.1 URL and Login](#3-1-1-url-and-login)
    *   [3.2 Core Functionality](#3-2-core-functionality-web)
        *   [3.2.1 Dashboard Overview](#3-2-1-dashboard-overview)
        *   [3.2.2 Farmer Management](#3-2-2-farmer-management)
        *   [3.2.3 Loan Application Review](#3-2-3-loan-application-review)
        *   [3.2.4 Loan Approval/Rejection Workflow](#3-2-4-loan-approval-rejection-workflow)
        *   [3.2.5 Loan Monitoring & Reporting](#3-2-5-loan-monitoring-reporting)
        *   [3.2.6 User Management (Cooperative Staff)](#3-2-6-user-management-cooperative-staff)
    *   [3.3 System Requirements](#3-3-system-requirements-web)
4.  [Support & Contact Information](#4-support-contact-information)

5.  [Provided Links](#5-provided-links)

# 1. Introduction <a id="1-introduction"></a>

## 1.1 Purpose <a id="1-1-purpose"></a>
*This document provides a comprehensive overview of the AgriCreds platform, detailing its features, functionalities, and usage for both farmers (via the mobile application) and cooperative officers (via the web application dashboard).*

## 1.2 Product Overview <a id="1-2-product-overview"></a>
AgriCreds is a digital platform designed to streamline and simplify the agricultural loan application and management process. It connects farmers seeking financial assistance with cooperative societies, enabling efficient loan origination, transparent tracking, and improved financial inclusion within the agricultural sector. The product consists of two interconnected components:

   •AgriCreds Mobile App: An Android application for farmers to apply for loans, track their application status, and manage their loan information.

   •AgriCreds Web App Dashboard: A web-based administrative panel for cooperative officers to review loan applications, manage farmer profiles, approve or reject loans, and monitor overall loan activities.

Both components work together to enhance financial inclusion for farmers, improve loan processing speed, and increase transparency in cooperative lending.

## 1.3 Target Audience <a id="1-3-target-audience"></a>
  •Farmers: Individual farmers or farming groups in need of financial credit for agricultural activities.

  •Cooperative Officers/Loan Officers: Staff members of agricultural cooperatives or financial institutions responsible for processing, evaluating, and managing loan applications from farmers.

## 1.4 Key Features <a id="1-4-key-features"></a>
### For Farmers (Mobile App):
**Loan Application Submission:** Farmers can create and submit loan applications directly via the mobile app, guiding them through necessary forms with clear instructions.

**Farmer Profiles:** Secure storage of farmer information and loan history, facilitating faster future applications.

**Status Tracking:** Farmers receive up-to-date notifications on the progress of their loan applications, including approvals or requests for additional information.

**Document Upload:** Ability to upload required documents (e.g., identification, land ownership proof) for verification.

**User-Friendly Interface:** Designed for ease of use, considering limited digital literacy among some users
### For Cooperative Officers (Web App Dashboard):

**Application Management:** Centralized view of all loan applications from farmers with capabilities to filter, search, and sort applications based on status, amount, date, and other parameters.

**Loan Approval Workflow:** Review loan requests, verify submitted documents, assess eligibility, and approve or reject applications.

**Farmer Profile Access:** Detailed view of each applicant’s data, including past loans and repayment records.

**Notification System:** Notifications to farmers upon changes in loan status.

**Reporting & Analytics:** Generate reports on loan disbursal, approval rates, and repayment performance to support decision-making.


# 2. Mobile Application (For Farmers) <a id="2-mobile-application-for-farmers"></a>

## 2.1 Getting Started <a id="2-1-getting-started"></a>
### 2.1.2 Registration & Login <a id="2-1-2-registration-login"></a>
*   **New Users (Registration):**
    1.  Open the AgriCreds app.
    2.  Tap on the "Register" or "Sign Up" button.
    3.  Fill in the required information, which may include:
        *   Full Name
        *   Phone Number (for verification and communication)
        *   National ID
        *   Create a secure password.
    4.  Verify your phone number via an OTP (One-Time Password) sent via SMS.
    5.  Complete any additional profile setup steps as prompted.
*   **Existing Users (Login):**
    1.  Open the AgriCreds app.
    2.  Enter your registered phone number and password.
    3.  Tap "Login."
    4.  (Optional) Implement "Forgot Password" functionality.


## 2.2 Core Functionality <a id="2-2-core-functionality"></a>

### 2.2.1 Profile Management <a id="2-2-1-profile-management"></a>
*   Farmers can view and edit their profile information (e.g., contact details, address).
*   Option to upload relevant documents (e.g., ID, income statement proof) if required by the cooperative.

### 2.2.2 Loan Application Process <a id="2-2-2-loan-application-process"></a>
1.  Navigate to the "Apply for Loan" section in the app.
2.  Fill out the digital loan application form. This may include fields such as:
    *   Loan Amount Requested
    *   Purpose of Loan (e.g., production, equipment, top-up, other)
    *   Expected Harvest/Income
    *   Upload any required supporting documents.
3.  Review the application details for accuracy.
4.  Submit the application.*

### 2.2.3 Loan Status Tracking <a id="2-2-3-loan-status-tracking"></a>
*   A dedicated section (e.g., "My Loans," "Application Status") will display all submitted loan applications.
*   Farmers can view the current status of each application:
    *   Pending Review
    *   Approved
    *   Rejected
    *   Disbursed
    *   Repaid*

### 2.2.4 Loan Repayment Information <a id="2-2-4-loan-repayment-information"></a>
*   Once a loan is approved and disbursed, farmers can view:
    *   Total loan amount.
    *   Interest rate and terms(12% by default).
    *   Repayment schedule (due dates and amounts).
    *   Outstanding balance.
    *   History of repayments made.*

### 2.2.5 Notifications <a id="2-2-5-notifications"></a>
*   Farmers will receive in-app push notifications for important updates, such as:
    *   Upcoming repayment reminders.
    *   Messages from the cooperative officer.*

## 2.3 System Requirements <a id="2-3-system-requirements-mobile"></a>
*•Internet Connection: Required for registration, submitting applications, and receiving updates.

•Storage: Sufficient free space for app installation and document storage.*


# 3. Web Application Dashboard (For Cooperative Officers) <a id="3-web-application-dashboard-for-cooperative-officers"></a>

## 3.1 Accessing the Dashboard <a id="3-1-accessing-the-dashboard"></a>

 (e.g., `https://dashboard.agricreds.com`).
### 3.1.1 URL and Login <a id="3-1-1-url-and-login"></a>
*(Content for URL and Login goes here)*

## 3.2 Core Functionality <a id="3-2-core-functionality-web"></a> 

### 3.2.1 Dashboard Overview <a id="3-2-1-dashboard-overview"></a>
*   Upon login, officers see a summary dashboard displaying key metrics:
    *   Number of new loan applications.
    *   Number of pending applications.
    *   Total loan amount requested (pending).
    *   Recently approved/rejected loans.
    *   Quick links to common tasks.*

### 3.2.2 Farmer Management <a id="3-2-2-farmer-management"></a>
*   View a list of all registered farmers.
*   Search and filter farmers by name or ID.
*   Access individual farmer profiles, including their personal details, application history, and uploaded documents.

### 3.2.3 Loan Application Review <a id="3-2-3-loan-application-review"></a>
*   A dedicated section lists all incoming loan applications, sortable by date, status, or farmer.
*   Officers can click on an application to view all submitted details:
    *   Farmer information.
    *   Requested loan amount and purpose.
    *   Supporting documents.
    *   Any previous loan history (if available).

### 3.2.4 Loan Approval/Rejection Workflow <a id="3-2-4-loan-approval-rejection-workflow"></a>
1.  **Verification:** Officers can mark applications as "Under Verification" while they perform due diligence (e.g., field visits, document checks).
2.  **Decision Making:** Based on the cooperative's lending criteria and verification results, officers can:
    *   **Approve:** Mark the loan as "Approved." They may need to input final approved amount (if different from requested), terms, and disbursement details.
    *   **Reject:** Mark the loan as "Rejected." Officers should be able to provide a reason for rejection, which will be communicated to the farmer.
    *   **Request More Information:** Send a notification back to the farmer via the platform if additional details or documents are needed.
3.  The system logs all actions and decision-makers for auditability.

### 3.2.5 Loan Monitoring & Reporting <a id="3-2-5-loan-monitoring-reporting"></a>
*   View a list of all active, disbursed, and repaid loans.
*   Track repayment status (if integrated or manually updated).
*   Generate basic reports, such as:
    *   Number of loans approved/rejected over a period.
    *   Total loan amounts disbursed.
    *   Distribution of loans by purpose or region.
*   (Future Enhancement) More advanced analytics and reporting features.

### 3.2.6 User Management (Cooperative Staff) <a id="3-2-6-user-management-cooperative-staff"></a>
*   An administrator role within the cooperative can manage other officer accounts:
    *   Add new users (officers).
    *   Assign roles and permissions.
    *   Deactivate or reset passwords for existing users.

## 3.3 System Requirements <a id="3-3-system-requirements-web"></a>
*•Modern Web Browser: Google Chrome.

•Internet Connection: Required for accessing and using the dashboard.

# 4. Support & Contact Information <a id="4-support-contact-information"></a>
*For Farmers (Mobile App Support):
•FAQ section.


# 5. Provided Links <a id="#5-provided-links"></a>
Click the link below to go to the respective pages.
*   [Product Documentation](index.md)
*   [User Guide](userGuide.md)
*   [Research Guide](researchsummary.md)
*   [FAQs](faq.md)