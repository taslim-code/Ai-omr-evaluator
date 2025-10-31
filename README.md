🧠 Innomatics AI OMR Evaluator

An AI-powered Optical Mark Recognition (OMR) evaluator that automates the process of reading and scoring OMR sheets using computer vision and machine learning.
Built with React, TypeScript, and Vite for a fast, responsive, and modern UI experience.

🚀 Features

📄 Upload and analyze OMR sheets automatically

🤖 AI-driven bubble detection and evaluation

📊 Real-time scoring and result visualization

⚙️ Configurable metadata and evaluation settings

🌐 Modern and responsive frontend with React + TypeScript

🔒 Environment-based configuration with .env.local

🧩 Tech Stack

Frontend:

React (TypeScript)

Vite

HTML, CSS

Victory Charts (for visual analytics)

Axios (for API integration)

Backend (optional integration):

Flask / FastAPI (Python-based OMR evaluation service)

OpenCV & NumPy for image analysis

TensorFlow / Scikit-learn for model inference (if used)

🗂️ Folder Structure
innomatics-ai-omr-evaluator-01/
├── App.tsx
├── index.tsx
├── index.html
├── index_new.html
├── constants.ts
├── metadata.json
├── types.ts
├── index.css
├── .env.local
├── package.json
├── vite.config.ts
└── tsconfig.json

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/yourusername/innomatics-ai-omr-evaluator.git
cd innomatics-ai-omr-evaluator-01


Install dependencies

npm install


Create environment file

cp .env.local.example .env.local


Configure your backend API or AI model endpoints inside .env.local.

Run the app

npm run dev


The app should be available at http://localhost:5173/

🧠 How It Works

Users upload scanned OMR sheets (JPG/PNG/PDF).

The AI engine (connected backend) detects filled bubbles using image processing.

Marks are evaluated based on metadata or answer key.

Results are displayed with detailed statistics and charts.

📦 Dependencies

Refer to the package.json
 for full dependency list.

Key packages include:

react, react-dom

vite

typescript

victory (for charts)

axios

tinyglobby

🧑‍💻 Author

Taslim
Machine Learning & Full Stack Developer
📧 taslimmia338@gmail.com

🔗 LinkedIn

💻 GitHub

🏁 License

This project is licensed under the MIT License
.

⭐ Acknowledgments

Developed as part of the Innomatics AI Project Series for exploring AI-driven automation in evaluation systems.
