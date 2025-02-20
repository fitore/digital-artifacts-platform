# PROTOTYPE] Digital Artifacts Platform

This is an open-source platform for storing and managing digital artifacts, such as books, art, and historical documents. The project integrates AI for OCR, image tagging, and metadata extraction.

## 🌟 Features
- Upload and search digital artifacts with AI-powered tagging and metadata.
- AI-based OCR for scanned books and documents.
- Image classification for artworks and photos.
- Secure user authentication and role-based access.

## 🚀 Project Structure
- **Frontend:** Next.js app for user interaction (`/frontend`)
- **Backend:** Node.js API for metadata and artifact management (`/backend`)
- **AI Services:** OCR, tagging, and metadata pipelines (`/ai-services`)
- **Database:** PostgreSQL with artifact metadata schema (`/database`)
- **Infrastructure:** Docker-based self-hosting (`/infra`)

## 🛠️ Setup and Deployment
1. **Install Dependencies:**  
```bash
npm install       # For frontend and backend
docker-compose up # To start services
