<img src="assets/banner.png" alt="Sepehr Khastoo, Backend Engineer. Python and Django, application security, data integrity." width="100%">

Backend engineer working in Python and Django, mostly on application security and data integrity. Computer engineering student in Tehran, open to backend roles and internships, remote or on-site.

[Portfolio](https://sepehrkhasto.github.io) · [فارسی](https://sepehrkhasto.github.io/fa/) · [LinkedIn](https://linkedin.com/in/sepehrkhasto) · [Email](mailto:sepehrkhasto.private@gmail.com)

## Projects

**[Aegis Planner, web](https://github.com/sepehrkhasto/aegis-zk-planner)** · Django, Web Crypto API · v7.1.0  
A zero-knowledge planner. The vault is encrypted in the browser with AES-256-GCM under a random data key, and that key is wrapped with a PBKDF2-SHA256 key derived from the password, so the server stores only the salt, the wrapped key and the ciphertext. Revision-checked saves, a strict CSP, Argon2, rate limiting and lockout. 146 Django tests and 556 JavaScript checks run in GitHub Actions.

**[Aegis Planner, desktop](https://github.com/sepehrkhasto/aegis-planner)** · Python, PyQt6 · v2.11.10  
An offline, encrypted planner for Windows, in Persian with a Jalali calendar. Atomic writes, encrypted backups, and installers built from tagged source with published SHA-256 checksums. 971 pytest tests.

**[Refinery Risk Monitor](https://github.com/sepehrkhasto/refinery-risk-monitor)** · FastAPI, SQLAlchemy, WebSocket  
Live risk scoring, P10/P50/P90 forecasts and anomaly detection for refinery process units, with JWT role-based access and a live simulator with fault injection. I led the four-person team; the project placed in the top three of the course.

**[Andarun](https://github.com/sepehrkhasto/andarun)** · Django · in development  
An invite-only, text-only social network designed to keep working through internet shutdowns. So far: a custom user model with username login, strict usernames and settings that fail closed. Next: invite-only sign-up, approved by the member who sent the invitation.

## Currently

Building Andarun v1, starting with accounts and invitations, and learning Django REST Framework.

## Stack

**Core:** Python, Django, SQL, PostgreSQL, MySQL, SQLite, Git  
**Working knowledge:** Docker, Linux, ORM query optimization, transactions and row-level locking, networking fundamentals  
**Also used:** FastAPI, SQLAlchemy, Alembic, WebSocket, Web Crypto API, PyQt6, GitHub Actions  
**Learning:** Django REST Framework, testing with Django TestCase
