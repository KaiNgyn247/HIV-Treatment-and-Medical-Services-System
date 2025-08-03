# HIV Treatment and Medical Services System 🧬💊

A comprehensive web application built with **Python Flask** using the **Clean Architecture** pattern, designed to manage HIV treatment processes and related medical services. This system aims to streamline patient management, enhance treatment tracking, and improve overall healthcare delivery for individuals living with HIV.

---

##  Features

-  Manage patients, appointments, and treatments  
-  Track prescriptions and test results  
-  Modular architecture (domain, services, infrastructure, API)  
-  Role-based access control  
-  Authentication and Authorization  
-  Swagger API documentation  
-  Unit tests included  

---

##  Project Structure

```
.
├── docs/                         # Project documentation
├── src/
│   ├── api/                      # API routes, schemas, controllers
│   ├── domain/                   # Business logic & interfaces
│   ├── infrastructure/           # Database and repository implementations
│   ├── services/                 # Service layer
│   ├── app.py                    # Main app runner
│   ├── config.py                 # Config settings
│   └── requirements.txt          # Python dependencies
├── README.md
└── .gitignore
```

---

##  Tech Stack

- **Backend:** Python 3, Flask  
- **Architecture:** Clean Architecture  
- **Database:** PostgreSQL (or MS SQL)  
- **API Docs:** Swagger/OpenAPI  
- **Authentication:** JWT / OAuth2  
- **Testing:** Pytest  

---

##  Installation

```bash
# 1. Clone the repository
git clone https://github.com/KaiNgyn247/HIV-Treatment-and-Medical-Services-System.git
cd HIV-Treatment-and-Medical-Services-System

# 2. Create virtual environment
python -m venv venv
venv\Scripts\activate       # Windows
# source venv/bin/activate    # Mac/Linux

# 3. Install dependencies
pip install -r src/requirements.txt

# 4. Configure the database
# Update the database connection settings in src/config.py

# 5. Run the app
python src/app.py
```

---

## 🔍 API Documentation

Visit: `http://localhost:5000/docs`  
This project uses **Swagger UI** to provide live API docs.

---

##  Contributing

Feel free to fork the repo, create a feature branch, and submit a pull request. Contributions are welcome!

---

##  License

This project is licensed under the MIT License.

---

##  Author

**Nguyễn Văn Khải**  
GitHub: [@KaiNgyn247](https://github.com/KaiNgyn247)