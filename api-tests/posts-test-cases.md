# Casos de Teste - API (Posts)

## TC001 - Buscar todos os posts

Endpoint:
GET /posts

Passos:
1. Enviar requisição GET para /posts

Resultado esperado:
Retornar lista de posts

Resultado atual:
Lista retornada com sucesso (status 200)

Status:
PASSOU

---

## TC002 - Buscar post específico

Endpoint:
GET /posts/1

Passos:
1. Enviar requisição GET para /posts/1

Resultado esperado:
Retornar dados de um post

Resultado atual:
Dados retornados corretamente (status 200)

Status:
PASSOU

---

## TC003 - Buscar post inexistente

Endpoint:
GET /posts/999999

Passos:
1. Enviar requisição para endpoint inválido

Resultado esperado:
Retornar vazio ou erro

Resultado atual:
Resposta vazia

Status:
PASSOU

---

## TC004 - Criar post com dados válidos

Endpoint:
POST /posts

Passos:
1. Enviar requisição POST com dados válidos

Body:
{
  "title": "Teste QA",
  "body": "Criando post via API",
  "userId": 1
}

Resultado esperado:
Criar post com sucesso (status 201)

Resultado atual:
Post criado com sucesso (status 201)

Status:
PASSOU
