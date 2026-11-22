# Vendor Compliance and SDS Email Automation Dashboard

A React-based vendor compliance dashboard for managing supplier records, sending document-request emails, and tracking Safety Data Sheet (SDS/MSDS) processing and compliance activity.

## Overview

Supplier compliance teams often need to request updated safety documentation, follow up with vendors, and monitor which documents have been received or processed. This application brings those workflows into a single dashboard interface.

## Key Features

- **Vendor management:** View and organize supplier records.
- **Compliance dashboard:** Monitor vendor counts, compliance rates, pending items, and recent activity.
- **Email request workflow:** Prepare and send vendor document-request emails using configurable templates.
- **SDS/MSDS processing interface:** Review safety-document records and their processing status.
- **Compliance analytics:** Present operational metrics for supplier documentation workflows.
- **Spreadsheet support:** Uses the SheetJS `xlsx` package for spreadsheet-related functionality.
- **Authentication interface:** Includes a login page and application-level session state.

## Technology Stack

- React 19
- Vite
- JavaScript
- Chart.js
- Lucide React
- SheetJS (`xlsx`)

## Run Locally

### Prerequisites

- Node.js
- npm

### Installation

```bash
git clone https://github.com/priyanshukannaujiya/vendoremailmarketing.git
cd vendoremailmarketing
npm install
```

### Start the development server

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

### Lint the project

```bash
npm run lint
```

## Project Structure

The application is organized into reusable React components, including the dashboard, vendor management, email workflow, SDS processing, compliance analytics, navigation, and notifications.

## Relevant Keywords

Vendor management dashboard, supplier compliance, SDS management, MSDS documentation, vendor email automation, React dashboard, compliance analytics, Vite, spreadsheet processing.

## Repository

https://github.com/priyanshukannaujiya/vendoremailmarketing

## Author

[Priyanshu Kannaujiya](https://github.com/priyanshukannaujiya)
