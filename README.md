Keeper — Simple Notes App 🗒️✨

Tiny, fast, and clean note-taking app where you can add notes (title + content) and delete them. Perfect for quick ideas, to-dos, and brain dumps.

🔥 Features

Add a note with a title and content

Delete notes you no longer need

Simple UI and minimal UX

Data persisted in localStorage (no backend required) — plug in an API later if you want



🚀 Tech Stack (suggested)

Frontend: React (Create React App / Vite)

Styling: CSS  / Bootstrap (your choice)




🧪 Install & Run (if using React)
# clone
git clone https://github.com/<your-username>/keeper-app.git
cd keeper-app

# install
npm install

# dev
npm start
# or for Vite
# npm run dev

🛠️ To Add a Backend (optional)

If you want server-side persistence:

Create a Node/Express API with routes:

GET /notes — fetch notes

POST /notes — add note { title, content }

DELETE /notes/:id — delete by id
