# 🧪 testeHcoder

Repositório de testes comportamentais (BDD) escritos com linguagem **Gherkin** para a história de usuário do **Programa de Recompensa e Benefícios da QAtest**

---

## 📋 Objetivo

Este projeto tem como objetivo validar, por meio de cenários BDD, as regras e funcionalidades descritas na história de usuário da operadora **QAtest**, responsável por um programa de benefícios segmentado por plano: **Basic**, **Premium** e **Black**

Os testes foram estruturados utilizando arquivos `.feature` com cenários escritos em **português (pt-BR)**, simulando interações reais de clientes com o sistema de resgates e visualização de recompensas.

---

## 📁 Estrutura de diretórios

```bash
testeHcoder/
├── tests/
│   ├── Condicoes_especiais.feature
│   ├── Historico_resgates.feature
│   ├── Plano_upgrade.feature
│   ├── Renovacao_beneficios.feature
│   ├── Resgate_beneficios.feature
│   ├── Restricoes_bloqueios_beneficios.feature
│   ├── Saldo_cliente.feature
├── README.md
```

## 🧩 Funcionalidades cobertas

- ✅ **Resgate de benefícios por nível de plano**
- 🔒 **Bloqueios por limite, inadimplência ou DDD**
- ⛔ **Benefícios esgotados e com estoque limitado**
- 🔁 **Reset automático de benefícios mensalmente**
- 🔼 **Upgrade de plano com novos benefícios liberados**
- 🧾 **Histórico de resgates com saldo disponível por mês**
- 🎯 **Acesso a experiências e sorteios por DDD e regras de plano**

## 🚀 Como usar

Este repositório pode ser usado como base para automação de testes com ferramentas como:

- [**Behave** (Python)](https://behave.readthedocs.io/)
- [**Cucumber** (Java, JS, Ruby)](https://cucumber.io/)
- [**Robot Framework com GherkinLibrary**](https://robotframework.org/GherkinLibrary/)

> Basta adaptar os arquivos `.feature` e os step definitions conforme o framework utilizado no seu projeto.

---


