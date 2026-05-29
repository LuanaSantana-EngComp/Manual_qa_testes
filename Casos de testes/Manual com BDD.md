# 🧪 Criação de Casos de Teste com BDD

**O que é BDD?**

BDD (Behavior Driven Development) é uma abordagem que descreve o comportamento esperado do sistema utilizando uma linguagem simples e de fácil compreensão para equipes de negócio, QA e desenvolvimento.

Os cenários são escritos utilizando as palavras-chave:

    Dado (Given) → Contexto inicial.
    Quando (When) → Ação executada.
    Então (Then) → Resultado esperado.
    E (And) → Complemento de uma condição ou ação.

## Estrutura Básica

_Exemplo 1 - Login com Sucesso_

**Funcionalidade: Login**

**Cenário: Realizar login com credenciais válidas**
    
    Dado que o usuário esteja cadastrado no sistema
    E possua credenciais válidas
    Quando informar usuário e senha válidos
    E clicar no botão "Entrar"
    Então o sistema deve realizar o login com sucesso
    E redirecionar o usuário para a página inicial

_Exemplo 2 - Login com Senha Inválida_

**Funcionalidade: Login**

**Cenário: Tentar login com senha inválida**

    Dado que o usuário esteja cadastrado no sistema
    Quando informar uma senha inválida
    E clicar no botão "Entrar"
    Então o sistema deve exibir a mensagem "Usuário ou senha inválidos"

## Boas Práticas
- Escreva cenários simples e objetivos;
- Utilize linguagem de negócio;
- Crie apenas um objetivo por cenário;
- Evite detalhes técnicos;
- Mantenha os cenários independentes;
- Reutilize pré-condições sempre que possível.
  
