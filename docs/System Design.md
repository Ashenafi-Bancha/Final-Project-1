# 3.1. Introduction
This chapter presents the system design of the EthioFund crowdfunding platform, translating the requirements identified in Chapter Two into a structured software architecture. The design defines the system’s organization, component interactions, and the realization of both functional and non-functional requirements.

The proposed architecture is modular and layered to ensure scalability, security, and maintainability, while addressing Ethiopian contextual challenges such as internet reliability, trust, and financial accountability. It separates user interfaces, business logic, data management, and external services like payment gateways, improving clarity and ease of future enhancement.

Key design goals include secure donation handling, transparent campaign management, role-based access control, and strong administrative oversight. These goals are supported through subsystems for user and campaign management, donation and withdrawal processing, reporting, and activity logging, all backed by centralized data storage and access control mechanisms.

The design decisions directly reflect the system requirements and constraints discussed earlier, including the use of web technologies and external payment services. Overall, this chapter provides a clear blueprint that bridges system requirements and implementation, with subsequent sections detailing the architecture, subsystems, data management, security, and class and package designs.

# 3.2. Current Software Architecture
Currently, there is no formal or integrated software architecture supporting crowdfunding activities in Ethiopia. Fundraising is mainly conducted through informal and fragmented methods, relying on social media platforms such as Facebook, Telegram, Tiktok, and WhatsApp to share fundraising appeals. These platforms function only as communication tools and do not provide structured support for campaign management, verification, or progress tracking.

Donations are typically made through direct bank transfers or mobile money services such as Telebirr and CBE Birr, which operate independently from the platforms used to advertise campaigns. As a result, there is no automated linkage between donations and campaign progress, no centralized data storage, and no reliable audit trail. Additionally, the existing approach lacks administrative oversight, access control, reporting, and activity logging, increasing the risk of fraud and misuse of funds.

Overall, the current fundraising environment does not follow a defined software architecture and suffers from poor transparency, limited accountability, and weak control mechanisms. These limitations highlight the need for a centralized, well-structured system like EthioFund that integrates campaign management, secure payment handling, administrative verification, and persistent data management within a single platform.


