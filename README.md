<div align="center">
<img width="200" src="public/llogo.png" alt="Eng.Manager Logo" />

# Eng.Manager
**Integrated Engineering Management System**
</div>

---

**Eng.Manager** is a comprehensive professional tool designed to streamline construction and engineering project documentation. It features robust document control, project tracking, and seamless file management capabilities, bridging the gap between local workflows and cloud collaboration.

## Key Features

*   **Project Management**: Create, edit, and track multiple engineering projects with detailed metadata (Owner, Consultant, Location, Code).
*   **Document Control System (DCS)**: Full lifecycle management for engineering documents:
    *   **Types**: Letters, Reports, Drawings, RFIs, Submittals, Contracts, Invoices, etc.
    *   **Disciplines**: Civil, Mechanical, Electrical, Architecture, HSE, QA/QC, Planning, etc.
    *   **Status Tracking**: Workflow states including Approved, Rejected, Pending, and Revise & Resubmit.
*   **Hybrid Vault System**:
    *   **Local Vault**: Direct file system access for high-speed local management.
    *   **Cloud Integration**: Seamless Google Drive integration for team collaboration and backup.
*   **Advanced Search & Filtering**: Precise filtering by Project, Discipline, Status, Assignee, or keyword search.
*   **Professional UI/UX**:
    *   **Bilingual Support**: Native Arabic Interface support (RTL).
    *   **Dark/Light Mode**: Built-in theming for comfortable usage in any environment.
    *   **Dashboard**: High-level overview of project statistics and document states.
*   **Integrated File Viewer**: Built-in preview for documents and attachments within the application.

## Tech Stack

Built with modern, performance-oriented technologies:

*   **Frontend**: React 19 + TypeScript
*   **Styling**: Tailwind CSS
*   **Desktop Runtime**: Electron
*   **Build Tool**: Vite
*   **Integrations**:
    *   Google Drive API
    *   Google Gemini AI (Intelligent Assistance)
*   **Visualization**: Recharts

## Getting Started

### Prerequisites

*   Node.js (v18 or higher)
*   npm or yarn

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/your-username/Eng.Manager.git
    cd Eng.Manager
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Configuration**
    *   Create a `.env.local` file in the root directory.
    *   Add your API keys (Gemini, Google Client ID) if using cloud/AI features.

### Running Locally

To start the application in development mode:

```bash
npm run dev
```

### Building for Desktop

To create a production-ready executable for Windows:

```bash
npm run electron:build
```
The executable will be generated in the `release` directory.

## License

This project is proprietary. All rights reserved.

---
Created by **Abdulrahman**
