InternMatch 🎯
A full-stack internship matching platform that connects students with the right opportunities through skill-based filtering and role-based access.
🔗 Live Demo: [internmatch-silk.vercel.app](https://internmatch-silk.vercel.app/internships)

Features

🔐 JWT-based authentication with role-based access for Students and Recruiters
🧠 Skill-matching engine that ranks internships based on applicant skill overlap
📋 Recruiters can post, manage, and review applications
🎓 Students can browse, filter, and apply to internships
☁️ Fully deployed — frontend on Vercel, backend on Render


Tech Stack
LayerTechFrontendReact.js, CSS3BackendNode.js, Express.jsDatabaseMongoDB (Mongoose)AuthJWT, bcryptDeploymentVercel (frontend), Render (backend)

Getting Started
Prerequisites

Node.js v18+
MongoDB URI (Atlas or local)

Installation
bash# Clone the repo
git clone https://github.com/palakbodkhe/InternMatch.git
cd InternMatch

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
Environment Variables
Create a .env file in the /server directory:
envMONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
Run Locally
bash# Start backend (from /server)
npm start

# Start frontend (from /client)
npm run dev

Project Structure
InternMatch/
├── client/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
└── server/          # Node/Express backend
    ├── models/
    ├── routes/
    ├── middleware/
    └── server.js



Author
Palak Bodkhe
B.Tech CSE 
