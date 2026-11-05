# JobConnect — Job Recruitment Website (Frontend Prototype)

A responsive job recruitment website built with HTML5, CSS3, JavaScript (ES6+) and Bootstrap 5.

## Run the project
1. Extract the ZIP file.
2. Open the `jobconnect` folder in Visual Studio Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.
4. Bootstrap, Bootstrap Icons and Google Fonts are loaded from CDNs, so an internet connection is needed for those assets.

## Features
- Responsive landing page and featured job cards
- Keyword, location, category and job-type filtering
- Salary sorting
- Job detail modal
- Save/unsave jobs using LocalStorage
- Demo job application form
- Employer job-posting form
- Demo sign-in form
- Browser-local persistence for jobs, saved jobs, applications and demo session

## Project structure
```text
jobconnect/
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── data.js
│   └── app.js
└── README.md
```

## Important limitations
This is a frontend learning prototype. LocalStorage is specific to one browser and is not secure. The sign-in form does not authenticate users, and job applications are not sent to employers. A production platform needs a backend API, database, secure password hashing, authorization, validation, file upload handling, and deployment configuration.

## Suggested next steps
1. Refactor the page into reusable components or separate pages.
2. Add a backend (for example Node.js + Express) and a database.
3. Implement secure authentication and role-based access (job seeker/employer/admin).
4. Add CV upload, application tracking, employer management, and admin moderation.
5. Add tests and deploy.
