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

---

## TC002 - Senha incorreta

Passos:
1. Inserir usuário válido
2. Inserir senha incorreta
3. Clicar em login

Resultado esperado:
Sistema deve exibir mensagem de erro

---

## TC003 - Usuário inválido

Passos:
1. Inserir usuário inválido
2. Inserir senha válida
3. Clicar em login

Resultado esperado:
Sistema deve bloquear acesso

---

## TC004 - Campos vazios

Passos:
1. Não preencher os campos
2. Clicar em login

Resultado esperado:
Sistema deve exigir preenchimento

---

## TC005 - Senha muito longa

Passos:
1. Inserir senha com muitos caracteres
2. Tentar login

Resultado esperado:
Sistema deve bloquear login
