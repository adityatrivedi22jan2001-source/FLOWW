# Textile Flow

A React-based workflow management system for textile manufacturing, featuring role-based access control, order management, and process tracking.

## Features

- User authentication with role-based access control
- Admin dashboard for order and user management
- Workflow stages: Inward, Processing, QC, Finishing
- Image upload for orders
- JSON-file backend (no SQL) for easy deployment
- LAN-accessible via XAMPP

## Setup

### Prerequisites
- Node.js and npm
- XAMPP (Apache + PHP)

### Local Development

```bash
npm install
npm start
```

### Production Build

```bash
npm run build
.\deploy.ps1  # Requires Administrator; mirrors build to XAMPP and restarts Apache
```

## Deployment

See [XAMPP Deployment Steps](./DEPLOYMENT.md)
