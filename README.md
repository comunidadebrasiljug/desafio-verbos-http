# 📌 Desafio Java — Verbos HTTP e Códigos de Status  
> Pratique conceitos fundamentais de APIs REST utilizando Java, HTTP Verbs e Status Codes

## 📖 Sobre o Desafio  
Este desafio tem como objetivo reforçar seu entendimento sobre **verbo HTTP**, **boas práticas REST**, e **códigos de status HTTP**, implementando uma pequena API em Java (Spring Boot ou Java puro, conforme preferência).

O foco principal é aprender **quando e como usar cada verbo HTTP de forma correta**, além de retornar **status codes adequados** em cada operação.

---

## 🎯 Objetivos de Aprendizagem
- Compreender a função dos principais **verbos HTTP**: `GET`, `POST`, `PUT`, `PATCH`, `DELETE`
- Retornar corretamente **status codes**: `200`, `201`, `204`, `400`, `404`, `409`, `500`, etc.
- Criar endpoints REST bem definidos
- Implementar uma API limpa e organizada
- Garantir respostas coerentes com a RFC 9110 (HTTP Semantics)

---

## 🧠 O Desafio

Você deverá implementar uma API simples para gerenciar um recurso (ex.: **Usuários**, **Produtos**, **Tarefas**, **Clientes**, etc.).

### ✔️ Requisito 1 — Verbo GET  
**Listar todos os itens**  
- Status esperado: `200 OK`

**Buscar item por ID**  
- Se existir → `200 OK`  
- Se não existir → `404 Not Found`

---

### ✔️ Requisito 2 — Verbo POST  
**Criar um novo item**  
- Se criado com sucesso → `201 Created`  
- Se dados inválidos → `400 Bad Request`  
- Se houver conflito (ex.: e-mail já existente) → `409 Conflict`

---

### ✔️ Requisito 3 — Verbo PUT  
**Atualizar TODOS os dados de um item existente**  
- Sucesso → `200 OK`  
- Se o item não existir → `404 Not Found`  

---

### ✔️ Requisito 4 — Verbo PATCH  
**Atualização parcial de dados**  
- Sucesso → `200 OK`  
- Se não existir → `404 Not Found`  
- Se requisição estiver mal formatada → `400 Bad Request`

---

### ✔️ Requisito 5 — Verbo DELETE  
**Remover item**  
- Sucesso → `204 No Content`  
- Se não existir → `404 Not Found`  

---

## 📝 Entregáveis  
- API implementada com os verbos HTTP acima  
- Respostas com **status code correto**  
- Mensagens de erro estruturadas em JSON  
- README atualizado explicando suas decisões  
