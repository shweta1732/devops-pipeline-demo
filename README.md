# 🚀 DevOps Pipeline Demo

A sample project demonstrating **Azure DevOps pipeline** and **Docker** integration for continuous integration and continuous deployment (CI/CD).

## 📁 Project Structure

```
/src → Sample .NET backend application  
azure-pipelines.yml → Azure DevOps pipeline configuration  
Dockerfile → Containerization setup
```

## ⚙️ Getting Started

### Prerequisites
- .NET 6 SDK
- Azure DevOps account
- Docker

### Local Build
```bash
cd src
dotnet build
dotnet run
```

### Docker Build
```bash
docker build -t devops-pipeline-demo .
docker run -p 5000:80 devops-pipeline-demo
```

### Azure DevOps Pipeline
- Commit code to `main` branch
- Pipeline will build, test, and push Docker image to container registry

## 📬 Contact
**Shweta**  
📧 1732shwetaa@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/your-profile)