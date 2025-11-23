<h1 align="center">Junipy </h1>
   <!-- 
   <p align="center">
   <image alt="header-main" src=""/>
   </p>   
   -->
<hr>

  <p align="center">
     <a href ="#objetivo">Objetivo</a>  |
     <a href ="#visão-do-produto">Visão do produto</a>  |
     <a href ="#cronograma">Cronograma</a>  |
     <a href ="#backlog--produto">Backlog Produto</a>  |
     <a href ="#documentacao">Documentação</a>  |
     <a href ="#requisitos">Requisitos</a>  |
     <a href ="#tecnologias">Tecnologias</a>  |
     <a href ="#como-usar">Como usar</a>   |
     <a href ="#equipe">Equipe</a>
   </p>


<span id="objetivo">
   
## :dart: Objetivo 
<blockquote>
O objetivo do projeto é desenvolver uma aplicação web que ofereça um agente conversacional inteligente, baseado no modelo LLM medGemma, com foco em suporte personalizado na área de nutrição. A aplicação deverá interagir de forma natural com os usuários, coletando informações sobre saúde, hábitos alimentares, restrições e objetivos nutricionais, a fim de gerar recomendações adequadas e contextualizadas. O desenvolvimento será conduzido com práticas ágeis, garantindo entregas iterativas, melhorias contínuas e alinhamento às necessidades do público-alvo.
</blockquote>

<span id="visão-do-produto">
   
## :eye_speech_bubble: Visão do Produto   
<blockquote>   
A visão do projeto é ser uma aplicação web inovadora em nutrição digital, oferecendo um agente conversacional inteligente que funcione como um assistente nutricional acessível e personalizado. A plataforma busca simplificar o acompanhamento alimentar, fornecer recomendações confiáveis e promover hábitos saudáveis, auxiliando tanto indivíduos quanto profissionais da área. A proposta é unir tecnologia e bem-estar em um ambiente responsivo e intuitivo, ampliando o acesso a orientações nutricionais de qualidade e incentivando maior engajamento no cuidado com a saúde.
</blockquote>

<span id="cronograma">  
   
## :spiral_calendar: Cronograma  
| FASE | INÍCIO | FIM |
| --- | --- | --- |
| Kick-off | 25/08/2025 | 29/08/2025 |
| Sprint 1 | 08/09/2025 | 28/09/2025 |
| Planning | 29/09/2025 | 03/10/2025 |
| Sprint 2 | 06/10/2025 | 26/10/2025 |
| Planning | 27/10/2025 | 31/10/2025 |
| Sprint 3 | 03/11/2025 | 23/11/2025 |
| Review   | 24/11/2025 | 28/11/2025 |

<span id="backlog--produto">
   
## :pushpin: Product Backlog

<details>
 <summary>Product Backlog</summary>
   
