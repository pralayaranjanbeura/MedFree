# HealthSync

## Overview
**HealthSync** is a full-stack web application that bridges the gap between government healthcare facilities and individuals for non-communicable diseases. It provides a seamless communication and consultation platform for patients and doctors, leveraging modern web technologies.

## Features

### 🏥 **Patient-Doctor Communication**
- **Joint Patient Chat Room**: Implemented using **WebSockets** for real-time and seamless communication among patients and doctors.
- **Video Call Interface**: Powered by **ZegoCloud**, enabling remote consultations between doctors and patients.

### 🌍 **Location-Based Services**
- Fetch user's **exact location** using **OpenStreetMap API**.
- Display nearby **medical stores and laboratories** where users can book medicines and lab tests.

### 💊 **Prescription Scanning & Medicine Search**
- Utilize **PyTesseract (OCR)** to extract text from scanned prescriptions.
- Perform an integrated medicine search based on the extracted text.

### 🤖 **AI-Powered Assistance**
- **OpenAI API & Prompt Engineering** for:
  - AI-driven **consultancy system** providing health recommendations.
  - **Daily log system** offering personalized health insights.

## Tech Stack
- **Frontend**: React.js, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **APIs & Libraries**:
  - WebSockets (for real-time chat)
  - ZegoCloud (for video calls)
  - OpenStreetMap API (for location-based services)
  - PyTesseract (for OCR-based medicine search)
  - OpenAI API (for AI-powered consultancy system)

## Installation & Setup
### Prerequisites
- **Node.js & npm**
- **MongoDB**
- **Python (for PyTesseract)**

### Steps to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/pralayaranjanbeura/health-sync.git
   cd health-sync
   ```

2. **Install dependencies**
   ```bash
   npm install
   cd backend && npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add:
   ```env
   MONGO_URI=your_mongo_db_uri
   ZEGO_CLOUD_API_KEY=your_zegocloud_api_key
   OPENAI_API_KEY=your_openai_api_key
   ```

4. **Run the backend server**
   ```bash
   cd backend
   node server.js
   ```

5. **Run the frontend**
   ```bash
   npm start
   ```

## Contributing
We welcome contributions! Feel free to submit pull requests or open issues.

---
📌 **Project by [Pralaya Ranjan Beura](https://github.com/pralayaranjanbeura)**
