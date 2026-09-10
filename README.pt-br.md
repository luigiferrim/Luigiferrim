<div align="center">
  <h1>👋 Olá, eu sou o Luigi Ferri Maines</h1>
  <p>
    <strong>QA Automation Engineer @ Bridge Lab · trilha SDET · Sistemas de Informação @ UFSC</strong>
  </p>
  <p>
    <a href="README.md">🇺🇸 Read in English</a>
  </p>

  <p>
    <a href="https://github.com/luigiferrim/assistente-juridico">
      <img src="https://img.shields.io/badge/-Assistente_Jurídico:_sistema_agêntico_em_produção-339933?style=flat&logo=node.js&logoColor=white" alt="Assistente Jurídico" />
    </a>
    <a href="https://github.com/luigiferrim/stock_finance_management_system">
      <img src="https://img.shields.io/badge/-Stockfee:_Gestão_para_Cafeterias-000?style=flat&logo=next.js&logoColor=white" alt="Stockfee" />
    </a>
    <a href="https://github.com/luigiferrim/cafe-landing">
      <img src="https://img.shields.io/badge/-Coxilha:_Minha_marca_de_café-6F4E37?style=flat&logo=buymeacoffee&logoColor=white" alt="Coxilha" />
    </a>
  </p>
</div>

---

### 👨‍💻 Sobre mim

Escrevo código de teste e código de produto, e gosto dos problemas em que errar tem custo real para alguém.

Sou estudante de Sistemas de Informação na UFSC e trabalho como **QA Automation Engineer no Laboratório Bridge**, numa plataforma nacional de educação desenvolvida com o Ministério da Educação. Testo o backend em Java/Spring Boot, as APIs REST e o aplicativo Flutter, e conduzo a migração da suíte manual existente para testes escritos em código.

Antes da Bridge passei um ano no LabTrans, no **Monitora SP**, plataforma do Governo do Estado de São Paulo para fiscalização de trânsito. Ali construí um framework de automação do zero em Playwright e C#, e aprendi a maior parte do que sei sobre por que suítes de teste falham por motivos que não têm nada a ver com o produto.

Fora do trabalho eu construo e publico coisas. A que mais me orgulha é um assistente jurídico agêntico que roda um ciclo diário totalmente automatizado **em produção desde agosto de 2026**.

* 🌍 **Idiomas:** Português (nativo) · Inglês (fluente) · Francês (fluente)
* 📍 **Localização:** Florianópolis, SC — Brasil
* 🇮🇹 **Cidadania italiana** — autorização de trabalho na União Europeia
* 🎯 **Foco:** Automação de testes (Playwright / C#), engenharia de backend (Node.js, TypeScript) e sistemas agênticos com aprovação humana no fluxo

---

### 🛠️ Stack

<div align="center">

**QA e Automação de Testes**
<br>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright" />
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />

**Desenvolvimento e Dados**
<br>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />

**Ambientes que eu testo**
<br>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />

</div>

---

### 🚀 Experiência

**QA Automation Engineer — Laboratório Bridge** *(jun/2026 – atual)*
* Testo o backend em Java/Spring Boot, as APIs REST e o aplicativo Flutter de uma plataforma com mais de 18 milhões de downloads, feita com o Ministério da Educação.
* Analiso a suíte manual existente e conduzo sua migração para testes escritos em código.
* Valido o estado persistido direto no banco com SQL, em vez de confiar no que a interface mostra.

**QA Analyst — LabTrans/UFSC (Monitora SP)** *(jul/2025 – jun/2026)*
* Construí um framework de automação do zero em **Playwright + C#**, estruturado em Page Object Model cobrindo **mais de 50 fluxos de telas e arquivos**.
* Descobri que **40% das falhas eram falso negativo**: massa de dados fixa colidia com as regras de negócio. Refiz a camada de dados para buscar no banco, em tempo de execução, um registro válido e livre, com teardown que devolve a base ao estado original. Os falsos negativos foram para perto de zero.
* Reduzi a regressão dos fluxos principais de **mais de um dia de execução manual para 90 segundos em 30 caminhos**.
* Validei mais de 60 releases em 4 ambientes e 3 instituições, com análise de causa raiz grey box sobre código-fonte e logs.

---

### 📊 Projetos em destaque

#### [Assistente Jurídico](https://github.com/luigiferrim/assistente-juridico) — *assistente jurídico agêntico, em produção*
Toda manhã ele lê o Diário de Justiça, faz a triagem do que chegou para cada advogado, monta um briefing por e-mail e, com **um clique de aprovação**, coloca a audiência na Google Agenda e prepara o aviso ao cliente. Construído para um escritório trabalhista real e rodando ciclo diário totalmente automático desde ago/2026.

A regra que não se negocia: **o sistema propõe, a advogada aprova.** Nenhuma ação externa acontece sem aprovação humana explícita.

* **Decisões de engenharia que valem a leitura:** auditoria append-only garantida por trigger de banco; chave de idempotência gravada *antes* da chamada externa; coleta que falha no meio volta `incompleto`, para que "0 itens" nunca vire "não há nada"; segredos no Keychain do sistema; sanitização recursiva de logs; e um teste de hermetismo que quebra o build se algum termo real do config local vazar para o repositório.
* **A triagem é determinística, não é IA.** Cada cartão diz quais sinais o classificaram. Nada de "o modelo achou que era urgente".
* **CI como portão, não como badge:** o GitHub Actions roda a suíte, um lint sem dependência e uma auditoria de vazamento sobre a árvore e o *histórico inteiro do git*; qualquer número de processo real, OAB, e-mail ou segredo derruba o build, e o relatório sai redigido porque o log é público.
* **Tech:** Node.js 22, **zero dependências npm** (só módulos nativos, incluindo `node:sqlite` e `node:test`), SQLite com tabelas `STRICT`, Google Apps Script, launchd. 131 testes herméticos.

#### [Stockfee](https://github.com/luigiferrim/stock_finance_management_system) — *sistema de gestão para cafeterias (projeto em equipe, UFSC)*
Sistema completo de estoque e gestão financeira para cafeterias e torrefações, construído com mais três colegas para a disciplina de desenvolvimento web e publicado em produção. Objetivo: transformar em um SaaS de verdade.
* **Minha parte:** integração e módulos internos (dashboard, estoque, financeiro, histórico).
* **Tech:** Next.js, TypeScript, PostgreSQL (Neon), NextAuth, Tailwind, Vercel.

#### [Coxilha](https://github.com/luigiferrim/cafe-landing) — *landing page de café especial (solo)*
Landing page que construí sozinho para vender café especial, com foco em front-end limpo e design responsivo.
* **Tech:** React, Tailwind CSS, Vercel.

#### [Sistema CaFerri](https://github.com/salmoriadev/Sistema_CaFerri) — *sistema desktop para cafeteria (equipe, acadêmico)*
Aplicação desktop em Python com arquitetura MVC + DAO: fornecedores, produtos, clientes, estoque, vendas e relatórios exportados em arquivos versionados por data.
* **Tech:** Python 3, POO, MVC, DAO, pickle, FreeSimpleGUI.

---

<div align="center">

### 📫 Vamos conversar

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/luigiferrimaines)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:luigiferrimaines@gmail.com)

</div>
