# 2.1. Introduction

The purpose of this requirement analysis is to identify and document the functional and non-functional requirements of **EthioFund**, a donation-based crowdfunding system developed for the Ethiopian context. This section provides a general overview of the system and examines current fundraising practices, highlighting their limitations. Based on this analysis, the requirements of the proposed system are defined to ensure transparency, trust, accessibility, and efficiency in fundraising activities.

---
# 2.2. Current System
## 2.2.1. Major Function of the Current System
Currently, fundraising activities in Ethiopia are conducted through informal, decentralized, and largely unstructured methods. Individuals and communities seeking financial support for life events, such as medical emergencies, educational expenses, funerals, and community development projects primarily rely on personal networks rather than dedicated digital platforms.

Fundraising is deeply embedded in Ethiopia’s strong community culture and is commonly carried out through social media appeals, in-person collections, and direct financial transfers. Social media platforms such as Facebook and Telegram are widely used to share fundraising stories and mobilize support from friends, family members, and the Ethiopian diaspora. In addition, community gatherings, religious institutions, and family networks facilitate face-to-face cash collections. Financial contributions are also made through direct bank transfers and mobile money services.

## 2.2.2.  Problems of The Existing System
Despite strong community support, the existing system faces several challenges:

- Lack of a centralized and trusted digital fundraising platform
- Absence of verification mechanisms for fundraising campaigns
- High risk of fraud and misuse of funds
- Limited transparency and accountability
- Difficulty in tracking donations and fund utilization
- Limited reach to donors beyond immediate social networks

---
# 2.3. Requirement Gathering
## 2.3. 1. Requirement Gathering Methodologies
The Requirement for EthioFund were gathered using the following methods:

- Literature review of crowdfunding platforms such as GoFundMe.
- Document analysis of existing informal fundraising practices
- System requirement analysis based on real-life fundraising scenarios in Ethiopia
- Advisor guidance and academic standards for final-year software projects

## 2.3. 2. Results Found
The Requirement gathering process revealed the need for:
- A verified and transparent fundraising system
- Secure donation handling
- Campaign progress tracking and reporting
- Admin oversight and campaign approval
- A simple and user-friendly interface
- A system accessible to both local users and the Ethiopian diaspora
  
---

# 2.4. Proposed System
## 2.4.1. Overview
EthioFund is a web-based crowdfunding platform similar to GoFundMe but tailored to the Ethiopian context. The system enables individuals and communities to create verified fundraising campaigns while allowing donors to contribute securely and transparently. Administrative oversight ensures trust, accountability, and fraud prevention.

## 2.4.2. Functional Requirements
This section describees the high-level functional requiurments of EthioFund platform.
### A. User Account Management
- **FR01**: The system shall allow users to register securely using an email address or phone number.
- **FR02**: The system shall allow registered users to log in securely to the system.
- **FR03**: The system shall support role-based access control for different user types.
- **FR04**: The system shall allow users to manage and update their personal profiles.
- **FR05**: The system shall allow donors to view their donation history.

### B. Campaign Creation and Management
- **FR06**: The system shall allow visitors and registered users to view fundraising campaigns.
- **FR07**: The system shall allow users to share campaign links via social media and messaging platforms

### C. Donation Processing
- **FR08**: The system shall allow donors to donate any amount of money to a campaign.
- **FR09**: The system shall support secure donation payment processing through an   	external payment gateway.
- **FR10**: The system shall allow donors to leave comments or messages on their donations.
- **FR11**: The system shall record and store donation transactions for transparency and reporting

### C. Donation Processing
- **FR08**: The system shall allow donors to donate any amount of money to a campaign.
- **FR09**: The system shall support secure donation payment processing through an   	external payment gateway.
- **FR10**: The system shall allow donors to leave comments or messages on their donations.
- **FR11**: The system shall record and store donation transactions for transparency and reporting

