# Rahul Devikar – Senior Software Engineer at Microsoft

With over 10 years of experience in designing, building, and optimizing large-scale AI platforms, distributed systems, and cloud-native solutions, I specialize in delivering secure, scalable, and high-impact software. My work spans AI-driven innovations, enterprise system design, and cloud architecture, with notable contributions to Microsoft 365 Copilot, Salesforce connectors, and large-scale data integrations.

---

## 🚀 **Core Expertise & Impact**

### **Agent 365 SDK**
- **Core contributor and maintainer** of **Agent 365**, an open-source platform that simplifies AI agent management, security, and integration in enterprise environments.
- Maintains **Python**, **JavaScript**, and **.NET** SDKs, along with DevTools and CLI integrations.
- Since its launch at **Microsoft Ignite 2025**, **Agent 365** has surpassed **11,000 downloads** and is actively used by thousands of developers across the globe.
- Authored multiple technical articles on **Agent 365**, establishing best practices for enterprise AI integration and positioning myself as a thought leader in this space.
- (Github Account linked to CorpNet: https://github.com/rahuldevikar761)

### **Microsoft 365 Copilot Federated Knowledge Integration**
- Built and optimized knowledge connectors bringing enterprise data (SharePoint, Salesforce, Dataverse) into **Microsoft 365 Copilot** for AI consumption.
- Improved **Salesforce connector** reliability from 70% to 95% success rate through bug resolution and intelligent NL2SQ fallback mechanisms.
- Enabled thousands of developers to extend **Microsoft 365 Copilot** with custom agents while maintaining enterprise security.
- Users now get AI-powered answers from enterprise data sources with **95% reliability**, improving knowledge discovery and decision-making.

### **Database Optimization**
- Migrated analytics metadata from standalone **Cosmos DB** to enterprise shared infrastructure across **20+ metadata types**.
- Re-architected database schema eliminating **2MB document limitations** and **thread-safety issues**.
- Optimized query patterns removing unnecessary index files.
- Implemented **intelligent retry logic** with exponential backoff for API rate limiting.
- Reduced daily infrastructure costs from **$2,500 to $270** (>90% savings).

### **Quality Engineering**
- Built **automated E2E test suite** running **100 prompts** across 6+ knowledge sources after every code check-in.
- Implemented island-specific testing for **ML model deployment**.
- Created offline validation framework for **pre-release testing**.
- Designed alert system for **knowledge source-specific failures**.
- Detected critical regressions before production (including secondary region failure).

### **Security & Reliability**
- Blocked vulnerable model deployments by integrating **security scanning** into the pipeline.
- Fixed production debugging enabling **distributed tracing**.
- Implemented proactive monitoring detecting failures before customer reports.
- Reduced **log noise** by **30,000+ lines** daily improving troubleshooting efficiency.

### **Multi-Cloud**
- Extended platform to **Government Cloud (GCC)** and **sovereign clouds**.
- Modernized CI/CD with **YAML-based pipelines**.
- Implemented security compliance with **OpenTelemetry** and **audit logging**.

### **Insights Apps Platform (IAP) Orchestration**
- Designed and shipped a **Service Fabric-based orchestrator** for IAP that coordinated long-running **ML/data pipelines** (minutes → multi-week).
- Scaled to **hundreds of TB** processed through **MEF batch/online inference paths**.
- Unified batch + online model execution by standardizing **MEF entry points** and **operational APIs**.
- Instrumented orchestration for **observability** and **failure isolation** across multi-stage pipelines; implemented retries, checkpointing, and guarded rollouts.
- Integrated **Dataverse/Dynamics application user management** for first-party Insights Apps (roles, identities, access paths).
- Drove **Secure Future Initiative (SFI)** compliance for IAP services (governed release pipelines, safe secrets, MSI onboarding, vulnerability management).
- Established repeatable test-cluster rollout for rapid developer iteration on IAP.

---

## 🏆 **Leadership & Recognition**
- Featured work in **Forbes**, **The Verge**, **CNBC**, and **Tech.co** in enterprise AI and cloud computing.
- Actively mentor engineers and contribute to open-source communities.

---

## 📝 **Key Achievements**
- **Cost Reduction**: 90%+ savings (**$2,500 → $270** daily infrastructure costs).
- **Reliability Improvement**: 70% → 95% success rate for **Salesforce connector**.
- **Zero-Downtime Migration**: 99% of production traffic migrated successfully with no escalations.
- **Security Enhancement**: 83% reduction in **RDP access** (1,200 → 200 requests/month).
- **Quality Assurance**: 100-prompt automated **E2E tests** across 6+ knowledge sources.
- **Log Reduction**: **30,000+ lines of noise** eliminated daily.
- **ML Pipeline Orchestration**: Scaled **Service Fabric orchestrator** to process hundreds of TB through MEF batch/online inference paths.
- **Developer Enablement**: Created integration samples for **Semantic Kernel**, **OpenAI**, and multiple agent frameworks.
- **Production Incident Prevention**: Proactive migration from failing legacy system preventing major outage.
- **Database Optimization**: Re-architected **Cosmos DB schema** eliminating **2MB document limitations**.
- **Platform Standardization**: Unified batch + online model execution reducing fragmentation across ML teams.
- **Security Compliance**: Drove **Secure Future Initiative (SFI)** compliance for IAP services.

---

## 💻 **Technical Skills**

- **Languages**: C#, Python, TypeScript, JavaScript, C++, C, X++, PowerShell, MATLAB, HTML
- **Frameworks & Tools**: React, Django, Flask, .NET, SocketIO, MQTT, Dependency Injection
- **Cloud & Infrastructure**: Azure Cloud Services, Service Fabric, Kubernetes, Cosmos DB, IaaS
- **Databases**: SQL, Cosmos DB
- **Development Tools**: Visual Studio, PyCharm, PowerShell ISE, Git, BitBucket
- **Operating Systems**: Windows, Linux, OS X
- **Specializations**: AI, Agents, Orchestration, Workflows, Distributed systems, asynchronous programming, CI/CD pipelines, DevOps, security & compliance, monitoring & alerting

---

## 🎓 **Education**

- **Master of Science in Electrical Engineering**  
  California State University, Long Beach, USA | August 2014 - May 2016
- **Bachelor of Engineering in Electronics Engineering**  
  Nagpur University, India | June 2009 - June 2013

---

## 🛠 **Other Experience**

### **Software Developer | Airwolf 3D, Costa Mesa, CA**  
*June 2016 - October 2018*

#### **Touchscreen Application for 3D Printers**
- Designed and developed a custom embedded application using **Python** and **QML** on **Raspberry Pi**.
- Implemented **UART communication** for printer control and firmware updates.
- Created auto-update services on **Raspbian OS** with **WiFi connectivity**.
- **Technologies**: Python3, QT 5.7, QML, serial communication, JavaScript

#### **Apex Slicing Software**
- Developed a custom slicing application based on **Cura's engine** for **Airwolf 3D printers**.
- Built GUI using **Python**, **WxPython**, and **OpenGL**.
- Implemented **UART communication** for manual printer controls.
- Added **online update** feature and notification system.
- **Technologies**: Python, WxPython, pyserial, OpenGL, URLlib, C, C++, Flask API

#### **Microsoft 3D Builder Integration**
- Integrated **Airwolf 3D printers** with **Microsoft's 3D Builder** software.
- Created custom **USB drivers** for printer detection and **UUID registration**.
- Added **network integration feature** (WSPRINT) for network-based printing.
- **Technologies**: V4 Driver tools, Windows Development Kit, 3D Printer SDK
