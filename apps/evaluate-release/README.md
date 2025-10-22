# 📦 API-EVALUATE

Azure Container Apps API (`api-evaluate`)
Evaluate a release by querying Cosmos DB and Azure Search, generates a JSON report, and uploads it to Azure Blob Storage.

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
