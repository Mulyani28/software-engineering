#  Proposal 

## Academic Consultation System  


### Prepared by: Group Program
   Name and matric no:
  1. Wan Nur Sofea Binti Mohd Hasbullah A22EC0115
  2. Maisarah Binti Rizal A22EC0192
  3. Nur Arini Fatihah Binti Mohd Sabir A22EC0244
  4. Mulyani Binti Saripuddin A22EC0223
<img src="https://user-images.githubusercontent.com/128214992/235843037-31e5d853-95de-4675-8a95-12832052dd16.jpg" width="400" height=auto>


### Table of Contents
- [Executive Summary](#1-executive-summary)
- [Background](#2-background)
- [Objectives](#3-objectives)
- [Scope](#4-scope)
- [Software Process Model](#5-software-process-model)
- [Budget](#6-budget)
- [System Architecture](#7-system-architecture)
- [Risks Assessment](#8-risks-assessment)
- [Resources](#9-resources)
- [Technical Specifications](#10-technical-specifications)
- [Timeline and Deliverables](#11-timeline-and-deliverables)
- [Conclusion](#12-conclusion)
  
### 1. Executive Summary

<img src="https://user-images.githubusercontent.com/128196055/235490755-87a5ad38-a137-4d46-85ba-0ab5a6b6a4c6.jpg" width="400" height=auto>


- Academic support services are crucial for students' academic success. However, traditional support methods such as office hours and group tutoring sessions can often be ineffective due to time constraints, lack of privacy, and disruption of class schedules. To overcome these limitations, the proposed solution is an academic support app that provides private appointments between students and lecturers at their convenience.

### 2. Background:

   The need for academic support services has become increasingly important in recent years as students face more challenges in their academic journeys. Many students struggle with academic performance due to various factors such as learning disabilities, time management issues, and lack of study skills. In response, academic institutions have developed support services to help students overcome these challenges and achieve academic success.

   However, traditional support methods such as office hours and group tutoring sessions have limitations that can hinder their effectiveness. For example, office hours may not be convenient for some students due to scheduling conflicts or lack of privacy. Group tutoring sessions may not provide the individualized attention some students need to succeed.

   The proposed academic support app addresses these limitations by providing private appointments between students and lecturers at their convenience. The app offers a more personalized and effective support system that can help students overcome the challenges they face and achieve academic success.
  
These are the current system interface from academic advisor view:

<img src="https://user-images.githubusercontent.com/128214992/236150766-f7463dd2-f294-448b-8de4-a01469125d4a.jpg" width="400" height=auto>
<img src="https://user-images.githubusercontent.com/128214992/236150893-9ba55c91-8924-441a-a1ca-a777cb205d7d.jpg" width="400" height=auto>
<img src="https://user-images.githubusercontent.com/128214992/236149794-9e95df6d-4400-4dad-b1fe-065e96ca9fc6.jpg" width="400" height=auto>
<img src="https://user-images.githubusercontent.com/128214992/236150477-dc2944e5-74bf-48ce-bf6f-927d3fcca888.jpg" width="400" height=auto>
<img src="https://user-images.githubusercontent.com/128214992/236149827-df6b0303-4ccf-4d44-9dbd-d5ae4ebe322f.jpg" width="400" height=auto>


### 3. Objectives:
The objectives of this proposal are to:

- Provide students with a more personalized and effective academic support system
- Enable lecturers to provide individualized attention to students without disrupting their class schedule
- Improve students' academic performance and engagement through one-on-one interactions with their lecturers

### 4. Scope: 

The Academic Support Services System will provide a web-based platform that allows students to book appointments with their lecturers for academic support services. The system will include the following features:

- Student and lecturer registration and login.
- Appointment scheduling and management.
- Communication and messaging between students and lecturers.
- Notifications and reminders for both academic advisors and students.
- Analytics and reporting for monitoring and evaluating the effectiveness of the system.
- The system will be limited to academic support services only and will not provide any additional features such as course content or assessment tools.

### 5. Software Process Model:

   The ideal software process model for this project is the Agile methodology. The Agile methodology is ideal for this project because it allows for flexibility and adaptability to changing requirements. This is important because the system will be continuously improved based on feedback from students and lecturers.

<img src="https://user-images.githubusercontent.com/128196055/235509164-0d5157b4-b28e-46a5-b02a-db9fd7601fa3.jpg" width="400" height=auto>

The Agile methodology is an iterative and incremental approach to software development that focuses on delivering working software frequently. The methodology is based on four core values:

- Individuals and interactions over processes and tools.
- Working software over comprehensive documentation.
- Customer collaboration over contract negotiation.
- Responding to change over following a plan.

The Agile methodology consists of several phases, including planning, requirements analysis, design, development, testing, and deployment. The phases overlap and are conducted in short iterations, typically lasting two to four weeks. The Agile methodology is well-suited for this project because it allows for continuous improvement and flexibility.

Activities for each phase of the Agile methodology:

- Planning: Define project scope, establish project team, create product backlog.
- Requirements Analysis: Gather user requirements, create user stories, prioritize user stories.
- Design: Create wireframes, design database schema, create UI mockups.
- Development: Implement features, conduct code reviews, conduct unit tests.
- Testing: Conduct integration testing, conduct acceptance testing, resolve defects.
- Deployment: Deploy software to production, train users, provide support.

### 6. Budget:
- The budget to develop the academic consultion system for a year involves various cost depending on the features and functionilities required. The estimation budget is **RM 824,000.00**

### Hardware and Software : RM 50,000
The Hardware and Software cost is used for development and testing of the system.

### Development Team : RM 480,000
The development team cost is to pay monthly salary for the developing the system, including a main developer, a technical lead, a UX/UI designer and QA/Test engineer.  

### Project Management and Quality Assurance : RM 144,000
The cost for project management and quality assurance is to define the escope of the project, create timeline and allocate recources while also undergoes several testing and veryfying to meet the specifiesd requirements of the system.

### Marketing and Promotion : RM 50,000
The marketing and promotion cost will cover the cost of promoting the system to potential users, which in here is Academic Advisor and also students.

### Other costs : RM 100,000
This is cost will cover any activities associated with developing and deploying the system, including legal and accounting fees, website desing and development, and ongoing maintenance and support. 

### 7. System Architecture:

**Architecture**:
  The proposed academic support app will consist of a client-server architecture, with the front-end developed using HTML and CSS and the back-end using Node.js and MongoDB. The app will be hosted on a cloud platform such as Amazon Web Services (AWS) or Microsoft Azure.

 **Data Storage and Management**:
  The app will use MongoDB, a NoSQL document-oriented database, to store student and lecturer data, appointment schedules, and other relevant information. MongoDB is a scalable, flexible, and highly available database that can handle large amounts of data.

**Data Analysis**:
  The app will not require complex data analysis since it primarily serves as a scheduling tool. However, basic data analysis such as appointment statistics and user activity tracking can be implemented using MongoDB's built-in analytics tools. 

**Hardware and Software Requirements**:
  The hardware requirements for the app are minimal, with a basic web server and a MongoDB database server being sufficient. The software requirements include Node.js, MongoDB, and any necessary libraries and frameworks.

**Data Visualization**:
The app does require complex data analysis, data visualization tools are not necessary.

**Tools and Technologies**:
The following tools and technologies will be used to develop and deploy the academic support app:
- HTML: For front-end development
- CSS: For styling and layout
- Node.js: For back-end development and server-side logic
- MongoDB: For data storage and management
- Amazon Web Services (AWS) or Microsoft Azure: For cloud hosting and deployment

### 8. Risks Assessment:

 **Potential Risks**:

 1. Technical Challenges: The development team may face technical challenges in implementing certain features of the app, such as the appointment scheduling system or the privacy features.
 2. Resource Constraints: Limited resources such as time, budget, or personnel may impact the timely completion of the project.
 3. Changes in Project Requirements: Changes in project requirements or specifications may occur during the development process, which may impact the project schedule and budget.

**Mitigation Strategies**:

 1. Technical Challenges: The development team will conduct thorough research and testing of the app's features before implementation. In case of any technical challenges, the team will seek the help of experts or consultants to overcome the issue.
 2. Resource Constraints: The team will prioritize tasks and allocate resources accordingly to ensure timely completion of the project. In case of any unexpected delays, contingency plans will be put in place.
 3. Changes in Project Requirements: The team will ensure effective communication and collaboration with stakeholders to ensure that any changes in project requirements are addressed promptly. The project plan and budget will be updated accordingly to accommodate any changes.
 
  **Our project team will maintain a proactive approach to risk management, regularly monitoring and identifying potential risks throughout the development process and implementing appropriate mitigation strategies to ensure the project's success.**



### 9. Resources:
**Staff**:

1. Main Developer: responsible for managing the project, ensuring that it is delivered on time, within budget, and to the required quality. The project manager will need to have experience in managing software development projects and be proficient in project management tools and methodologies.
2. UX/UI Designer:  responsible for designing and developing the user interface of the academic support app using HTML and CSS. Responsible for developing the server-side logic, API, and database using Node.js and MongoDB.
3. QA/ Test Engineer: responsible for testing the app and ensuring that it meets the functional and non-functional requirements.
4. Technical Lead: responsible for analyzing the app usage and providing insights to improve the app.

**Equipment**:

1. Desktop computers or laptops for each team member
2. Servers to host the app and database
3. Testing devices like computers and laptops.

**Software**:

1. HTML and CSS editor such as Visual Studio Code or Sublime Text
2. Node.js and MongoDB for server-side development
3. Project management software such as Trello or Asana
4. Version control software such as Git and GitHub
5. Testing tools such as Mocha and Chai
6. Data visualization and analysis tools such as Tableau or Power BI

<!--**Other Expenses**:

1. Cloud hosting services such as AWS or Google Cloud Platform
2. Domain name registration and SSL certificate
3. Marketing and promotion expenses such as social media ads and email marketing campaigns
4. Contingency budget for unexpected expenses-->

### 10. Technical Specifications:

Technical specifications play a vital role in the success of any project. Here are the technical specifications of the proposed project:

1. **Data sources**: The data for this project will be obtained from various sources, including APIs, databases, and flat files. The primary data sources will be social media platforms and news websites.

2. **Data schema**: The data schema will be designed to store data in a structured format that can be easily queried and analyzed. The schema will be flexible enough to accommodate changes in data sources or requirements.

3. **Data transformations**: The data will be transformed using ETL (Extract, Transform, Load) processes to clean, preprocess, and enrich the data. The data transformations will be designed to handle missing values, outliers, and other anomalies in the data.

4. **Machine learning algorithms**: Machine learning algorithms will be used to extract insights from the data. The algorithms will include supervised and unsupervised learning techniques, such as classification, regression, clustering, and anomaly detection.

5. **Data visualization tools**: The data will be visualized using interactive dashboards and charts. The visualization tools will be selected based on their ability to handle large volumes of data and provide real-time insights.

6. **Programming languages, frameworks, and libraries**: The project will be developed using a combination of programming languages, frameworks, and libraries, including Python, Flask, Pandas, NumPy, Scikit-learn, TensorFlow, Keras, Matplotlib, and Plotly.

7. **Hardware and software requirements**: The proposed system will require a robust hardware and software infrastructure. The hardware requirements will include high-performance servers with sufficient RAM, storage, and processing power. The software requirements will include operating systems, databases, web servers, and other software components.

8. **Data security measures**: The project will implement various data security measures, including data encryption, access controls, and secure data transfer protocols. The project will comply with relevant data privacy regulations and guidelines, such as GDPR and CCPA

### 11. Timeline and Deliverables: 
1. **Milestone 1: Project Planning and Requirements Gathering**
- Deadline: Week 1-2
<ul>Deliverables:

   - Project plan and timeline
   - Requirements document
   - Resource allocation plan</ul>
 
2. **Milestone 2: Data Collection and Preparation**
- Deadline: Week 3-4
<ul>Deliverables:
   
- Data sources identified and collected
- Data cleaning and preprocessing scripts
- Documented data schema</ul>
   
3. **Milestone 3: Data Analysis and Modeling**
- Deadline: Week 5-8
<ul>Deliverables:
   
- Exploratory data analysis report
- Machine learning models developed and trained
- Model validation and evaluation report</ul>

4. **Milestone 4: Data Visualization and Reporting**
- Deadline: Week 9-10
<ul>Deliverables:
   
   - Data visualization dashboards and reports
   - Final project report
   - Presentation slides
   - Quality Assurance and Testing Procedures:
      1. Code review and testing will be conducted throughout the development process to ensure high-quality code.
      2. Unit testing will be performed to verify the functionality of individual components.
      3. Integration testing will be conducted to test the integration of various components.
      4. User acceptance testing will be performed to ensure the system meets the requirements and is user-friendly.
      5. Automated testing scripts will be developed and executed to ensure the system is functioning as expected.
      6. Data quality assurance procedures will be implemented to ensure data accuracy and completeness.
      7. Security testing will be performed to identify and mitigate any security vulnerabilities.
      8. All deliverables will be reviewed and approved by the project stakeholders before being considered complete.
</ul>
   
### 12. Conclusion:
  In conclusion, our proposed project aims to provide a comprehensive solution for the given problem statement through the use of advanced technologies and methodologies. Our solution is designed to provide accurate and efficient data analysis, visualization, and decision-making capabilities for the client.

Throughout this proposal, we have outlined the problem statement, objectives, approach, methodology, risks, resources, and technical specifications of the proposed project. We are confident that our solution will help the client achieve their goals and objectives in a timely and cost-effective manner.

We understand that challenges and limitations may arise during the project, but we are fully prepared to tackle them with our team's expertise and experience. We will follow rigorous quality assurance and testing procedures to ensure that our deliverables meet the highest standards.

We urge the client to approve our proposal and proceed with the project as soon as possible to realize the benefits of our proposed solution. We are committed to delivering a successful project that meets and exceeds the client's expectations. 

### Thank you for considering our proposal.

## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/software-engineering/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

![](https://visitor-badge.glitch.me/badge?page_id=drshahizan)
