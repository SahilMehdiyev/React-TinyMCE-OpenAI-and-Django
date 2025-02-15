# **React TinyMCE + OpenAI + Django**

This project integrates **React, TinyMCE, OpenAI API, and Django** to provide an intelligent text editing experience. Users can create and edit content with **TinyMCE**, while OpenAI enhances the editor with AI-powered suggestions.

---

## 🚀 **Technologies Used**
- **Frontend:** [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Text Editor:** [TinyMCE](https://www.tiny.cloud/)
- **AI Integration:** [OpenAI API](https://openai.com/)
- **Backend:** [Django](https://www.djangoproject.com/) + Django REST Framework (DRF)

---

## 📂 **Project Structure**
```
React-TinyMCE-OpenAI-and-Django
│── backend/            # Django backend (API and AI processing)
│   ├── src/            # Django source files
│   ├── manage.py       # Django entry point
│   ├── requirements.txt # Dependencies for the backend
│── frontend/           # React frontend (TinyMCE & OpenAI integration)
│   ├── src/            # React source files
│   ├── package.json    # Dependencies for the frontend
│── README.md           # Project documentation
```

---

## ⚡ **Installation and Setup**

### 🔹 **1. Clone the Repository**
```bash
git clone https://github.com/SahilMehdiyev/React-TinyMCE-OpenAI-and-Django.git
cd React-TinyMCE-OpenAI-and-Django
```

### 🔹 **2. Backend Setup (Django)**
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Create and activate a virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # Windows users: .venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```bash
   python manage.py migrate
   ```
5. Run the Django development server:
   ```bash
   python manage.py runserver
   ```
   
---

### 🔹 **3. Frontend Setup (React + Vite)**
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

---

## 🎯 **Usage**
- Open **http://localhost:5173/** to access the frontend.
- The **TinyMCE editor** is integrated with OpenAI to provide AI-powered text generation.
- The backend API processes and responds to requests from the editor.

---

## 🔥 **Key Features**
✅ **Rich Text Editing**: Provides a WYSIWYG editor for enhanced content creation.  
✅ **AI-Powered Suggestions**: OpenAI API integration helps users generate intelligent text suggestions.  
✅ **Fast and Lightweight**: Built using Vite for optimal performance.  
✅ **Scalable Architecture**: Django REST Framework ensures a robust backend API.  

---

## 📜 **Environment Variables**
To configure API keys and settings, create a `.env` file in the backend directory and add:
```ini
OPENAI_API_KEY=your_openai_api_key
DEBUG=True
```

For the frontend, create a `.env` file in the `frontend` directory:
```ini
VITE_OPENAI_API_KEY=your_openai_api_key
```

---

## 🚀 **Contributing**
Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 **License**
This project is licensed under the **MIT License**.

---

## 🎉 **Author**
Developed by [Sahil Mehdiyev](https://github.com/SahilMehdiyev).  

Happy coding! 🚀✨

