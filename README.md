Node & Dotnet Core Additional Practice Exercise.
 
Case Study: MCQ Exam Portal

Client Background:ABC University wants to digitalize their examination process for multiple-choice questions. They have decided to develop an online exam portal to conduct MCQ-based exams efficiently.

Requirements:
User Authentication: Users should be able to sign up, log in, and reset their passwords.
Exam Creation: Professors should be able to create exams, specifying the number of questions, time limit, and other details.
Question Bank: Maintain a repository of questions categorized by subject or topic.
Exam Taking: Students should be able to take exams once they're scheduled, with a countdown timer and an option to submit before the time expires.
Scoring: Automatic scoring and instant feedback for students after submitting the exam.
Results: Display exam results to both students and professors.

Proposed Solution:
Frontend Development: Use HTML, CSS, and JavaScript to create an intuitive user interface. Consider using frameworks like React.js for dynamic UI elements.
Backend Development: Utilize Node.js for server-side scripting. Choose a database system like MongoDB to store user data, exam details, and question banks.
User Authentication: Implement authentication using packages like Passport.js, allowing users to sign up, log in, and reset passwords securely.
Exam Creation: Design an interface for professors to create exams. Store exam details in the database and associate questions from the question bank.
Question Bank: Develop a feature to manage questions, including adding, editing, and deleting questions. Organize questions by categories for easy retrieval.
Exam Taking: Create a timer component using JavaScript for exams. Implement logic to prevent users from navigating away or accessing exam content after submission.
Scoring: Develop an algorithm to calculate scores based on user responses compared to the correct answers. Store scores in the database for later retrieval.
Results: Display exam results to students immediately after submission. Professors should have access to detailed results for grading purposes.

Multiselect and single select both the question can be there
