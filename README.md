# 🛡️ Relatório de Auditoria de Segurança: Botium Toys

> **Projeto Integrante do Google Cybersecurity Professional Certificate**

## 📋 Visão Geral do Projeto

Este projeto consiste em uma auditoria de segurança completa realizada para a **Botium Toys**, uma varejista de brinquedos fictícia. O trabalho foi desenvolvido como parte prática do **Google Cybersecurity Professional Certificate**, simulando um cenário real de análise de risco e conformidade.

O objetivo foi avaliar a postura de segurança atual da empresa, identificar vulnerabilidades críticas e recomendar controles para mitigar riscos e garantir a conformidade com regulamentações internacionais. O escopo abrangeu todo o programa de segurança da Botium Toys, incluindo ativos físicos, digitais, processos internos e conformidade regulatória.

## 🏢 Cenário e Escopo

A Botium Toys está expandindo sua presença online, mas sua infraestrutura de segurança não acompanhou esse crescimento. A avaliação de risco inicial indicou uma pontuação de risco de **8/10**, considerada alta devido à falta de controles adequados e adesão às melhores práticas.

**Ativos Gerenciados pelo TI:**
* Equipamentos locais e dispositivos de usuários finais (desktops, laptops, smartphones).
* Sistemas de gerenciamento (contabilidade, banco de dados, e-commerce).
* Rede interna, acesso à internet e armazenamento de dados.
* Sistemas legados.

## 🔍 Metodologia e Frameworks

A auditoria foi baseada na função "Identificar" do **NIST Cybersecurity Framework (CSF)** e avaliou a conformidade com os seguintes regulamentos e padrões:

* **PCI DSS** (Payment Card Industry Data Security Standard).
* **GDPR** (General Data Protection Regulation).
* **SOC** (System and Organizations Controls).

## 🚩 Principais Vulnerabilidades Identificadas

A análise dos controles atuais revelou lacunas críticas na segurança da informação:

* **Controle de Acesso:** O princípio do menor privilégio não é aplicado; todos os funcionários têm acesso a dados internos e sensíveis.
* **Criptografia:** Não há uso de criptografia para proteger dados de cartão de crédito ou informações de clientes, tanto em repouso quanto em trânsito.
* **Recuperação de Desastres:** Inexistência de planos de recuperação de desastres e backups de dados críticos.
* **Gerenciamento de Senhas:** Políticas de senha fracas que não exigem complexidade mínima e ausência de um sistema de gerenciamento centralizado.
* **Monitoramento:** Ausência de Sistema de Detecção de Intrusão (IDS).

## ✅ Controles Existentes (Pontos Fortes)

Apesar das falhas, a empresa possui alguns controles implementados:
* Firewall configurado com regras de segurança definidas.
* Software antivírus instalado e monitorado regularmente.
* Segurança física robusta (fechaduras, CCTV, detecção de incêndio).
* Plano de notificação de violação para clientes da U.E. (GDPR).

## 🚀 Recomendações Estratégicas

Com base na auditoria, foram propostas as seguintes ações prioritárias para a gestão de TI:

1.  **Implementar Criptografia:** Essencial para conformidade com PCI DSS e proteção de PII.
2.  **Adotar o Princípio do Menor Privilégio:** Restringir o acesso aos dados apenas a usuários autorizados.
3.  **Estabelecer Plano de Recuperação de Desastres (DR):** Criar rotinas de backup e procedimentos de continuidade de negócios.
4.  **Fortalecer Políticas de Senha:** Implementar requisitos de complexidade e um gerenciador de senhas.
5.  **Instalar IDS:** Para detecção proativa de tráfego anômalo na rede.

## 📂 Estrutura de Arquivos

Os documentos detalhados desta auditoria estão organizados na pasta `docs/`:

* `docs/Botium Toys: Scope, goals, and risk assessment report.pdf`: Documento detalhando o escopo da auditoria e a análise de risco inicial.
* `docs/Controls and compliance checklist.pdf`: Checklist preenchido com a avaliação dos controles e conformidade.
* `docs/Control categories.pdf`: Referência sobre categorias e tipos de controles de segurança utilizados na análise.

## 🛠️ Habilidades Demonstradas

* Avaliação de Risco (Risk Assessment).
* Auditoria de Conformidade (Compliance Auditing - PCI DSS, GDPR, SOC).
* Análise de Controles de Segurança (NIST CSF).
* Governança de TI.
* Identificação de Vulnerabilidades.

---
