# CS 499 Computer Science ePortfolio
**Student:** Rimon Hamo  
**Aspiration:** Mobile Software Engineer  
**Institution:** Southern New Hampshire University  
**Live Site URL:** [https://github.io](https://rayhamo98.github.io/CS-499-ePortfolio/)

---

## 👔 Professional Self-Assessment

### Introduction & Career Alignment
My professional objective is to operate as a Mobile Software Engineer specializing in high-performance health, fitness, and wellness applications. Throughout my computer science journey at SNHU, I have integrated industry-standard architectural frameworks and security practices to deliver responsive, user-centric mobile solutions. This portfolio represents my evolutionary growth, showcasing a transition from structural programming paradigms to secure, decoupled, and algorithmically efficient software architectures.

### Architectural Strategy & Collaborative Engineering
In modern software development, delivering high-quality solutions requires choosing structures that can adapt to changing demands while remaining easy for teams to maintain. My capstone work highlights this by taking a legacy application and completely separating its responsibilities using the Model-View-ViewModel (MVVM) pattern. Moving code out of monolithic blocks makes it easier for multiple developers to work together on different features without creating merge conflicts, improving team collaboration and efficiency.

### Algorithmic Optimization & Trade-off Management
Writing efficient code requires analyzing how data structures perform under strict memory and hardware limitations. For mobile platforms, calculations must run fast without draining the battery or overheating the device. My work addresses this by moving data processing away from slow cloud endpoints directly onto the local hardware (Mobile Edge Computing). By utilizing ordered TreeMap collections and linear regression algorithms, the application processes real-time user metrics instantly on-device while maintaining optimal memory performance.

### Security Mindset & Data Privacy
As mobile applications handle increasingly sensitive user health records, security must be built directly into the codebase rather than treated as a network configuration after-thought. Adopting a Zero-Trust architecture means verifying all data locally and assuming the operating environment may be compromised. I implemented this by replacing open cleartext data paths with compiled, type-safe database migrations and applying robust cryptographic hashing (BCrypt) to protect local user records from unauthorized extraction or physical hardware harvesting.

---

## 📽️ Informal Code Review Video
*   **Video Walkthrough:** [Watch My Module Two Code Review Video](PASTE_YOUR_ACTUAL_VIDEO_URL_HERE)
*   **Description:** A detailed structural analysis reviewing the legacy baseline code line-by-line to outline the engineering vulnerabilities and enhancement strategies.

---

## 🛠️ Artifact Enhancements (CS360 Android Weight Tracker)

### 1. Software Design & Engineering
*   **Artifact Source:** CS360 Mobile Architecture and Programming
*   **Supporting Files:** [Download All Narratives (.zip)](./narratives.zip)
*   **Source Code:** [Original Legacy ZIP](./original_weight_tracker.zip) | [Enhanced MVVM Code Base](./enhanced_weight_tracker.zip)
*   **Summary:** Refactored un-optimized Activity code blocks into modular **MVVM components** utilizing clean repositories, explicit background thread executors, **ViewBinding**, and lifecycle-aware **LiveData** streams.

### 2. Algorithms & Data Structures
*   **Artifact Source:** CS360 Mobile Architecture and Programming
*   **Supporting Files:** [Download All Narratives (.zip)](./narratives.zip)
*   **Source Code:** [Original Legacy ZIP](./original_weight_tracker.zip) | [Enhanced Algorithmic Code Base](./enhanced_weight_tracker.zip)
*   **Summary:** Implemented an on-device "Trends & Insights" forecasting core utilizing **Linear Regression models** and multi-day moving averages backed by an ordered **`TreeMap<Date, Double>`** collection to achieve efficient $O(\log N)$ processing speeds.

### 3. Databases & Security
*   **Artifact Source:** CS360 Mobile Architecture and Programming
*   **Supporting Files:** [Download All Narratives (.zip)](./narratives.zip)
*   **Source Code:** [Original Legacy ZIP](./original_weight_tracker.zip) | [Enhanced Database Code Base](./enhanced_weight_tracker.zip)
*   **Summary:** Upgraded cleartext SQLite calls into the modern **Android Jetpack Room ORM** framework with strict compiled schemas, relational foreign keys, and secure **BCrypt cryptographic password hashing**.
