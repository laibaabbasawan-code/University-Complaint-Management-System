# University-Complaint-Management-System
University Complaint Management System built with Bolt/React and n8n. Students submit complaints through the frontend, while n8n generates a unique Complaint ID, stores complaint data, sends automated Gmail confirmation, and returns the response to the frontend. A practical project exploring webhooks and workflow automation
🚀 University Complaint Management System

A web-based University Complaint Management System that connects a modern frontend with an automated backend workflow using n8n.

The project is currently under development, with more features planned for future versions.

✨ Current Features
📝 Student complaint submission form
🆔 Automatic unique Complaint ID generation
⚙️ Frontend-to-n8n communication using Webhooks
🗄️ Complaint data storage using n8n Data Tables
📧 Automatic confirmation email using Gmail
📤 Response from n8n back to the frontend
📊 Admin dashboard for viewing complaints
🏗️ Architecture
Student
   ↓
Bolt / React Frontend
   ↓
n8n Webhook
   ↓
Code Node
   ↓
Generate Complaint ID
   ↓
Data Table
   ↓
Store Complaint
   ↓
Gmail
   ↓
Send Confirmation Email
   ↓
Respond to Webhook
   ↓
Frontend
🛠️ Technologies Used
Bolt.new — Frontend development
React — Frontend framework
Vite — Development/build tool
JavaScript — Application logic
n8n — Backend workflow automation
n8n Webhook — Frontend/backend communication
n8n Code Node — Complaint ID generation
n8n Data Table — Complaint data storage
Gmail — Automated email notifications
GitHub — Version control and project sharing
🔄 How It Works
A student submits a complaint through the frontend.
The frontend sends the complaint data to an n8n Webhook.
n8n receives the submitted information.
A Code Node generates a unique Complaint ID.
The complaint information is stored in the n8n Data Table.
Gmail automatically sends a confirmation email to the student.
The Respond to Webhook node sends the Complaint ID back to the frontend.
The frontend displays the successful submission.
📌 Project Status

🟡 In Progress

This is an ongoing project. Future versions will include additional functionality and improvements to make the system more complete and production-oriented.

🔮 Future Improvements
Complaint tracking
Complete complaint status management
Automatic department assignment
Improved admin dashboard
Advanced notifications
AI-powered complaint classification
Analytics and reporting
👩‍💻 Developer

Laiba Abbas

Built as a learning and portfolio project to explore web development, backend integration, workflow automation, and n8n.
