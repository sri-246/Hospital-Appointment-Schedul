# HOSPITAL APPOINTMENT SCHEDULER
1. Introduction 
1.1 Purpose
The purpose of this document is to provide a detailed overview of the requirements for the development of the Hospital Appointment Scheduler, a system designed to facilitate appointment scheduling, notification management, and medical record access for both patients and doctors. Maintaining a computerised easy-to-use circulation system and generating various reports are the primary goals of this project. Using UML and ER diagrams, this project explains the specifications for the hardware and software interface.
1.2 Document Conventions
The entire document should be justified.
Convention for the Main title
•	Font face: Times New Roman 
•	Font style: Bold
•	Font Size: 14 
Convention for Subtitle
•	Font face: Times New Roman
•	Font style: Bold
•	Font Size: 12
Convention for body
•	Font face: Times New Roman
•	Font Size: 12
1.3 Scope of Development Project
The scope of the Hospital Appointment Scheduler project is extensive, aiming to enhance both patient and doctor experiences. For patients, the system will offer a user-friendly platform to seamlessly initiate, schedule, and confirm appointments with their preferred doctors. 

This includes the ability to submit appointment requests, choose suitable time slots based on doctor availability, and conveniently confirm or reschedule appointments through the system. Patients will also benefit from secure access to their medical records, allowing them to view and retrieve their complete medical history, diagnostic reports, and treatment details with strict privacy measures in place.

On the doctor-centric side, the system will provide efficient schedule management tools, empowering doctors to organize their daily schedules effortlessly. Real-time updates on doctor availability will be available, facilitating accurate appointment scheduling.

1.4 Definitions, Acronyms and Abbreviations 
JAVA -> platform independence 
SQL-> Structured Query Language 
ER-> Entity Relationship 
UML -> Unified Modelling Language 
IDE-> Integrated Development Environment 
SRS-> Software Requirement Specification
1.5 References 

Books
•	Software Requirements and Specifications: A Lexicon of Practice, Principles and Prejudices (ACM Press) by Michael Jackson 
•	Software Requirements (Microsoft) Second Edition by Karl E. Wiegers 
•	Software Engineering: A Practitioner’s Approach Fifth Edition By Roger S. Pressman  

Websites
•	http://www.slideshare.net/ 
•	https://www.freeprojectz.com/entity-relationship/doctor-appointment-system-er-diagram 

2. Overall Descriptions
2.3 User Classes and characteristics
     In the context of a hospital appointment scheduler, we can identify several user classes with distinct characteristics. Understanding these user classes is crucial for designing a system that meets the needs of various stakeholders. Here are some potential user classes for this project:

Admin
Characteristics
•	has full access to the system.
•	responsible for system configuration and maintenance.
•	manages user roles and permissions.
Responsibilities
•	Manages user accounts.
•	monitors system performance.
•	configures system settings.

Medical Staff
Characteristics
•	includes doctors, nurses, and administrative staff.
•	requires access to patient records.
•	needs to schedule, reschedule, and manage appointments.
Responsibilities
•	schedules patient appointments.
•	Updates patient records.
•	receives and responds to appointment requests.

Patients
Characteristics
•	requires access to personal health information.
•	schedules and manages appointments.
•	receives appointment notifications.
Responsibilities
•	Requests appointments.
•	provides accurate personal and medical information.
•	confirms or reschedules appointments.

Understanding the characteristics and responsibilities of these user classes will aid in designing user interfaces, access controls, and functionalities tailored to the specific needs of each group. It's essential to conduct user interviews and engage stakeholders during the system design process to refine and validate these user classes and their associated characteristics.

2.4 Operating Environment

The product will be operating in windows environment. The Hospital Appointment Schedular is a website and shall operate in all famous browsers, for a model we are taking Microsoft Internet Explorer, Google Chrome, and Mozilla Firefox. Also it will be compatible with the IE 6.0. Most of the features will be compatible with the Mozilla Firefox & Opera 7.0 or higher version. The only requirement to use this online product would be the internet connection.
The hardware configuration includes Hard Disk: 40 GB, Monitor: 15” Color monitor, Keyboard: 122 keys. The basic input devices required are keyboard, mouse and output devices are monitor, 
printer etc.

