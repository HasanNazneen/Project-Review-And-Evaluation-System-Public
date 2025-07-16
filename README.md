#Project Review And Evaluation System

A web-based system designed to streamline the process of submitting, reviewing, and evaluating projects. It provides tools for administrators, guides, and students to collaborate efficiently in academic project assessments.

#Description

- User authentication and role management (Admin, Guides, Students)
- Project submission with file uploads
- View submission status and review projects.
- Add qualitative feedback and approve/reject projects.
- Check for title similarity among the uploaded projects to avoid similar projects.

#Steps to run:
1.Clone the Repository
git clone https://github.com/HasanNazneen/Project-Review-And-Evaluation-System-Public.git

2.Set Up Virtual Environment
python -m venv venv
venv/Scripts/activate

3.Install Dependencies
pip install -r requirements.txt

4.Run the project
python run.py

5.Application runs at
http://127.0.0.1:5000

#Features

Student Portal - Login And Registration, Upload Documents to Guide, HOD, Receive Feedback and submit the final project details to HOD if approved.
Guide Portal - Login and Registration, Receive Documents from Student, Give feedback and either approve or reject, Check project status. |
Head of the Department -Login and registration, Receive approved projects from students, Give feedback and either approve or reject, Check project status, Approved project will make it to the final List.


#Tech Stack
- Python
- Flask
- SQLite
- Natural Language Processing(Sentence Transformers)

Acknowledgments
- Inspired by real-world academic review processes.
- Built using Flask, SQLite, and Sentence Transformers. 

