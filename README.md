# Bank of Anthos Group 4 Hackathon Submission

## Team Group 4 - Modern Banking Platform

## 🚀 Project Overview

We've rearchitected Google's BankOfAnthos microservices application to create a more scalable, maintainable, and cloud-native banking platform. Our improvements include:

- **Microservices Decoupling**: Split the monolithic repository into 11 independent services
- **Modernized Tech Stack**: Enhanced with stock trading capabilities and AI features
- **Google Cloud Optimization**: Redesigned for better GCP integration
- **Improved Developer Experience**: Independent development and deployment workflows

## 🏗️ Repository Structure

| Service | Repository | Description |
|---------|------------|-------------|
| 🖥️ Frontend | [victoradepoju/frontend](https://github.com/victoradepoju/frontend) | Main customer banking interface |
| 🌐 Landing Page | [Overbugger/Bank-of-anthos-landing-page](https://github.com/Overbugger/Bank-of-anthos-landing-page) | Marketing and onboarding portal |
| 👥 User Service | [victoradepoju/userservice](https://github.com/victoradepoju/userservice) | Authentication and user management |
| 📇 Contacts | [Cheesom99/contacts](https://github.com/Cheesom99/contacts) | Customer contact management |
| 📝 Ledger Writer | [victoradepoju/ledgerwriter](https://github.com/victoradepoju/ledgerwriter) | Core transaction processing |
| 📊 Transaction History | [Overbugger/transaction-history](https://github.com/Overbugger/transaction-history) | Transaction records and statements |
| 💰 Balance Reader | [midepeter/balance-reader-repo](https://github.com/midepeter/balance-reader-repo) | Real-time balance calculations |
| 📈 Stock Fetcher | [victoradepoju/stock-fetcher](https://github.com/victoradepoju/stock-fetcher) | Market data collection service |
| 🏛️ Stock API | [victoradepoju/stock-api-service](https://github.com/victoradepoju/stock-api-service) | Stock trading interface |
| 🧾 Receipt Service | [midepeter/receipt-service](https://github.com/midepeter/receipt-service) | Digital receipt generation |
| 🤖 Anthos AI | [Overbugger/Anthos-ai](https://github.com/Overbugger/Anthos-ai.git) | AI-powered banking assistant |

## ✨ Key Improvements

1. **Independent Service Deployment**:
   - Each microservice can now be developed, tested, and deployed independently
   - Reduced deployment blast radius
   - Team autonomy with service ownership

2. **Enhanced Features**:
   - Added stock trading capabilities (Stock Fetcher & Stock API)
   - Implemented AI banking assistant (Anthos AI)
   - Improved transaction reporting (Receipt Service)

3. **Google Cloud Optimization**:
   - Cloud Run for stateless services
   - Cloud SQL for PostgreSQL databases
   - Anthos for hybrid deployments

4. **Operational Improvements**:
   - Individual CI/CD pipelines per service
   - Fine-grained monitoring and logging
   - Improved security boundaries
