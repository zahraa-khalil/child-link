# childLink-landingPage

Introduction
Child Link is a web platform designed to help orphanages manage child profiles and connect with potential adopters and donors. The platform allows orphanages to easily register, manage children's data, and facilitate the adoption process. For adopters, it provides a seamless way to browse child profiles and contact the orphanage directly to start the adoption journey.

Deployed Site: Child link landing page - Live Site
Final Project Blog Article: Read the Blog Post
Author's LinkedIn: Your Name - LinkedIn

Installation
Follow these steps to install and run the project locally:

Clone the repository:

https://zahraa-khalil.github.io/child-link/
git clone https://github.com/zahraa-khalil/orphanage.git
Create a virtual environment (recommended):


python3 -m venv venv
source venv/bin/activate  # For Windows, use venv\Scripts\activate
Install dependencies:


pip install -r requirements.txt
Set up environment variables:
Create a .env file in the project root directory and add the required environment variables for your project (database connection, JWT secret, etc.). Example:


FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=your_secret_key
Run the application:

flask run
Access the application:
Visit http://127.0.0.1:5000 in your browser.

Usage
Once the application is running, here are the main features you can use:

Orphanage Registration: Orphanages can sign up to create an account, add children's profiles, and manage their details.
Browse Child Profiles: Potential adopters can browse detailed profiles of children available for adoption, including age, background, and photos.
Admin Dashboard: Admins can review orphanage registrations and approve or reject applications.
Direct Contact: Adopters can contact orphanages directly to begin the adoption process.
Contributing
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:



Related Projects
Adoption Agency Platform
Donation Management System
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
For any inquiries, feel free to reach out via email 
Email: zahraa.khalil2025@gmail.com


