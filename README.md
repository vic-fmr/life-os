# Life OS - ERP Pessoal

Projeto pessoal de um sistema robusto e integrado para gestão de vida, unificando finanças, estudos e rotina em uma única plataforma. 

O intuito do desenvolvimento foi sanar uma dor pessoal ao mesmo tempo que pratico stacks interessantes pra mim.

## Sobre
O **Life OS** nasceu da necessidade de centralizar dados que normalmente ficam espalhados. Diferente do Notion ou Excel, este sistema utiliza regras de negócio ativas para correlacionar produtividade, saúde financeira e desempenho acadêmico.

## Stacks
- **Backend:** Java 25, Spring Boot 3, Spring Data JPA, Spring Security.
- **Frontend:** Angular 21 (Signals, RxJS).
- **Banco de Dados:** PostgreSQL via Docker.
- **Infra:** Docker & Docker Compose.

## MVP
O sistema é dividido em módulos integrados:
- **Financeiro:** Controle de fluxo de caixa com categorias personalizadas.
- **Estudos:** Registro de horas líquidas e progresso por disciplina.
- **Rotina/Treino:** Habit tracker integrado com sistema de "penalidades" ou metas.

## 🚀 Como rodar o ambiente de desenvolvimento

### Pré-requisitos
- Docker instalado.
- JDK 25.

### Passo 1: Subir o banco de dados
Na raiz do projeto, execute:
```bash
docker compose up -d
```
### Passo 2: Rodar o com o maven:
```bash
./mvnw spring-boot:run
```
---
#### Desenvolvido por Victor Ferreira Marques como projeto pessoal de Engenharia de Software.
