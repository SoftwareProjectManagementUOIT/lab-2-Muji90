# <ins> Use Case Models</ins>

__<ins> Overview</ins>__

Use cases are an effective technique in system design because they offer an organized method of capturing the many ways that different actors engage with the system. From the viewpoint of the user, they provide an understandable and succinct depiction of the system's functionality. We can guarantee that the system is made to meet the real demands of its users and is both functional and user-friendly by establishing use cases.

__<ins> Use Case Model</ins>__

![image](https://github.com/SOFE3650F23/project-delivery-1-gp-31/assets/145510715/10488caa-55f9-447f-8833-bc2119f8b859)

__<ins> Main Use Cases: </ins>__

1. Login
2. View Grades
3. Manage Grades
4. Course Enrollment
6. Post news
7. Send emails
8. Create Course
9. Upload Course Material
10. Manage course visability
11. Import Roster
12. Duplicate course
13. Manage Teams
14. Search

__<ins> Actors: </ins>__ 

1. Students
2. Lecturers
3. Administrators

__<ins> Detailed Use Cases</ins>__

__<ins> UC 1: Login </ins>__

__<ins> UC 2: Course Enrollment </ins>__

__• Name:__ Course Enrollment

__• Actors:__ Students, Administrators

__• Related Requirements:__ RS1 and RA3

__• Preconditions:__ The student is included in the database. Enrollment in the course is open.

__• Post conditions:__ The student is enrolled in the desired course.

__Main Flow:__

1. The student logs into the CMS.

2. The student browses available courses.

3. The student selects a course for enrollment.

4. The system confirms the enrollment.

__Alternative Flows:__ If the course is full, the system notifies the student.

__Exceptions:__ If there's a system error, the enrollment process is halted.


__<ins> UC 3: View Grades </ins>__

__• Name:__ View Grades

__• Actors:__ Students

__• Related Requirements:__ RS7, RS9

__• Preconditions:__ The student has completed courses with graded assignments/exams.

__• Post conditions:__ The student views their grades for selected courses.

__Main Flow:__

1. The student logs into the CMS.

2. The student navigates to the "Grades" section.

3. The system displays the grades for the student's courses.

__Exceptions:__ If there's a system error, the grade viewing process is halted.


__<ins> UC 4: Upload Course Material </ins>__

__• Name:__ Upload Course Material

__• Actors:__ Lecturers

__• Related Requirements:__ RL1

__• Preconditions:__ The lecturer is assigned to a course.

__• Post conditions:__ Course material is uploaded and available for students.

__Main Flow:__

1. The lecturer logs into the CMS.

2. The lecturer navigates to their assigned course.

3. The lecturer selects the option to upload course material.

4. The system confirms the successful upload.

__Exceptions:__ If the file size exceeds the limit, the system notifies the lecturer


__<ins> UC 5: Manage Grades </ins>__

__• Name:__ Manage Grades

__• Actors:__ Lecturers

__• Related Requirements:__ RL2, RL3 and RL12

__• Preconditions:__ Students have submitted assignments/exams.

__• Post conditions:__ Grades are updated in the system.

__Main Flow:__

1. The lecturer logs into the CMS.

2. The lecturer navigates to the "Grades" section of their course.

3. The lecturer updates grades for assignments/exams.

4. The system confirms the grade updates.

__Alternative Flows:__ The lecturer can choose to calculate the final grade based on grading policy.

__Exceptions:__ If there's a system error, the grade management process is halted


__<ins> UC 6: Course Creation </ins>__

__• Name:__ Manage Grades

__• Actors:__ Administrators, Lecturers

__• Related Requirements:__ RA1

__• Preconditions:__ The administrator/lecturer has the necessary permissions.

__• Post conditions:__ A new course is added to the CMS.

__Main Flow:__

1. The actor logs into the CMS.

2. Navigates to the "Create Course" section.

3. Inputs course details and saves.

4. The system confirms the course creation.

__Exceptions:__ If there's a system error, the course creation process is halted.


__<ins> UC 7: Student Profile Management </ins>__

__• Name:__ Student Profile Management

__• Actors:__ Students

__• Related Requirements:__ RS3

__• Preconditions:__ The student has an account on the CMS.

__• Post conditions:__ The student's profile is updated.

__Main Flow:__

1. The student logs into the CMS.

2. Navigates to the "Profile" section.

3. Edits and updates personal details.

4. The system confirms the profile update.

__Exceptions:__ If there's a system error, the profile update process is halted.


__<ins> UC 8: Course Feedback and Evaluation </ins>__

__• Name:__ Course Feedback and Evaluation

__• Actors:__ Students

__• Related Requirements:__ RS7, RL9 and RL11

__• Preconditions:__ The student has completed the course.

__• Post conditions:__ Feedback is submitted.

__Main Flow:__

1. The student logs into the CMS.

2. Navigates to the completed course.

3. Submits feedback and evaluation.

4. The system confirms the submission.

__Exceptions:__ If there's a system error, the feedback submission process is halted.


__<ins> UC 9: News and Announcements Posting </ins>__

__• Name:__ News and Announcements Posting

__• Actors:__ Lecturers, Administrators

__• Related Requirements:__ RL7

__• Preconditions:__ The actor has the necessary permissions.

__• Post conditions:__ News or announcement is posted.

__Main Flow:__

1. The actor logs into the CMS.

2. Navigates to the "News/Announcements" section.

3. Creates a new post and publishes.

4. The system confirms the post publication.

__Exceptions:__ If there's a system error, the posting process is halted.


__<ins> UC 10: Course Deletion </ins>__

__• Name:__ Course Deletion

__• Actors:__ Administrators

__• Related Requirements:__ RA1

__• Preconditions:__ The course exists in the CMS.

__• Post conditions:__ The course is removed from the CMS.

__Main Flow:__

1. The administrator logs into the CMS.

2. Navigates to the course list.

3. Selects a course and opts for deletion.

4. The system confirms the course deletion.

__Exceptions:__ If there's a system error, the course deletion process is halted.


__<ins> UC 11: Manage Course Schedule </ins>__

__• Name:__ Manage Course Schedule

__• Actors:__ Lecturers, Administrators

__• Related Requirements:__ R1, R2, R3, RS15 and RA1

__• Preconditions:__  The course exists in the CMS

__• Post conditions:__ The course schedule is updated.

__Main Flow:__

1. The actor logs into the CMS.

2. Navigates to the desired course.

3. Edits the course schedule.

4. The system confirms the schedule update.

__Exceptions:__ If there's a system error, the schedule update process is halted.


__<ins> UC 12: Manage Team Members </ins>__

__• Name:__ Manage Team Members

__• Actors:__ Lecturers

__• Related Requirements:__ RL8

__• Preconditions:__  The course has team-based assignments or projects.

__• Post conditions:__ Team members are managed.

__Main Flow:__

1. The lecturer logs into the CMS.

2. Navigates to the "Teams" section of the course.

3. Adds or removes students from teams.

4. The system confirms the team update.

__Exceptions:__ If there's a system error, the team management process is halted.


__<ins> UC 13: Password Reset Request </ins>__

__• Name:__ Password Reset Request

__• Actors:__ Students, Lecturers, Administrators

__• Related Requirements:__ RS5

__• Preconditions:__  The actor has an account on the CMS.

__• Post conditions:__ A password reset link is sent to the actor's email.

__Main Flow:__

1. The actor navigates to the CMS login page.

2. Clicks on "Forgot Password".

3. Inputs registered email.

4. The system sends a password reset link to the email.

__Exceptions:__ 

• If the email is not registered, the system notifies the actor.

• If there's a system error, the password reset process is halted.

__<ins> UC 14: Search </ins>__


# <ins> Architectural Concerns</ins>

__<ins> Overview</ins>__

Architectural concerns encompass the various considerations and challenges that arise during the design and implementation of a system's architecture. These concerns can influence the system's structure, behavior, and evolution. Addressing these concerns is crucial to ensure that the system meets its functional requirements while also satisfying non-functional requirements like performance, security, and maintainability.

__<ins> List of Architectural Concerns</ins>__

| Name | Description | Implications | Related Requirements |
| :---         |     :---:      |   :---: |   :---: |
| Scalability   | The system's capacity to manage higher loads, such additional users or data input     | Whether there are more users, courses, or students at once, the architecture should be able to grow with them    | __RM5:__ The system shall be scalable |
| Modularity     | Dividing the system up into separate parts or sections that are capable of working alone       | Modular designs facilitate updates and maintenance and guarantee that modifications to one element don't negatively impact other modules      | __R2:__ The system shall store course information. __RS1:__ The system shall enable students to subscribe/unsubscribe to courses. __RL1:__ The system shall allow lecturers to upload course material for lectures. __RM1:__ The system shall allow maintainers to create and restore back-ups of the entire and partial system. __RA1:__ The system shall allow the administration to create and delete courses. |
| Performance   | Making sure the system loads material quickly and satisfies user demands     | Poor performance may turn off users. Retrieving and processing data efficiently should be the top priority in the architecture    | __R2:__ The system shall store course informationn and __RM5:__ The system shall be scalable. |
| Security     | Safeguarding the system against hostile activity, data breaches, and unauthorized access      | A breach may jeopardize user confidence and result in legal action. The design should incorporate security features like authentication and encryption      | __RS8:__ The system shall protect the user’s privacy, __RL12:__ The system shall allow lecturers to view all grades of all students in the course, __RM2:__ The system shall allow maintainers to limit the size of files being uploaded by lecturers and by students, __RM3:__ The system shall allow maintainers to limit the total available space for specific courses, __RA6:__ The system shall allow the administration to make exceptions with regard to student enrolment to courses.  |
| Maintainability   | The ease with which the system can be updated, debugged, or enhanced     | A system that's hard to maintain can become obsolete quickly. The architecture should be designed with future updates in mind    | __RM1:__ The system shall allow maintainers to create and restore back-ups of the entire and partial system and __RM4:__ The system shall be easily extensible and evolvable
| Integration     | The system's ability to seamlessly connect and exchange data with other systems       | Poor integration can lead to data silos and inefficiencies. The architecture should support standard integration protocols      | __RM6:__ The system shall be interoperable with secondary university systems, __RA4:__ The system shall automatically synchronize with secondary university systems and __RA5:__ The system shall be interoperable with secondary university systems
| Usability   | The simplicity with which users may use the technology to accomplish their objectives     | A system that is difficult to use might frustrate consumers and even drive them away by producing a bad user experience    | __RS13:__ The system shall have a UI which is intuitive (the behavior of the system is according to the intuition of a standard end user) and __RS14:__ The system shall have a descriptive UI (all UI elements should have a descriptive text) |
| Accessibility     | Ability of those with impairments, especially those who depend on assistive technology, to utilize the system       | If accessibility requirements are not followed, there may be legal repercussions and a large section of the user base would be excluded      | __RS8:__ The system shall protect the user’s privacy |
| Reliability   | The system's capacity to operate as designed for a predetermined amount of time without interruption     | Systems that are unreliable might experience downtime, lose data, and lose user confidence    | __RS10:__ The system shall have downtime at most 4 hours/month |
| Flexibility     | The system's capacity to adjust to shifting conditions or settings       | Lack of adaptability can cause a system to quickly become outdated or cost a lot of money to upgrade      | __RM4:__ The system shall be easily extensible and evolvable and __RM5:__ The system shall be scalable.
| Interoperability   | The system's compatibility with other systems, despite the fact that they employ various protocols or data formats     | Data silos, inefficiencies, and a lack of communication across various systems can all be consequences of poor interoperability    | __RM6:__ The system shall be interoperable with secondary university systems and __RA5:__ The system shall be interoperable with secondary university systems |
| Compliance     | The system's compliance with pertinent laws, rules, and guidelines       | Infractions may result in fines, harm to one's reputation, and even possible injury to users      | __RA6:__ The system shall allow the administration to make exceptions with regard to student enrollment to courses |




# <ins> System Constraints for the Application</ins>

__<ins> Overview</ins>__

The limitations or restrictions placed on a system's functionality and design are referred to as system constraints. These limitations may be the result of a number of factors, such as budgetary constraints, stakeholder demands, legal obligations, or technical limitations. It is essential to comprehend and deal with these limitations as they have a big impact on the system's overall architecture and design choices.

__<ins> List of Constraints</ins>__

| Constraint  | Description | Related Requirements |
| ------------- | ------------- | ------------- |
| Platform Independence  | Users should be able to access the CMS from a variety of devices and operating systems without experiencing any compatibility problems if it is platform-independent  | __R2__ (The system shall store course information), __RS2__ (The system shall facilitate searches in all static information of courses), __RM4__ (The system shall be easily extensible and evolvable), __RM5__ (The system shall be scalable), and __RA5__ (The system shall be interoperable with secondary university systems)|
| Data Storage  | The system has to have a strong database with a set storage limit because of the volume of course materials, student information, and grades  | __R2__ (The system shall store course information) and __RL1__ (The system shall allow lecturers to upload course material for lectures)
| Security Protocols  | Strict security guidelines must be followed by the CMS to safeguard user data, particularly private and sensitive data like grades  | __RS8__ (The system shall protect the user’s privacy) __RA4__ (The system shall automatically synchronize with secondary university systems)
| Integration  | The system has to support common data interchange formats and protocols in order to be compatible with other university systems  | __R2__ (The system shall store course information) __RM6__ (The system shall be interoperable with secondary university systems) and __RA4__ (The system shall automatically synchronize with secondary university systems)
| Regulatory Compliance  | In order to guarantee that user data is treated properly and ethically, the CMS must abide by legislation pertaining to data protection and education  | __RA6__ (The system shall allow the administration to make exceptions with regard to student enrollment to courses)
| Accessibility  | The system must to comply with online accessibility guidelines and be usable by those with impairments  | __RS1__ (The system shall enable students to subscribe/unsubscribe to courses), __RS3__ (The system shall allow students to edit their personal information), __RS4__ (The system shall allow students to change their password), __RS5__ (The system shall provide a password reset function, which resets the password and mails it to the user), __RS6__ (The system shall notify students of events), __RS15__ (The system shall provide an export to commonly used calendar formats), __RL2__ (The system shall enable lecturers to manage grades) and __RL3__ (The system shall allow lecturers to specify and change the grading policy)
| User Interface Consistency  | To guarantee a smooth user experience, the CMS should maintain a consistent user interface throughout all modules  | __RS13__ (The system shall have a UI which is intuitive), __RS14__ (The system shall have a descriptive UI), and __RL7__ (The system shall allow lecturers to post news messages)
| Scalability  | The system should be able to scale as needed without performance degrading as user numbers and data volumes rise  | __RM5__ (The system shall be scalable)
| Backup and Recovery  | The system data should be regularly backed up, and a reliable recovery method should be in place in case of data loss  | __RM1__ (The system shall allow maintainers to create and restore backups of the entire and partial system)
| Maintenance and Support  | To ensure that any problems are quickly fixed and the system is maintained current, the CMS should have a dedicated team for maintenance and support  | __RM1__ (The system shall allow maintainers to create and restore backups of the entire and partial system), __RM2__ (The system shall allow maintainers to limit the size of files being uploaded by lecturers and by students), __RM3__ (The system shall allow maintainers to limit the total available space for specific courses), and __RM4__ (The system shall be easily extensible and evolvable)




# <ins> Quality Attributes for the Application</ins>

__<ins> Overview </ins>__

Quality attributes are the non-functional requirements of a system, defining how the system operates rather than what it does. They play a vital role in shaping the system's architecture, ensuring it meets certain standards of performance, security, usability, and more. By identifying and prioritizing these attributes, we can design a system that not only fulfills its functional requirements but also delivers a high-quality user experience.

__<ins> List of Quality Attributes</ins>__


| Name | Description | Rationale | Use case relation |
| :---         |     :---:      |   :---:    |   :---:    |
| Performance   |  The system's ability to respond quickly to user requests   | To ensure users can access course information and perform tasks without delays    |  All 12 Use cases |
| Security     | Protecting user data and ensuring unauthorized access is prevented       | To safeguard sensitive student and course information and maintain user trust.      |  UC 1: Course Enrollment, UC 3: Upload Course Material, UC 4: Manage Grades, UC 5: Course Creation, UC 6: Student Profile Management, UC 7: Course Feedback and Evaluation, UC 8: News and Announcements Posting, UC 9: Course Deletion, UC 10: Manage Course Schedule, UC 11: Manage Team Members and UC 12: Password Reset Request |
| Usability   | The system's interface is intuitive and user-friendly     | To ensure users can easily navigate and utilize the system without facing challenges    |   All 12 Use cases |
| Availability     | Ensuring the system is accessible and operational when users need it       | Students, lecturers, and administrators rely on the CMS for various tasks. Downtime can disrupt academic processes and schedules      |   All 12 Use cases |
| Scalability   | The system's ability to handle increased loads, whether more users, courses, or data entries     | As the institution grows and more students enroll, the CMS should be able to accommodate this growth without performance degradation    |   All 12 Use cases |
| Interoperability     | The system's capability to interact and exchange data seamlessly with other university systems       | The CMS might need to integrate with other institutional systems like registration platforms, library systems, or payment gateways      |   All 12 Use cases |
| Modifiability   | The ease with which the system can be modified to accommodate changes or additions     | Educational requirements and technologies evolve. The CMS should be adaptable to these changes without extensive overhauls    |  UC 5: Course Creation |
| Reliability     | The system's ability to operate without failure under specified conditions       | Users should be able to trust that the CMS will function consistently, especially during critical periods like enrollment or exam grading      |  All 12 Use cases |
| Portability   | The ease with which the system can be transferred from one environment to another    | If there's a need to migrate the CMS to a different server or platform, the process should be straightforward    | UC 5: Course Creation |
| Maintainability     | The architecture of the system should make it simple to update, repair bugs, and make enhancements without impairing its general operation       | Frequent maintenance keeps the CMS current and free of problems that might impair its functionality      |  UC 5: Course Creation|
| Privacy  | Safeguarding the private data of educators, administrators, and students     | Users should feel secure knowing that their academic and personal information is protected and out of the hands of unauthorized individuals    |  All 12 Use cases|

