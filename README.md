# Upskill - E-Learning Platform

Upskill is an interactive, responsive web-based e-learning platform designed to help students and professionals enhance their skills in various domains such as Artificial Intelligence, Web Development, Data Science, and Design.

## Features

- **Responsive Design**: Optimized for seamless viewing and interaction across all screen sizes using a modern CSS Grid layout.
- **Interactive User Interface**: Smooth transitions, dynamic states (hover/active), and clean, minimalist styling.
- **Login Authentication Simulation**: Persistent Login/Signup system using client-side `localStorage`. Users must sign up before accessing course content.
- **Course Catalog**: A dedicated section displaying popular courses with ratings, prices, and detailed curriculum information via dynamic course pages.
- **Enrollment System Simulation**: Mock course enrollment feedback mechanisms using JavaScript alerts.
- **Multi-Page Navigation**: Separate pages for Home, About, Courses, Course Details, and Contact, all linked logically.

## Technologies Used

- **HTML5**: For structural semantics, page layout, and crisp, indentation-formatted code.
- **CSS3**: Vanilla CSS for styling, custom CSS Grid layouts, and modern visual aesthetics (no external frameworks).
- **JavaScript**: Vanilla JS for interactive elements such as login messaging, authentication checks, and enrollment notifications.
- **XML & XSD**: For structured data storage and schema validation.

## Folder Structure

The repository maintains a clean and organized folder hierarchy:

```text
E-Learning-Platform
│
├── pages/                 # Contains all sub-page HTML files
│   ├── about.html         # About Us page
│   ├── courses.html       # Courses catalog 
│   ├── course-details.html# Comprehensive curriculum and instructor details
│   └── contact.html       # Contact info and form
│
├── styling/               # Contains modular CSS styling files
│   ├── about.css          # Styling for the About page
│   ├── courses.css        # Styling for the Courses page
│   ├── course-details.css # Styling for the Course Details page
│   └── contact.css        # Styling for the Contact page
│
├── data/                  # XML and XSD files for structured data
│   ├── courses.xml        
│   └── courses.xsd
│
├── index.html             # Homepage and Login (Entry Point)
├── index.css              # Main stylesheet for the Homepage
├── img.jpeg               # Hero background asset
└── README.md              # Project documentation
```

## How to Run This Project Locally

This project does not require any backend server or build process to run. Follow these standard steps to view it on your local machine:

1. **Clone the repository** (if you haven't downloaded the zip file directly):
   ```bash
   git clone https://github.com/PravAl2028/E-Learning-Platform.git
   ```
2. **Navigate into the project directory**:
   ```bash
   cd E-Learning-Platform
   ```
3. **Open the project in a browser**:
   - Simply double-click on `index.html` in the root directory.
   - Alternatively, open your preferred web browser (Google Chrome, Firefox, Edge, etc.) and drag `index.html` into the window.
   - For an optimal view in your code editor, you can use the Live Server extension in VS Code.

## Usage Highlights

- **Home Page (`index.html`)**: Features the primary layout, quick course highlights, and the login/signup area.
- **Courses Page (`pages/courses.html`)**: View the available courses. Clicking any course ensures users are logged in.
- **Course Details (`pages/course-details.html`)**: View the detailed breakdown of the courses, explaining their structure and duration. Clicking "Enroll Now" provides visual feedback.
- **Navigation Navbar**: Allows intuitive, responsive routing throughout the platform, stacking smartly on mobile devices.
