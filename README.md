# Programa Desenvolve | Grupo Boticário e Escola Koru

## Descrição 
Este repositório contém estudos e exercícios realizados através da primeira fase do Programa Desenvolve | Grupo Boticário e Escola Koru, mais especificamente instruções da trilha de Fundamentos de Dados, pelo professor Anderson Gonçalves.

O projeto descrito seria de uma planilha de Gestão de Gastos, onde os registros seriam feitos e posteriormente, transformados em gráficos para melhor visualização.

## Descrição do Projeto Adaptado

O projeto **Gestão de Gastos** é uma aplicação desenvolvida para o Google Sheets que auxilia no controle financeiro pessoal, permitindo registrar, atualizar e acompanhar transações financeiras. A interface HTML integrada possibilita um registro ágil e intuitivo das despesas, receitas e custos fixos.

---

## Funcionalidades
* **Registro de transações:**
  * Inserção de descrição, data, valor, tipo (receita, despesa ou custo fixo), categoria, banco, modo de pagamento e status (pago ou não).
  * Suporte para transações parceladas e custo fixo: Se for em Modo Crédito, o valor inteiro será parcelado. Se for um Custo Fixo, o número de parcelas indicará o número de repetições.

* **Atualização de status:**
  * Permite marcar o pagamento de uma transação diretamente na interface.
    
* **Cadastro de categorias:**
  * Inclusão dinâmica de novas categorias diretamente no formulário.
  
* **Interface intuitiva:**
  * Utilização de HTML com um layout simples e responsivo.

---

## Tecnologias Utilizadas

* **Google Apps Script:** Backend para manipulação das planilhas e controle de dados.
* **HTML:** Interface de usuário para registro e atualização.
* **JavaScript:** Interação e processamento de dados no formulário.

---

## Estrutura do Projeto

* **Code.gs:** Script principal para criar menus, registrar transações e atualizar status.
* **formulario.html:** Interface para cadastro de transações.
* **Planilha Google Sheets:** Armazenamento das transações e categorias.

### Colunas da Planilha 'Controle'

| Coluna    | Descrição                      |
| --------- | ------------------------------ |
| Registro  | Número único da transação      |
| Data      | Data da transação              |
| Descrição | Descrição da transação         |
| Valor     | Valor da transação             |
| Tipo      | Receita, Despesa ou Custo Fixo |
| Categoria | Categoria da transação         |
| Banco     | Origem ou destino financeiro   |
| Modo      | Forma de pagamento             |
| Pago      | Status de pagamento (Checkbox) |

---

## Como Usar

1. Abra o Google Sheets.
2. Acesse o menu **💰 Controle de Gastos** e clique em **Registrar Transação**.
3. Preencha os campos obrigatórios e clique em **Registrar**.
4. Para atualizar o status de pagamento, insira o ID do registro e o novo status.

---
