# Smart India Hackathon Workshop
# Date:
## Register Number:212224110041
## Name:S.NAVINKUMAR

## Problem Title

SIH 1653: Web based Selector-Applicant Simulation Software

## Problem Description

Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization

Ministry of Defence

## Idea

The Web-Based Selector Applicant Simulation Software automates applicant evaluation for job recruitment, university admissions, and grant approvals. Organizations can set custom selection criteria, and the system uses rule-based or AI-driven models to rank applicants.It features simulation-based decision-making, data analytics, and reporting to improve transparency and efficiency. The web-based platform integrates with HR and university systems and provides role-based access for applicants, evaluators, and administrators.By reducing manual effort, minimizing bias, and enhancing decision-making, this software streamlines the selection process, ensuring a fair, data-driven, and efficient approach to applicant evaluation.

## Proposed Solution / Architecture Diagram

1. User Interface (Frontend) – Presentation Layer
  * Web-based application (React, Angular, or Vue.js)
  * User authentication & dashboard
  * Forms for applicant data entry & criteria selection
  * Visualization of results and reports

2. Backend – Application Layer
  * Business logic for applicant evaluation & ranking
  * Selection algorithm (rule-based, AI-powered, or weighted scoring)
  * API endpoints for data processing (REST/GraphQL)
  * Report generation and notifications

3. Database – Storage Layer
  * SQL (MySQL/PostgreSQL) for structured applicant data
  * NoSQL (MongoDB/Firebase) for dynamic evaluation models
  * Cloud Storage for uploaded documents

4. External Services
  * Authentication (OAuth, JWT-based security)
  * Document verification APIs
  * Third-party analytics/reporting tools

5. Cloud Hosting (Optional)
  * AWS/Azure/GCP for scalable deployment
  * CI/CD pipeline for automated updates

![Screenshot 2025-03-05 203454](https://github.com/user-attachments/assets/f99cfc2a-2b28-4a0e-8819-1fb05ce67568)


## Use Cases

1. User Authentication & Role-Based Access
   * Users (admin, evaluators, applicants) log in using credentials or third-party authentication.

2. Creating a New Selection Simulation
   * Admins define selection criteria, weightages, and simulation models.

3. Applicant Data Entry & Document Upload
   * Applicants submit personal details, qualifications, and supporting documents.

4. Running the Selection Simulation
   * The system processes applicants based on the defined criteria.
   * AI/ML-based ranking or rule-based filtering is applied.

5. Viewing and Analyzing Results
  * Evaluators access the shortlisted candidates with analytics.
  * Data visualization for better decision-making.

6. Generating Reports & Notifications
  * Results can be exported as PDF, Excel, or sent via email.

7. Final Selection & Feedback
  * Admins finalize the selection and notify successful applicants.

![Screenshot 2025-03-05 204416](https://github.com/user-attachments/assets/ff22fe99-675e-4e14-9510-eda61845fe3a)

## Technology Stack
* React.js,Angular,Vue.js
* Node.js,Python(Django),Java(Spring Boot)
* PostgreSQL,MySQL,MongoDB
* Firebase Auth,Auth0,JWT
* AWS S3,Google Cloud Storage
* AWS,Vercel,Netlify,Docker,Kubernetes
* Puppeteer,ExcelJs,Chart.js
* Twilio(SMS),SendGrid(Email)

## Dependencies
*React-router,axios,formil or react-hook-from,chart.js or D3.js
*express,jsonwebtoken,multer,dotenv
*sequelize,mongoose
*puppeteer,nodemailer
*docker-compose,pm2


