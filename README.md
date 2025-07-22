# 📊 Excel Analytics Platform

An end-to-end platform for securely uploading, analyzing, and visualizing Excel data. Designed for users and admins with support for 2D/3D chart generation, downloadable reports, and full upload history tracking.

---

## 🚀 Features

### ✅ Core Features
- **Secure Authentication with JWT**
  - Role-based login for users and admins.
- **Excel Upload Support (.xls, .xlsx)**
  - Upload using Multer middleware.
- **Excel Parsing with SheetJS**
  - Converts Excel data into structured JSON.
- **Dynamic Column Selection**
  - Users choose columns to visualize (X and Y axes).
- **Interactive Chart Generation**
  - 2D Charts: Chart.js (bar, line, pie, scatter)
  - 3D Charts: Three.js (surface, 3D bar, etc.)
- **Export Charts**
  - Download as PNG or PDF using Chart.js, html2canvas, jsPDF.
- **User History Tracking**
  - View past uploads, chart types, and axis selections.
- **Admin Dashboard**
  - Monitor usage statistics, manage users and uploads.

### 🧠 Optional (Pluggable)
- **AI Insights (e.g., OpenAI API)**
  - Automatically generate summaries and insights from uploaded data.

---

## 🛠️ Tech Stack

| Layer        | Technology                  |
|--------------|------------------------------|
| Frontend     | React.js, Chart.js, Three.js |
| Backend      | Node.js, Express.js          |
| File Parsing | SheetJS (xlsx)               |
| File Upload  | Multer                       |
| Auth         | JSON Web Tokens (JWT)        |
| Database     | MongoDB                      |
| Export       | jsPDF, html2canvas           |

---

