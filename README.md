# Perambalur Arivuthirukovil - Event Hub (Serverless)

A premium, high-performance event calendar tool designed for the Perambalur Arivuthirukovil Yoga Center. This application runs entirely in the browser and requires no backend server, making it perfect for free hosting on **GitHub Pages**.

## Key Features
- **Multi-Calendar Support**: Toggle between Public, Member, and Special Events.
- **Advanced Views**: Switch between Month, Week, Day, and Time Chart visualizations.
- **Client-Side Exports**: Download event summaries as PDF, Word, or JPG directly from your browser.
- **Admin Controls**: Add and manage events with ease.
- **Data Persistence**: All your events are saved locally in your browser's `localStorage`.
- **Responsive Design**: Elegant teal-themed UI that works on desktop and mobile.

## Technical Details
- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript.
- **Libraries**:
  - `jsPDF`: For PDF generation.
  - `docx.js`: For Word document generation.
  - `html2canvas`: For JPG image capture.
  - `FontAwesome`: For icons.

## Data Security
Since this is a serverless application, all event data is stored **locally on your computer** (in your browser). This ensures your data remains private and doesn't require a database server.

