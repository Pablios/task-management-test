### 📌 **Teste Prático: Sistema de Tarefas (Task Manager)**  

**🎯 Objetivo:**  
Criar uma aplicação full stack de gerenciamento de tarefas, onde o usuário pode adicionar, editar, marcar como concluída e excluir tarefas.  

**🚀 Tecnologias Obrigatórias:**  
- **Frontend:** Angular (última versão estável)  
- **Backend:** PHP (Yii2 Framework)  
- **Banco de Dados:** MySQL  
- **Extras:** Diferenciais incluem uso de Docker, autenticação JWT e deploy da aplicação  

---

## 🏗 **Descrição do Projeto**  
A aplicação deve permitir:  
✅ Criar novas tarefas  
✅ Editar e excluir tarefas  
✅ Listar todas as tarefas  
✅ Filtrar por tarefas pendentes e concluídas  
✅ Marcar tarefas como concluídas  

---

## 📡 **Backend (API RESTful em Yii2)**  
Criar uma API RESTful com os seguintes endpoints:  

### 🛠 **Endpoints:**  

1️⃣ **Listar todas as tarefas**  
`GET /api/tasks`  

2️⃣ **Obter uma tarefa por ID**  
`GET /api/tasks/{id}`  

3️⃣ **Criar uma nova tarefa**  
`POST /api/tasks`  
- **Body:** `{ "title": "title task", "description": "descriptions...", "status": "pending" }`  

4️⃣ **Atualizar uma tarefa**  
`PUT /api/tasks/{id}`  

5️⃣ **Marcar como concluída**  
`PATCH /api/tasks/{id}/complete`  

6️⃣ **Excluir uma tarefa**  
`DELETE /api/tasks/{id}`  

### 🗄 **Banco de Dados (MySQL)**  
Tabela `tasks` com os campos:  
- `id` (int, primary key, auto_increment)  
- `title` (varchar)  
- `description` (text)  
- `status` (enum: `pending`, `completed`)  
- `created_at` (timestamp)  

---

## 🎨 **Frontend (Angular)**  
O frontend consumirá a API e terá as seguintes páginas:  

1️⃣ **Página inicial** → Lista todas as tarefas com título e status  
2️⃣ **Modal de detalhes** → Exibe descrição e status da tarefa  
3️⃣ **Modal de criação/edição** → Formulário para adicionar ou editar tarefas  
4️⃣ **Modal de exclusão** → Confirmação antes de excluir uma tarefa  
5️⃣ **Filtro de status** → Permite visualizar apenas tarefas concluídas ou pendentes  

---

## 🔥 **Extras (Diferencial)**  
✅ **Docker** para rodar MySQL e backend Yii2  
✅ **Autenticação JWT** para proteger criação/edição/exclusão de tarefas  
✅ **Implementação de um calendário** para exibir as tarefas do mês  
✅ **Deploy do backend (ex: Render, Heroku, DigitalOcean)**  
✅ **Deploy do frontend (ex: Firebase Hosting, Vercel, Netlify)**  

### **🚀 Como entregar?**
1️⃣ Desenvolva a solução e envie o código para um repositório público no **GitHub**.  
2️⃣ Inclua um **README** com instruções para rodar o projeto.  
3️⃣ Envie o link do repositório para avaliação.  

---

### **Layout de Exemplo para Desenvolvimento**  
Este layout serve como uma referência inicial para o desenvolvimento. Ele não inclui todos os requisitos necessários, mas pode ser útil para começar a estrutura do projeto. Algumas informações extras estão presentes, mas o foco principal é fornecer um ponto de partida.

### **Acesso ao Layout**  

Você pode visualizar o layout de exemplo através do link abaixo:

[Layout de Exemplo no Figma]([https://www.figma.com/community/file/1363381610478131725](https://www.figma.com/design/H2QeQ5dpYXIo1AWtoajsEk/Simple-Project%2FTask-Management-Dashboard-(Community)?node-id=20176-21207&t=DOWgbP2n4avwjSlZ-1))

## Instruções

1️⃣ Acesse o layout no Figma.  
2️⃣ Use-o como guia para começar a implementação da interface.  
3️⃣ Lembre-se de que o layout contém elementos extras e pode não estar 100% alinhado com as necessidades finais do projeto. Certifique-se de adaptar conforme necessário.  

---