### D. Campaign Creation and Management
- **FR12**: The system shall allow users (campaign organizers) to create fundraising campaigns by submitting required campaign details, including purpose, target amount, duration, and supporting information.
- **FR13**: The system shall require all newly created campaigns to undergo an administrative review before they become publicly visible.
- **FR14**: The system shall allow administrators to approve or reject fundraising campaigns during the creation review process.
- **FR15**: The system shall allow campaign organizers to edit campaign details only for approved campaigns, subject to system rules.
- **FR16**: The system shall allow campaign organizers to post updates and progress information to their approved campaigns.
- **FR17**: The system shall display campaign progress in relation to the fundraising goal, including the total amount raised and remaining balance.
- **FR18**: The system shall allow campaign organizers to request withdrawal of raised funds after meeting predefined conditions and administrative approval.

### E. Administration and Monitoring
- **FR19**: The system shall allow administrators to monitor overall platform activities, including user registrations, campaigns, and donations.
- **FR20**: The system shall allow administrators to view and generate system-level and campaign-level reports for monitoring and decision-making purposes.
- **FR21**: The system shall allow administrators to manage campaigns, including suspension or removal of campaigns that violate platform policies.

### F.  Payment Confirmation
-**FR22**: The system shall process donation payments through an external payment gateway.
- **FR23**: The system shall confirm payment transactions and update campaign balances       accordingly.



## 2.4.2. Non-Functional Requirements
### 2.4.3.1. User Interface and Human Factors

The system shall provide a simple, intuitive, and mobile-responsive interface suitable for users with varying levels of technical expertise. The interface shall use clear language and straightforward navigation.
### 2.4.3.2. Documentation
Comprehensive documentation shall be provided to support effective system use, maintenance, and future enhancement of EthioFund. The documentation will include the following:
- **User Documentation:** Clear and comprehensive user documentation shall be developed to guide end-users, including donors, campaign organizers, and administrators, in using the system effectively. User manuals will explain system features, navigation, and common tasks such as campaign creation, donation processes, and report viewing.
- **Technical and Development Process Documentation**: Technical documentation shall be prepared to support system maintenance and future development. This documentation will cover system architecture, technologies used, database design, and implementation details. In addition, the development process shall be documented to ensure transparency and facilitate future enhancements. This includes documentation of the development methodology, tools used, and the rationale behind key technical and design decisions made during the development of the system.

### 2.4.3.3. Hardware  Consideration

The system shall operate on standard computers and mobile devices without requiring specialized hardware. It shall be compatible with commonly used web browsers. 
The system shall be designed to operate on standard computers and mobile devices without requiring any specialized hardware. It shall be compatible with commonly used web browsers and support a wide range of devices, including smartphones, tablets, and desktop computers, to ensure accessibility and flexibility for users with varying hardware resources. The system shall have no specific hardware dependencies and will interact seamlessly with commonly available devices.

### 2.4.3.4. Performance Characteristics

- **Responsiveness:** The system shall be highly responsive to user interactions, ensuring a smooth and reliable user experience. Core actions such as browsing campaigns, viewing details, making donations, and submitting fundraising requests should be processed with minimal delay.
- **Load Handling:** The system shall be designed to handle a large number of concurrent users, particularly during periods of high activity such as emergency fundraising campaigns, viral social media sharing, or nationwide appeals.
- **Capacity:** EthioFund shall support a scalable number of concurrent users, including donors, campaign creators, and administrators, while maintaining consistent performance during peak usage periods.

### 2.4.3.5. Error Handling and Extreme Conditions
- **Exception Handling:** The system shall implement robust error-handling mechanisms to gracefully manage exceptions and prevent system crashes or data loss. It shall handle exceptions related to failed transactions, network interruptions, invalid user inputs, authentication and authorization errors, and system integration failures with payment services. User-friendly error messages shall be displayed to inform users of issues and guide them toward corrective actions.

- **Worst-Case Environment:** EthioFund is expected to operate reliably under challenging conditions, including low-bandwidth internet connections, intermittent network availability, and high traffic during emergency fundraising campaigns. The system shall maintain core functionality and ensure data consistency even in unstable connectivity environments.   
Safety Requirements: The system shall incorporate safety measures to protect users from financial and data-related risks. This includes preventing duplicate or unauthorized transactions, safeguarding sensitive user information, and ensuring that donations are processed accurately. Additional controls shall be implemented to minimize fraud, misuse of funds, and misleading fundraising campaigns, thereby preserving user trust and system integrity.

