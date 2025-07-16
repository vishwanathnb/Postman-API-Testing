API Testing with Postman

This repository contains API testing collections created using Postman. The purpose is to test student-related APIs for various operations such as GET, POST, PUT, and DELETE And validate the Responses by Writing the Scripts.

Project Structure ├── Student_Api.postman # Postman collection (custom file) ├── Student.json # Sample student data payload

Features Covered

✔️ Create a new student (POST)
✔️ Get student details (GET)
✔️ Update student details (PUT)
✔️ Delete student record (DELETE)
✔️ Validations for invalid inputs
✔️ JSON body with headers and authentication
How to Use

Open Postman.
Click Import → Select Student_Api.postman
Open the Command Prompt in the Desktop and create the remote api *navigate to the file (Student.json) location in the cmd promt *Run the cmd prompt (json-server Student.json) to keep the api alive and don't close the cmd prompt
Explore the saved requests under Collections.
Run requests individually or use Runner for automation.
Tools Used

Postman for REST API testing JSON format for payloads and collections Local environment setup

Future Improvements

Add Newman for CLI test automation Write test cases using Postman tests (JavaScript snippets) Include environment variables for dynamic URLs.

Author
Vishwanath 
vishwanathbiradar236@gmail.com
Bangalore, India
