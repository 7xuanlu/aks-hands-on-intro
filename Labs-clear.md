# Docker Desktop for Windows 與 Azure Kubernetes Service 實機操作

## 刪除 Azure Container Registry 與 Azure Kubernetes Service 叢集之資源群

在命令列模式下達以下指令即會刪除過程中所建立的資源群組和 Azure Kubernetes Service 叢集，整個過程會花費數分鐘時間。

```powershell
az group delete -n <your-resource-group-name>
```

* [返回 README](README.md)