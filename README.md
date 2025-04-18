# Sistema de Consultas Médicas
<img alt="Banner do Sistema" src="https://img.shields.io/badge/Sistema-Consultas_Médicas-27ae60?style=for-the-badge">


Uma plataforma completa para agendamento de consultas médicas, integrando um frontend moderno em Next.js com backend robusto em NestJS e banco de dados PostgreSQL.


<img alt="Next.js" src="https://img.shields.io/badge/frontend-Next.js-000000?style=flat&amp;logo=next.js">
<img alt="NestJS" src="https://img.shields.io/badge/backend-NestJS-E0234E?style=flat&amp;logo=nestjs">
<img alt="PostgreSQL" src="https://img.shields.io/badge/database-PostgreSQL-336791?style=flat&amp;logo=postgresql">
<img alt="Docker" src="https://img.shields.io/badge/container-Docker-2496ED?style=flat&amp;logo=docker">

## 🔍 Visão Geral
O Sistema de Consultas Médicas é uma plataforma completa para gerenciar agendamentos de consultas médicas. Os pacientes podem pesquisar médicos por especialidade, visualizar avaliações, agendar consultas e gerenciar seus agendamentos. Os médicos podem visualizar e gerenciar seus horários e consultas agendadas.

Principais Funcionalidades
✅ Cadastro de usuários
✅ Pesquisa de médicos por especialidade
✅ Visualização de horários disponíveis
✅ Agendamento de consultas

## 📦 Requisitos

Node.js 18.x ou superior
PostgreSQL 14.x ou superior
Docker e Docker Compose (opcional)

## 🚀 Configuração de Desenvolvimento

### Configuração com Docker

Para iniciar o sistema completo com Docker:
```bash
# Entre na pasta raiz do projeto
cd projeto-consultas

# Inicie os containers
docker compose up -d --build

# Para visualizar os logs
docker compose logs -f
```

Após inicializar, você poderá acessar:

Frontend: http://localhost:3000
Backend: http://localhost:5000

