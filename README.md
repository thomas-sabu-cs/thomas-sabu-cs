# Thomas Sabu
### Software Engineer | Systems & ML Engineering
[LinkedIn](https://www.linkedin.com/in/thomas-sabu/) • [Portfolio](https://thomas-sabu-cs.github.io/Website)

---

### 01. Engineering Focus
I build high-performance, data-intensive applications with a focus on **system reliability** and **low-level optimization**. As a CS graduate from the **University of St. Thomas**, I specialize in bridging the gap between complex backend systems and production-ready ML models.

---

### 02. Selected Technical Projects

#### 🛰️ [Sentinel Stream](https://github.com/thomas-sabu-cs/sentinel-stream) | Go, Redis, InfluxDB, Docker
*High-throughput distributed monitoring engine for real-time telemetry.*
- **Performance:** Achieved **<1ms P99 latency** for ingestion pipelines using a decoupled Redis Pub/Sub architecture.
- **Scalability:** Designed for horizontal scaling with containerized microservices and automated health checks.
- **Key Focus:** Concurrency patterns, service boundaries, and time-series data persistence.

#### 🧠 [Nexus Alloc](https://github.com/thomas-sabu-cs/nexus-alloc) | C++, Memory Management, Systems
*Custom high-performance memory allocator designed for reduced fragmentation.*
- **Architecture:** Implemented a [Buddy/Slab] allocation strategy with thread-local caching to minimize lock contention.
- **Optimization:** Optimized for [small/large] block allocations, outperforming standard `malloc` in [specific use-case] benchmarks.
- **Key Focus:** Pointer arithmetic, memory alignment, and thread-safety.

#### 🤖 [SkillGap AI Coach](https://github.com/thomas-sabu-cs/skillgap-ai-coach) | FastAPI, Next.js, Postgres, OpenAI
*Full-stack AI agent for automated resume-to-job alignment and career coaching.*
- **Hybrid Logic:** Features a deterministic keyword-matching baseline and an optional LLM-powered "Expert Mode."
- **Persistence:** Built a robust history tracking system using Postgres and Docker Compose for 1-command deployment.
- **Key Focus:** RAG (Retrieval-Augmented Generation), API design, and full-stack integration.

#### 🎨 [Image Editor Pro](https://github.com/thomas-sabu-cs/image-editor-pro) | Python, PyQt6, Pillow, NumPy
*Desktop image processor featuring a professional layer-based editing system.*
- **Design Patterns:** Implemented the **Command Pattern** for a robust 50-step undo/redo history and **MVC** for UI state.
- **Features:** Built custom filters (Gaussian Blur, Edge Detection) using NumPy for efficient pixel-array manipulation.
- **Key Focus:** Desktop architecture, state management, and image processing.

#### ✅ [Transaction Monitor](https://github.com/thomas-sabu-cs/transaction-monitor-service) | Java, Spring Boot 3, JUnit 5
*Backend financial service for automated risk scoring and fraud detection.*
- **Quality:** Achieved high test coverage with JUnit 5 and automated quality gates via GitHub Actions CI.
- **Reliability:** Built a RESTful API with Spring Data JPA and H2 for persistent, transactional state management.
- **Key Focus:** Enterprise patterns, automated testing, and CI/CD.

#### 📊 [Risk Dashboard](https://github.com/thomas-sabu-cs/risk-decision-dashboard) | React 18, TypeScript, Redux Toolkit
*Enterprise UI for visualizing complex financial datasets and risk decisions.*
- **State:** Managed complex, multi-step state transitions using Redux Toolkit and the Context API.
- **Type Safety:** Leveraged TypeScript for strict interface definitions across the data visualization layer.
- **Key Focus:** UI performance, responsive design (Tailwind CSS), and state normalization.

---

### 03. Technical Stack
- **Languages:** Go, C++, Python, Java, TypeScript, SQL
- **Systems & Infra:** Docker, Redis, InfluxDB, PostgreSQL, GitHub Actions, Linux
- **Machine Learning:** PyTorch, TensorFlow, scikit-learn, XGBoost, pandas, NumPy
- **Web/Backend:** FastAPI, Spring Boot, React, Redux, Flask
