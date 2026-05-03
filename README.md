🎓 Face Recognition Attendance System

A Python-based application that uses **face recognition technology** to automatically mark student attendance. This system helps reduce manual work and improves accuracy in attendance tracking.

---

## 📌 Features

* 👤 Student Registration
* 🔐 User Login System
* 📸 Face Detection & Recognition
* 🗂️ Automatic Attendance Marking
* 📊 Attendance Stored in CSV File
* 🧠 Model Training Support

---

## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* Pandas
* Face Recognition Library

---

## 📁 Project Structure

```
Face-Recognition-Attendance/
│── attendance.py          # Handles attendance marking
│── attendance.csv         # Stores attendance records
│── databaseTest.py        # Database connection/testing
│── developer.py           # Developer module
│── face_recognition.py    # Face detection & recognition
│── helpsupport.py         # Help/support module
│── login.py               # Login functionality
│── register.py            # Student registration
│── student.py             # Student data handling
│── train.py               # Model training
│── main.py                # Main entry point
│── README.md              # Project documentation
```

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

```bash
python main.py
```

---

## 📦 Requirements

Create a `requirements.txt` file with:

```
opencv-python
numpy
pandas
face-recognition
```

---

## 🚀 How It Works

1. Register a student with their details
2. Capture and store face data
3. Train the model using `train.py`
4. Run the system using `main.py`
5. Attendance is automatically recorded when a face is recognized

---

## 📊 Output

* Attendance is saved in `attendance.csv`
* Each record includes:

  * Name
  * Date
  * Time

---

## 🔒 Future Improvements

* Database integration (MySQL / SQLite)
* GUI enhancement
* Cloud-based storage
* Real-time dashboard

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📧 Contact

For any queries or support, please reach out.
