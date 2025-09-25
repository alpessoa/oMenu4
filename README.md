# oMenu4 — Cardápio Digital Interativo com Acessibilidade 🎯

## Sobre o Projeto

O **oMenu4** é um cardápio digital inclusivo, desenvolvido para restaurantes, com foco em **acessibilidade** para pessoas com deficiência visual severa e baixa visão, sem deixar de lado a usabilidade para qualquer cliente.  
A ideia central é tornar a experiência de atendimento **mais acessível, prática e moderna**, usando tecnologia para reduzir barreiras no dia a dia.

O sistema contempla:
- Gerenciamento de fila de espera  
- Indicação de mesa livre  
- Realização de pedidos  
- Fechamento da conta e pagamento  
- Cadastro e gerenciamento de produtos, mesas e usuários  
- Relatórios de itens mais vendidos por categoria  

---

## Tecnologias Utilizadas

- **Backend:** Django / Django REST Framework  
- **Banco de Dados:** PostgreSQL  
- **Frontend:** React  
- **Serviços de Voz / Acessibilidade:** Amazon Polly (Text-to-Speech)  

---

## Minha Participação no Projeto

Durante o desenvolvimento do **oMenu4**, minhas principais contribuições foram:

- **Gerenciamento do projeto**: atuei organizando o fluxo de trabalho, distribuindo tarefas e acompanhando os prazos.  
- **Integração da equipe**: fui responsável por alinhar o trabalho entre backend, frontend e design, garantindo coesão no desenvolvimento.  
- **Validação com usuários finais**: realizei **entrevistas presenciais com pessoas cegas**, a fim de compreender suas necessidades e validar as soluções propostas.  
- **Apresentação do projeto**: conduzi a apresentação final para os colegas de curso, comunicando de forma clara os objetivos, diferenciais e funcionalidades do sistema.  

Essa participação me permitiu desenvolver competências em **gestão ágil de projetos, liderança de equipe e contato com usuários para levantamento de requisitos**, além de reforçar a importância da **acessibilidade** no desenvolvimento de soluções digitais.  

---

## Como Executar Localmente

### ⛑ Pré-requisitos

- Python 3.11+  
- Node.js 18+  
- PostgreSQL  
- Docker (opcional)  

### 🚀 Passo a Passo

1. Clonar o repositório  
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git
   cd seu-repo
   ```

2. Backend  
   ```bash
   cd backend
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```

3. Frontend  
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. Acesse o app via navegador  
   ```
   http://localhost:3000
   ```

---

## Roadmap / Próximas Funcionalidades

- Cadastro de clientes  
- Integração com carteiras digitais (Pix, Apple Pay, etc.)  
- Recomendações personalizadas via IA  
- Estatísticas avançadas de consumo  

---

## Licença

Projeto desenvolvido como parte da disciplina **Projetos 4** do curso de **Gestão em Tecnologia da Informação** do **CESAR School**.  
Mantido em colaboração pelos integrantes do Grupo 02.  
