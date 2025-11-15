# 🏛️ Oficina de IA: Prompts para Desenvolvedores Mainframe

Bem-vindo! Este repositório é um catálogo público de prompts de Inteligência Artificial, com foco especial em acelerar e otimizar o desenvolvimento no ambiente Mainframe (COBOL, JCL, DB2, CICS, etc.).

O objetivo é transformar a maneira como interagimos com a IA, saindo da "tentativa e erro" para a **"engenharia de prompts"**.

## 🚀 A sua Jornada ! 

Para organizar o conhecimento, estruturamos este repositório seguindo uma jornada de proficiência. Cada nível representa um domínio maior na "arte de perguntar" à IA.

As pastas deste projeto refletem estes níveis:

* **🧰 Nível 1: Aprendiz**
    * **Quem é:** O desenvolvedor que está começando.
    * **Objetivo:** Usar prompts prontos (copiar e colar) para resolver tarefas imediatas e comuns.
    * **Exemplos:** "O que é um ABEND S0C7?", "Gere um esqueleto de programa COBOL".

* **🛠️ Nível 2: Artesão**
    * **Quem é:** O desenvolvedor que já entende o básico.
    * **Objetivo:** Adaptar e refinar prompts, fornecendo seu *próprio contexto* (como seu código, JCL ou erro) para obter respostas específicas.
    * **Exemplos:** "Por que *este* meu código está dando S0C7?", "Otimize *esta* query SQL".

* **📐 Nível 3: Mestre (de Ofício)**
    * **Quem é:** O desenvolvedor que domina a "conversa" com a IA.
    * **Objetivo:** Projetar e engenheirar prompts complexos do zero, usando técnicas avançadas (como Personas, "Few-Shot") para resolver problemas novos ou criar soluções completas.
    * **Exemplos:** "Atue como um DBA sênior e analise...", "Gere um programa COBOL completo com estas 5 regras de negócio".

* **🧭 Nível 4: Mentor**
    * **Quem é:** O facilitador ou especialista (como você!).
    * **Objetivo:** Criar padrões, guias de boas práticas e templates reutilizáveis (como Stacks do StackSpot) para escalar o conhecimento para toda a equipe.
    * **Exemplos:** "Guia de Segurança de IA", "Template para documentar um programa".

## 🗺️ Como Usar este Repositório

1.  **Identifique seu Nível:** Pense na tarefa que você quer realizar. É uma pergunta simples (Aprendiz) ou você precisa de uma análise complexa (Mestre)?
2.  **Navegue pelas Pastas:** Acesse a pasta que corresponde ao seu nível de necessidade.
3.  **Encontre seu Prompt:** Os prompts estarão (provavelmente) em arquivos `.md` individuais, com título claro e uma breve explicação.
4.  **Copie e Adapte:** Copie o prompt, cole na sua ferramenta de IA de preferência e adapte-o conforme necessário.

### Navegação Rápida

* ./Mainframe/Kit de Ferramentas do Aprendiz - Prompts prontos para uso imediato.
* ./Mainframe/Técnicas de Artesão - Exemplos de como adicionar seu contexto.
* ./Mainframe/Projetos de Mestre - Técnicas avançadas de engenharia de prompt.
* ./Mainframe/Guias do Mentor/Principios de Design de Prompt - Guias de boas práticas, padrões e templates.

---

## 🚨 REGRA DE OURO: SEGURANÇA E DADOS SENSÍVEIS 🚨

As ferramentas de IA Generativa são, em sua maioria, ambientes públicos. A regra é simples:

**NUNCA, EM HIPÓTESE ALGUMA, INSIRA DADOS REAIS DA EMPRESA OU DE CLIENTES EM UM PROMPT PÚBLICO.**

Isso inclui:

* ❌ **NÃO USE:** Dados pessoais de clientes (CPFs, nomes, números de conta, telefones).
* ❌ **NÃO USE:** Código-fonte proprietário que contenha segredos (chaves de API, senhas, tokens, lógica de negócio confidencial).
* ❌ **NÃO USE:** Informações de infraestrutura interna (nomes de servidores, IPs, credenciais).

**COMO USAR COM SEGURANÇA?**
Use a IA para a **lógica** e o **padrão**, não para os **dados**.

* **RUIM:** "Otimize este código que acessa a conta do cliente [NOME REAL DO CLIENTE]..."
* **BOM:** "Otimize este código COBOL que lê um arquivo e atualiza uma tabela. O padrão do código é este: [colar um trecho de código *genérico*, com nomes de variáveis e campos alterados para 'CAMPO-TESTE', 'VALOR-TESTE', etc.]"

## 🤝 Como Contribuir

Vamos modernizar o Mainframe juntos!
