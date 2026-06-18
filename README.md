
---

## 🛠️ Tech Stack

### Backend
| Technology | Version | Purpose |
|------------|---------|---------|
| Python | 3.11+ | Core language |
| FastAPI | 0.104.0 | Web framework |
| MongoDB | 6.0 | Database |
| Redis | 7.0 | Caching & queues |
| Celery | 5.3.4 | Task queue |
| Scikit-Learn | 1.3.0 | ML/AI |

### Frontend
| Technology | Version | Purpose |
|------------|---------|---------|
| React | 18.2.0 | UI framework |
| Tailwind CSS | 3.3.5 | Styling |
| Recharts | 2.8.0 | Charts |
| React Query | 3.39.3 | Data fetching |

### Security Tools
| Tool | Purpose |
|------|---------|
| Nmap | Network scanning |
| Subfinder | Subdomain discovery |
| Amass | Asset enumeration |
| OWASP ZAP | Web application security |
| MobSF | Mobile security |
| WhatWeb | Technology detection |

---

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose (recommended)
- OR Python 3.11+, Node.js 18+, MongoDB 6.0+

### One-Click Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/attack-surface-platform.git
cd attack-surface-platform

# Copy and configure environment
cp backend/.env.example backend/.env

# Start with Docker (Recommended)
docker-compose up -d

# Or install manually
# Backend
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload

# Frontend (in new terminal)
cd frontend
npm install
npm start
