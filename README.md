# ai2model
An image converting platform built with the Python. Converts 2D images to 3D models which can be used as assets for designing and game development.


An interactive web app combining **Django** (as the web framework) and **Gradio** (for ML model interfaces).  
Deployed using [Render](https://render.com).

---

## 🚀 Features
- Django web interface  
- Gradio components  
- REST APIs

---

## 🧰 Tech Stack
- Python 3.x  
- Django  
- Gradio  

---

## ⚙️ Local Setup

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/django-gradio-app.git
cd django-gradio-app

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate   # (Windows: venv\Scripts\activate)

# 3. Install dependencies
pip install -r requirements.txt

# 4. Apply migrations
python manage.py makemigrations
python manage.py migrate

# 5. Run locally
python manage.py runserver
