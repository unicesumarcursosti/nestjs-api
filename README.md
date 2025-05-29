
# 📘 Atividade Prática: Cadastro e Gerenciamento de Reviews Literárias

## 🎯 Objetivo

Desenvolver uma aplicação NestJS com TypeORM para realizar o CRUD da entidade `BookReview`, treinando habilidades de modelagem, persistência e exposição de endpoints RESTful.

O repositório de referência utilizado em sala de aula se encontra em: [https://github.com/rafael-labegalini/nestjs-api.git](https://github.com/rafael-labegalini/nestjs-api.git)

Ele possui todas as configurações necessárias e implementações para conseguir resolver o exercício.

---

## ✅ Requisitos

### 📌 Backend (Spring Boot + JPA)

1. Configurar o acesso ao banco de dados pelo NestJS:
    - adicionar as configurações necessárias no `app.module`

2. Criar a entidade `BookReview` com os seguintes campos:
   - `bookTitle`: String
   - `reviewerName`: String
   - `reviewText`: String
   - `rating`: Integer
   - `recommended`: Boolean

3. Criar o repositório `BookReviewRepository`

4. Implementar as operações de **CRUD completo**:
   - Criar uma nova review
   - Listar todas as reviews
   - Buscar uma review por ID
   - Atualizar uma review existente
   - Deletar uma review

3. Todos os dados devem ser retornados em formato JSON.

---

## 📂 Entrega

- O código deve ser entregue pelo GitHub Education.

---

Boa prática e mãos à obra! 🚀