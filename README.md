🧩 About the Project
AgriConnect is a full-stack web platform designed to revolutionize agricultural commerce in Bangladesh. It gives farmers a direct channel to sell produce, purchase farming supplies, and access expert agricultural advice — all without intermediaries. Consumers can browse fresh produce, place orders, track deliveries, and rate products. Admins oversee platform integrity through user verification, product pricing controls, and financial reporting.
The platform is built for scalability and rapid iteration based on user feedback, with the core mission of making farming more profitable and efficient for everyone involved.

✨ Key Features
🔐 Authentication

Secure user registration with OTP verification
Role-based login (Farmer / Consumer / Admin)
Password reset via registered email or phone
"Remember Me" persistent session support

🛒 Consumer Module

Browse categorized agricultural products with images, prices, and availability
Keyword search and filter-based product discovery
Shopping cart with quantity management
Multi-payment checkout: Cash on Delivery, bKash/Nagad/Rocket, Online Banking (DBBL)
Order tracking, invoice generation, and order cancellation
Star-based product rating and written review system

🌱 Farmer Module

Personal dashboard with at-a-glance metrics (orders, earnings, pending payments)
Order management: place, track, and manage supply orders
Product listing: list agricultural produce for direct sale to consumers
Transaction history with filtering by date and type
Expert support request booking (consultation slot scheduling)
Marketplace access for seeds, fertilizers, and farming supplies

🛠️ Admin Module

Dashboard with platform-wide statistics (users, transactions, top products)
User management: search, filter, and verify farmer/consumer accounts (NID-based)
Product management: set minimum price and quantity limits per category
Financial report generation and Excel export
Role-based admin creation (Director, GM, Collector) with permission assignment


👥 User Roles
RoleDescriptionFarmerLists produce, buys supplies, books expert consultationsConsumerBrowses products, places orders, rates purchasesAdminManages users, products, reports, and platform settingsExpertProvides agricultural advice to farmers (via support system)

🛠️ Tech Stack
LayerTechnologyFrontendHTML, CSS, JavaScriptBackendServer-side web frameworkDatabaseRelational Database (structured schema)PaymentsbKash API, DBBL Nexus GatewayTestingBlack-Box Testing methodologyVersion ControlGit

🗂️ System Architecture
The WBS (Work Breakdown Structure) covers 7 major phases:
AgriConnect
├── 1.1 Project Planning       (Goals, Requirements, Budget, Risk, Schedule)
├── 1.2 Design                 (Auth, Prototype, Architecture, DB Schema, UI/UX, OOAD)
├── 1.3 Development            (Features, Backend, Frontend, DB Connection, Security)
├── 1.4 Testing                (Requirement Analysis, Test Cases, Execution, Reports)
├── 1.5 Integration            (Deployment, Handover, Feedback, Documentation, Patches)
├── 1.6 Marketing              (Market Analysis, Social Media, Email, Demo Videos)
└── 1.7 Support                (Feedback Analysis, Maintenance, Training)

📊 Project Planning
COCOMO Estimation
MetricValueSource Lines of Code (estimated)5,000 SLOCEffort (PM)13.00 person-monthsDevelopment Time (DM)6.63 monthsRequired Staff~2 people
Earned Value Analysis (EVA)
MetricValueBAC (Budget at Completion)521 person-daysBCWS (Planned Value)457BCWP (Earned Value)443ACWP (Actual Cost)451SPI (Schedule Performance Index)0.97CPI (Cost Performance Index)0.98Schedule Variance (SV)-14 person-daysCost Variance (CV)-8 person-days% Work Scheduled87.71%% Work Completed85.02%
Project Timeline (Gantt)
PhasePeriodProject PlanningMay 2025DesignJune 2025DevelopmentJuly – August 2025TestingSeptember 2025IntegrationSeptember – October 2025MarketingOctober 2025SupportNovember 2025
Key Risks Identified
RiskProbabilityImpactMitigationCustomer changes requirements80%MediumAgile methods + change control processLack of training on tools80%HighEarly training + mentorsTest coverage insufficient75%HighTDD + coverage benchmarksImproper auth & access control70%MediumSecure coding + penetration testingLess reuse than planned70%MediumIdentify reusable components early

👨‍💻 Team
NameStudent IDContributionsIshan, Ibnul Ishtiak22-49545-3UI/UX (Admin), Test Cases, WBS, Gantt Chart, EVASiddique, Md Abu Bakar22-48322-3UI/UX (Auth), Test Cases, COCOMO, EVA, Risk ManagementMd. Ibtihazaman22-49153-3UI/UX (Consumer), Test Cases, Gantt Chart, EVA, Risk ManagementMd. Anisur Rahman22-49553-3UI/UX (Farmer), Test Cases, Gantt Chart, COCOMO, Risk Management

🏫 Academic Info

University: American International University-Bangladesh (AIUB)
Department: Computer Science, Faculty of Science & Technology
Course Outcome: CO4 — Software Project Management
Semester: Spring 2024–25 | Section H | Group 01


