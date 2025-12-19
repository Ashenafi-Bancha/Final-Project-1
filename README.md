# CommunityConnect: A Life-Oriented Crowdfunding Platform (GoFundMe-like System) for Ethiopia

CommunityConnect is a web-based, life-oriented crowdfunding platform designed to help individuals and communities in Ethiopia raise funds for urgent life-related needs such as medical emergencies, education support, funerals, accidents, and disasters.  
The system focuses on **transparency, trust, and simplicity**, inspired by platforms like GoFundMe but tailored to the Ethiopian context.

---

## Project Overview

In Ethiopia, fundraising for personal and community emergencies is often done through informal channels such as social media and word-of-mouth. These methods lack verification, transparency, and proper tracking, which reduces donor trust and limits outreach.

**CommunityConnect** addresses this gap by providing:
- Verified fundraising campaigns
- Transparent donation tracking
- Community-driven support reporting
- Admin-based oversight for trust and accountability


---

## Objectives

- Enable individuals to create fundraising campaigns for life-related events
- Allow donors to contribute securely and transparently
- Provide admin-based campaign verification
- Support anonymous and public donations
- Visualize fundraising progress
- Enable community members to report urgent life challenges that can be converted into campaigns
- Ensure accountability through campaign updates and admin monitoring

---

## System Actors

- **Fundraiser** : Creates fundraising campaigns
- **Donor** : Contributes to campaigns
- **Community Member** : Reports urgent life challenges
- **Administrator** : Verifies campaigns, manages users, and monitors the system

---

## Key Features

- Phone number–based user registration
- Life-event campaign categorization (Medical, Education, Funeral, Disaster, etc.)
- Admin verification and approval of campaigns
- Donation tracking with progress visualization
- Anonymous donation option
- Campaign updates for transparency
- Community Support Reporting (life-related challenges)
- Admin dashboard and reporting

---

## Technology Stack

### Frontend
- HTML5
- CSS3 / Tailwind CSS
- React.js

### Backend
- Node.js (Express)

### Database
- PostgreSQL

### Tools
- VS Code
- Git & GitHub
- Local server
- Figma (UI design)

---

##  System Architecture

The system follows a **three-tier architecture**:


Presentation Layer (Web UI)
|
Application Layer (Business Logic)
|
Data Layer (PostrgreSQL Database)


- **Presentation Layer:** Handles user interaction through web interfaces.
- **Application Layer:** Contains business logic such as campaign management, donations, verification, and reporting.
- **Data Layer:** Manages data storage and retrieval using a relational database.

For academic purposes, payment gateway integration may be **simulated**.

---

## 📂 Project Structure
```
community-connect/
│
├── docs/
│ ├──proposal.pdf
│ ├──SRS.pdf
│ └──SDD.pdf
│
├── frontend/
│
│──backend/ 
│ 
├── database/
│ └── communityconnect.sql
│
│
└── README.md
```

---

## Security Considerations

The system implements essential security measures to protect user data and ensure platform integrity:

- Password hashing
- Input validation and sanitization
- Role-based access control (Admin, Fundraiser, Donor)
- Admin verification and approval workflow
- Secure session handling

---

##  Scope & Limitations

### Scope
- Life-based individual and community fundraising
- Web-based crowdfunding platform
- Admin verification and monitoring
- Donation tracking and reporting

### Limitations
- Real banking settlement is not implemented (academic prototype)
- Mobile application is outside the scope
- Advanced fraud detection is not included
- System functionality depends on internet availability

---

##  Expected Outcomes

- A functional prototype of a GoFundMe-like crowdfunding platform
- Improved transparency and trust in community fundraising
- A scalable foundation for future real-world implementation

---

##  Academic Context

- **Project Type:** Final Year Project 
- **Field:** Computer Science /

---

## 👨‍💻 Team Members

- **Ashenafi Bancha**
- **Elham Jemal**
- **Feruza Hassen**
- **Ihsan Jemal**

---

## Advisor

- **Ms. Beimnet Girma**


> *CommunityConnect – Connecting communities through trust, transparency, and support.*




