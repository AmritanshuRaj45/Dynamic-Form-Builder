# Dynamic Form Builder

## 🚀 Overview
Dynamic Form Builder is a next-generation, full-stack web application that empowers users to design, manage, and deploy dynamic forms with zero code. Built with a modern Angular frontend and a robust Python FastAPI backend, it offers a seamless, interactive, and highly customizable experience for individuals, teams, and enterprises.

---

## ✨ Key Features

- **No-Code Dynamic Form Builder:** Effortlessly create complex forms with drag-and-drop, conditional logic, custom validations, and a wide variety of field types (text, dropdown, boolean, number, etc.).
- **Template Versioning & History:** Instantly track, compare, and restore previous versions of any form template. Visual diff viewer highlights every change.
- **Submission Management:** View, filter, and manage all form submissions. Drill down into individual responses, compare versions, and export data.
- **Team Collaboration:** Assign templates to teams, track authorship, and enable collaborative editing.
- **Theme Toggle:** Switch between beautiful light and dark modes for optimal comfort.
- **Real-Time Date/Time:** Always know when you’re working—current date and time are displayed in the header.
- **Modern, Responsive UI:** Built with Angular Material for a sleek, accessible, and mobile-friendly experience.
- **Animated Feedback:** Enjoy delightful animated popups for actions, confirmations, and notifications.
- **Custom Dialogs:** Interactive, context-aware dialogs for confirmations, prompts, and help.
- **Helpdesk & Support:** Integrated helpdesk for FAQs and support ticket submission.
- **Powerful Backend API:** FastAPI backend with MongoDB for scalable, secure, and lightning-fast data operations.
- **Secure Authentication (Planned):** Password hashing and user authentication ready for enterprise use.
- **Extensible Schema:** Easily add new field types, validation rules, and integrations.
- **Audit Trail:** Every change is logged for compliance and transparency.
- **Export & Import:** Export templates and submissions for backup or migration.
- **Accessibility First:** WCAG-compliant design for all users.

---

## 🖥️ Technologies Used

- **Frontend:** Angular, Angular Material, SCSS, TypeScript, HTML5
- **Backend:** Python, FastAPI, MongoDB (via Motor), Pydantic
- **Other:** RxJS, bcrypt, dotenv, DeepDiff, and more

---

## 📁 Folder Structure

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

---

## ⚡ Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn
- Python 3.10+
- MongoDB (local or Atlas)

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
venv\Scripts\activate  # On Windows

# Install dependencies
pip install -r requirements.txt

# Configure MongoDB connection in .env
# Example: MONGO_DETAILS=mongodb+srv://<user>:<password>@cluster.mongodb.net/?retryWrites=true&w=majority

# Run the FastAPI server
uvicorn main:app --reload
```
The API will be available at `http://localhost:8000`.

---
## 🎬 Demo
### landing page(light mode)
![image](https://github.com/user-attachments/assets/4a4752ea-5d6d-47be-b531-b529394aa8a8)

### landing page(Dark mode)
![image](https://github.com/user-attachments/assets/d3bf256c-b25d-4179-904d-927e7d861823)

### creation of a Form Template
![image](https://github.com/user-attachments/assets/4f17ff2f-5763-4758-9e27-b4173ddf39af)
### Adding new field

![image](https://github.com/user-attachments/assets/30ded009-b436-468e-b43c-8a6c12001a5d)

### History of updation of Form
![image](https://github.com/user-attachments/assets/64334d7e-f19c-47bc-b5d6-0da93c990e9a)

### check the Submission(Responses) with comparision Feature
![image](https://github.com/user-attachments/assets/f17dba88-614a-49a1-ac9c-b0915cd689b9)

### there are two view option tab view and list view
### following is the list view :
![image](https://github.com/user-attachments/assets/7e091483-bdaa-4905-bbf0-c01abc419776)
### various data type Supported

![image](https://github.com/user-attachments/assets/68309296-8b10-45a1-b83d-e58cb0a7bb14)

### live preview pane during creation of Form
![image](https://github.com/user-attachments/assets/4f7c26b2-abb7-4cce-bee7-d3b888db7d19)

### Search bar with Advanced search Feature
![image](https://github.com/user-attachments/assets/45c65b9a-8c5b-42a8-84e4-6fe0017d8eac)



*This section will be updated in the future with a full walkthrough and a live demo link. Stay tuned!*

---
## 🌟 Wow Features (Why You'll Love It)

- **Drag-and-Drop Form Creation:** Instantly build forms with a beautiful, interactive UI.
- **Live Preview:** See your form as you build it—no guesswork.
- **Conditional Logic:** Show/hide fields based on user input.
- **Field-Level Validation:** Regex, required, custom rules, and more.
- **Template Version Diff:** Visualize changes between template versions with a built-in diff viewer.
- **Submission Comparison:** Compare responses across different submissions.
- **Animated Popups:** Enjoy smooth, modern feedback for every action.
- **Team & Author Tracking:** Know who created or edited every template.
- **Helpdesk Integration:** Get help or submit issues directly from the app.
- **Export/Import:** Move your templates and data anywhere.
- **Mobile-Ready:** Use it on any device, anywhere.
- **Extensible:** Add new field types, integrations, and automations easily.
- **Secure:** Passwords are hashed, and authentication is ready for production.
- **Audit Trail:** Every change is logged for compliance.
- **Accessibility:** Designed for everyone, everywhere.

---

## 🔥 Use Cases

- Internal tools for enterprises
- Customer feedback forms
- Event registrations
- Surveys and polls
- Workflow automation
- Data collection for research
- And much more!

---

## 🛠️ Contributing
Contributions are welcome! Please open issues or submit pull requests for new features, bug fixes, or improvements.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

---

## 📜 License
This project is licensed under the MIT License.

---




