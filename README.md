# Jan Zajíček

**BSc. Computer Science student** at Silesian University in Opava (expected 2026). Previously completed 3 years at FIT VUT Brno. Passionate about the intersection of IT and physics, with coursework in Quantum Mechanics and AI ethics.

[GitHub Profile](https://github.com/Noemkinator)

---

### Tech Stack & Tools

#### Languages
- **Python** – Production applications, AI/ML pipelines, automation scripts
- **C++** – Game engines, simulations, performance-critical systems
- **C# / .NET** – Desktop applications (Avalonia UI), enterprise systems
- **TypeScript / JavaScript** – Modern React frontends, Node.js backends
- **GDScript** – Godot 4.x game development
- **Java** – Spring Boot applications, OOP projects
- **PHP** – Legacy web applications, testing tools
- **Bash / PowerShell** – DevOps, automation, deployment scripts

#### Frameworks & Libraries
- **Backend:** FastAPI, Flask, Django, ASP.NET Core, Spring Boot, Express
- **Frontend:** React, Vite, TailwindCSS, Framer Motion, React Query, React Hook Form
- **AI/ML:** LangChain, CrewAI, Hugging Face Transformers, PyTorch, ChromaDB, Ollama (qwen2.5:7b, nomic-embed-text), vLLM, GPU offload (CUDA), RAG systems, vector embeddings, semantic search
- **Game Dev:** Godot 4.x, SFML, SDL2, OpenCV
- **Desktop:** Avalonia UI, .NET MAUI
- **Testing:** pytest, Vitest, Playwright, xUnit

#### Databases & Storage
- **RDBMS:** PostgreSQL, SQLite, MySQL/MariaDB, MSSQL
- **NoSQL:** Redis, ChromaDB
- **Search Engines:** Meilisearch (full-text), SQLite FTS5
- **ORM:** SQLAlchemy, Entity Framework Core, Prisma

#### DevOps & Infrastructure
- **Containerization:** Docker, Docker Compose, multi-stage builds, health checks
- **Orchestration:** Kubernetes (k8s), Helm charts, ConfigMaps, PVCs, Deployments
- **CI/CD:** GitHub Actions (workflows, self-hosted runners, matrices), GitLab CI
- **Version Control:** Git, GitLab, GitHub (Actions, Dependabot, Pages, GHCR)
- **Web Servers:** Caddy (Let's Encrypt, Cloudflare DNS-01, automatic HTTPS), Nginx, Uvicorn, Gunicorn
- **Cloud Platforms:** Cloudflare (R2 storage, DNS, CDN, WAF), AWS (S3, EC2 basics, Route53)
- **Reverse Proxy:** Caddyfile configuration, location blocks, VPN-only access rules
- **Server OS:** Linux (Ubuntu, Debian, Alpine), Windows Server, WSL2
- **Monitoring:** AP Scheduler, structured logging (JSON), telemetry, dashboards (Dashdot, Portainer)
- **Backup & Recovery:** rclone (Cloudflare R2, S3-compatible), GPG-encrypted backups, cron jobs, disaster recovery scripts

#### Development Tools
- **IDEs:** Visual Studio 2022, VS Code, JetBrains Rider, Godot Editor, PyCharm
- **Build Systems:** CMake, MSBuild, Vite, Webpack, Make
- **Package Managers:** pip, npm, NuGet, vcpkg, Cargo, apt, winget
- **Documentation:** Sphinx, MkDocs, TypeDoc, JSDoc, ReadTheDocs
- **AI-Assisted Development:** opencode (custom agents, build workflows), GitHub Copilot
- **Shells & Scripting:** Bash (production scripts, cron jobs), PowerShell (automation, deployment)
- **Database Tools:** pgAdmin, DBeaver, SQLite Browser, Redis Commander, Portainer
- **Web Scraping:** Crawl4AI, Playwright, httpx, selectolax, rapidfuzz
- **Frontend UI:** Streamlit (mobile-first dashboards)

---

### Areas of Focus

#### Game Development
Building 2D/3D games and interactive simulations with procedural generation, pathfinding algorithms, and real-time physics. Experience with grid-based systems, transport logistics, and RTS mechanics. Interest in Vulkan game engines and low-level graphics programming.

#### AI & Automation
Developing agentic workflows with tool-calling capabilities, local LLM deployment (Ollama, vLLM), and RAG systems. Focus on deterministic evaluation and reproducible results.

#### Full-Stack Engineering
End-to-end web applications with modern React frontends, FastAPI backends, PostgreSQL databases, and Docker deployment. Emphasis on type safety, validation, and security best practices. Production deployments with Caddy reverse proxy, Cloudflare DNS/CDN, automated SSL (Let's Encrypt DNS-01), and VPN-only admin access.

#### DevOps & Platform Engineering
Containerized applications with Docker Compose (multi-service, health checks, volumes), Kubernetes manifests (Deployments, ConfigMaps, PVCs), and GitHub Actions CI/CD (self-hosted runners, matrix builds, automated testing). Cloudflare R2 backup automation with rclone, GPG encryption, and cron scheduling. Infrastructure as Code principles with reproducible environments.

#### Scientific Computing
Numerical simulations, quantum algorithm implementation, combinatorial optimization, and data visualization. Experience with HPC environments and Slurm workload management.

#### Application Security
Secure software design with OWASP ASVS compliance, threat modeling, and security-first architecture. Implementation of authentication systems (WebAuthn, TOTP), audit logging with tamper-evident hash chains, and defense-in-depth strategies for full-stack applications.

---

### Security & Privacy

#### Authentication & Authorization
- **Password Security:** Argon2id hashing (OWASP recommended), password strength validation, breach detection
- **Multi-Factor Authentication:** TOTP (pyotp), WebAuthn/FIDO2 passkeys, backup codes
- **Session Management:** JWT tokens with rotation, refresh token blacklisting, secure cookie flags (HttpOnly, Secure, SameSite)
- **Access Control:** Role-based (RBAC), attribute-based (ABAC), policy-based authorization (Spring Security)

#### Application Security
- **Input Validation:** Pydantic models, Zod schemas, class-validator, whitelist sanitization
- **XSS Prevention:** DOMPurify, Content-Security-Policy headers, output encoding
- **CSRF Protection:** Synchronizer tokens, SameSite cookies, double-submit pattern
- **SQL Injection:** Parameterized queries, ORM (SQLAlchemy, Entity Framework), query builders
- **Rate Limiting:** FastAPI-Limiter, pyrate-limiter, Redis-backed sliding windows, IP/user-based throttling

#### Cryptography
- **Encryption:** AES-256-GCM, ChaCha20-Poly1305, RSA-OAEP, ECC (P-256, P-384)
- **Hashing:** SHA-256, SHA-3, BLAKE2, HMAC-SHA256
- **Key Management:** Environment variables, secrets managers, key derivation (PBKDF2, scrypt)
- **Libraries:** `cryptography` (Python), `System.Security.Cryptography` (.NET), `javax.crypto` (Java)

#### Secure Development
- **Audit Logging:** Tamper-evident hash chains, immutable logs, structured logging (JSON)
- **Security Testing:** ASVS checklist, OWASP Top 10 verification, penetration testing scripts
- **Dependency Scanning:** `pip-audit`, `npm audit`, Dependabot, Snyk integration
- **Secure Headers:** HSTS, X-Frame-Options, X-Content-Type-Options, Referrer-Policy
- **Secret Management:** `.env` files (gitignored), dotenv, Azure Key Vault basics

#### Compliance & Standards
- **OWASP:** ASVS Level 2, Top 10 2021 mitigation
- **GDPR:** Data minimization, right to erasure, consent management, audit trails
- **Secure SDLC:** Threat modeling, security code review, abuse cases

---

### Development Practices

- **Type Safety:** Strict type hints (Python), TypeScript strict mode, C# nullable reference types
- **Testing:** Unit tests, integration tests, E2E tests (Playwright), coverage tracking, pytest, Vitest
- **Code Quality:** ESLint, Prettier, Black, isort, SonarQube, pre-commit hooks
- **Documentation:** Inline docstrings, README files, API documentation (OpenAPI/Swagger), MkDocs, ReadTheDocs
- **Version Control:** Semantic versioning, conventional commits, feature branching, protected branches
- **AI-Assisted Development:** opencode (custom agents, build workflows), GitHub Copilot
- **Scripting & Automation:** Bash (production scripts, cron jobs, backup automation), PowerShell (Windows automation, deployment)

---

### Education

**B.Sc. in Computer Science** (Expected 2026)  
*Institute of Computer Science, Faculty of Philosophy and Science, Silesian University in Opava*  
- Weighted mean: 2.01 (Strong results in core IT subjects)
- Relevant coursework: Quantum Mechanics, Ethics of AI, Graph Theory, Algorithms & Data Structures, Operating Systems (Linux/Unix), Computer Architecture, Linear Algebra, Mathematical Analysis

**Previous Studies:** FIT VUT Brno (Faculty of Information Technology) | 2021 – 2024  
*Completed 3 years of Information Technology program*  
- Completed courses: C/C++ programming, Signals and Systems, Design of Computer Systems, Algorithms (IAL), Formal Languages (FLK), Operating Systems (IOS), Computer Networks (IPK), Database Systems (ISA), Seminal Project (ISJ)
- Hardware architecture, formal languages, low-level programming foundations

---

### Contact

- **ORCID:** [0009-0007-2375-7590](https://orcid.org/0009-0007-2375-7590)
- **Location:** Czech Republic (UTC+2)
- **GitHub:** [@Noemkinator](https://github.com/Noemkinator) — 9 repositories (2 private), 1 follower, 7 following
- **LinkedIn:** [in/noemkinator](https://www.linkedin.com/in/noemkinator/)
---

### Experience

**C# Developer Intern** | AT Computers, Ostrava | Jun 2025 – Jul 2025 (2 months)
- Developed and maintained software solutions using C# and ASP.NET MVC
- Integrated internal systems using Web Services APIs
- Utilized AI tools for code generation and optimization to accelerate development workflows
- Collaborated with the development team to troubleshoot issues and improve system performance

**Seasonal Roles** | Various Companies (Lidl, Catalyst Czech Republic, Gebauer & Griller) | 2020 – 2024
- Cashier (Lidl), Event Support (Catalyst), Factory Worker (Gebauer & Griller)
- Developed adaptability, reliability, and strong interpersonal skills in fast-paced environments

---

<details>
<summary><strong>More Details</strong></summary>

#### Additional Technologies
- **Cloud:** Cloudflare (R2, DNS, CDN, WAF, DNS-01 SSL), AWS (S3, EC2, Route53 basics), on-premise HPC clusters
- **Web Servers:** Caddy (automatic HTTPS, Let's Encrypt, DNS providers), Nginx, Apache (basic)
- **APIs:** REST, GraphQL, WebSocket, OpenAPI/Swagger, gRPC basics, External APIs (NHTSA vPIC, CarQuery API, API Ninjas, OpenStreetMap Overpass)
- **Identity:** OAuth2, OpenID Connect, SAML, LDAP, Kerberos
- **Message Queues:** Redis Pub/Sub, RabbitMQ basics, ZeroMQ
- **Graphics:** GLSL basics, Three.js, Canvas API, ImGui, Vulkan (learning)
- **Audio:** SFML Audio, OpenAL basics, FMOD exposure
- **Networking:** TCP/UDP sockets, HTTP/2, WebSocket, gRPC, SSH, OpenVPN, WireGuard
- **Virtualization:** KVM, VirtualBox, WSL2, Docker Desktop, Podman
- **Monitoring & Observability:** Prometheus basics, Grafana exposure, ELK stack basics, Jaeger tracing
- **Configuration Management:** Ansible basics, Terraform exposure
- **Reverse Engineering:** Binary analysis, protocol analysis, decompilation basics
- **Web Scraping:** Crawl4AI, Playwright, automated browser testing, CSS extraction strategies

#### Certifications & Projects
- **Sololearn Certifications (2022):** C Intermediate, Python Core, Python for Data Science, Intermediate Python, SQL, PHP, Ruby, Game Development with JavaScript
- **Operating Systems Project (SLU):** Shell scripts for system automation, process synchronization in Linux
- **Web Technologies Project:** Responsive website using HTML5, CSS3, valid markup
- **NEXT GEN Hackathon (2025):** Raiffeisenbank campaign strategist - "How should RB speak to Gen Z"

#### Interests & Hobbies
- **Game Engines:** Vulkan, game architecture, renderer design
- **Math Visualization:** Manim, 3Blue1Brown-style educational content
- **Code Analysis:** AST parsing, knowledge graphs, code search tools
- **Digital Logic:** Circuit design, FPGA, Verilog/VHDL (Logisim Evolution)
- **Discord Bots:** Highly modular architectures, automation
- **Algorithms:** Sorting visualization, pathfinding, combinatorial optimization

#### Languages (Natural)
- **Czech:** Native
- **English:** Professional working proficiency (B2/C1)
- **German:** Elementary (A1)
- **Russian:** Elementary (A1)

</details>
