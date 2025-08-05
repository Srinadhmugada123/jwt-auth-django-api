# 🔐 JWT Authentication API with Django & DRF

This is a simple Django REST Framework (DRF) backend project that implements user **registration**, **login**, **logout**, and **JWT token-based authentication** using `djangorestframework-simplejwt`.

---

## 🚀 Features

- ✅ User Registration
- ✅ JWT Login (access & refresh tokens)
- ✅ Logout (Blacklist refresh token)
- ✅ JWT configuration in settings
- ✅ API tested using Postman or frontend
- ✅ Secure Protected View Example (Optional)

---

## 📁 Project Structure

jwt-auth-django-api/
├── authapp/ # App with views, serializers, URLs
│ ├── views.py
│ ├── serializers.py
│ └── urls.py
├── jwt_auth_project/
│ └── settings.py # JWT & DRF settings
├── manage.py
└── requirements.txt

---

## 🧑‍💻 Technologies Used

- Python 3.x
- Django 3.x or 4.x
- Django REST Framework
- Simple JWT (`djangorestframework-simplejwt`)

---

## 🔧 Installation & Setup

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/jwt-auth-django-api.git
cd jwt-auth-django-api.

2. Create Virtual Environment
python -m venv venv
source venv/bin/activate

3. Install   Dependencies
pip install -r requirements.txt

4. Apply Migreations
py manage.py makemigrations
py manage.py migrate

5. Run The Server
py manage.py runserver
