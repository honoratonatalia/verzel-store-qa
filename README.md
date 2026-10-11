# Verzel Store QA - Teste Técnico

Repositório dedicado à entrega do desafio técnico de Quality Assurance para a Verzel.



📌 1. Mapeamento de Cenários (BDD / Gherkin) & Evidências

Todos os cenários de teste (funcionais, exploratórios, casos de borda) e o relatório detalhado de defeitos encontrados estão documentados e organizados no arquivo PDF anexado na raiz do repositório:

📄 Cenarios_Gherkin_Passo_a_Passo_Evidencias.pdf



 🎭 2. Automação de Testes (Playwright)

A suíte de testes automatizados cobre os cenários principais da aplicação utilizando **Playwright** + **TypeScript**.

🛠️ Pré-requisitos

* **Node.js** (versão 18 ou superior)
* **npm** (gerenciador de pacotes do Node)

 🚀 Como executar os testes

1. Clone o repositório ou faça o download dos arquivos:
bash
git clone https://github.com/honoratonatalia/verzel-store-qa.git
cd verzel-store-qa

2. Instale as dependências do projeto:
bash
npm install

3. Execute os testes automatizados do Playwright:
bash
npx playwright test

4. Para visualizar o relatório de execução dos testes:
bash
npx playwright show-report

---

## 📂 Estrutura do Projeto

* `testes/` - Scripts de automação do Playwright em TypeScript.
* `Cenarios_Gherkin_Passo_a_Passo_Evidencias.pdf` - Relatório detalhado dos cenários em BDD, testes exploratórios, bugs e evidências.
* `playwright.config.ts` - Configurações do framework de automação.
* `.gitignore` - Filtro de arquivos e diretórios ignorados pelo Git.
