**JOTBOT – A Notes App Using Django**

**📌 Project Overview**

JOTBOT is a simple and efficient Notes App built with Django. It allows users to Create, Read, Update, and Delete (CRUD) notes easily. The project is designed as a beginner-friendly Django application and can be extended further with authentication, search, or categorization features.

🚀 **Features**
1. Create new notes
2. View all saved notes
3. Edit existing notes
4. Delete notes
5. Clean and modern UI

🛠️**Technologies Used**
1. Backend: Django (Python)
2. Frontend: HTML, CSS, Bootstrap (with custom dark theme styling)
3. Database: SQLite (default Django database)

**📂 Project Structure:**

notes_project/
│── manage.py
│── db.sqlite3
│── notes/                
│   │── migrations/
│   │── templates/
│   │   └── notes/
│   │       ├── base.html
│   │       ├── note_list.html
│   │       ├── note_form.html
│   │       └── note_confirm_delete.html
│   │── static/notes/     
│   │── admin.py
│   │── apps.py
│   │── models.py
│   │── urls.py
│   │── views.py
│   └── ...
│── notes_project/        
│   │── settings.py
│   │── urls.py
│   └── ...
└── venv/                 

**⚙️ Installation & Setup**

1. Clone the Repository
git clone https://github.com/ashish-00123/JOTBOT-A-NOTES-APP-USING-DJANGO-.git
cd JOTBOT-A-NOTES-APP-USING-DJANGO-

2. Create Virtual Environment & Activate
python -m venv venv
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Run Migrations
python manage.py migrate

5. Start Development Server
python manage.py runserver

App will be live at: http://127.0.0.1:8000/

**📖 Usage**

1. Go to the homepage to view all notes.
2. Click "Add Note" to create a new note.
3. Use Edit to update an existing note.
4. Use Delete to remove a note.

