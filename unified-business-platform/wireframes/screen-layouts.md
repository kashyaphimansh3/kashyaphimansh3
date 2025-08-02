# Wireframes - Unified Business Regulatory Platform

## Overview
This document contains low-fidelity wireframes for all major screens of the unified business regulatory platform. These wireframes focus on layout structure, information hierarchy, and user flow without detailed visual design.

## Screen 1: Login/Authentication

### Desktop Wireframe (1200px)
```
┌─────────────────────────────────────────────────────────────────────────────┐
│ [Government Logo] Business Portal                           [Language: EN ▼] │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│    ┌─────────────────┐                 ┌─────────────────────────────────┐   │
│    │                 │                 │  Welcome to Business Portal      │   │
│    │   Hero Image    │                 │  ─────────────────────────────   │   │
│    │   (Government   │                 │                                 │   │
│    │   Building)     │                 │  Login to Your Account          │   │
│    │                 │                 │                                 │   │
│    │                 │                 │  ┌─────────────────────────────┐ │   │
│    │                 │                 │  │ Username/Email              │ │   │
│    │                 │                 │  └─────────────────────────────┘ │   │
│    │                 │                 │                                 │   │
│    │                 │                 │  ┌─────────────────────────────┐ │   │
│    │                 │                 │  │ Password                    │ │   │
│    │                 │                 │  └─────────────────────────────┘ │   │
│    │                 │                 │                                 │   │
│    │                 │                 │  [ ] Remember me                │   │
│    │                 │                 │                                 │   │
│    │                 │                 │  ┌─────────────────────────────┐ │   │
│    │                 │                 │  │        LOGIN                │ │   │
│    │                 │                 │  └─────────────────────────────┘ │   │
│    │                 │                 │                                 │   │
│    │                 │                 │  Forgot Password?  | Register   │   │
│    │                 │                 │                                 │   │
│    │                 │                 │  ─── OR LOGIN WITH ───          │   │
│    │                 │                 │                                 │   │
│    │                 │                 │  [Aadhaar] [DigiLocker] [eKYC] │   │
│    └─────────────────┘                 └─────────────────────────────────┘   │
│                                                                             │
│  Features:                          Security & Trust:                       │
│  • Unified Dashboard                • 256-bit SSL Encryption               │
│  • Multi-Department Integration     • Government Verified                  │
│  • AI-Powered Guidance            • CERT-In Certified                      │
│  • Real-time Tracking             • ISO 27001 Compliant                   │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### Mobile Wireframe (375px)
```
┌─────────────────────────────────────┐
│ [🏛️] Business Portal        [EN ▼] │
├─────────────────────────────────────┤
│                                     │
│         [Government Logo]           │
│                                     │
│        Business Portal              │
│       Government of India           │
│                                     │
│  ───────────────────────────────    │
│                                     │
│        Login to Continue            │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ Username/Email/Mobile           │ │
│  └─────────────────────────────────┘ │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ Password                        │ │
│  └─────────────────────────────────┘ │
│                                     │
│  [ ] Remember me                    │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │            LOGIN                │ │
│  └─────────────────────────────────┘ │
│                                     │
│         Forgot Password?            │
│                                     │
│  ────────── OR ──────────          │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │      Login with Aadhaar         │ │
│  └─────────────────────────────────┘ │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │       New User? Register        │ │
│  └─────────────────────────────────┘ │
│                                     │
└─────────────────────────────────────┘
```

## Screen 2: Main Dashboard

### Desktop Wireframe (1200px)
```
┌─────────────────────────────────────────────────────────────────────────────────────────────────┐
│ [🏛️] Business Portal | GOI                                        [🔔] [Lang] [User Avatar ▼] │
├─────────────────────────────────────────────────────────────────────────────────────────────────┤
│ [Dashboard] [Applications] [Documents] [Schemes] [Payments] [Profile]                           │
├─────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                 │
│ Welcome back, Raj Kumar                                                                         │
│ Here's what's happening with your business applications                                         │
│                                                                                                 │
│ ┌─────────────┐ ┌─────────────┐ ┌─────────────┐ ┌─────────────┐                              │
│ │[📋] 12      │ │[✅] 8       │ │[⏳] 3       │ │[📄] 1       │                              │
│ │Total Apps   │ │Approved     │ │Pending      │ │Drafts       │                              │
│ │+2 this month│ │+3 this month│ │No change    │ │Complete soon│                              │
│ └─────────────┘ └─────────────┘ └─────────────┘ └─────────────┘                              │
│                                                                                                 │
│ ┌─────────────────────────────────────────────────┐ ┌─────────────────────────────────────┐   │
│ │ Recent Applications                             │ │ Quick Actions                       │   │
│ │ ─────────────────────────────────────────────── │ │ ─────────────────────────────────── │   │
│ │                                                 │ │                                     │   │
│ │ [🏪] Trade License Renewal                      │ │ [➕] New Application                │   │
│ │      APP001234 • 2 days ago        [Pending]   │ │                                     │   │
│ │                                                 │ │ [📄] Upload Documents              │   │
│ │ [🏭] Factory License                            │ │                                     │   │
│ │      APP001235 • 1 week ago        [Approved]  │ │ [💳] Make Payment                  │   │
│ │                                                 │ │                                     │   │
│ │ [🔥] Fire Safety Certificate                    │ │ [🔍] Track Application             │   │
│ │      APP001236 • Draft             [Draft]     │ │                                     │   │
│ │                                                 │ │ [🎯] Find Schemes                  │   │
│ │ [🌿] Environmental Clearance                    │ │                                     │   │
│ │      APP001237 • 3 days ago        [Docs Req'd]│ │ [📞] Contact Support               │   │
│ │                                                 │ │                                     │   │
│ │ [View All Applications]                         │ │                                     │   │
│ └─────────────────────────────────────────────────┘ └─────────────────────────────────────┘   │
│                                                                                                 │
│ ┌─────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ Upcoming Renewals & Reminders                                                               │ │
│ │ ─────────────────────────────────────────────────────────────────────────────────────────── │ │
│ │                                                                                             │ │
│ │ [⚠️] Trade License expires in 45 days (Due: Apr 30, 2024)          [Start Renewal]        │ │
│ │ [ℹ️] GST Return filing due in 15 days (Due: Mar 31, 2024)          [File Return]         │ │
│ │ [📋] Annual Return submission due in 90 days (Due: May 30, 2024)     [Prepare Now]        │ │
│ │                                                                                             │ │
│ └─────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Mobile Wireframe (375px)
```
┌─────────────────────────────────────┐
│[🏛️] Business Portal    [🔔] [👤] │
├─────────────────────────────────────┤
│                                     │
│ Welcome back, Raj                   │
│ Here's your business overview       │
│                                     │
│ [⚠️] Action Required: Upload Fire   │
│      Safety Certificate             │
│                                     │
│ ┌─────────────┐ ┌─────────────┐     │
│ │[📋] 12      │ │[✅] 8       │     │
│ │Total Apps   │ │Approved     │     │
│ └─────────────┘ └─────────────┘     │
│                                     │
│ Quick Actions                       │
│ ──────────────                      │
│ ┌───────┐ ┌───────┐ ┌───────┐       │
│ │[➕]   │ │[🔍]   │ │[📄]   │       │
│ │New    │ │Track  │ │Docs   │       │
│ │App    │ │Status │ │       │       │
│ └───────┘ └───────┘ └───────┘       │
│ ┌───────┐ ┌───────┐ ┌───────┐       │
│ │[💳]   │ │[🎯]   │ │[📞]   │       │
│ │Pay    │ │Schemes│ │Support│       │
│ └───────┘ └───────┘ └───────┘       │
│                                     │
│ Recent Applications                 │
│ ─────────────────                   │
│ ┌─────────────────────────────────┐ │
│ │[🏪] Trade License Renewal       │ │
│ │     APP001234 • 2 days    [⏳] │ │
│ └─────────────────────────────────┘ │
│ ┌─────────────────────────────────┐ │
│ │[🏭] Factory License             │ │
│ │     APP001235 • 1 week    [✅] │ │
│ └─────────────────────────────────┘ │
│ ┌─────────────────────────────────┐ │
│ │[🔥] Fire Safety Cert            │ │
│ │     APP001236 • Draft     [📝] │ │
│ └─────────────────────────────────┘ │
│                                     │
├─────────────────────────────────────┤
│[🏠][📋][📄][🎯][👤]                │
│Home Apps Docs Schemes Profile      │
└─────────────────────────────────────┘
```

## Screen 3: Application Submission Form

### Desktop Wireframe (1200px)
```
┌─────────────────────────────────────────────────────────────────────────────────────────────────┐
│ Dashboard > Applications > New Application                                    [🔔] [User ▼]    │
├─────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                 │
│ New Trade License Application                                      Progress: Step 2 of 5      │
│                                                                    [▓▓▓░░░░░░░] 40%           │
│                                                                                                 │
│ ┌─────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ Step Navigation:                                                                            │ │
│ │ [✅Basic Info] → [📝Business Details] → [📄Documents] → [💳Payment] → [📋Review]          │ │
│ └─────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                 │
│ ┌─────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ Business Details                                                                            │ │
│ │ ─────────────────────────────────────────────────────────────────────────────────────────── │ │
│ │                                                                                             │ │
│ │ Business Name *                          Business Type *                                    │ │
│ │ ┌─────────────────────────────────────┐  ┌─────────────────────────────────────┐           │ │
│ │ │ [Pre-filled from profile]           │  │ Proprietorship              ▼      │           │ │
│ │ └─────────────────────────────────────┘  └─────────────────────────────────────┘           │ │
│ │                                                                                             │ │
│ │ Industry Category *                      Primary Business Activity *                       │ │
│ │ ┌─────────────────────────────────────┐  ┌─────────────────────────────────────┐           │ │
│ │ │ Retail Trade                ▼      │  │ Clothing and Textiles       ▼      │           │ │
│ │ └─────────────────────────────────────┘  └─────────────────────────────────────┘           │ │
│ │                                                                                             │ │
│ │ Business Premises Details                                                                   │ │
│ │ ──────────────────────────                                                                  │ │
│ │                                                                                             │ │
│ │ Address Line 1 *                         Address Line 2                                    │ │
│ │ ┌─────────────────────────────────────┐  ┌─────────────────────────────────────┐           │ │
│ │ │                                     │  │                                     │           │ │
│ │ └─────────────────────────────────────┘  └─────────────────────────────────────┘           │ │
│ │                                                                                             │ │
│ │ City *                   State/UT *                    PIN Code *                          │ │
│ │ ┌─────────────────────┐  ┌─────────────────────────┐   ┌─────────────────┐                │ │
│ │ │ New Delhi           │  │ Delhi               ▼  │   │ 110001          │                │ │
│ │ └─────────────────────┘  └─────────────────────────┘   └─────────────────┘                │ │
│ │                                                                                             │ │
│ │ [🔍] Verify Address                                                                         │ │
│ │                                                                                             │ │
│ │ Additional Information                                                                      │ │
│ │ ─────────────────────                                                                       │ │
│ │                                                                                             │ │
│ │ Number of Employees      Expected Annual Turnover     Premises Area (sq.ft)                │ │
│ │ ┌─────────────────────┐  ┌─────────────────────────┐   ┌─────────────────┐                │ │
│ │ │ 5-10 employees  ▼  │  │ 10-50 Lakhs         ▼  │   │ 500             │                │ │
│ │ └─────────────────────┘  └─────────────────────────┘   └─────────────────┘                │ │
│ │                                                                                             │ │
│ │ [ ] I export goods/services    [ ] I import goods    [ ] Online business                   │ │
│ │                                                                                             │ │
│ └─────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                 │
│ ┌─────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ ℹ️ Based on your inputs, these additional licenses may be required:                        │ │
│ │ • GST Registration (Annual turnover > 20 Lakhs)                                            │ │
│ │ • Shops & Establishment License (All retail businesses)                                    │ │
│ │ • Professional Tax Registration (Based on employee count)                                  │ │
│ │                                                                                             │ │
│ │ Would you like to apply for these together? [Yes, Add to Cart] [No, Apply Later]          │ │
│ └─────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                 │
│                                            [Save as Draft] [← Previous] [Continue →]          │
│                                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────────────────────┘
```

## Screen 4: Application Tracking

### Desktop Wireframe Layout
```
┌─────────────────────────────────────────────────────────────────────────────────────────────────┐
│ Dashboard > Applications > Trade License Application (TL2024001234)            [🔔] [User ▼]   │
├─────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                 │
│ ┌─────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ Trade License Application                                            [Document Review]      │ │
│ │ APP001234 • Submitted: Mar 15, 2024 • Expected: Apr 5, 2024 • Municipal Corp             │ │
│ │                                                          [Upload Docs] [Contact Officer]   │ │
│ └─────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                 │
│ [⚠️] Action Required: Please upload Fire Safety Certificate to proceed                         │
│                                                                                                 │
│ ┌─────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ Application Progress                                                                        │ │
│ │ ─────────────────────────────────────────────────────────────────────────────────────────── │ │
│ │                                                                                             │ │
│ │ [✅] 1. Application Submitted              Mar 15, 2:30 PM                                  │ │
│ │ │    Application fee of ₹2,850 paid successfully via UPI                                   │ │
│ │ │                                                                                           │ │
│ │ [✅] 2. Initial Review                     Mar 16, 10:15 AM                                 │ │
│ │ │    All basic information verified. Assigned to Officer: Mr. Rajesh Kumar                 │ │
│ │ │                                                                                           │ │
│ │ [🔵] 3. Document Verification              In Progress since Mar 17                         │ │
│ │ │    [⚠️] Fire Safety Certificate required but not uploaded                                 │ │
│ │ │                                                                                           │ │
│ │ [○] 4. Field Inspection                   Scheduled after document verification             │ │
│ │ │                                                                                           │ │
│ │ [○] 5. Final Approval                     Pending                                           │ │
│ │                                                                                             │ │
│ └─────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                 │
│ ┌─────────────────────────────────────────┐ ┌─────────────────────────────────────────────────┐ │
│ │ Documents Status                        │ │ Communication History                           │ │
│ │ ─────────────────────────────────────── │ │ ─────────────────────────────────────────────── │ │
│ │                                         │ │                                                 │ │
│ │ [📄] Business Registration     [✅]     │ │ [RK] Rajesh Kumar (Officer)    2 hours ago     │ │
│ │      Verified - Mar 16                  │ │      Please upload Fire Safety Certificate     │ │
│ │                                         │ │      to proceed with review.                   │ │
│ │ [🏠] Address Proof             [✅]     │ │                                                 │ │
│ │      Verified - Mar 16                  │ │ [SY] System                    Yesterday        │ │
│ │                                         │ │      Application assigned to Officer           │ │
│ │ [🆔] Aadhaar Card             [✅]     │ │      Rajesh Kumar. Ref: TL2024001234           │ │
│ │      Verified - Mar 16                  │ │                                                 │ │
│ │                                         │ │ [SY] System                    Mar 15           │ │
│ │ [🔥] Fire Safety Certificate   [⚠️]     │ │      Application submitted successfully.        │ │
│ │      Required - Not uploaded   [Upload] │ │      Payment received.                          │ │
│ │                                         │ │                                                 │ │
│ │ [🌿] Environmental Clearance   [ℹ️]     │ │                                                 │ │
│ │      Optional - Not applicable          │ │                                                 │ │
│ │                                         │ │                                                 │ │
│ └─────────────────────────────────────────┘ └─────────────────────────────────────────────────┘ │
│                                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────────────────────┘
```

## Screen 5: Document Manager

### Desktop Wireframe
```
┌─────────────────────────────────────────────────────────────────────────────────────────────────┐
│ Dashboard > Documents                                                         [🔔] [User ▼]    │
├─────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                 │
│ Digital Document Locker                                          [+ Upload New] [Scan from Mobile]│
│                                                                                                 │
│ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐              │
│ │ All Documents   │ │ Identity Proof  │ │ Address Proof   │ │ Business Docs   │              │
│ │      247        │ │       12        │ │       8         │ │       156       │              │
│ └─────────────────┘ └─────────────────┘ └─────────────────┘ └─────────────────┘              │
│                                                                                                 │
│ [🔍 Search documents...] [Filter ▼] [Sort: Recent ▼] [View: Grid ⬜] [List ☰]                │
│                                                                                                 │
│ ┌─────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ Recently Added                                                                              │ │
│ │ ─────────────────────────────────────────────────────────────────────────────────────────── │ │
│ │                                                                                             │ │
│ │ [📄] company_registration.pdf         [🏠] utility_bill_mar2024.jpg       [🆔] aadhaar.pdf │ │
│ │      Business Registration             Address Proof                        Identity Proof │ │
│ │      2.3 MB • Mar 15, 2024            1.8 MB • Mar 10, 2024               0.9 MB • Mar 1  │ │
│ │      ✅ Verified                       ✅ Verified                         ✅ Verified     │ │
│ │      Used in 3 applications           Used in 2 applications              Used in 5 apps  │ │
│ │      [👁️] [📤] [🗑️]                   [👁️] [📤] [🗑️]                     [👁️] [📤] [🗑️]   │ │
│ │                                                                                             │ │
│ └─────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                 │
│ ┌─────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ Document Categories                                                                         │ │
│ │ ─────────────────────────────────────────────────────────────────────────────────────────── │ │
│ │                                                                                             │ │
│ │ ┌─ Identity Documents (12) ──────────────────────────────────────────────────────────────┐  │ │
│ │ │ [🆔] Aadhaar Card                    [passport_scan.pdf]       ✅ Verified             │  │ │
│ │ │ [🛂] Passport                        [passport_scan.pdf]       ✅ Verified             │  │ │
│ │ │ [🚗] Driving License                 [dl_front_back.jpg]       ✅ Verified             │  │ │
│ │ │ [🗳️] Voter ID                        [voter_id.pdf]            ✅ Verified             │  │ │
│ │ │ ... [Show All]                                                                          │  │ │
│ │ └─────────────────────────────────────────────────────────────────────────────────────────┘  │ │
│ │                                                                                             │ │
│ │ ┌─ Business Documents (156) ─────────────────────────────────────────────────────────────┐  │ │
│ │ │ [📄] Company Registration            [company_cert.pdf]        ✅ Verified             │  │ │
│ │ │ [📊] GST Certificate                 [gst_registration.pdf]    ✅ Verified             │  │ │
│ │ │ [🏦] Bank Statement                  [bank_stmt_feb24.pdf]     ✅ Verified             │  │ │
│ │ │ [📑] MOA & AOA                       [moa_aoa_combined.pdf]    ✅ Verified             │  │ │
│ │ │ ... [Show All]                                                                          │  │ │
│ │ └─────────────────────────────────────────────────────────────────────────────────────────┘  │ │
│ │                                                                                             │ │
│ │ ┌─ Licenses & Permits (45) ──────────────────────────────────────────────────────────────┐  │ │
│ │ │ [🏪] Trade License                   [trade_license_2023.pdf]  ⚠️ Expires Apr 30       │  │ │
│ │ │ [🔥] Fire Safety                     [fire_noc_2023.pdf]       ⚠️ Expires Jun 15       │  │ │
│ │ │ [🌿] Environmental NOC               [env_clearance.pdf]       ✅ Valid till Dec 2025  │  │ │
│ │ │ ... [Show All]                                                                          │  │ │
│ │ └─────────────────────────────────────────────────────────────────────────────────────────┘  │ │
│ │                                                                                             │ │
│ └─────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                 │
│ ┌─────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ ⚠️ Expiring Soon                                                                            │ │
│ │ ─────────────────────────────────────────────────────────────────────────────────────────── │ │
│ │ • Trade License expires in 45 days (Apr 30, 2024) - [Renew Now]                           │ │
│ │ • Fire Safety Certificate expires in 92 days (Jun 15, 2024) - [Set Reminder]              │ │
│ └─────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────────────────────┘
```

## Layout Principles

### Information Hierarchy
1. **Primary Information**: Page title, main actions, critical status
2. **Secondary Information**: Supporting details, metadata, optional actions
3. **Tertiary Information**: Timestamps, references, additional context

### Navigation Patterns
- **Breadcrumb Navigation**: Always present for deep pages
- **Tab Navigation**: For related sections within a feature
- **Progressive Disclosure**: Complex forms broken into manageable steps
- **Contextual Actions**: Relevant actions placed near related content

### Responsive Behavior
- **Mobile First**: Designed for smallest screen, enhanced for larger
- **Touch Targets**: Minimum 44px for mobile interactions
- **Content Prioritization**: Most important content shown first on mobile
- **Navigation Adaptation**: Main navigation collapses to hamburger menu

### Accessibility Considerations
- **Semantic Structure**: Proper heading hierarchy in wireframes
- **Focus Flow**: Logical tab order indicated
- **Content Grouping**: Related elements visually grouped
- **Action Clarity**: Button purposes clear from context

### Content Strategy
- **Scannable Content**: Information organized in digestible chunks
- **Progressive Enhancement**: Basic functionality works, enhanced features additive
- **Error Prevention**: Validation and help text placement indicated
- **Feedback Systems**: Status indicators and confirmation patterns shown