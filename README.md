# Sistema de Agendamento de Visitas - Qualidade de Software

Este repositório contém o desenvolvimento de uma aplicação web para gestão de visitas, servindo como base prática para a aplicação de conceitos de qualidade, testes automatizados e integração contínua.

Funcionalidades do Sistema

A aplicação está estruturada em três níveis de acesso para atender ao fluxo de agendamento:

* **Administrador (Dev):** Responsável pelo gerenciamento de infraestrutura, incluindo o cadastro e controle de locais de visita, cidades e configurações gerais do sistema.
* **Funcionário:** Atua na gestão operacional, cadastrando pessoas a serem visitadas em seus respectivos estabelecimentos e efetuando o agendamento das visitas.
* **Visitante:** Interface de consulta onde o usuário seleciona cidades e estabelecimentos para interação e solicitações no sistema.

## Requisitos de Qualidade (CI/CD)

Para cumprir os objetivos da disciplina, o projeto implementa obrigatoriamente:

**Testes Unitários:** Validação de funções, regras de negócio e integridade dos dados[cite: 5, 6].
**Pipeline de CI/CD:** Integração contínua com feedback automático de sucesso ou falha e logs de execução.
**Revisão de Código:** Utilização de GitHub Apps para análise automatizada e comentários em Pull Requests (PRs).
**Proteção de Branch:** A branch principal exige a execução bem-sucedida da pipeline e aprovação via PR para integração.
**Deploy Automatizado:** Publicação contínua da aplicação através do GitHub Pages.

## :tools: Abordagem Técnica

**Tipo de Projeto:** [A definir: Frontend estático ou Integração com Backend/BaaS][cite: 11, 12].
**Justificativa:** A arquitetura será detalhada conforme a evolução do desenvolvimento, visando atender aos critérios de persistência de dados necessários para os perfis de acesso.

---
**Alunos:** Gabriel Sanches de Souza e Higor Silva Monteiro de Souza
**Docente:** Guilherme Ferraz
**Data Limite:** 14/04/2026
