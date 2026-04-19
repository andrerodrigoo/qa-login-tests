# Casos de Teste - Login

## TC001 - Login válido

Pré-condição:
Usuário já cadastrado

Passos:
1. Acessar tela de login
2. Inserir usuário "student"
3. Inserir senha "Password123"
4. Clicar em login

Resultado esperado:
Usuário deve acessar o sistema com sucesso

Resultado atual:
Login realizado com sucesso

Status:
PASSOU

---

## TC002 - Senha incorreta

Passos:
1. Inserir usuário válido
2. Inserir senha incorreta
3. Clicar em login

Resultado esperado:
Sistema deve exibir mensagem de erro

Resultado atual:
...

Status:
PASSOU

---

## TC003 - Usuário inválido

Passos:
1. Inserir usuário inválido
2. Inserir senha válida
3. Clicar em login

Resultado esperado:
Sistema deve bloquear acesso

Resultado atual:
Mensagem exibida: "Seu nome de usuário é inválido"

Status:
PASSOU

---

## TC004 - Campos vazios

Passos:
1. Não preencher os campos
2. Clicar em login

Resultado esperado:
Sistema deve exigir preenchimento

Resultado atual:
...

Status:
PASSOU

---

## TC005 - Senha muito longa

Passos:
1. Inserir senha com muitos caracteres
2. Tentar login

Resultado esperado:
Sistema deve bloquear login

Resultado atual:
...

Status:
PASSOU
