# Olá, eu sou o Carlos Hygor Félix 

**Desenvolvedor Back-End & Web | Graduando em Sistemas de Informação (UFAC)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carloshygor)
[![Portfólio](https://img.shields.io/badge/Portfólio_Completo-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CarlosHygor/backend-portfolio)
[![E-mail](https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:carlos.feliix@hotmail.com)

---

## 🎯 Sobre Mim

Desenvolvedor focado na construção de **APIs RESTful escaláveis, microsserviços e sistemas de alta performance**, utilizando os ecossistemas **Java (Spring Boot)** e **C# (.NET 8)** no back-end, aliados ao **Angular (TypeScript)** no front-end. 

Tenho vivência prática em resiliência distribuída, engenharia defensiva (Padrão Saga, Idempotência, Row-Level Locking), otimização de cache e suítes rigorosas de testes automatizados (67+ testes).

- 🎓 Graduando em Sistemas de Informação na **Universidade Federal do Acre (UFAC)** (Previsão: 2028.1).
- 💡 Bolsista de capacitação corporativa pela **Web Academy (+600h) em parceria com a Motorola**.
- 🏆 1º Lugar no **Hackathon Google (GenAI for Community Impact - $500 USD)**.
- 👨‍🏫 Instrutor de lógica e programação com **Python** no projeto **+Ciência na Escola**.

---

## 🛠️ Tecnologias & Habilidades

### Back-End & Arquitetura
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

**Conceitos Aplicados:** APIs RESTful, Microsserviços, Clean Architecture, SOLID, Design Patterns, Padrão Saga (Ação Compensatória), Idempotência, Multi-tenancy, Concorrência e Row-Level Locking.

### Front-End & Acessibilidade
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=for-the-badge&logo=reactivex&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Conceitos Aplicados:** Formulários Reativos, Consumo Reativo de APIs, WCAG 2.2 Level AAA (Acessibilidade Web & VLibras).

### Bancos de Dados & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Caffeine](https://img.shields.io/badge/Caffeine_Cache-000000?style=for-the-badge&logo=java&logoColor=white)

**Conceitos Aplicados:** Modelagem Relacional, EF Core, JPA/Hibernate, Geoprocessamento (GeoJSON), Cache em Memória, Compressão GZip.

### DevOps, Qualidade & Ferramentas
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-0078D4?style=for-the-badge&logo=dotnet&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Conceitos Aplicados:** CI/CD, Devcontainers, Agentes de IA, Testes Automatizados (67+ testes), Moq, FluentAssertions.

---

## 🏛️ Projetos em Destaque

### 📦 1. Sistema de Gestão de Estoque e Faturamento (.NET 8 + Angular 22)
* **Arquitetura de Microsserviços & Resiliência:** Microsserviços desacoplados (`Estoque.API` e `Faturamento.API`) com comunicação resiliente, suporte a `IdempotencyKey` e ações compensatórias automatizadas via **Padrão Saga** em falhas de rede.
* **Prevenção de Overbooking:** Proteção contra inconsistências de estoque sob concorrência simultânea via *Pessimistic Row-Level Locking* no PostgreSQL e validação em 3 camadas (*Defense in Depth*).
* **Qualidade Automatizada:** Suíte de **67 testes automatizados aprovados** (43 xUnit/Moq no C# + 24 Vitest no Angular) e conformidade **WCAG 2.2 Level AAA** com widget VLibras e Modo Alto Contraste.
* 💻 [Repositório Público no GitHub](https://github.com/CarlosHygor/Korp_Teste_CarlosHygor)

### 🏢 2. Automação e Gestão de Relatórios P&D (SUFRAMA)
* **Multi-tenancy & Segurança:** Implementação de arquitetura Multi-tenancy isolada utilizando *Tokens de Contexto (JWT Customizado)* para prevenir falhas de autorização (IDOR) entre projetos.
* **Integração Assíncrona:** Eliminação de gargalos HTTP ao integrar a API do Google Drive via `@Async` com *Retry + Exponential Backoff*.
* **Liderança & DevOps:** Atuação como SCRUM Master validando entregas com Product Owners e estruturação da esteira de CI/CD automatizada via Docker, Dokploy e GitHub Actions.
* 📖 [Estudo de Caso Completo](https://github.com/CarlosHygor/backend-portfolio/tree/main/projects/01-suframa-pd-system)

### 🗺️ 3. Hierarchical Team Management System (GLC)
* **Otimização de Performance:** Solução de gargalos no envio de dados geoespaciais (GeoJSON de 62k+ linhas), reduzindo a latência e o tráfego em **75%** (de ~350KB para ~80KB) através de Caffeine Cache, Redis, compressão GZip e `Cache-Control` HTTP.
* **SOLID & Segurança:** Abstração de contexto de segurança JWT via `AuthenticatedContext` injetável, mantendo a camada de serviço desacoplada do Spring Security.
* 📖 [Estudo de Caso Completo](https://github.com/CarlosHygor/backend-portfolio/tree/main/projects/02-hierarchical-team-management)

---

## 🏆 Conquistas, Competições & Extensão

* **1º Lugar no Hackathon Google (GenAI for Community Impact - $500 USD):** Desenvolveu solução de Inteligência Artificial Generativa para impacto comunitário na região amazônica em competição global.
* **Professor de Programação (Projeto +Ciência na Escola):** Ministra aulas de lógica de programação e pensamento computacional utilizando Python para alunos do ensino fundamental público.
* **Moonlight Games (Estúdio Indie):** Co-fundador e dev. Escalou a equipe de 5 para 11 membros na entrega de 4 protótipos ágeis. 1º Lugar na Gamejam TXAI e 1º Lugar (Voto Popular) na Headscom, sendo selecionado para exibição presencial na **Gamescom Latam (SP)** e **Gamescom (Alemanha)**.
* **Maratona de Programação da SBC:** 2º Lugar no Estado do Acre (Fase Zero), resolvendo problemas de alta complexidade algorítmica sob pressão em equipe.

---

## 📬 Contato & Redes

- 💼 **LinkedIn:** [Carlos Hygor](https://www.linkedin.com/in/carloshygor)
- 🐙 **GitHub:** [@CarlosHygor](https://github.com/CarlosHygor)
- ✉️ **E-mail:** [carlos.feliix@hotmail.com](mailto:carlos.feliix@hotmail.com)

---
⭐️ *Construindo software robusto, resiliente e orientado a testes.*
