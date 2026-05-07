# Kinesis Web

Sistema web para gerenciamento de escolinhas esportivas, desenvolvido como projeto acadêmico da disciplina de Engenharia de Software II.  
O objetivo da plataforma é centralizar o controle de atletas, responsáveis, desempenho esportivo, pagamentos e comunicação em um único ambiente digital.

---

# 📌 Sobre o Projeto

O **Kinesis** foi idealizado para auxiliar coordenadores e treinadores no gerenciamento de clubes e escolinhas esportivas, permitindo também que pais e responsáveis acompanhem o desempenho dos atletas.

A solução foi estruturada utilizando conceitos de arquitetura de software e modelagem C4, com foco em organização, escalabilidade e integração entre sistemas.

---

# 🧩 Diagrama de Contexto (C1)

O sistema interage com dois principais atores:

- **Coordenador/Treinador**
  - Gerencia clubes e atletas

- **Pais/Responsáveis**
  - Acompanham desempenho e informações

Além disso, o sistema realiza integração com:

- APIs de mensagens (WhatsApp Business API)
- Gateway de pagamentos

---

# 🏗️ Diagrama de Contêiner (C2)

A arquitetura do sistema é composta por:

| Camada | Tecnologia | Responsabilidade |
|---|---|---|
| Front-end Web | React | Interface administrativa |
| App Mobile | Flutter | Uso em campo e acompanhamento |
| API Back-end | Java + Spring Boot | Regras de negócio e autenticação |
| Banco de Dados | PostgreSQL / Supabase | Persistência dos dados |
| APIs Externas | Serviços terceiros | Mensagens e pagamentos |

Comunicação baseada em APIs REST utilizando JSON.

---

# 🚀 Tecnologias Utilizadas

## Front-end
- React
- JavaScript
- HTML5
- CSS3

## Back-end
- Java
- Spring Boot

## Mobile
- Flutter

## Banco de Dados
- PostgreSQL
- Supabase

## Integrações
- WhatsApp Business API
- Gateway de pagamentos do Mercado Pago

---

# 📂 Estrutura da Arquitetura

```text
Frontend Web (React)
        ↓
API REST (Spring Boot)
        ↓
Banco de Dados (Supabase/PostgreSQL)

Integrações:
- APIs de Mensagens
- APIs de Pagamento
```

---

# 🎯 Funcionalidades Esperadas

- Cadastro de atletas
- Cadastro de responsáveis
- Controle de clubes e escolinhas
- Acompanhamento de desempenho
- Gestão financeira
- Notificações automáticas
- Integração com pagamentos
- Comunicação com responsáveis

---

# 🔐 Objetivos da Arquitetura

- Separação clara de responsabilidades
- Facilidade de manutenção
- Escalabilidade
- Integração entre plataformas
- Centralização da lógica de negócio

---

# 📖 Modelagem Arquitetural

O projeto utiliza o modelo C4 para documentação arquitetural:

- **C1 — Diagrama de Contexto**
- **C2 — Diagrama de Contêiner**

---

# 👨‍💻 Equipe

Projeto desenvolvido para a disciplina de Engenharia de Software II.

---

# 📚 Referências

- Modelo C4 para Arquitetura de Software
- Spring Boot Documentation
- React Documentation
- Flutter Documentation
- Supabase Documentation
- PostgreSQL Documentation
