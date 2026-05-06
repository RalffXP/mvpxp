# mvp
# 🚀 Documento de Definição de MVP (Produto Mínimo Viável)

Este documento serve como guia para o planeamento e execução do projeto de Desenvolvimento de Sistemas. O foco aqui é a **entrega de valor real** com o menor esforço possível, garantindo um software funcional e testável.

---

## 1. Visão Geral do Projeto
* **Nome do Sistema:** [Insira o nome do projeto]
* **Equipa:** [Nomes dos Alunos e respetivos papéis]
* **O Problema (A Dor):** Descreva de forma clara o problema que o sistema resolve. Por que é que este software precisa de existir?
* **Público-Alvo:** Quem são os utilizadores finais? (Ex: Estudantes do IFSP, donos de pequenos negócios, utilizadores de ginásios).

## 2. Proposta de Valor
* **Solução Central:** Em apenas uma frase, o que o sistema faz?
* **Diferencial do MVP:** Qual é a funcionalidade mínima que permite que o utilizador já consiga usar o sistema para resolver o problema?

## 3. Âmbito do MVP (Priorização)
Utilize a técnica **MoSCoW** para definir o que será entregue nesta primeira versão.

| Categoria | Funcionalidades (O que o sistema faz) | Justificação |
| :--- | :--- | :--- |
| **Essencial (Must-have)** | • Ex: Cadastro de usuários e login.<br>• Ex: CRUD de tarefas. | Sem isto o projeto não pode ser apresentado. |
| **Importante (Should-have)** | • Ex: Recuperação de password.<br>• Ex: Filtro de pesquisa. | Importante, mas o sistema funciona sem isto. |
| **Desejável (Could-have)** | • Ex: Modo Noturno.<br>• Ex: Exportação para PDF. | "Perfumaria" para ser feita se sobrar tempo. |
| **Fora do Âmbito (Won't-have)** | • Ex: Integração com IA ou Pagamentos. | Demasiado complexo para o prazo atual. |

## 4. Stack Tecnológica
Definição das ferramentas que serão utilizadas pela equipa:

* **Front-end / Mobile:** [Ex: Ionic com React, Kotlin Nativo, ou HTML/CSS]
* **Back-end (API):** [Ex: Node.js, PHP, Java Spring Boot]
* **Base de Dados:** * *Relacional:* [Ex: MySQL / PostgreSQL]
    * *Não-Relacional:* [Ex: MongoDB] (se aplicável)
* **Controlo de Versão:** GitHub (Utilização de branches `main` e `develop`).

## 5. Modelação da Base de Dados
*(Dica: Podem anexar aqui o link para o diagrama do BRModelo ou um print do Modelo Relacional)*

* **Entidades Principais:** [Ex: Usuario, Produto, Pedido]
* **Relacionamentos:** [Ex: Um Usuário pode ter muitos Pedidos (1:N)]

## 6. Fluxo Principal (Caminho Feliz)
Descreva o passo a passo que será testado na demonstração:
1. O utilizador abre o sistema e faz login.
2. O utilizador acede ao menu "X" e clica em "Adicionar".
3. O utilizador preenche os campos e guarda.
4. O sistema confirma a gravação e lista o item no Dashboard.

## 7. Critérios de Aceitação
O MVP será considerado concluído se:
- [ ] O sistema corre sem erros críticos de execução (crashing).
- [ ] É possível realizar o fluxo principal completo (CRUD).
- [ ] Os dados estão a ser persistidos corretamente na base de dados.
- [ ] O repositório no GitHub está organizado e atualizado.

---
*Modelo criado para as aulas de Desenvolvimento de Sistemas - ETEC Prof. Milton Gazzetti.*
