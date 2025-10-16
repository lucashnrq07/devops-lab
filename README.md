# 🧩 Projeto DevOps - Etapa Kubernetes

## 📘 Descrição

Aplicação **full stack (frontend + backend + MongoDB)** containerizada, evoluindo de **Docker Compose** para **Kubernetes** (Minikube).

## 🐳 Etapa Docker

```bash
docker-compose up --build
```

A aplicação ficará disponível em `http://localhost:3000`.

## ☸️ Etapa Kubernetes

1. Iniciar o cluster:

```bash
minikube start
```

2. Aplicar os manifests:

```bash
kubectl apply -f k8s/
```

3. Verificar pods:

```bash
kubectl get pods
```

4. Acessar frontend:

```bash
minikube service frontend
```

## 🔜 Próximos passos

Terraform, Ansible, CI/CD e Monitoramento.
