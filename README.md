# OEAS 705 / 805 Advanced Environmental Data Science 
3 credits, Fall 2026

Dr. Jessie Turner, jturners@odu.edu
Class times: 11:00 AM–12:15 PM, T/Th, OCNPS 320
Office hours: 12:15–12:30 PM, T/Th, OCNPS 320, and 1:00–3:00 PM, M, OCNPS 441

## Course description
The environmental sciences are quickly moving from being a data- poor to data-rich disciplines, with many scientific and industry-related applications enabled by the analysis, synthesis and statistical modeling of large and diverse environmental data sets. This is an advanced data analysis course designed to introduce students to data management and analysis methods commonly used in data science applications. The data analysis portion of the course will include machine learning methods. The course will also give an overview of a selection of scientific databases which host freely available environmental data and output from numerical model simulations. This course is not discipline specific. It will be useful for any students who want to work with data efficiently and gain experience in data management, proper techniques in developing analytical pipelines, and applying machine learning to their research.

The class will meet two days a week, Tuesday and Thursday. Classes will consist of a combination of lectures, discussions and practical coding exercises where collaboration and teamwork will be encouraged. The outcome of the course will be an individual project where each student applies the techniques learned during the course to undertake a data analysis project based on their own specific research interests using at least two different data sources from open scientific databases and may include data that they have generated themselves. Students will be expected to publish the code developed and results of their project in a public GitHub repository.

## Learning objectives
1.	Understand FAIR data principles (Findable, Accessible, Interoperable, and Reusable) and how to apply them.
2.	Develop a working knowledge of existing environmental science databases and how to efficiently access data from them, including via APIs (Application Programming Interfaces).
3.	Develop data analysis toolboxes using, but not limited to, python and shell scripts.
4.	Understand and apply version control (e.g. git), environments (e.g. conda) and code repositories (e.g. GitHub) to manage and share code.
5.	Understand the underlying principles of machine learning techniques for regression and classification, including supervised and unsupervised learning, and apply them to a targeted research question.
6.	Understand the process of model evaluation and optimization and commonly used metrics for reporting model performance.

## Pre-requisites
Students should have some basic knowledge of at least one programming language, any language will do (e.g. MATLAB, R, or python) and some familiarity with using the command line. The course will be taught primarily using python. Students should have a basic working knowledge of statistics and calculus. Most importantly, students need a can-do attitude, perseverance, and willingness to iteratively learn through trial and error.

## Software
The course will be taught using python. Students are encouraged to use the Anaconda package manager, but this is not required. Students are also encouraged to use Virtual Studio Code or other interactive notebook interface. We will use git and GitHub for version control. The software packages used in this class are all available for free.

## Project
The goal of the final project is to assess students’ ability to combine and apply the skills learned in class in the context of a real-world research problem. The project MUST be directly related to the students’ own individual thesis or dissertation research. The project should be focused on data analysis, visualization, and developing and evaluating machine learning models. Students must have the dataset(s) and general scope of their project approved by the instructor by mid-September. 

## AI Policy
The use of artificial intelligence (AI) is encouraged in this course. The goal is to train scientists, not computer programmers. With attribution and transparency, students are encouraged to use AI tools (e.g., ChatGPT, CoPilot, Claude, etc.) to help write, debug, or improve python code, explain errors or unexpected outputs, and/or translate code between languages (e.g., MATLAB to python). Students are required to: 
•	credit the specific AI tool used, including the version if known, and 
•	provide the complete dialogue/interaction with the AI tool used. 
The goal of this policy is to learn collectively and share AI interactions among students in the course. Together we can improve our ability to prompt well, write code, and translate code efficiently. Students are responsible for testing all code, whether an AI tool assisted in its creation or not. Submitting AI-generated code without attribution or without providing the full dialogue will be treated as a violation of academic integrity. AI tools will support students’ learning, not replace it.

## Attendance
Students are expected to attend class in person and fully participate. If you know that you will be gone for a specific reason (conference travel, field work), please inform me at least one week before the day of the planned absence, preferably sooner.

