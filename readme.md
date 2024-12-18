
User Management System Final Project 🎉✨🔥

---

About the Project 🌟

The User Management System is a robust, scalable platform designed to manage user accounts with features like:
- User Registration
- Authentication
- Authorization
- Profile Management
- Professional Status Toggling

This project emphasizes teamwork, quality assurance, and test coverage to simulate real-world development scenarios.
---
Implemented Features 🚀

- Professional Status Toggle:
  - Endpoint: /users/{user_id}/upgrade-professional
  - Allows admins or managers to toggle a user's professional status.

---

Project Highlights 🔥

Closed Issues:
- #5: Upgrade to Toggle
- #4: Connect to MinIO Bucket
- #3: Admin Create User Authentication Email Issue
- #2: Create_User Response
- #1: [Your Issue Title]

New Tests:
Test Files:
- Test_users_api.py
  - Upgrade to Professional - Success
  - Upgrade to Professional - User Not Found
  - Upgrade to Professional - Unauthorized Access
  - Upgrade to Professional - Access Denied
  
- Test_user_model.py
  - Set Professional Status - True
  - Set Professional Status - False
  
- Test_upgrade_to_professional.py
  - Toggle Professional Status - Success
  - Toggle Professional Status - Multiple Toggles
  - Toggle Professional Status - Non-Existent User
  - Toggle Professional Status - Already Professional

---

Deployment 🌐

The project is successfully deployed to DockerHub.  
DockerHub Repository: [Link to DockerHub Repository]

---

Reflection 📝

This project provided an incredible learning experience, helping me:
1. Understand real-world software workflows.
2. Develop robust testing skills through TDD and QA processes.
3. Explore new technologies like MinIO. While I couldn’t fully implement it for profile picture functionality, I plan to use it in future personal projects to enhance object storage capabilities.

---

How to Test 🤝

1. Clone the repository:
   git clone <repository-link>
   cd user-management-system

2. Set up the project:
   docker compose up

3. Run the tests:
   docker compose exec fastapi pytest tests/

---

Let’s conquer the world of software engineering, one epic project at a time! 🚀🌟✨
