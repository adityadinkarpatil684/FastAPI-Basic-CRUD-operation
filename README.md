# 🏥 FastAPI Patient CRUD App

A simple backend application using **FastAPI** to perform **CRUD operations** on patient data stored in a `patient.json` file. It leverages **Pydantic** for data validation.

---

## 📁 Project Structure

```
fastapi-patient-crud/
├── __pycache__/
├── myenv/                   # Virtual environment
├── main.py                  # FastAPI app with CRUD logic
├── patient.json             # JSON file to store patient data
```

---

## 🚀 Features

* ✅ Create a new patient record
* 📖 Read patient data (all or by ID)
* 📝 Update patient information
* ❌ Delete a patient record
* 🔐 Data validation with **Pydantic**

---

## ⚙️ Setup Instructions

1. **Create a virtual environment**:

   ```bash
   python -m venv myenv
   ```

2. **Activate the virtual environment**:

   * On **Windows**:

     ```bash
     myenv\Scripts\activate
     ```
   * On **Unix or MacOS**:

     ```bash
     source myenv/bin/activate
     ```

3. **Install the dependencies**:

   ```bash
   pip install fastapi pydantic uvicorn
   ```

4. **Run the FastAPI application**:

   ```bash
   uvicorn main:app --reload
   ```

5. **Test the API**:
   Open your browser and go to:

   * Swagger UI: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)
   * ReDoc: [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

---

## 📄 patient.json

A simple JSON file that stores patient records in a list format.

---

## 📦 Dependencies

* [FastAPI](https://fastapi.tiangolo.com/)
* [Pydantic](https://docs.pydantic.dev/)
* [Uvicorn](https://www.uvicorn.org/)

---

## 🧪 Example API Endpoints

* `GET /patients` → Get all patients
* `GET /patients/{id}` → Get patient by ID
* `POST /patients` → Create new patient
* `PUT /patients/{id}` → Update existing patient
* `DELETE /patients/{id}` → Delete patient by ID

---

## 📬 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

This project is licensed under the MIT License.