## Grades and expectations
The grading policy for this class is non-competitive; there will be no curve. If everyone in the class does well, everyone will get an A. The grading scheme follows 93-100%=A, 90-92.9%=A-, 87-89.9%=B+, etc. Half of the final grade is based on completion of homeworks, and the other half is based on the final project.

| Grading Summary | |
| :-- | :-- |
| Homeworks	| 50% |
| Project report | 20% |
| Project dataset/code | 15% |
| Project presentation | 15% |

## Late work policy
For every day late, 10% of the grade will be deducted from the grade for that assignment. Assignments will not be accepted beyond two weeks after the due date. If work is turned in late, the student is responsible for catching up to the rest of the class and attending office hours to seek help as needed. In the case of field work, conferences, or other important absences, students are expected to bring a plan to the instructor at least one week ahead of time (preferred as early as possible) to arrange to complete the work ahead of time.

## Academic Integrity and Classroom Conduct
Old Dominion University is committed to students’ personal and academic success. To achieve this vision, students, faculty, and staff work together to create an environment that provides the best opportunity for academic inquiry and learning. Your work in this course and classroom behavior must align with the expectations outlined in the Code of Student Conduct, which can be found at www.odu.edu/oscai. The following behaviors along with classroom disruptions violate this policy, corrupt the educational process, and will not be tolerated: cheating, plagiarism, fabrication (including creation of fake data with the assistance of AI tools, and facilitation (helping another student violate policy or failure to report violations). Academic dishonesty will be reported to the Office of Student Conduct & Academic Integrity and may result in sanctions up to and including expulsion from the University.

## Course Accommodations
Students are encouraged to self-disclose disabilities that have been verified by the Office of Educational Accessibility by providing Accommodation Letters to their instructors early in the semester to start receiving accommodations. Accommodations will not be made until the Accommodation Letters are provided to instructors each semester. The Office of Educational Accessibility (OEA) is located at 1021 Student Success Center and its phone number is (757) 683-4655. Additional information is available on the OEA website: https://www.odu.edu/accessibility 

## Course Schedule

*Subject to change.*

| Week (Tues) | Topic | Assignment |
| :--- | :--- | :--- |
| **1 (8/25)** | Introductions, opening survey<br>Open Science framework and FAIR data<br>Version control (git, GitHub) | HW 1 – git and GitHub (due 8/31) |
| **2 (9/1)** | Initial data access and exploration<br>Basic plotting in python<br> | HW 2 – Exploratory Data Analysis (due 9/28) |
| **3 (9/8)** | Project exploration<br>Meetings with instructor about projects | Project outline (due 10/5) |
| **4 (9/15)** | **NO CLASSES THIS WEEK – Conference** | |
| **5 (9/22)** | Oceanographic databases and repositories<br>Oceanographic toolboxes<br>Mapping toolboxes | |
| **6 (9/29)** | Building packages and sharing code<br>Collaborative workspaces | |
| **7 (10/6)** | Machine Learning overview<br>Introduction to scikit-learn | HW 3 – Regression (due 10/19) |
| **8 (10/13)** | **NO CLASS Tuesday 10/13 – Fall Break** | |
| *(Thurs 10/15)* | Supervised Learning Overview of algorithms<br>Training and testing algorithms | |
| **9 (10/20)** | Unsupervised learning<br>Clustering Classification | HW 4 – Classification (due 10/26) |
| **10 (10/27)** | Model evaluation<br>Cross-validation (dealing w/ small training sets) | |
| **11 (11/3)** | Project development | |
| **12 (11/10)** | Machine Learning applications in oceanography<br>Work on projects | |
| **13 (11/17)** | Work on projects | |
| **14 (11/24)** | Work on projects | Project and code review peer evaluation (due 11/30) |
| *(11/26)* | **NO CLASS 11/26 – THANKSGIVING BREAK** | |
| **15 (12/1)** | Work on projects<br>In-class project presentations | Project – report and published GitHub repository (due 12/7) |
| **16 (12/8)** | In-class project presentations (if needed)<br>FAIR data summaries<br>Student opinion surveys | |


