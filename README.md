# 💼 DevShowcase

DevShowcase is a full stack portfolio management app where developers can easily add and display their projects. It provides a simple UI to showcase your work and is powered by a MongoDB, Express, and React stack.

---

## ✨ Features

- Add new projects via a form
- Store project data in MongoDB
- Display project details on the frontend
- Responsive and clean UI
- Modern full stack architecture

---

## 🚀 Tech Stack

**Frontend**  
- React  
- Axios  
- CSS Modules / Plain CSS (no Tailwind)

**Backend**  
- Node.js  
- Express  
- MongoDB  
- Mongoose

---

## 📸 Screenshots

_Add screenshots of your app here (optional but recommended)_

---

## 🧑‍💻 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/devshowcase.git
cd devshowcase

### 2. Setup backend
cd server
npm i

Create a .env file in the backend folder and add your MongoDB URI:
MONGO_URI=your-mongodb-connection-string

Start the backend server:
node server.js


3. Setup frontend
cd ../client
npm install
npm start

🛠️ API Endpoints
POST /projects
Add a new project.

Request Body:
{
  "title": "Project Title",
  "description": "Description here...",
  "techStack": ["React", "Node.js"],
  "githubLink": "https://github.com/yourrepo",
  "liveDemo": "https://yourliveapp.com",
  "screenshot": "https://image.url"
}
GET /projects
Get all saved projects.

📂 Folder Structure
devshowcase/
├── client/    # React frontend
├── server/     # Node.js + Express backend
│   └── models/  # Mongoose schemas
│   └── server.js


📌 TODO
1.Add user authentication
2.Enable editing and deleting projects
3.Add tags/filter by tech stack
4.Deploy on Vercel + Render


Render

🧑‍🎨 Author
@bhaviiii24

📃 License
This project is open source and available under the MIT License.


---

Let me know if you want this README tailored for deployment, with custom screenshots, or adjusted based on changes to your stack.







