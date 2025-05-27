# Smart Receipt Uploader.ai 🧾🤖

An AI-enhanced receipt digitization tool for small businesses. Upload your physical or digital receipts, extract key data using OCR + AI, and manage your sales logs in one place.

## Features

- Upload image/PDF receipts
- Auto-extract:
  - Date
  - Item list
  - Total amount
- View all past receipts in a searchable table
- Export data to Excel/CSV
- Built with Python (FastAPI) and React.js

## Tech Stack

| Layer         | Tech                                |
|---------------|-------------------------------------|
| Frontend      | React.js, Tailwind CSS, Vite        |
| Backend       | FastAPI (Python)                    |
| OCR Engine    | Tesseract.js / EasyOCR              |
| Database      | MongoDB Atlas                       |
| Deployment    | Vercel (frontend) + Railway (API)   |

## Folder Structure

smart-receipt-uploader/ ├── client/        # React frontend ├── server/        # FastAPI backend └── README.md

## Setup Instructions

### Frontend

```bash
cd client
npm install
npm run dev
```

### Backend

```bash
cd server
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

## Upcoming Features
- Login & User dashboard (Firebase Auth)
- Monthly sales summaries
- Mobile image upload support
- Multi-language OCR support

## Contribution
Feel free to fork and contribute to this tool—especially if you're into OCR, AI, or building tools for local businesses.

License
MIT
---

Built by @muzammil-13 with a mission to help small businesses go digital..