2.5 Assumption and Dependencies

The assumptions are

•	Assumes a reliable internet connection is available for both the server and client device.
•	Assumes that users have devices (e.g., computers, smartphones) compatible with the web-based application.
•	Assumes that users (both patients and doctors) will receive adequate training to effectively use the system.
•	Assumes compliance with healthcare regulations and data protection standards in the project's design and implementation.
•	Assumes the availability of necessary APIs or integration points for seamless integration with Electronic Health Record (EHR) systems.
•	Assumes the availability and compatibility of external notification services (e.g., email, SMS) for timely communication.
•	Assumes the implementation of robust security measures to protect sensitive patient data during transmission and storage.
•	Assumes that users will adopt and adapt to the new appointment scheduling system effectively.

The dependencies are

•	Dependency on the stability and compatibility of the chosen DBMS (e.g., MySQL, PostgreSQL).
•	Dependency on the selected web framework's features and updates for efficient development and maintenance.
•	Dependency on continued compatibility with major web browsers (Chrome, Firefox, Safari, Edge) for user access.
•	Dependency on the availability and functionality of APIs for integrating with external systems, such as EHR systems.
•	Dependency on external notification services for delivering appointment reminders and updates to users.
•	Dependency on reliable and consistent services provided by Internet Service Providers.
•	Dependency on the stability and consistency of healthcare regulations and data protection standards.
•	Dependency on the reliability and scalability of the chosen hardware infrastructure, including server capabilities.

3. External Interface Requirement

Hospital Appointment Scheduler GUI Overview
The Hospital Appointment Scheduler system is designed with an intuitive graphical interface to cater to both patients and administrative staff, ensuring a seamless scheduling experience. Patients can effortlessly navigate the system to view available appointment slots, schedule, reschedule, or cancel appointments, and securely manage their personal information. Simultaneously, administrative staff members have access to efficient tools for managing appointment calendars, verifying patient details, and handling appointment requests.
Patient Interface: -
Within the patient interface, users can effortlessly view available appointment slots based on preferred doctors or departments, schedule appointments, and receive confirmation and reminder notifications. The design prioritizes simplicity, allowing patients to easily access educational resources or guidelines related to their upcoming appointments.
Administrative Interface: -
Administrative staff members benefit from a dedicated interface that facilitates the efficient management of appointment calendars, verification of patient details, and streamlined processing of appointment requests. The administrative interface also provides tools for generating reports on appointment statistics and trends, contributing to overall system efficiency.
Login Interface: -
The login interface ensures a secure access point for both patients and administrative staff. Patients can register if they are new to the system or login with their existing credentials. In the case of incorrect login details, appropriate error messages guide users through the authentication process, ensuring a secure login/logout module.
Appointment Scheduling: -
Appointment scheduling is a focal point of the system, allowing patients to search for available slots based on preferred doctors, departments, or timeframes. The interface facilitates easy appointment scheduling, rescheduling, or cancellation, with real-time updates to the appointment calendar. This functionality ensures a flexible and responsive scheduling process.
Calendar Management for Administrative Staff: -
Administrative staff benefit from a comprehensive calendar view, enabling efficient management and updates to appointment schedules. The calendar management interface includes features for blocking out times, accommodating urgent appointments, and managing the availability of doctors, ensuring effective coordination and resource utilization.
User Profiles: -
User profiles, designed with a focus on user-friendliness, allow both patients and administrative staff to manage personal information, view appointment history, and access relevant resources. The design prioritizes ease of use, contributing to a positive and efficient user experience.
Automated Confirmation and Reminders: -
Automated confirmation messages and reminders enhance patient engagement, ensuring individuals are well-prepared for their scheduled appointments. This feature contributes to the overall reliability and effectiveness of the appointment scheduling process.
Design Philosophy: -
The GUI's design philosophy ensures consistency across all modules, providing a standardized and intuitive user experience for all stakeholders involved in the hospital appointment scheduling process. This approach contributes to the reliability, efficiency, and user satisfaction of the entire system.
















    
