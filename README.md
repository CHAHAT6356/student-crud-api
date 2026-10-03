\# Student CRUD API



A simple Student Management REST API built using \*\*FastAPI\*\* and \*\*Python\*\*. This project provides CRUD (Create, Read, Update, Delete) operations for managing student records using in-memory storage.



\## 🚀 API Documentation



\*\*Swagger UI / API:\*\*



`http://127.0.0.1:8000/docs`



The `/docs` URL opens the interactive Swagger documentation.



\## 📌 Main Endpoints



Supports:



\* `POST /students`

\* `GET /students`

\* `GET /students/{student\_id}`

\* `PUT /students/{student\_id}`

\* `DELETE /students/{student\_id}`



\## ✨ Features



\* Create a new student

\* Retrieve all students

\* Retrieve a student by ID

\* Update existing student details

\* Delete a student

\* Input validation using Pydantic

\* Proper HTTP status codes

\* Interactive API documentation using Swagger UI

\* In-memory student data storage



\## 🛠️ Tech Stack



\* Python

\* FastAPI

\* Pydantic

\* Uvicorn



\## 📁 Project Structure



```text

student-crud-Asm1/

│

├── controllers/

│   └── student\_controller.py

│

├── models/

│   └── student\_model.py

│

├── routes/

│   └── student\_routes.py

│

├── main.py

├── requirements.txt

└── README.md

```



\## ⚙️ Installation and Setup



\### 1. Navigate to the project folder



```bash

cd student-crud-Asm1

```



\### 2. Install dependencies



```bash

pip install -r requirements.txt

```



\### 3. Run the application



```bash

uvicorn main:app --reload

```



\### 4. Open the API documentation



Visit:



`http://127.0.0.1:8000/docs`



\## 🧪 Testing



Use Swagger UI to test all five CRUD endpoints.



1\. Open `/docs`.

2\. Select an endpoint.

3\. Click \*\*Try it out\*\*.

4\. Enter the required student data.

5\. Click \*\*Execute\*\*.

6\. View the API response.



\## 💾 Data Storage



This project uses \*\*in-memory storage\*\*. Student records are not permanently saved and are cleared whenever the application restarts.



\## 📊 Student Fields



Each student record contains:



\* `id` — Student ID

\* `name` — Student name

\* `email` — Student email

\* `course` — Student course

\* `semester` — Current semester



\## 🔗 API Response Codes



\* `201` — Student successfully created

\* `200` — Request successfully completed

\* `204` — Student successfully deleted

\* `404` — Student not found

\* `422` — Validation error



\## 👨‍💻 Author



\*\*Nikunj Makwana\*\*



GitHub: `Your GitHub Profile`



Repository: `student-crud-Asm1`



````



This is aligned with Assignment 2's requirement that the README explain \*\*what the project is and how to run it\*\*.



\### Now do this



Save this as:



```text

README.md

````



inside:



```text

C:\\Desktop\\sem 7\\Dev Opps\\Assignment\\student-crud-Asm1

```



Then run:



```cmd

dir

```



and confirm that \*\*`README.md` appears\*\*.



After that we'll do the \*\*second Git commit\*\*.



