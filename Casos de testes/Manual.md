# 🧪 Criação de Casos de Testes

## 📌 Objetivo
Os casos de teste têm como objetivo validar funcionalidades do sistema, garantindo que os requisitos estejam funcionando conforme esperado.

## 📋 Estrutura de um Caso de Teste
Todo caso de teste deve conter informações claras e objetivas para facilitar a execução e entendimento.

| Campo | Descrição |
|------------|------------|
| ID | Identificação única do teste |
| Título | Nome resumido do cenário |
| Objetivo | O que será validado |
| Pré-condição | Requisitos necessários antes da execução |
| Passos | Ações executadas pelo testador |
| Resultado Esperado | Comportamento esperado |
| Status	| Não Executado, Aprovado ou Reprovado | 

## ✅ Exemplo de Caso de Teste
CT-001 — Login com credenciais válidas

### Objetivo
      Validar que o usuário consiga acessar o sistema com login válido.

### Pré-condição
      Dado que o usuário esteja cadastrado no sistema
      E possua credenciais válidas

### Passos de Execução
      1. Acessar a tela de login;
      2. Informar usuário válido;
      3. Informar senha válida;
      4. Clicar no botão "Entrar".

### Resultado Esperado
     Então o sistema deve realizar o login com sucesso
     E redirecionar o usuário para a página inicial

###  Status
     Não Executado


## 💡 Boas Práticas
- Criar títulos objetivos;
- Utilizar linguagem clara;
- Manter os passos organizados;
- Validar apenas um objetivo por caso de teste;
- Utilizar BDD quando possível;
- Adicionar evidências após execução.

## 🚫 O que Evitar
- Casos de teste genéricos;
- Muitos objetivos no mesmo teste;
- Passos incompletos;
- Falta de resultado esperado;
- Cenários sem pré-condição.
