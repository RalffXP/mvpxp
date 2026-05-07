# mvp
# 🚀 Documento de Definição de MVP (Produto Mínimo Viável)

Este documento serve como guia para o planeamento e execução do projeto de Desenvolvimento de Sistemas. O foco aqui é a **entrega de valor real** com o menor esforço possível, garantindo um software funcional e testável.

---

## 1. Visão Geral do Projeto
* **Nome do Sistema:** [Salva Pet]
* **Equipa:** [Ralff,Yasmim Colares,Ana Andrade,Larissa e Lavinia]
* **O Problema (A Dor):** O abandono de animais é alto, enquanto muitos interessados em adotar não encontram fontes confiáveis.
O processo atual de adoção e doação é desorganizado e pouco transparente.
ONGs e protetores têm dificuldade para divulgar pets e encontrar bons adotantes.
Assim, é necessário um sistema que conecte pessoas de forma segura e facilite adoções responsáveis.
* **Público-Alvo:** Pessoas de todas as idades).

## 2. Proposta de Valor
* **Solução Central:** Plataforma online que conecta pessoas interessadas em adotar ou doar pets a abrigos e protetores de forma simples, segura e organizada.
* **Diferencial do MVP:** Um sistema básico onde usuários podem cadastrar pets para adoção e buscar animais disponíveis com informações essenciais e contato direto com o responsável.

## 3. Âmbito do MVP (Priorização)
Utilize a técnica **MoSCoW** para definir o que será entregue nesta primeira versão.

| Categoria | Funcionalidades (O que o sistema faz) | Justificação |
| :--- | :--- | :--- |
| **Essencial (Must-have)** | • Ex: • Cadastro de usuários e login <br> • Cadastro de pets para adoção/doação <br> • Visualização de pets disponíveis <br> • Contato entre adotante e responsável | Sem essas funcionalidades, o sistema não cumpre seu objetivo principal. |
| **Importante (Should-have)** |• Filtro de busca (espécie, idade, localização) <br> • Recuperação de senha <br> • Perfil do usuário| Melhora a experiência do usuário, mas não impede o funcionamento do sistema. |
| **Desejável (Could-have)** |• Avaliação de usuários <br>• Upload de várias fotos <br>• Notificações por email | Funcionalidades extras que agregam valor, mas não são essenciais. |
| **Fora do Âmbito (Won't-have)** | • Integração com pagamentos<br>• Inteligência artificial <br>• Aplicativo mobile | Muito complexas para o MVP e podem ser implementadas futuramente. |

## 4. Stack Tecnológica
Definição das ferramentas que serão utilizadas pela equipa:

* **Front-end / Mobile:** [React Native com Expo (aplicativo mobile multiplataforma) e HTML/CSS para painel web administrativo.]
* **Back-end (API):** [Node.js.]
* **Base de Dados:** *~Relacional: PostgreSQL <br>
Não-Relacional: MongoDB (para armazenamento de imagens, logs ou chats, se necessário).
* **Controlo de Versão:** GitHub (Utilização de branches `main` e `develop`).

## 5. Modelação da Base de Dados
*(Dica: Podem anexar aqui o link para o diagrama do BRModelo ou um print do Modelo Relacional)*

* **Entidades Principais:** [Usuário <br> Animal <br> Adoção <br> ONG/Instituição <br> Localização <br> Denúncia <br> Vacinação <br> Histórico Médico ]
* **Relacionamentos:** [ Usuário cadastra Animal. <br> ONG administra Animal. <br> Usuário realiza Adoção. <br> Animal possui Vacinação.]

## 6. Fluxo Principal (Caminho Feliz)
• O utilizador acede ao site Salva Pet e faz login ou cadastro. <br> • O utilizador entra no dashboard principal. <br>• O utilizador navega até à lista de animais disponíveis. <br> • O utilizador seleciona um animal para ver detalhes. <br> • O utilizador pode solicitar adoção ou cadastrar um novo animal. <br> • O sistema confirma a ação e atualiza a lista no site.

## 7. Critérios de Aceitação
O MVP será considerado concluído se:
- [ ] O sistema corre sem erros críticos de execução (crashing).
- [ ] É possível realizar o fluxo principal completo (CRUD).
- [ ] Os dados estão a ser persistidos corretamente na base de dados.
- [ ] O repositório no GitHub está organizado e atualizado.

---
*Modelo criado para as aulas de Desenvolvimento de Sistemas - ETEC Prof. Milton Gazzetti.*
