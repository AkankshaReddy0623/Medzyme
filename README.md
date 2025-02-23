# Medzyme

Medzyme is a telemedicine platform designed to facilitate remote diagnosis and monitoring using AI. The platform includes features such as a medicine tracker, report generation, and a user-friendly interface for seamless healthcare access.

## Features
- **Telemedicine Consultation**: Connect with healthcare professionals remotely.
- **Medicine Tracker**: Keep track of prescriptions and medication schedules.
- **Report Generation**: Generate and manage medical reports.
- **User Authentication**: Secure login and sign-up system.

## Project Structure
```
Medzyme/
├── frontend/
│   ├── index.html  # Home Page
│   ├── login.html  # Login Page
│   ├── signup.html # Signup Page
│   ├── telemedicine.html  # Telemedicine Page
│   ├── diagnosis.html  # Diagnosis Page
│   ├── profile.html  # User Profile Page
│   ├── assets/
│   │   ├── css/  # Stylesheets
│   │   ├── js/   # JavaScript files
│   │   ├── images/  # Images & Icons
│   ├── README.md  # This file
├── backend/ (if applicable)
```

## Getting Started
To view and run the project locally, follow these steps:

### 1. Clone the Repository
```sh
git clone https://github.com/AkankshaReddy0623/Medzyme.git
cd Medzyme
```

### 2. Set Up a Local Server
Since this project contains frontend files (HTML, CSS, JavaScript), you need to run it on a local server to avoid CORS issues and enable proper routing.

#### **Using Python (Simple HTTP Server)**
Run the following command in the `frontend` directory:

For Python 3:
```sh
cd frontend
python -m http.server 8000
```
For Python 2:
```sh
python -m SimpleHTTPServer 8000
```
Now, open your browser and visit:
```
http://localhost:8000/index.html
```

#### **Using VS Code Live Server (Recommended)**
1. Install the **Live Server** extension from VS Code.
2. Open the `frontend` folder in VS Code.
3. Right-click `index.html` and select **Open with Live Server**.

## Contributions
Contributions are welcome! If you’d like to improve Medzyme, follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m "Added new feature"`
4. Push the changes: `git push origin feature-branch`
5. Open a Pull Request.

## License
This project is licensed under the MIT License.

---
Feel free to modify or enhance as needed. Happy coding! 🚀