| ID     | Prioridade | Descrição                                                                                                                                                                                                                                                                       | Pontos | Sprint   |
|--------|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|----------|
| US-01  | Alta       | Como paciente, quero receber recomendações de dieta geradas pela IA com base no meu perfil, para que eu tenha planos personalizados que se encaixem na minha rotina e estilo de vida.                                                                                              | 9      | Sprint 1 |
| US-02  | Alta       | Como administrador, quero visualizar a lista completa de pacientes cadastrados na plataforma, incluindo nome, e-mail e data de registro, para que eu possa gerenciar contas, promovê-las a administradores ou nutricionistas e excluir contas quando necessário.                     | 2      | Sprint 1 |
| US-03  | Baixa      | Como paciente, quero visualizar a composição nutricional detalhada de cada refeição sugerida, para que eu possa tomar decisões informadas sobre o que consumir.                                                                                                                    | 6      | Sprint 1 |
| US-04  | Alta       | Como paciente, quero selecionar entre diferentes agentes de IA especializados em Análise Nutricional e Recomendação de Dieta, onde cada agente utiliza diferentes bases de dados nutricionais, para receber respostas direcionadas e adequadas ao meu contexto. | 8      | Sprint 2 |
| US-05  | Alta       | Como paciente, quero que a IA mantenha o contexto das minhas conversas anteriores, para que eu não precise repetir informações sempre que interajo com o chat.                                                                                                                     | 8      | Sprint 2 |
| US-06  | Média      | Como paciente, quero visualizar, editar ou solicitar novas versões das minhas dietas semanais, para que eu tenha controle total sobre meu plano alimentar e possa ajustá-lo caso não esteja satisfeito ou prefira outras opções.                                                    | 5      | Sprint 2 |
| US-07  | Média      | Como paciente, quero poder enviar as dietas geradas pela IA para um nutricionista, para garantir que meu plano alimentar seja seguro, adequado às minhas necessidades.                                                                                                              | 5      | Sprint 2 |
| US-08  | Baixa      | Como paciente, quero que a IA acompanhe minha evolução e ajuste automaticamente meus objetivos nutricionais, para que eu continue motivado e receba recomendações cada vez mais personalizadas e adequadas à minha rotina.                                                           | 8      | Sprint 2 |
| US-09  | Alta       | Como nutricionista, quero fornecer feedback sobre as respostas geradas pela IA, para garantir que as recomendações fornecidas aos pacientes sejam confiáveis, precisas e seguras.                                                                                                   | 8      | Sprint 3 |
| US-10  | Alta       | Como paciente, quero ter controle total sobre minhas informações pessoais, físicas, de saúde e preferências alimentares, para que eu decida o que a IA poderá usar na geração de recomendações.                                                                                     | 3      | Sprint 3 |
| US-11  | Baixa      | Como nutricionista, quero ter acesso às tabelas e referências nutricionais utilizadas pela IA e poder alterá-las quando necessário, para garantir que as informações fornecidas aos pacientes sejam corretas, confiáveis e atualizadas.                                              | 4      | Sprint 3 |
| US-12  | Média      | Como paciente, quero que a IA identifique automaticamente o agente mais adequado para responder minha dúvida, para que eu receba respostas precisas e relevantes mesmo sem saber de qual área da nutrição minha pergunta pertence.                                                   | 7      | Sprint 3 |
| US-13  | Média      | Como paciente, quero que a IA sugira alterações nos meus dados com base nas informações que compartilho (como mudanças de peso, atividade física ou hábitos), para que meus registros fiquem sempre atualizados.                                                                    | 4      | Sprint 3 |
| US-14  | Baixa      | Como paciente, quero que todas as respostas geradas pela IA sejam revisadas por um agente de Conformidade e Ética, para garantir que as recomendações estejam em conformidade com princípios éticos e preservem a integridade das minhas informações, além de assegurar a segurança e adequação das dietas sugeridas.                                                                    | 4      | Sprint 3 |


</details>

<span id="documentacao">
   
## 📚 Documentação do Projeto

<!--
<details>
 <summary>Documentação do Projeto</summary>
 -->
   
Este repositório contém a documentação organizada por sprints.  
Abaixo você encontra os links para cada documentação detalhada:

| Sprint | Período       | Documentação |
|--------|---------------|--------------|
| Sprint 1 | 08/09 - 28/09 | [Acessar Documentação](documentation/sprint1/sprint1doc.md) |
| Sprint 2 | 06/10 - 26/10 | [Acessar Documentação](documentation/sprint2/sprint2doc.md) |
| Sprint 3 | 03/10 - 23/10 | [Acessar Documentação](documentation/sprint3/sprint3doc.md) |

<!--
## 🎥 Video Apresentação

<details>
 <summary>Sprints</summary>
## Sprint 1   
https://github.com/user-attachments/assets/
## Sprint 2
https://github.com/user-attachments/assets/
## Sprint 3
https://github.com/user-attachments/assets/
## Sprint 4
https://github.com/user-attachments/assets/
</details>
-->

   
<span id="requisitos">
   
## 🔎 Requisitos
  <ul>
   <li>Manual de Instalação (requisito Fatec – obrigatório, no Git).</li>
   <li>Manual do Usuário (requisito Fatec – obrigatório).</li>
   <li>Modelos LLM de uso público via API (Hugging Face, Gemini, Grok, Llama, OpenAI) (requisito Fatec).</li>
   <li>Framework LangChain (Python) (requisito Fatec).</li>
   <li>Vue.JS para Frontend (requisito Fatec).</li>
   <li>SpringBoot para Backend (requisito Fatec).</li>
   <li>ADK Google (requisito sugerido Xertica).</li>
</ul>
   
<span id="tecnologias">
   
## 🖥️Tecnologias:
   <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,fastapi,mysql,java,spring,mongodb,maven,docker,vue,vite,typescript,axios&perline=4">
   </a>
   
<span id="ferramentas">

## 🛠️ Ferramentas:
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,github,git&perline=4">
  </a>
   
<span id="como-usar">

## Como utilizar

Este projeto é composto por três serviços independentes, mas integrados: **AIService_Junipy**, **Backend_Junipy** e **Frontend_Junipy**. Siga os passos abaixo para configurar e executar todos os componentes corretamente.

