# LAB03-DAMD-Microserviços
Microsserviços com API Gateway e NoSQL

## Objetivos
- Implementar arquitetura de microsserviços com 2 serviços básicos (User e Product)
- Utilizar bancos NoSQL independentes baseados em JSON
- Implementar API Gateway com service discovery
- Demonstrar comunicação REST entre serviços
- Aplicar padrões fundamentais: Circuit Breaker, Service Registry, Database per
Service
## Fundamentação Teórica
Microsserviços representam uma abordagem arquitetural que estrutura uma aplicação
como uma coleção de serviços fracamente acoplados. Esta implementação utiliza
bancos NoSQL independentes para cada serviço, demonstrando o princípio de
**Database per Service**.
### Características Implementadas
- **Service Discovery**: Registry centralizado para localização de serviços
- **API Gateway**: Ponto único de entrada com roteamento e agregação
- **Circuit Breaker**: Proteção contra falhas em cascata
- **Database per Service**: Cada serviço possui seu próprio banco NoSQL
- **Schema Flexível**: Documentos JSON adaptáveis sem migração
### Padrões Demonstrados
- **API Gateway Pattern**: Centralização do acesso aos serviços
- **Service Registry Pattern**: Descoberta automática de serviços
- **Circuit Breaker Pattern**: Resiliência contra falhas
- **Aggregator Pattern**: Combinação de dados de múltiplos serviços
- **Database per Service**: Isolamento de dados por contexto
