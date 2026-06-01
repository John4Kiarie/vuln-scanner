# Vuln-Scanner

A comprehensive **Vulnerability Scanner & Management Platform** that automates the detection, tracking, and remediation of vulnerabilities in your codebase and dependencies.

## Features

✅ **Automated Dependency Scanning** - Detect vulnerabilities in Python, JavaScript, and other dependencies  
✅ **Code Vulnerability Detection** - Identify security issues using static analysis (Bandit, SonarQube)  
✅ **Centralized Dashboard** - Visualize all vulnerabilities across projects  
✅ **Remediation Tracking** - Track vulnerability fixes and remediation progress  
✅ **CI/CD Integration** - Automated scans on every commit via GitHub Actions  
✅ **Detailed Reports** - Generate compliance and vulnerability reports  
✅ **Multi-Project Support** - Manage vulnerabilities across multiple repositories  

## Tech Stack

- **Backend:** Python (FastAPI)
- **Frontend:** React + TypeScript
- **Database:** PostgreSQL
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
- **Scanning Engines:** Bandit, Safety, OWASP Dependency-Check

## Getting Started

### Prerequisites

- Python 3.9+
- PostgreSQL 12+
- Node.js 16+ (for frontend)
- Docker & Docker Compose

### Installation

```bash
# Clone the repository
git clone https://github.com/John4Kiarie/vuln-scanner.git
cd vuln-scanner

# Start with Docker Compose
docker-compose up -d

# Access the application
# Backend: http://localhost:8000
# Frontend: http://localhost:3000
# API Docs: http://localhost:8000/docs
```

## Project Structure

```
vuln-scanner/
├── backend/                 # Python FastAPI backend
│   ├── app/
│   │   ├── api/            # API routes
│   │   ├── models/         # Database models
│   │   ├── schemas/        # Pydantic schemas
│   │   ├── main.py         # FastAPI app entry point
│   ├── tests/              # Unit and integration tests
│   ├── requirements.txt    # Python dependencies
│   └── Dockerfile
├── frontend/               # React + TypeScript frontend
├── docker-compose.yml
├── .github/workflows/      # GitHub Actions workflows
└── docs/                   # Documentation
```

## API Documentation

Once running, visit `http://localhost:8000/docs` for interactive Swagger documentation.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License - see LICENSE file for details

---

Built with ❤️ for better security automation
