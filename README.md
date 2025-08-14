# 📄 NF-e Didática — Gerador de XML + DANFE

Aplicação web interativa em **HTML, CSS e JavaScript** para **simular a emissão de Notas Fiscais Eletrônicas (NF-e)** em ambiente educacional.  
Projetada para **aulas de logística** e treinamentos, permitindo que os alunos pratiquem o preenchimento de campos, inclusão de produtos e geração do DANFE **sem usar dados reais**.

---

## 🚀 Funcionalidades

- **Editor completo** para:
  - Configurações de operação (UF, série, número, CFOP, alíquotas, frete, etc.).
  - Dados do emitente e destinatário.
  - Inclusão de múltiplos itens com código, descrição, NCM, CFOP, unidade, quantidade, valor unitário e tributos.
  - Informações complementares.

- **Geração de XML** no padrão NF-e 4.00:
  - Baixar arquivo `.xml`.
  - Copiar para área de transferência.
  - Salvar e reabrir rascunhos no navegador.

- **Visualização de DANFE**:
  - Exibição em formato A4 com canhoto e logomarca.
  - Tabela de produtos e totais.
  - Cálculo de impostos.
  - Código de barras (Code128C) da chave de acesso.
  - Impressão direta pelo navegador.

---

## 🎯 Público-alvo

- Estudantes de logística, administração e contabilidade.
- Instrutores e professores.
- Profissionais em treinamento de emissão de NF-e.

---

## 📂 Estrutura do projeto

- **`nfe_VERSAO_FINAL.html`** → Arquivo único contendo toda a aplicação.
  - Inclui HTML, CSS e JavaScript integrados.
  - Não requer instalação de bibliotecas externas.
  - Funciona offline no navegador.

---

## 🖥️ Como usar

1. Baixe o arquivo `nfe_VERSAO_FINAL.html`.
2. Abra no navegador (Google Chrome, Edge ou Firefox).
3. Na aba **Preencher & Gerar XML**:
   - Preencha as informações necessárias.
   - Adicione itens clicando em **+ Adicionar item**.
4. Clique em **Gerar XML (baixar)** ou **Gerar & Visualizar** para ver o DANFE.
5. Para imprimir, use o botão **Imprimir** na aba **Visualizar DANFE**.

---

## ⚠️ Aviso Importante

Este sistema é **estritamente didático**:
- Os dados e cálculos são **fictícios**.
- Não deve ser usado para fins fiscais reais.

---

## 📜 Licença

Distribuído sob a licença MIT.  
Você pode usar, modificar e distribuir, **mantendo o crédito ao autor**.

---
