# 🧠 Mental Health Web App

A Django-based web application to support **mental wellness** — daily mood tracking, curated resources, and community support.

---

## 🚀 Key Features
- ✅ User registration & authentication (Django auth)  
- ✅ Daily mood / mental-health tracker  
- ✅ Resource library (articles, helplines)  
- ✅ Discussion forum / comment section (optional)  
- ✅ Responsive UI for mobile & desktop

---

## 🛠 Tech Stack
- **Backend:** Python, Django, Django REST Framework  
- **Frontend:** HTML, CSS, JavaScript (can integrate React later)  
- **Database:** SQLite (dev) / PostgreSQL (prod)  
- **Dev Tools:** Git, GitHub, VS Code, virtualenv

---

## Folder Structure
mental-health-app/
├── manage.py                   # Django project manager    
├── requirements.txt            # Python dependencies     
├── README.md                   # Documentation       
├── .gitignore                  # Ignore venv, pycache, env files      
├── config/                     # Project settings          
│   ├── __init__.py      
│   ├── settings.py        
│   ├── urls.py        
│   ├── wsgi.py        
│   └── asgi.py          
├── core/                      # Main app         
│   ├── migrations/            # DB migrations         
│   ├── templates/             # HTML templates              
│   ├── static/                # CSS, JS, Images                      
│   ├── models.py              # Database models                        
│   ├── views.py               # Business logic                    
│   ├── urls.py                # Routes                             
│   └── forms.py               # User forms                      
├── templates/                 # Global templates                        
├── static/                    # Global static files                           
├── media/                     # Uploaded files                       
└── docs/                      # Documentation & screenshots                         
