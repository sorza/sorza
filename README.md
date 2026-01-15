#  Olá! Sou Alexandre Zordan

** Professor Centro Paula Souza | Desenvolvedor Backend .NET **


##  Sobre Mim

Além de transformar vidas através da educação tecnológica,
Especialista em construir sistemas distribuídos escaláveis utilizando Clean Architecture, Domain-Driven Design e Event Sourcing.

- Desenvolvedor Backend com foco em **microserviços .NET**
- Experiência em **Clean Architecture**, **DDD** e padrões de design (Strategy, Factory, Repository)
- Proficiente em **Azure** (Container Apps, Service Bus, Functions, API Management)

---

##  Projetos em Destaque

### FCG Games
Arquitetura completa de microserviços para plataforma de venda de jogos digitais, com 6 serviços independentes:

#### 🎮 **[FCG-Games](https://github.com/sorza/FCG-Games)** - Catálogo de Jogos
- API RESTful para gestão de catálogo de games
- Entity Framework Core com SQL Server
- Publicação de eventos de domínio (GameCreated, GameUpdated)
- Background Service consumindo eventos de outros bounded contexts

#### 💳 **[FCG-Payments](https://github.com/sorza/FCG-Payments)** - Processamento de Pagamentos
- **Strategy Pattern** para múltiplos métodos de pagamento (Cartão, PayPal, PIX)
- **Event Sourcing** com MongoDB (auditoria completa de transações)
- Integração assíncrona via Azure Service Bus
- HttpClient para comunicação síncrona com Libraries Service

#### 👤 **[FCG-Users](https://github.com/sorza/FCG-Users)** - Gestão de Usuários
- Autenticação JWT com validação em todos os serviços
- Hash de senhas com PBKDF2 (100.000 iterações)
- Event-driven: publica UserCreatedEvent para outros serviços
- Autorização baseada em Claims

#### 📚 **[FCG-Libraries](https://github.com/sorza/FCG-Libraries)** - Biblioteca de Jogos
- Gerenciamento de biblioteca pessoal de cada usuário
- Integração com Payments via eventos (adiciona jogo após pagamento aprovado)
- Consumer pattern para processamento assíncrono
- Validação de ownership (previne duplicação)

#### ⚡ **[FCG-Functions](https://github.com/sorza/FCG-Functions)** - Azure Functions
- Processamento serverless de tarefas assíncronas
- Trigger do Service Bus para envio de emails
- Isolated Worker (.NET 8)
- Demonstração de arquitetura híbrida (microserviços + serverless)

#### 📦 **[FCG-Contracts](https://github.com/sorza/FCG-Contracts)** - Shared Kernel
- Base classes para Event Sourcing (Entity, ValueObject)
- Interfaces compartilhadas (IDomainEvent, IEventPublisher, IEventStore)
- Enums de domínio (EOrderStatus, EPaymentStatus, EPaymentType)
- Pattern Result para tratamento de erros

---

##  Stack Tecnológico

### Backend & Frameworks
![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

### Cloud & Infrastructure
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

### Databases
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Cosmos DB](https://img.shields.io/badge/Cosmos%20DB-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)

### Messaging & Integration
![Azure Service Bus](https://img.shields.io/badge/Service%20Bus-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

### Architecture & Patterns
- **Clean Architecture** 
- **Domain-Driven Design** 
- **SOLID Principles**
- **Event Sourcing** + **CQRS**
- **Event-Driven Architecture** 
- **Design Patterns**: Strategy, Factory, Repository, Unit of Work

---

##  GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=sorza&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sorza&layout=compact&langs_count=8&theme=tokyonight"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sorza&theme=tokyonight" alt="GitHub Streak"/>
</div>

---


## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/alexandre-zordan-3070a0103/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alexandre.sorza@outlook.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sorza)

---

**Disponível para oportunidades** em desenvolvimento backend .NET e arquitetura de microserviços!
