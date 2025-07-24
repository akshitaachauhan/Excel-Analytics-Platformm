# Excel Analytics Platform

A powerful web-based platform to upload, visualize, and analyze Excel files with interactive 2D and 3D charts. Built with user-friendly tools and admin-level control for managing data-driven workflows.



## Key Features

### 1. Secure Login System 
- Role-based login for both **Users** and **Admins**.
- All API routes protected using **JSON Web Tokens (JWT)**.
- Ensures secure access and prevents unauthorized actions.



###  2. Upload Excel Files
- Supports `.xls` and `.xlsx` uploads using **Multer** middleware.
- Files are validated and temporarily stored for parsing.
- Accepts **real Excel data** for instant analysis.



###  3. Parse and Read Excel Data (SheetJS)
- Excel content is parsed into **structured JSON** using **SheetJS (xlsx)**.
- Supports multi-sheet Excel files.
- Enables easy integration with charting and filtering logic.



###  4. Select Columns for Visualization
- Users can **pick any two columns** for X and Y axes.
- Automatically populated dropdowns after file parsing.
- Enables **custom chart creation** based on user preference.



### 5. Generate Interactive  Charts
- **2D Charts**: Line, bar, pie, scatter using **Chart.js**.
- **3D Charts**: Advanced visualizations using **Three.js**.
- Charts update in real-time based on selected columns.



###  6. Download Charts 
- Export visualizations as **PNG images**.
- Generate and download **PDF reports** using `html2canvas` and `jsPDF`.
- Perfect for presentations, reports, and sharing.



### 7. Upload and Analysis History
- Tracks each user's:
  - Uploaded files
  - Selected axes
  - Chart types generated
- Provides **personal analysis history dashboard**.



###  8. Admin Dashboard
- Accessible only to admin users.
- Displays:
  - Number of users
  - File upload stats
  - Popular chart types
  - Platform usage metrics
- Allows **user management and monitoring**.



## AI Integration
- Connect to tools like **OpenAI API** to:
  - Generate **automated insights**
  - Summarize trends and anomalies in uploaded data
- Adds smart assistance to raw Excel analytics.




##  Ideal For
- Business analysts needing quick data visualization.
- Teams who want to turn Excel into interactive insights.
- Admins managing multiple users and data interactions.


