# AFFORDMED ASSIGNMENT
This project is my submission for the Affordmed evaluation.  
It implements a simple URL shortening service with custom logging middleware, redirect handling, and click statistics.

### Author
- **Name:** ISHITA MODI  
- **Roll No:** 2201641550051  
- **Email:** ishitamodi0@gmail.com  
- **GitHub Username:** ishita230105 

### Tech Stack
- Python 3.10+
- FastAPI
- SQLAlchemy
- SQLite
- Pydantic
- Uvicorn

### Features
- Create short URLs with optional custom shortcode
- Redirect from short URL to original URL
- Expiry handling (default 30 minutes)
- Track click details (timestamp, source, coarse IP)
- Stats endpoint to view total clicks and click history
- Structured JSON logging middleware (no console prints)

### How to Run
```bash
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
uvicorn app:app --reload
