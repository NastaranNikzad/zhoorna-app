# zhoorna-app
💬 A note-sharing and messaging platform for students

📚 ZHORNA | ژورنا

ZHORNA is a modern web application designed to simplify academic note sharing, promote collaborative learning, and streamline student communication through an internal messaging system.

## ✨ Key Features

- ✅ Sign up with phone number & OTP verification  
- ✅ Upload and tag course notes (with subject, university, instructor)  
- ✅ Preview and download shared notes (PDF or image)  
- ✅ Page-specific comments and Q&A for each document  
- ✅ In-app SMS-style messaging  
- ✅ User profile with activity history  

## 📁 Project Folder Structure

```plaintext
ZHORNA/
│
├── frontend/            ← HTML, CSS, JS or React components
├── backend/             ← Django project (settings, models, views, API)
├── static/              ← Brand assets: logo, fonts, images
├── wireframes/          ← UI designs, PNG mockups, UX assets
├── docs/                ← Proposal documents, brand guideline PDF
│
├── README.md            ← This project file
├── requirements.txt     ← Python dependencies (e.g. Django, Pillow)
├── .gitignore
├── LICENSE
````

## 🧪 How to Run Locally

1. Download the project files manually from this repository.

2. Extract the ZIP file and open the project folder.

3. Navigate to the `/backend` directory using terminal.

4. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

5. Install required Python packages:

   ```bash
   pip install -r ../requirements.txt
   ```

6. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

7. Start the development server:

   ```bash
   python manage.py runserver
   ```

8. Open your browser and visit:
   **[http://127.0.0.1:8000](http://127.0.0.1:8000)**

## 🧰 Tech Stack

* Django (Python)
* HTML / CSS / JavaScript
* Bootstrap or TailwindCSS
* SQLite (development) → PostgreSQL (production)
* SMS API (e.g. SMS.ir or Kavenegar)
* Git + GitHub

## 💰 MVP Development Cost (IRR – Estimated)

| Item                     | Estimated Cost (in Toman) |
| ------------------------ | ------------------------- |
| Backend + Frontend Dev   | 25M – 30M                 |
| Hosting + Domain + SSL   | 1M – 1.5M                 |
| SMS Platform Integration | 600K                      |
| Initial Ads & Marketing  | 3M – 5M                   |
| Miscellaneous            | 2M                        |
| **Total**                | **\~32M – 40M Toman**     |

## 👤 About

* **Project Name:** ZHORNA
* **Founder & Designer:** Ms. Nikzad
* **Website:** Coming soon
* **Email:** [gitnikna@gmail.com](mailto:gitnikna@gmail.com)
* **Phone:** +98 9xx xxx xxxx

## 📄 License

This project is licensed under the MIT License.
See the [LICENSE](./LICENSE) file for details.

## 🤝 Contribution

Contributions are welcome!
Please feel free to fork, open issues, or submit pull requests.

