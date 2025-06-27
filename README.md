# Dynamic Form Generator

A modern, full-stack web application for building, managing, and submitting dynamic forms. This project features a robust Angular frontend and a Python (FastAPI) backend, enabling users to create, edit, and track form templates and submissions with ease.

## Features

- **Dynamic Form Builder:** Create and customize forms with various field types and validation rules.
- **Template Management:** View, edit, and maintain a history of form templates.
- **Submission Viewer:** Review and manage form submissions in a user-friendly interface.
- **Theme Toggle:** Switch between light and dark modes for optimal user experience.
- **Real-Time Date/Time:** Displays current date and time in the header.
- **Modern UI:** Responsive, accessible, and visually appealing design using Angular Material.
- **Backend API:** FastAPI-based backend for form data storage, retrieval, and template management.

## Technologies Used

- **Frontend:** Angular, Angular Material, SCSS
- **Backend:** Python, FastAPI, SQLite (or your preferred database)
- **Other:** TypeScript, HTML5, CSS3

## Folder Structure

```
├── backend/                # Python FastAPI backend
│   ├── __init__.py
│   ├── database.py
│   ├── main.py
│   ├── models.py
│   └── requirements.txt
├── public/                 # Static assets
├── src/                    # Angular frontend source
│   ├── app/                # Main Angular app code
│   │   ├── dynamic-form/   # Dynamic form builder components
│   │   ├── template-history/ # Template history components
│   │   └── ...
│   ├── index.html
│   ├── main.ts
│   └── styles.scss
├── angular.json            # Angular project config
├── package.json            # Node dependencies
├── tsconfig.json           # TypeScript config
├── README.md               # Project documentation
└── ...
```

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn
- Python 3.10+

### Frontend Setup (Angular)
```bash
# Install dependencies
npm install

# Start the Angular development server
npm start
# or
ng serve
```
The app will be available at `http://localhost:4200`.

### Backend Setup (FastAPI)
```bash
# Navigate to backend directory
cd backend

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the FastAPI server
uvicorn main:app --reload
```
The API will be available at `http://localhost:8000`.

## Usage
- Access the Angular app in your browser.
- Use the UI to create, edit, and manage form templates.
- Submit forms and view submissions.
- Toggle between light and dark themes.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for new features, bug fixes, or improvements.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License
This project is licensed under the MIT License.

