# Projeto Chatbot 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/joaogabriel-barcelos/rasa/HEAD)


## Objetivo do Projeto
Este projeto foi desenvolvido como parte de uma atividade prática para a criação de um assistente virtual (Chatbot) do Apple Academy. O objetivo é auxiliar alunos de uma plataforma de ensino, respondendo automaticamente a dúvidas frequentes (FAQ) sobre cursos, certificados, gratuidade e acessos.

O bot foi construído utilizando a biblioteca **Rasa** (framework open-source de PNL) e conta com tratamento de fluxo conversacional, saudações, desvios de assunto (small talk) e mecanismos de fallback.

---

## Tecnologias Utilizadas
* **Python 3.10**
* **Rasa Framework**
* **MyBinder** (Ambiente de execução na nuvem)

---

## Como Executar e Testar no Binder

Não é necessário instalar nada no seu computador! Siga os passos abaixo para testar diretamente pelo navegador:

1. Clique no botão **`launch binder`** no início deste documento.
2. Aguarde até que o ambiente do JupyterLab seja construído e aberto na tela.
3. No menu superior ou na tela inicial do JupyterLab, abra um **Terminal**.
4. *(Opcional)* Se o repositório não mantiver o arquivo de modelo gerado, treine a IA digitando: **rasa train**
 

Para iniciar a conversa com o chatbot, digite no terminal: **rasa shell**

Aguarde a mensagem Bot loaded e comece a conversar com o assistente!