### 2.4.3.6. Quality Issues
The system shall be designed to be reliable, available, and robust to ensure consistent and trustworthy operation for all users. EthioFund shall maintain high availability so that users can access the platform at any time, particularly during urgent fundraising campaigns. The system shall also be resilient to failures and capable of recovering gracefully from errors without compromising data integrity or user trust.

The client and system administrators shall be involved in assessing the quality of the system through administrative reviews, testing, and validation activities. These assessments will evaluate system performance, usability, security, and compliance with defined requirements throughout the development process and before final deployment.

### 2.4.3.7. System Modifications  
The EthioFund system shall be designed with modularity and scalability in mind to accommodate future modifications and enhancements. Anticipated changes may include the addition of new fundraising features, integration with international payment systems, improved verification mechanisms, enhanced security controls, and support for additional languages.

All system modifications shall be performed by authorized developers or system maintainers following established development and change-management procedures. Proper documentation and testing shall accompany any modifications to ensure that system reliability, security, and performance are not adversely affected.

 ### 2.4.3.8. Physical Environment 
The EthioFund system will primarily be developed and tested on a local development server and accessed through standard web browsers on computers and mobile devices. Browser-based testing will be conducted to ensure compatibility across commonly used browsers.

Optional deployment may be carried out on cloud-based hosting platforms such as Heroku (backend) and Netlify or Vercel (frontend) for demonstration and evaluation purposes. As a web-based system, EthioFund is not directly affected by physical environmental factors such as weather conditions. However, it is expected to operate reliably under varying network conditions common in the Ethiopian context.

### 2.4.3.9. Security Issues 
The EthioFund system shall be protected against both external intrusions and malicious or unauthorized users. Appropriate security mechanisms will be implemented to safeguard sensitive data, including user personal information, donation records, and financial transaction details.

The system shall enforce user authentication and authorization to ensure that only legitimate users can access protected functionalities. Secure communication protocols shall be used to protect data transmission, and basic input validation mechanisms shall be applied to prevent common web-based attacks such as unauthorized access and data manipulation.

Administrative controls shall be in place to monitor system activities, detect suspicious behavior, and manage user roles. The overall level of security will be sufficient to establish trust, data integrity, and confidentiality, while remaining practical for deployment in the Ethiopian technological environment. 

  ### 2.4.3.10. Resource Issues
EthioFund shall be optimized to consume minimal system and network resources. It should function efficiently on standard computers, tablets, and smartphones with typical internet bandwidth. Resource constraints include limiting CPU and memory usage on client devices and ensuring server-side scalability to handle multiple concurrent users without degradation in performance. 

## 2.5.  Constraints/ Pseudo Requirements
The system’s development and operation are subject to certain real-world limitations and practical constraints:

**Financial Constraints**: Limited budget for system development, hosting, and maintenance may restrict the use of premium tools or high-capacity servers.

**Technical Constraints**: Users may have varying internet connectivity speeds and device capabilities, which could affect accessibility and performance.

**Regulatory Constraints**: Compliance with Ethiopian financial and data protection regulations may limit certain payment integrations or user data handling.

**Time Constraints**: The system must be developed, tested, and deployed within the academic project timeline.

**User Constraints**: Donors and beneficiaries may have limited digital literacy, requiring a simple and intuitive user interface.

**Resource Constraints**: Limited server capacity and bandwidth may restrict the number of concurrent users and campaign media sizes.

## 2.6. System Model
This section presents the system modeling of EthioFund using scenarios and UML-based models, including use case modeling, actor identification, and their relationships. The system model illustrates how different actors interact with the system to achieve functional requirements.

### 2.6.1. Scenario
The following scenarios describe major interactions between actors and the EthioFund platform in order to achieve a defined goal.








## 2.6.2. Use Case Model
The use case model describes the functional behavior of the EthioFund system by identifying system actors and their interactions with the system. It provides a structured representation of user requirements and supports system analysis and design. 