<details>
 <summary>Como utilizar</summary>

## ⚙️ 0. Configurações e Pré-requisitos Gerais

Certifique-se de ter instalado:

* **Python 3.8+** e **pip**
* **Java/JDK** e **Maven (mvn)**
* **Node.js** e **npm**
* **Docker** (necessário para o banco de dados MongoDB)

---

## 📌 1. Configuração e Execução do Banco de Dados (MongoDB)

O Backend requer uma instância do MongoDB. Use o Docker para iniciar um contêiner rapidamente.

1.  **Crie e Inicie o Contêiner MongoDB:**
    ```bash
    docker run -d -p 27017:27017 --name junipymongo mongo:7
    ```

---

## 🧠 2. AIService — FastAPI (Python)

Este é o serviço de Inteligência Artificial.

### **Passos de Configuração**

1.  **Crie e Ative um Ambiente Virtual:**
    * **Linux/macOS:**
        ```bash
        python -m venv venv
        source venv/bin/activate
        ```
    * **Windows:**
        ```bash
        python -m venv venv
        venv\Scripts\activate
        ```

2.  **Instale as Dependências:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Configure o Modelo:**
    * Crie uma cópia do arquivo `.env.example` e renomeie-a para **`.env`** no diretório do projeto.
    * Preencha o arquivo `.env` com as chaves e configurações necessárias para a API de IA.

### **Execução**

* **Rode o Servidor FastAPI:**
    ```bash
    uvicorn main:app --reload
    ```
* **Acesso:** O serviço estará disponível em `http://localhost:8000`. A documentação **Swagger** pode ser acessada em `http://localhost:8000/docs`.

---

## ☕ 3. Backend — NutritionAgent (Spring Boot)

Este é o servidor de aplicação principal que se conecta ao Frontend, ao AIService e ao MongoDB.

### **Configuração**

1.  **Configure a Conexão com o AIService:**
    * No arquivo de configurações (geralmente `application.properties` ou `application.yml`, ou variáveis de ambiente), verifique e ajuste a URL base do AIService para `http://localhost:8000`.

### **Execução**

* **Rode o Projeto (com Maven):**
    ```bash
    mvn spring-boot:run
    ```
* **Acesso:** O Backend estará disponível em `http://localhost:8080`.

---

## 💻 4. Frontend — Junipy (Vue 3 + Vite)

Esta é a interface do usuário.

### **Passos de Configuração**

1.  **Instale as Dependências:**
    ```bash
    npm install
    ```
    > **Recomendação:** Use o **VSCode** com a extensão **Volar** para melhor experiência de desenvolvimento Vue.

### **Execução**

1.  **Rode em Modo Desenvolvimento:**
    ```bash
    npm run dev
    ```
* **Acesso:** A aplicação estará disponível em `http://localhost:5173`.

### **Build para Produção (Opcional)**

1.  **Gere os Arquivos Estáticos de Produção:**
    ```bash
    npm run build
    ```

---

## ✅ Resumo da Ordem de Inicialização

1.  **MongoDB** (Docker)
2.  **AIService** (Python)
3.  **Backend** (Java/Spring Boot)
4.  **Frontend** (Node/Vue)

   </details>

<span id="equipe">
   
## 👥 Equipe:

   ### ![Static Badge](https://img.shields.io/badge/Product_Owner-219ebc) - Arthur Silva: 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://br.linkedin.com/in/arthur-sousa-3287391b1)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/Meowo2)

   ### ![Static Badge](https://img.shields.io/badge/Scrum_Master-red) - Jaqueline Silva : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](
   https://www.linkedin.com/in/jaqueline-maria-fran%C3%A7a-veloso-silva/)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/jaquemfvs)


   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - João Eduardo Messias : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/jo%C3%A3o-eduardo-messias-a3019125b/)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/joao-eduardo17)


   ###  ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Markos Nunes : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://linkedin.com/in/markos-vinícius-nunes-230448268)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/MarkVN2)
   [<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/markos_vn2)


   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Sandro Pimentel : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/sandro-roberto-pimentel-junior-1287a3254/)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/Sandro-Pimentel)
   

   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Vinícius Forcato : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/vinícius-felipe-forcato-789462268)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/nininhosam)
   [<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/nao_sou_felps)

  
   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Vitor Saborito : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://br.linkedin.com/in/vitor-henrique-saborito-216219268)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/VituuSaborito )


   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Isabel Vitoria : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/isabel-reis-09806920b/)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/IsabelRReis)


   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Gabriel Luis : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/gabriel-luis-de-angelis/)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/GabrAngelis)
