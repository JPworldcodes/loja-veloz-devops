# Loja Veloz DevOps

## Sobre o Projeto
Projeto desenvolvido para demonstrar uma arquitetura baseada em microsserviços com práticas de DevOps, incluindo conteinerização, orquestração com Kubernetes e CI/CD.

---

## Arquitetura

- API Gateway
- Serviço de Pedidos
- Serviço de Pagamentos
- Serviço de Estoque
- Banco de Dados PostgreSQL

---

## Execução Local (Docker Compose)

```bash
docker-compose up --build
kubectl apply -f k8s/
CI/CD

Pipeline automatizado com GitHub Actions:

- Build
- Testes
- Validações
- Observabilidade
- Logs centralizados
- Métricas com Prometheus
- Tracing com OpenTelemetry
- Escalabilidade
- HPA (Horizontal Pod Autoscaler)
- Baseado em uso de CPU
- Estratégia de Deploy

- Rolling Update

- Execução do Projeto
- Docker

- Kubernetes

- CI/CD
