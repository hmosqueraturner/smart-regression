# 📦 UPDATE-RAG

Scheduled job (cron) to fetch test cases from JIRA, update Cosmos DB, and index results in Azure Cognitive Search.

---

## 🚀 Requisitos

- Node.js >= 18
- Docker
- Azure CLI (`az`)
- Azure Container Registry (ACR)
- Azure Container Apps Environment
- `.env` con:

```env
REACT_APP_EVALUATE_API=https://<tu-api-evaluate>.azurecontainerapps.io/evaluate
REACT_APP_JSON_URL=https://<tu-storage>.blob.core.windows.net/<container>/result.json
